.Net CLI 設定 user-secrets 指令

啟用secret storage
dotnet user-secrets init

設定 user-secrets
dotnet user-secrets set "Movies:ServiceApiKey" "12345"

列出 user-secrets
dotnet user-secrets list