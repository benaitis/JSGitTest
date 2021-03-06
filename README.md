# Prettier and eslint setup

1. clone repository
2. `npm install`
3. install prettier extension in VsCode
4. install eslint extension in VsCode (and enable in bottom toolbar)
5. open VSCode settings -> (ctrl + ,)
6. enable format on save
7. search for `codeActionsOnSave`
8. click edit in settings.json
9. add this in settings.json

```
    "editor.formatOnSave": true,
    "editor.codeActionsOnSave": {
        "source.fixAll.eslint": true,
    }
```

10. You should now see eslint errors in your code and prettier should try to auto format.

Feel free to edit `.prettierc.json`
