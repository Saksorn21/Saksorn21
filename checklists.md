# **Relx**
<sub> 
environmentAndConfigfiles Cli commander
</sub>

### Librarys
- commander.js
- eciesjs

### lists
>path: ./lib/main.js
- [ ] 1.main.js
   - [ ] mainClass **Relx**
    - [x] private constructor 
    - [x] setup new Relx
     - [ ] config
       - [x] parameter filePaths
       - [ ] valitdate parameter
       - [x] path Array
            - >Ex: { path: [env1,env2] }
    - [x] Assigns parsed environment variables to the instance.
        - >Ex: relx.valuEnv()
    - [ ] check env CONFIG_RELX (defaultConfig)
>path: ./lib/handleerror.js
- [ ] 1.handleerror.js
   - [ ] mainClass **RelxError**
         - extends Error
    - [ ] constructor
    - [x] parameter
         - code
         - path
         - message
         - >Ex: throw new RelxError({ code: 'ENOENT', path: '/path/to/file', message: 'File not found' })
     - [ ] config
       - [x] parameter filePaths



<!---
Saksorn21/Saksorn21 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
