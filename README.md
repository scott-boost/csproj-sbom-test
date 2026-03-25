# csproj-sbom-test

1. install scalibr
`go install github.com/google/osv-scalibr/binary/scalibr@latest`

2. run scalibr
`scalibr -o spdx23-json=result.spdx.json --plugins=dotnet/csproj <PATH TO FOLDER containing CSPROJ>`

3. inspect SPDX sbom
`cat result.spdx.json`
