# vtils ![Test](https://github.com/fjc0k/vtils/workflows/Test/badge.svg?branch=v3) ![Coverage](https://codecov.io/gh/fjc0k/vtils/branch/v3/graph/badge.svg)

一个面向业务的 JavaScript/TypeScript 实用程序库。

```ts
import { dedent } from 'vtils'

console.log(dedent`
  - Lodash
  - date-fns
  - react-use
  - type-fest
  - ts-essentials
`)
```

## 特性

- **🙅‍♀️ 拒绝重复**：基于社区优质程序库（[Lodash](https://lodash.com/)、[date-fns](https://date-fns.org/)、[react-use](https://github.com/streamich/react-use#readme)、[type-fest](https://github.com/sindresorhus/type-fest#readme)、[ts-essentials](https://github.com/krzkaczor/ts-essentials#readme) 等），补充常用业务代码。

- **🌸 精致优雅**：为每一个工具都添加了注释、测试，不看文档亦可直接使用。

- **🌈 面向未来**：使用 [TypeScript](https://www.typescriptlang.org/) 编写，支持 [Tree Shaking](https://webpack.js.org/guides/tree-shaking/)、[ECMAScript Modules](https://nodejs.org/api/esm.html)，也可以在 [Deno](https://deno.land/) 中使用。

## 安装

```bash
# npm
npm i vtils

# yarn
yarn add vtils

# pnpm
pnpm add vtils
```

若在国内，推荐安装 [tbify](https://github.com/fjc0k/tbify#readme) 使用淘宝镜像加速：

```bash
# npm
tnpm i vtils

# yarn
tyn add vtils

# pnpm
tpm add vtils
```

## 使用

```ts
// 基础工具库
import { wait, isNumber, EventBus, base64Encode } from 'vtils'

// 日期时间工具库
import { formatRelative, subDays, zhCN } from 'vtils/date'

// React 工具库
import { useClassName, useToggle, useScrollLoadMore } from 'vtils/react'

// 类型工具库
import { OmitStrict, LiteralUnion, PartialDeep } from 'vtils/types'
```

详细用法见文档：[https://fjc0k.github.io/vtils/v3/](https://fjc0k.github.io/vtils/v3/)。

## 许可

Jay Fong (c) MIT
