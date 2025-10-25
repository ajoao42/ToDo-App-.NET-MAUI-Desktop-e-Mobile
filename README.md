# ToDo App - .NET MAUI

Aplicativo multiplataforma criado com **.NET MAUI**, capaz de rodar em **Windows, Android e iOS**.  
O app consome a **ToDo API (ASP.NET Core)** e oferece uma interface moderna para gerenciar tarefas.

---

## 🚀 Tecnologias
- C# / .NET 8
- .NET MAUI (XAML + MVVM)
- SQLite (para armazenamento offline)
- HttpClient (para comunicação com API)
- ASP.NET Core API

---

## ⚙️ Funcionalidades
- CRUD completo de tarefas (online e offline)
- Sincronização com API RESTful
- Interface responsiva e moderna com XAML
- Suporte a múltiplas plataformas: Windows, Android, iOS
- Padrão MVVM com Data Binding

---

## 🧩 Como executar

```bash
# Clonar o repositório
git clone https://github.com/ajoao42/ToDo-App-.NET-MAUI-Desktop-e-MobilePublic.git
cd ToDo-App-.NET-MAUI-Desktop-e-MobilePublic

# Restaurar dependências
dotnet restore

# Executar no Windows
dotnet build -t:Run -f net8.0-windows10.0.19041.0

# Executar no Android
dotnet build -t:Run -f net8.0-android

# Executar no iOS (macOS necessário)
dotnet build -t:Run -f net8.0-ios

