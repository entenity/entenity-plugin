.
├── .gitignore                  //配置不需要加入版本管理的文件
├── .vscode                     // VS Code的整合
│   ├── launch.json
│   ├── settings.json
│   └── tasks.json
├── .vscodeignore                //配置不需要加入最终发布到拓展中的文件
├── README.md
├── src                         // 源文件
│   └── extension.ts            // 如果我们使用js来开发拓展，则该文件的后缀为.js
├── test                        // test文件夹
│   ├── extension.test.ts       // 如果我们使用js来开发拓展，则该文件的后缀为.js
│   └── index.ts                // 如果我们使用ts来开发拓展，则该文件的后缀为.ts
├── node_modules
│   ├── vscode                  // vscode对typescript的语言支持。
│   └── typescript              // TypeScript的编译器
├── out                         // 编译之后的输出文件夹(只有TypeScript需要，JS无需)
│   ├── src
│   |   ├── extension.js
│   |   └── extension.js.map
│   └── test
│       ├── extension.test.js
│       ├── extension.test.js.map
│       ├── index.js
│       └── index.js.map
├── package.json                // 该拓展的资源配置文件
├── tsconfig.json               // 
├── typings                     // 类型定义文件夹
│   ├── node.d.ts               // 和Node.js关联的类型定义
│   └── vscode-typings.d.ts     // 和VS Code关联的类型定义
└── vsc-extension-quickstart.md 