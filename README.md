GeradorDeClientes
=================

Aplicação ASP.NET Core (Razor Pages) que gera planilhas XLSX com dados fictícios e permite envio por e-mail. O login via deploy não está funcionando no momento, mas está operando normalmente em ambiente local (localhost). 
Como rodar? Você pode baixar este projeto como .zip, abra a pasta GeradorDeClientes no VS Code. Com o projeto aberto no VS Code, abra o arquivo Program.cs e pressione F5.

-------------------
- Restaurar e compilar:

`powershell
dotnet restore
dotnet build
`

- Executar:

`powershell
dotnet run --project .\GeradorDeClientes.csproj
