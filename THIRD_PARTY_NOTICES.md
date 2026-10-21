# 第三方组件 / Third-party notices

囤囤鼠使用第三方软件、字体和本地识别模型；其版权和许可归相应权利人所有。本仓库不提供囤囤鼠应用源代码，也未授予应用整体的开源许可。以下许可证适用于对应第三方内容。

Stash uses third-party software, fonts and local recognition models. Their respective copyright and license terms remain in effect. The application itself is not released as open source in this repository.

## 本地识别 / On-device recognition

- TinyCLIP 模型：[来源](https://huggingface.co/onnx-community/TinyCLIP-ViT-8M-16-Text-3M-YFCC15M-ONNX)，固定版本 `9463a9c508a344c837ffefe9d724f3827bf2dc79`。[MIT 原文](licenses/vision/TinyCLIP-LICENSE.txt)。
- Transformers.js：[Apache-2.0 原文](licenses/vision/Transformers-LICENSE.txt)。
- ONNX Runtime：[MIT 原文](licenses/vision/ONNXRuntime-LICENSE.txt)。
- Tesseract.js 和 Core：[许可目录](licenses/ocr)。中文、英文模型来源及说明见 [OCR NOTICE](licenses/ocr/NOTICE.txt)，模型基于 Tesseract tessdata，采用 Apache-2.0。
- Roboto 字体的 OFL 许可保留在下表所链接的原文中。

## 依赖许可参考 / Dependency license reference

以下从当前依赖锁文件及已安装包收集原始许可，保守保留直接和间接依赖的声明。部分条目仅用于 Node.js 或构建环境，不表示 APK 包含所有列出的原生平台组件；此清单不是 APK 的逐文件软件组成清单。

Original notices collected from the dependency lock and installed packages are retained below. Some entries apply only to Node.js or build tooling; inclusion here does not mean every listed native component is shipped in the Android APK.

| Component | Version | License | Text |
| --- | --- | --- | --- |
| @floating-ui/core | 1.7.5 | MIT | [License](<licenses/dependencies/@floating-ui/core/LICENSE>) |
| @floating-ui/dom | 1.7.6 | MIT | [License](<licenses/dependencies/@floating-ui/dom/LICENSE>) |
| @floating-ui/react-dom | 2.1.8 | MIT | [License](<licenses/dependencies/@floating-ui/react-dom/LICENSE>) |
| @floating-ui/utils | 0.2.11 | MIT | [License](<licenses/dependencies/@floating-ui/utils/LICENSE>) |
| @fontsource/roboto | 5.2.10 | OFL-1.1 | [License](<licenses/dependencies/@fontsource/roboto/LICENSE>) |
| @huggingface/jinja | 0.5.10 | MIT | [License](<licenses/dependencies/@huggingface/jinja/LICENSE>) |
| @huggingface/tokenizers | 0.2.0 | Apache-2.0 | [License](<licenses/dependencies/@huggingface/tokenizers/LICENSE>) |
| @huggingface/transformers | 4.3.1 | Apache-2.0 | [License](<licenses/dependencies/@huggingface/transformers/LICENSE>) |
| @img/colour | 1.1.0 | MIT | [License](<licenses/dependencies/@img/colour/LICENSE.md>) |
| @img/sharp-win32-x64 | 0.35.5 | Apache-2.0 AND LGPL-3.0-or-later | [License](<licenses/dependencies/@img/sharp-win32-x64/LICENSE>) |
| @protobufjs/aspromise | 1.1.2 | BSD-3-Clause | [License](<licenses/dependencies/@protobufjs/aspromise/LICENSE>) |
| @protobufjs/base64 | 1.1.2 | BSD-3-Clause | [License](<licenses/dependencies/@protobufjs/base64/LICENSE>) |
| @protobufjs/codegen | 2.0.5 | BSD-3-Clause | [License](<licenses/dependencies/@protobufjs/codegen/LICENSE>) |
| @protobufjs/eventemitter | 1.1.1 | BSD-3-Clause | [License](<licenses/dependencies/@protobufjs/eventemitter/LICENSE>) |
| @protobufjs/fetch | 1.1.1 | BSD-3-Clause | [License](<licenses/dependencies/@protobufjs/fetch/LICENSE>) |
| @protobufjs/float | 1.0.2 | BSD-3-Clause | [License](<licenses/dependencies/@protobufjs/float/LICENSE>) |
| @protobufjs/path | 1.1.2 | BSD-3-Clause | [License](<licenses/dependencies/@protobufjs/path/LICENSE>) |
| @protobufjs/pool | 1.1.0 | BSD-3-Clause | [License](<licenses/dependencies/@protobufjs/pool/LICENSE>) |
| @protobufjs/utf8 | 1.1.2 | BSD-3-Clause | [License](<licenses/dependencies/@protobufjs/utf8/LICENSE>) |
| @radix-ui/primitive | 1.1.5 | MIT | [License](<licenses/dependencies/@radix-ui/primitive/LICENSE>) |
| @radix-ui/react-arrow | 1.1.11 | MIT | [License](<licenses/dependencies/@radix-ui/react-arrow/LICENSE>) |
| @radix-ui/react-collection | 1.1.12 | MIT | [License](<licenses/dependencies/@radix-ui/react-collection/LICENSE>) |
| @radix-ui/react-compose-refs | 1.1.3 | MIT | [License](<licenses/dependencies/@radix-ui/react-compose-refs/LICENSE>) |
| @radix-ui/react-context | 1.2.0 | MIT | [License](<licenses/dependencies/@radix-ui/react-context/LICENSE>) |
| @radix-ui/react-dialog | 1.1.19 | MIT | [License](<licenses/dependencies/@radix-ui/react-dialog/LICENSE>) |
| @radix-ui/react-direction | 1.1.2 | MIT | [License](<licenses/dependencies/@radix-ui/react-direction/LICENSE>) |
| @radix-ui/react-dismissable-layer | 1.1.15 | MIT | [License](<licenses/dependencies/@radix-ui/react-dismissable-layer/LICENSE>) |
| @radix-ui/react-dropdown-menu | 2.1.20 | MIT | [License](<licenses/dependencies/@radix-ui/react-dropdown-menu/LICENSE>) |
| @radix-ui/react-focus-guards | 1.1.4 | MIT | [License](<licenses/dependencies/@radix-ui/react-focus-guards/LICENSE>) |
| @radix-ui/react-focus-scope | 1.1.12 | MIT | [License](<licenses/dependencies/@radix-ui/react-focus-scope/LICENSE>) |
| @radix-ui/react-icons | 1.3.2 | MIT | [License](<licenses/dependencies/@radix-ui/react-icons/LICENSE>) |
| @radix-ui/react-id | 1.1.2 | MIT | [License](<licenses/dependencies/@radix-ui/react-id/LICENSE>) |
| @radix-ui/react-menu | 2.1.20 | MIT | [License](<licenses/dependencies/@radix-ui/react-menu/LICENSE>) |
| @radix-ui/react-popper | 1.3.3 | MIT | [License](<licenses/dependencies/@radix-ui/react-popper/LICENSE>) |
| @radix-ui/react-portal | 1.1.13 | MIT | [License](<licenses/dependencies/@radix-ui/react-portal/LICENSE>) |
| @radix-ui/react-presence | 1.1.7 | MIT | [License](<licenses/dependencies/@radix-ui/react-presence/LICENSE>) |
| @radix-ui/react-primitive | 2.1.7 | MIT | [License](<licenses/dependencies/@radix-ui/react-primitive/LICENSE>) |
| @radix-ui/react-roving-focus | 1.1.15 | MIT | [License](<licenses/dependencies/@radix-ui/react-roving-focus/LICENSE>) |
| @radix-ui/react-slot | 1.3.0 | MIT | [License](<licenses/dependencies/@radix-ui/react-slot/LICENSE>) |
| @radix-ui/react-use-callback-ref | 1.1.2 | MIT | [License](<licenses/dependencies/@radix-ui/react-use-callback-ref/LICENSE>) |
| @radix-ui/react-use-controllable-state | 1.2.3 | MIT | [License](<licenses/dependencies/@radix-ui/react-use-controllable-state/LICENSE>) |
| @radix-ui/react-use-effect-event | 0.0.3 | MIT | [License](<licenses/dependencies/@radix-ui/react-use-effect-event/LICENSE>) |
| @radix-ui/react-use-is-hydrated | 0.1.1 | MIT | [License](<licenses/dependencies/@radix-ui/react-use-is-hydrated/LICENSE>) |
| @radix-ui/react-use-layout-effect | 1.1.2 | MIT | [License](<licenses/dependencies/@radix-ui/react-use-layout-effect/LICENSE>) |
| @radix-ui/react-use-rect | 1.1.2 | MIT | [License](<licenses/dependencies/@radix-ui/react-use-rect/LICENSE>) |
| @radix-ui/react-use-size | 1.1.2 | MIT | [License](<licenses/dependencies/@radix-ui/react-use-size/LICENSE>) |
| @radix-ui/rect | 1.1.2 | MIT | [License](<licenses/dependencies/@radix-ui/rect/LICENSE>) |
| @types/node | 26.6.5 | MIT | [License](<licenses/dependencies/@types/node/LICENSE>) |
| @types/react | 19.2.17 | MIT | [License](<licenses/dependencies/@types/react/LICENSE>) |
| @types/react-dom | 19.2.3 | MIT | [License](<licenses/dependencies/@types/react-dom/LICENSE>) |
| @use-gesture/core | 10.3.1 | MIT | [License](<licenses/dependencies/@use-gesture/core/LICENSE>) |
| @use-gesture/react | 10.3.1 | MIT | [License](<licenses/dependencies/@use-gesture/react/LICENSE>) |
| adm-zip | 0.6.1 | MIT | [License](<licenses/dependencies/adm-zip/LICENSE>) |
| ansi-regex | 5.0.1 | MIT | [License](<licenses/dependencies/ansi-regex/license>) |
| ansi-styles | 4.3.0 | MIT | [License](<licenses/dependencies/ansi-styles/license>) |
| aria-hidden | 1.2.6 | MIT | [License](<licenses/dependencies/aria-hidden/LICENSE>) |
| bmp-js | 0.1.0 | MIT | [License](<licenses/dependencies/bmp-js/LICENSE>) |
| camelcase | 5.3.1 | MIT | [License](<licenses/dependencies/camelcase/license>) |
| cliui | 6.0.0 | ISC | [License](<licenses/dependencies/cliui/LICENSE.txt>) |
| color-convert | 2.0.1 | MIT | [License](<licenses/dependencies/color-convert/LICENSE>) |
| color-name | 1.1.4 | MIT | [License](<licenses/dependencies/color-name/LICENSE>) |
| csstype | 3.2.3 | MIT | [License](<licenses/dependencies/csstype/LICENSE>) |
| decamelize | 1.2.0 | MIT | [License](<licenses/dependencies/decamelize/license>) |
| define-data-property | 1.1.4 | MIT | [License](<licenses/dependencies/define-data-property/LICENSE>) |
| define-properties | 1.2.1 | MIT | [License](<licenses/dependencies/define-properties/LICENSE>) |
| detect-libc | 2.1.2 | Apache-2.0 | [License](<licenses/dependencies/detect-libc/LICENSE>) |
| detect-node-es | 1.1.0 | MIT | [License](<licenses/dependencies/detect-node-es/LICENSE>) |
| dijkstrajs | 1.0.3 | MIT | [License](<licenses/dependencies/dijkstrajs/LICENSE.md>) |
| emoji-regex | 8.0.0 | MIT | [License](<licenses/dependencies/emoji-regex/LICENSE-MIT.txt>) |
| es-define-property | 1.0.1 | MIT | [License](<licenses/dependencies/es-define-property/LICENSE>) |
| es-errors | 1.3.0 | MIT | [License](<licenses/dependencies/es-errors/LICENSE>) |
| escape-string-regexp | 4.0.0 | MIT | [License](<licenses/dependencies/escape-string-regexp/license>) |
| find-up | 4.1.0 | MIT | [License](<licenses/dependencies/find-up/license>) |
| flatbuffers | 25.9.23 | Apache-2.0 | [License](<licenses/dependencies/flatbuffers/LICENSE>) |
| framer-motion | 12.42.2 | MIT | [License](<licenses/dependencies/framer-motion/LICENSE.md>) |
| get-caller-file | 2.0.5 | ISC | [License](<licenses/dependencies/get-caller-file/LICENSE.md>) |
| get-nonce | 1.0.1 | MIT | [License](<licenses/dependencies/get-nonce/LICENSE>) |
| global-agent | 4.1.3 | BSD-3-Clause | [License](<licenses/dependencies/global-agent/LICENSE>) |
| globalthis | 1.0.4 | MIT | [License](<licenses/dependencies/globalthis/LICENSE>) |
| gopd | 1.2.0 | MIT | [License](<licenses/dependencies/gopd/LICENSE>) |
| has-property-descriptors | 1.0.2 | MIT | [License](<licenses/dependencies/has-property-descriptors/LICENSE>) |
| idb-keyval | 6.3.0 | Apache-2.0 | [License](<licenses/dependencies/idb-keyval/LICENCE>) |
| is-fullwidth-code-point | 3.0.0 | MIT | [License](<licenses/dependencies/is-fullwidth-code-point/license>) |
| is-url | 1.2.4 | MIT | [License](<licenses/dependencies/is-url/LICENSE-MIT>) |
| jsqr | 1.4.0 | Apache-2.0 | [License](<licenses/dependencies/jsqr/LICENSE>) |
| locate-path | 5.0.0 | MIT | [License](<licenses/dependencies/locate-path/license>) |
| long | 5.3.2 | Apache-2.0 | [License](<licenses/dependencies/long/LICENSE>) |
| matcher | 4.0.0 | MIT | [License](<licenses/dependencies/matcher/license>) |
| motion | 12.42.2 | MIT | [License](<licenses/dependencies/motion/LICENSE.md>) |
| motion-dom | 12.42.2 | MIT | [License](<licenses/dependencies/motion-dom/LICENSE.md>) |
| motion-utils | 12.39.0 | MIT | [License](<licenses/dependencies/motion-utils/LICENSE.md>) |
| node-fetch | 2.7.0 | MIT | [License](<licenses/dependencies/node-fetch/LICENSE.md>) |
| object-keys | 1.1.1 | MIT | [License](<licenses/dependencies/object-keys/LICENSE>) |
| opencollective-postinstall | 2.0.3 | MIT | [License](<licenses/dependencies/opencollective-postinstall/LICENSE>) |
| p-limit | 2.3.0 | MIT | [License](<licenses/dependencies/p-limit/license>) |
| p-locate | 4.1.0 | MIT | [License](<licenses/dependencies/p-locate/license>) |
| p-try | 2.2.0 | MIT | [License](<licenses/dependencies/p-try/license>) |
| path-exists | 4.0.0 | MIT | [License](<licenses/dependencies/path-exists/license>) |
| platform | 1.3.6 | MIT | [License](<licenses/dependencies/platform/LICENSE>) |
| pngjs | 5.0.0 | MIT | [License](<licenses/dependencies/pngjs/LICENSE>) |
| protobufjs | 7.6.6 | BSD-3-Clause | [License](<licenses/dependencies/protobufjs/LICENSE>) |
| qrcode | 1.5.4 | MIT | [License](<licenses/dependencies/qrcode/license>) |
| react | 19.2.7 | MIT | [License](<licenses/dependencies/react/LICENSE>) |
| react-dom | 19.2.7 | MIT | [License](<licenses/dependencies/react-dom/LICENSE>) |
| react-remove-scroll | 2.7.2 | MIT | [License](<licenses/dependencies/react-remove-scroll/LICENSE>) |
| react-style-singleton | 2.2.3 | MIT | [License](<licenses/dependencies/react-style-singleton/LICENSE>) |
| regenerator-runtime | 0.13.11 | MIT | [License](<licenses/dependencies/regenerator-runtime/LICENSE>) |
| require-directory | 2.1.1 | MIT | [License](<licenses/dependencies/require-directory/LICENSE>) |
| require-main-filename | 2.0.0 | ISC | [License](<licenses/dependencies/require-main-filename/LICENSE.txt>) |
| scheduler | 0.27.0 | MIT | [License](<licenses/dependencies/scheduler/LICENSE>) |
| semver | 7.8.5 | ISC | [License](<licenses/dependencies/semver/LICENSE>) |
| serialize-error | 8.1.0 | MIT | [License](<licenses/dependencies/serialize-error/license>) |
| set-blocking | 2.0.0 | ISC | [License](<licenses/dependencies/set-blocking/LICENSE.txt>) |
| sharp | 0.35.5 | Apache-2.0 | [License](<licenses/dependencies/sharp/LICENSE>) |
| string-width | 4.2.3 | MIT | [License](<licenses/dependencies/string-width/license>) |
| strip-ansi | 6.0.1 | MIT | [License](<licenses/dependencies/strip-ansi/license>) |
| tesseract.js | 7.0.0 | Apache-2.0 | [License](<licenses/dependencies/tesseract.js/LICENSE.md>) |
| tesseract.js-core | 7.0.0 | Apache-2.0 | [License](<licenses/dependencies/tesseract.js-core/LICENSE>) |
| tslib | 2.8.1 | 0BSD | [License](<licenses/dependencies/tslib/LICENSE.txt>) |
| type-fest | 0.20.2 | (MIT OR CC0-1.0) | [License](<licenses/dependencies/type-fest/license>) |
| undici-types | 8.9.0 | MIT | [License](<licenses/dependencies/undici-types/LICENSE>) |
| use-callback-ref | 1.3.3 | MIT | [License](<licenses/dependencies/use-callback-ref/LICENSE>) |
| use-sidecar | 1.1.3 | MIT | [License](<licenses/dependencies/use-sidecar/LICENSE>) |
| wasm-feature-detect | 1.9.0 | Apache-2.0 | [License](<licenses/dependencies/wasm-feature-detect/LICENSE>) |
| webidl-conversions | 3.0.1 | BSD-2-Clause | [License](<licenses/dependencies/webidl-conversions/LICENSE.md>) |
| whatwg-url | 5.0.0 | MIT | [License](<licenses/dependencies/whatwg-url/LICENSE.txt>) |
| which-module | 2.0.1 | ISC | [License](<licenses/dependencies/which-module/LICENSE>) |
| wrap-ansi | 6.2.0 | MIT | [License](<licenses/dependencies/wrap-ansi/license>) |
| y18n | 4.0.3 | ISC | [License](<licenses/dependencies/y18n/LICENSE>) |
| yargs | 15.4.1 | MIT | [License](<licenses/dependencies/yargs/LICENSE>) |
| yargs-parser | 18.1.3 | ISC | [License](<licenses/dependencies/yargs-parser/LICENSE.txt>) |
| zlibjs | 0.3.1 | MIT | [License](<licenses/dependencies/zlibjs/LICENSE>) |
