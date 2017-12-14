# eslint-config-hostelworld-vue

[![Build Status](https://api.travis-ci.org/Hostelworld/eslint-config-hostelworld-vue.svg?branch=master)](https://travis-ci.org/Hostelworld/eslint-config-hostelworld-vue)
[![npm](https://img.shields.io/npm/v/eslint-config-hostelworld-vue.svg)](https://www.npmjs.com/package/eslint-config-hostelworld-vue)
[![npm](https://img.shields.io/npm/dt/eslint-config-hostelworld-vue.svg)](https://www.npmjs.com/package/eslint-config-hostelworld-vue)

ESLint Shareable Config extending:

+ [`eslint-config-hostelworld`](https://github.com/Hostelworld/eslint-config-hostelworld)
+ [`eslint-config-standard`](https://github.com/standard/eslint-config-standard)
+ [`eslint-plugin-vue (vue/recommended)`](https://github.com/vuejs/eslint-plugin-vue)

## Installation

1. First install the following npm packages:

    ```bash
    # core package
    npm install --save-dev eslint-config-hostelworld-vue
    # plus the peer dependencies
    npm install --save-dev babel-eslint eslint eslint-config-standard eslint-plugin-import eslint-plugin-node eslint-plugin-promise eslint-plugin-standard eslint-config-hostelworld eslint-plugin-vue@next
    ```

2. Then add `eslint-config-hostelworld-vue` to your `.eslintrc.*` **extends** section:

    ```js
    {
        "extends": [
            "hostelworld-vue"
        ],
        "rules": {
            // Additional, per-project rules or overrides...
        }
    }
    ```

