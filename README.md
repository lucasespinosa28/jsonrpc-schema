# jsonrpc-schema

### recommend use demo page, not the playground

# 1- eth schema was 
the schema was uptaded an now have example 
## source: https://github.com/lucasespinosa28/ethereum-json-rpc-specification
## demo page: https://lucasespinosa28.github.io/ethereum-json-rpc-specification/api-documentation/
## playground: https://playground.open-rpc.org/?uiSchema%5BappBar%5D%5Bui:splitView%5D=false&schemaUrl=https://raw.githubusercontent.com/lucasespinosa28/ethereum-json-rpc-specification/master/openrpc.json

# 1- bsc schema 
the bsc schema was created, it wasn't much different from eth 
## source: https://github.com/lucasespinosa28/bsc-json-rpc-specification
## demo page: https://lucasespinosa28.github.io/bsc-json-rpc-specification/api-documentation
## playground: https://playground.open-rpc.org/?uiSchema%5BappBar%5D%5Bui:splitView%5D=false&schemaUrl=https://raw.githubusercontent.com/lucasespinosa28/bsc-json-rpc-specification/main/openrpc.json

# 3- avax schema 
Every methods support by public node was add to the schema with examples 
How some methods have different URL paths you need to combine the tag of method with serve URL, the eth methods have tags /bc/C/rpc the path is https://api.avax.network/ext/bc/P
## source: https://github.com/lucasespinosa28/Avalanche-json-rpc-specification
## demo page: https://lucasespinosa28.github.io/Avalanche-json-rpc-specification/api-documentation/
## playground: https://playground.open-rpc.org/?uiSchema%5BappBar%5D%5Bui:splitView%5D=false&schemaUrl=https://raw.githubusercontent.com/lucasespinosa28/Avalanche-json-rpc-specification/main/openrpc.json

# 4 - besu
the methods "DEBUG","ETH","ADMIN","WEB3","IBFT","NET","TXPOOL","TRACE","PRIV"  were added with examples 
as I can't find any public node, I ran one on my local machina using docker , source have the command to run basic fullnode with docker
## source: https://github.com/lucasespinosa28/Hyperledger-Besu-json-rpc-specification
## demo page: https://lucasespinosa28.github.io/Hyperledger-Besu-json-rpc-specification/api-documentation
## playground:https://playground.open-rpc.org/?uiSchema%5BappBar%5D%5Bui:splitView%5D=false&schemaUrl=https://raw.githubusercontent.com/lucasespinosa28/Hyperledger-Besu-json-rpc-specification/main/openrpc.json

⚠ sometimes the first request fails, try again 
