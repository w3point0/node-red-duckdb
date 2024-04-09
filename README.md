# Node-RED and DuckDB

<img src="https://github.com/w3point0/node-red-duckdb/assets/993459/dfe7dae4-6de7-4b78-a7c0-13225020602f" width="50%" height="50%">


Node-RED and DuckDB have become an exceptional combination, allowing the use of quick coding techniques to configure, cache, and modify flows dynamically. This synergy facilitates a seamless transition from rapid prototyping to production, simplifying the development process. With AI snippets, you can also store WASM files generated by Go, Rust, C, C++, and more, adding a robust layer of functionality to your workflows. 

## Environment
- Node v20.12.1  
- Node-RED v3.8.1  
- Ubuntu 22.04.3 LTS

# Setup DuckDB with No-Code Package Version Latest


# Setup DuckDB Set Package Version


## Install Duck DB into the .node-red directory

Step 1: cd into your home directory.

You will see the .node-red.

Step 2: cd into .node-red

```
cd ~/.node-red
```

![image](https://github.com/w3point0/node-red-duckdb/assets/993459/1044b0b0-71ba-4f37-a44a-ee401dfe6e54)


Step 3: Install DuckDB

![image](https://github.com/w3point0/node-red-duckdb/assets/993459/043095d5-88e9-441f-95ef-e95ae9862c47)

Note: We could have configured DuckDB during the setup phase. However, unfortunately, this defaults to the latest version. To specify a version, we need to set it up in both `package.json` and `settings.js`.

```
npm install duckdb@0.10.1 --save
```
Done!

## Modify Your settings.js File

Step: 1 Add your favorite node package. For this example a simple word-to-number package will be used.
```
vi settings.js
```

![image](https://github.com/w3point0/node-red-duckdb/assets/993459/1636216d-f875-473a-b54a-63003b4d52ad)

Step 2: Restart node-red
You will now be able to use this package. 

Done!


