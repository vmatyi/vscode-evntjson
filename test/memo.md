# publish memo
https://code.visualstudio.com/api/working-with-extensions/publishing-extension
> nvm use ^16.17.0
> npm install -g vsce  // must be installed globally :/
> vsce package  // create VSIX without publishing
// In Powershell. Running from CMD will not ask for the PET, and fail with unauthorized...
> vsce login vmatyi
Personal Access Token for publisher 'vmatyi': r7f9u788gi7pn9twv25pekfg99y0ud1dnt7hink1td1dy0u2haha
> vsce publish  // build extension & publish
