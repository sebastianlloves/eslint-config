npm init @eslint/config@latest
npm i standard -D

"eslintConfig": {
    "extends": [
      "./node_modules/standard/eslintrc.json"
    ]
  }

en .eslintrc.cjs
 extends: [
    'eslint:recommended',
    'plugin:react/recommended',
    'plugin:react/jsx-runtime',
    'plugin:react-hooks/recommended',
    'standard',
    'standard-jsx'
  ],
