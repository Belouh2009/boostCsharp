# 🚀 boostCsharp

**boostCsharp** est une application de bureau développée en **C# avec WPF**. Elle permet de gérer des données (CRUD) stockées dans une base de données **PostgreSQL**.

## 📌 Fonctionnalités

- 🔍 Affichage de la liste des enregistrements
- ➕ Ajout de nouvelles entrées
- 📝 Modification d’enregistrements existants
- ❌ Suppression d’éléments
- 🎯 Connexion simple et rapide à PostgreSQL

## 🛠️ Technologies utilisées

- C# .NET
- WPF (Windows Presentation Foundation)
- PostgreSQL (via Npgsql)

## ⚙️ Configuration de la base de données

Assurez-vous d'avoir PostgreSQL installé avec une base nommée `csharp`. Le projet se connecte à la base de données avec les identifiants suivants (modifiable dans `DataBase.cs`) :

```csharp
connectionString = "Host=localhost;Port=5432;Database=csharp;Username=postgres;Password=123";

