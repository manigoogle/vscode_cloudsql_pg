Google Cloud SQL for Visual Studio Code (Preview)

This is a Visual Studio Code extension designed to help you connect to your Google Cloud SQL databases directly from VS Code and perform all common database operations—querying, exploring, modifying schemas, importing data, and more—without leaving your development environment.

The project is authored by Mani HK (manihk@google.com).

Key Features

Connect to Cloud SQL DatabasesSeamlessly connect to your Google Cloud SQL instances running PostgreSQL, MySQL, or SQL Server.

Explore your DatabaseBrowse through tables, views, stored procedures, and other database objects via a friendly visual interface.

Run SQL QueriesWrite and execute SQL queries with full IntelliSense support. View results in a grid and export them to CSV, JSON, or Excel.

Schema VisualizationQuickly visualize your database schema and relationships between tables.

Command-line PowerRun psql, mysql, or sqlcmd sessions from within VS Code for more advanced usage.

Optional AI Features (Experimental)Use GitHub Copilot (if enabled) to chat with your database, design schemas, and generate queries using natural language prompts.

Getting Started

Install the extension from the Visual Studio Code Marketplace.

Open the Command Palette (Ctrl+Shift+P or Cmd+Shift+P on macOS) and search for Cloud SQL: Connect.

Enter your instance details and credentials.

Start exploring or writing queries in a .sql file.

To enable experimental Copilot integrations:

Open settings (Ctrl + ,)

Search for Cloud SQL Copilot

Enable the experimental features

You’ll be prompted to reload VS Code to activate Copilot features.

Feedback and Support

For support, issues, or feature requests, please contact manihk@google.com or open an issue on the repository (if public).

To include debug logs when reporting issues:

Open the Command Palette.

Search for Cloud SQL: Show Extension Logs.

Copy and share the logs, after reviewing them for sensitive information.

Platform Support

✅ Windows

✅ macOS

✅ Linux

⚠️ Experimental support for ARM64 on macOS and Linux
