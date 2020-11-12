# pycom-devcontainers
An example on developing with pycom in vscode devcontainers


# Error

VS code error when loading @serialport

    [Extension Host] Error: Could not locate the bindings file. Tried: 
    → /home/node/.vscode-server/extensions/pycom.pymakr-1.1.7/node_modules/@serialport/bindings/build/bindings.node 
    → /home/node/.vscode-server/extensions/pycom.pymakr-1.1.7/node_modules/@serialport/bindings/build/Debug/bindings.node 
    → /home/node/.vscode-server/extensions/pycom.pymakr-1.1.7/node_modules/@serialport/bindings/build/Release/bindings.node 
    → /home/node/.vscode-server/extensions/pycom.pymakr-1.1.7/node_modules/@serialport/bindings/out/Debug/bindings.node 
    → /home/node/.vscode-server/extensions/pycom.pymakr-1.1.7/node_modules/@serialport/bindings/Debug/bindings.node 
    → /home/node/.vscode-server/extensions/pycom.pymakr-1.1.7/node_modules/@serialport/bindings/out/Release/bindings.node 
    → /home/node/.vscode-server/extensions/pycom.pymakr-1.1.7/node_modules/@serialport/bindings/Release/bindings.node 
    → /home/node/.vscode-server/extensions/pycom.pymakr-1.1.7/node_modules/@serialport/bindings/build/default/bindings.node 
    → /home/node/.vscode-server/extensions/pycom.pymakr-1.1.7/node_modules/@serialport/bindings/compiled/12.14.1/linux/x64/bindings.node 
    → /home/node/.vscode-server/extensions/pycom.pymakr-1.1.7/node_modules/@serialport/bindings/addon-build/release/install-root/bindings.node 
    → /home/node/.vscode-server/extensions/pycom.pymakr-1.1.7/node_modules/@serialport/bindings/addon-build/debug/install-root/bindings.node 
    → /home/node/.vscode-server/extensions/pycom.pymakr-1.1.7/node_modules/@serialport/bindings/addon-build/default/install-root/bindings.node 
    → /home/node/.vscode-server/extensions/pycom.pymakr-1.1.7/node_modules/@serialport/bindings/lib/binding/node-v72-linux-x64/bindings.node
    	at bindings (/home/node/.vscode-server/extensions/pycom.pymakr-1.1.7/node_modules/bindings/bindings.js:126:9)
    	at Object.<anonymous> (/home/node/.vscode-server/extensions/pycom.pymakr-1.1.7/node_modules/@serialport/bindings/lib/linux.js:2:36)
    	at Module._compile (internal/modules/cjs/loader.js:955:30)
    	at Object.Module._extensions..js (internal/modules/cjs/loader.js:991:10)
    	at Module.load (internal/modules/cjs/loader.js:811:32)
    	at Function.Module._load (internal/modules/cjs/loader.js:723:14)
    	at Function.t._load (/home/node/.vscode-server/bin/fcac248b077b55bae4ba5bab613fd6e9156c2f0c/out/vs/server/remoteExtensionHostProcess.js:1088:776)
    	at Function.i._load (/home/node/.vscode-server/bin/fcac248b077b55bae4ba5bab613fd6e9156c2f0c/out/vs/server/remoteExtensionHostProcess.js:1058:665)
    	at Function.n._load (/home/node/.vscode-server/bin/fcac248b077b55bae4ba5bab613fd6e9156c2f0c/out/vs/server/remoteExtensionHostProcess.js:1054:844)
    	at Module.require (internal/modules/cjs/loader.js:848:19)
    	at require (internal/modules/cjs/helpers.js:74:18)
    	at Object.<anonymous> (/home/node/.vscode-server/extensions/pycom.pymakr-1.1.7/node_modules/@serialport/bindings/lib/index.js:14:22)
    	at Module._compile (internal/modules/cjs/loader.js:955:30)
    	at Object.Module._extensions..js (internal/modules/cjs/loader.js:991:10)
    	at Module.load (internal/modules/cjs/loader.js:811:32)
    	at Function.Module._load (internal/modules/cjs/loader.js:723:14)
    	at Function.t._load (/home/node/.vscode-server/bin/fcac248b077b55bae4ba5bab613fd6e9156c2f0c/out/vs/server/remoteExtensionHostProcess.js:1088:776)
    	at Function.i._load (/home/node/.vscode-server/bin/fcac248b077b55bae4ba5bab613fd6e9156c2f0c/out/vs/server/remoteExtensionHostProcess.js:1058:665)
    	at Function.n._load (/home/node/.vscode-server/bin/fcac248b077b55bae4ba5bab613fd6e9156c2f0c/out/vs/server/remoteExtensionHostProcess.js:1054:844)
    	at Module.require (internal/modules/cjs/loader.js:848:19)
    	at require (internal/modules/cjs/helpers.js:74:18)
    	at Object.<anonymous> (/home/node/.vscode-server/extensions/pycom.pymakr-1.1.7/node_modules/serialport/lib/index.js:2:17)
    	at Module._compile (internal/modules/cjs/loader.js:955:30)
    	at Object.Module._extensions..js (internal/modules/cjs/loader.js:991:10)
    	at Module.load (internal/modules/cjs/loader.js:811:32)
    	at Function.Module._load (internal/modules/cjs/loader.js:723:14)
    	at Function.t._load (/home/node/.vscode-server/bin/fcac248b077b55bae4ba5bab613fd6e9156c2f0c/out/vs/server/remoteExtensionHostProcess.js:1088:776)
    	at Function.i._load (/home/node/.vscode-server/bin/fcac248b077b55bae4ba5bab613fd6e9156c2f0c/out/vs/server/remoteExtensionHostProcess.js:1058:665)
    	at Function.n._load (/home/node/.vscode-server/bin/fcac248b077b55bae4ba5bab613fd6e9156c2f0c/out/vs/server/remoteExtensionHostProcess.js:1054:844)
    	at Module.require (internal/modules/cjs/loader.js:848:19)
    	at require (internal/modules/cjs/helpers.js:74:18)
    	at prepareSerialPort (/home/node/.vscode-server/extensions/pycom.pymakr-1.1.7/pymakr.js:148:9)
    	at activate (/home/node/.vscode-server/extensions/pycom.pymakr-1.1.7/pymakr.js:7:5)
    	at Function._callActivateOptional (/home/node/.vscode-server/bin/fcac248b077b55bae4ba5bab613fd6e9156c2f0c/out/vs/server/remoteExtensionHostProcess.js:957:980)
    	at Function._callActivate (/home/node/.vscode-server/bin/fcac248b077b55bae4ba5bab613fd6e9156c2f0c/out/vs/server/remoteExtensionHostProcess.js:957:631)
    	at /home/node/.vscode-server/bin/fcac248b077b55bae4ba5bab613fd6e9156c2f0c/out/vs/server/remoteExtensionHostProcess.js:956:126
    	at processTicksAndRejections (internal/process/task_queues.js:94:5)
    	at async Promise.all (index 5)
    	at async Promise.all (index 0)