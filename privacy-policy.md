# Privacy Policy / 隐私政策 — 书签助手 (Bookmark Assistant)

**Effective date / 生效日期:** 2026-10-03  
**Applies to / 适用对象:** 书签助手 (Bookmark Assistant), a browser extension for Microsoft Edge / Google Chrome  
**Contact / 联系方式:** that_who@qq.com

---

## English

### 1. Summary

Bookmark Assistant is a local bookmark manager. It reads your existing browser bookmarks and displays them in a card-style popup, as an alternative to the built-in bookmark bar. **It does not collect, transmit, sell or share your data. It has no backend server and makes no network requests of its own.**

### 2. Data the extension accesses

- **Bookmarks** — the bookmark tree is read so the popup can render your folders and bookmarks. Bookmarks are created, renamed, moved, or deleted **only** when you explicitly use the corresponding button or drag action in the popup.
- **Extension settings** — a single local record (`ls_data`) storing your display preferences: view mode, single-column layout, whether the custom scrollbar is enabled, the popup window size and position, and the last-used search state.
- **Website icons (favicons)** — the URL of a bookmark you are already viewing is passed to the browser's *built-in* favicon service so its icon can be displayed. This is a browser-internal call; the URL is not sent to the developer or to any third party.

### 3. Where the data is stored

All of the above stays inside your browser profile, on your device. The extension uses only the browser's local bookmark and local storage APIs (`chrome.bookmarks`, `chrome.storage.local`).

### 4. What the extension never does

- It does not transmit bookmark data, settings, browsing history, or any other personal information to the developer or to any third party.
- It does not read your browsing history or the URL/title of your open tabs.
- It does not collect analytics, telemetry, crash reports, advertising identifiers or device identifiers.
- It does not sell, rent, or share user data.
- It does not use data for advertising, profiling, creditworthiness, or lending purposes.
- It does not load or execute remote code.

### 5. Third parties and remote resources

There are none. No analytics SDK, no advertising network, no CDN. All scripts, styles and images are packaged inside the extension itself.

### 6. Search shortcuts

The popup can open a search engine with the keyword you typed. This simply opens the search engine's website in a new tab, exactly as if you had typed the query there yourself. The extension does not send the query anywhere.

### 7. Your control

- Uninstalling the extension removes the locally stored settings.
- Your bookmarks remain in the browser and are unaffected.
- Cross-device sync is handled by the browser's own sync feature (for example, Edge sync), not by this extension.

### 8. Children

The extension is not directed at children and collects no data from anyone.

### 9. Changes

Any change to this policy will be published at this URL with a new effective date.

### 10. Contact

Questions about this policy: that_who@qq.com

---

## 中文

### 一、摘要

书签助手是一款**纯本地**书签管理扩展。它读取你浏览器中已有的书签，以卡片式弹窗呈现，作为浏览器书签栏的替代方案。**它不收集、不传输、不销售、不共享你的数据；没有后端服务器，自身不发起任何网络请求。**

### 二、扩展访问的数据

- **书签** —— 读取书签树，以便弹窗渲染你的书签夹与书签条目。新增、重命名、移动、删除**仅在你于弹窗中显式点击对应按钮或拖拽时**发生。
- **扩展设置** —— 一条本地记录（`ls_data`），保存你的显示偏好：视图模式、单列显示、是否启用自定义滚动条、弹窗尺寸与位置、上次搜索状态。
- **网站图标（favicon）** —— 把你正在查看的书签 URL 交给浏览器**自带的**图标服务以显示其图标。这是浏览器内部调用，URL 不会发送给开发者或任何第三方。

### 三、数据存放位置

以上全部只存在于你设备上的浏览器配置目录内。扩展仅使用浏览器本地的书签与存储 API（`chrome.bookmarks`、`chrome.storage.local`）。

### 四、扩展不会做的事

- 不向开发者或任何第三方传输书签数据、设置、浏览记录或其他任何个人信息。
- 不读取你的浏览历史，也不读取打开中标签页的地址或标题。
- 不收集统计数据、遥测、崩溃报告、广告标识或设备标识。
- 不销售、不出租、不共享用户数据。
- 不将数据用于广告、用户画像、信用评估或借贷用途。
- 不加载、不执行任何远程代码。

### 五、第三方与远程资源

没有。无统计 SDK、无广告网络、无 CDN。全部脚本、样式与图片均打包在扩展内部。

### 六、搜索跳转

弹窗可将你输入的关键词跳转至搜索引擎。该行为只是在新标签页打开搜索引擎网站，等同于你亲自在该网站输入关键词。扩展本身不发送任何查询。

### 七、你的控制权

- 卸载扩展即删除本地保存的设置。
- 你的书签仍保留在浏览器中，不受影响。
- 多设备同步由浏览器自带的同步功能（例如 Edge 同步）完成，与本扩展无关。

### 八、儿童

本扩展不面向儿童，不收集任何人的数据。

### 九、政策变更

本政策的任何变更将在本 URL 发布，并更新生效日期。

### 十、联系方式

关于本政策的问题请联系：that_who@qq.com

---

> 发布提示：把上面内容贴到 GitHub Gist（gist.github.com）、Notion 公开页或你自己的网站上，得到公开 URL 后填入 Partner Center 的 **Privacy Policy URL**。发布前记得把 `<your-email@example.com>` 换成你的真实邮箱。
