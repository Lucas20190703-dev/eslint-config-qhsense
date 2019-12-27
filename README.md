# eslint-config-qhsense

A shareable eslint config for qhsense's projects.

## Install

```bash
npm install --save-dev qhsense/eslint-config-qhsense
```

### Installing peerDependencies

```bash
npm install --save-dev babel-eslint eslint-plugin-flowtype eslint-plugin-import
```

## Usage

Add the following to your `.eslintrc.js`.

```
{
  'extends': 'eslint-config-qhsense'
}
```

### Additional

If you want to enforce `jsdoc` rules used by qhsense.

```bash
npm install --save-dev eslint-plugin-jsdoc
```

```
{
  'extends': [
    'eslint-config-qhsense',
    'eslint-config-qhsense/jsdoc'
  ]
}
```

If you are using `react`.

```bash
npm install --save-dev eslint-plugin-react
```

```
{
  'extends': [
    'eslint-config-qhsense',
    'eslint-config-qhsense/react'
  ]
}
```
