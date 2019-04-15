## eslint-config-luo

### usage

参考至 [eslint-config-alloy](https://github.com/AlloyTeam/eslint-config-alloy)

Add the extension:

```
// .eslintrc.js
module.exports = {
   extends: "luo",
   globals: {
         // 这里填入你的项目需要的全局变量
         // 这里值为 false 表示这个全局变量不允许被重新赋值，比如：
         //
         // jQuery: false,
         // $: false
   },
   rules: {
         // 这里填入你的项目需要的个性化配置，比如：
         //
         // // 一个缩进必须用两个空格替代
         // 'indent': [
         //     'error',
         //     2,
         //     {
         //         SwitchCase: 1,
         //         flatTernaryExpressions: true
         //     }
         // ]
         // // 一个缩进必须用两个空格替代
         // '@typescript-eslint/indent': [
         //     'error',
         //     2,
         //     {
         //         SwitchCase: 1,
         //         flatTernaryExpressions: true
         //     }
         // ]
   }
}

// OR

// .eslintrc
{
   "extends": "luo",
   globals: {
         // 这里填入你的项目需要的全局变量
         // 这里值为 false 表示这个全局变量不允许被重新赋值，比如：
         //
         // jQuery: false,
         // $: false
   },
   rules: {
         // 这里填入你的项目需要的个性化配置，比如：
         //
         // // 一个缩进必须用两个空格替代
         // 'indent': [
         //     'error',
         //     2,
         //     {
         //         SwitchCase: 1,
         //         flatTernaryExpressions: true
         //     }
         // ]
         // // 一个缩进必须用两个空格替代
         // '@typescript-eslint/indent': [
         //     'error',
         //     2,
         //     {
         //         SwitchCase: 1,
         //         flatTernaryExpressions: true
         //     }
         // ]
   }
}
```

Then install the config:

```
npm i eslint-config-luo --save-dev
```