# prettier-config-fronttigger

## Installation

```bash
npm install prettier-config-fronttigger prettier --save-dev
```

## Usage

`package.json` 파일의 `scripts` 속성에 다음을 추가해주세요.

```json
{
  "scripts": {
    "prettier": "prettier . --check",
    "prettier:fix": "prettier . --write"
  }
}
```

`.prettierrc` 파일을 생성하고 다음을 추가해주세요.

```js
'prettier-config-fronttigger';
```

또는 `package.json` 파일에 다음을 추가해주세요.

```json
{
  "prettier": "prettier-config-fronttigger"
}
```
