<style>
:root { --brand:#6b46c1; --text:#111827; --muted:#6b7280; --bg:#f8fafc; --border:#e5e7eb; }
body { font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,"Helvetica Neue",Arial,"Noto Sans","PingFang SC",sans-serif; background:var(--bg); color:var(--text); }
.header { position: sticky; top: 0; background:#ffffffcc; backdrop-filter: blur(8px); border-bottom:1px solid var(--border); }
.nav { max-width:860px; margin:0 auto; padding:12px 20px; display:flex; justify-content:space-between; align-items:center; }
.nav .left a { margin-right:16px; color:var(--muted); text-decoration:none; }
.nav .left a.active { color:var(--brand); font-weight:600; }
.nav .lang a { padding:6px 10px; border:1px solid var(--border); border-radius:8px; text-decoration:none; color:#374151; }
.nav .lang a.primary { background:var(--brand); color:#fff; border-color:var(--brand); }
.main { max-width:860px; margin:32px auto; padding:0 20px; }
</style>

<header class="header">
  <div class="nav">
    <div class="left">
      <a href="./index.md">首页</a>
      <a href="./privacy.md">隐私政策</a>
      <a href="./support.md" class="active">技术支持</a>
    </div>
    <div class="lang">
      <a href="./support.en.md">English</a>
    </div>
  </div>
</header>

<div class="main"></div>

# NightGuard 技术支持

最后更新：2025-11-07  
联系邮箱：NightGuard@vectrakode.com

---

## 1. 概览
NightGuard 是一款用于睡眠分析与健康洞察的 iOS 应用。若您遇到问题、需要数据请求或功能建议，请先查看以下常见问题，或通过邮箱联系我们。

---

## 2. 联系我们
- 支持邮箱：NightGuard@vectrakode.com  
- 反馈内容建议包含：设备型号、iOS 版本、App 版本、问题步骤与时间

---

## 3. 常见问题

### 3.1 HealthKit 权限
- iOS 设置 > 健康 > 数据访问与设备 > NightGuard，确认授予睡眠、心率、HRV、呼吸频率等所需读取权限。  
- 若数据不同步：关闭再重新开启相关权限，并在 App 内重新触发同步。

### 3.2 iCloud/CloudKit 同步
- iOS 设置 > [Apple ID] > iCloud > 确认已开启 iCloud 与 CloudKit 同步。  
- 同步延迟通常与网络或系统状态相关，请保持联网并稍后查看。

### 3.3 定位与天气
- 如需本地天气洞察，请授权定位（大致或精确）。  
- 若天气不可用，请确认网络与系统天气服务可用。

### 3.4 通知提醒
- iOS 设置 > 通知 > NightGuard，开启允许通知。  
- 若仍无法收到，请检查系统专注模式或低电量模式。

### 3.5 订阅与购买
- 通过 App Store 订阅管理退款与取消。  
- 购买恢复：在 App 内选择“恢复购买”（如有）。

### 3.6 数据准确性
- NightGuard 基于 HealthKit 与设备传感器，可能受佩戴方式与传感噪声影响。  
- 分析结果仅作健康管理参考，不能替代医疗建议。

---

## 4. 数据请求与隐私
- 导出数据：邮件联系我们，说明导出范围与账号标识。  
- 删除数据：  
  - iOS 健康 App 中删除相关健康数据；  
  - 在 App（如提供）执行“删除账户/清除数据”；  
  - 或通过邮箱请求删除。  
- GDPR/CCPA 请求：请在邮件中标注请求类型（访问、更正、删除、携带、反对处理等）。

---

## 5. 兼容性与要求
- 支持 iOS 版本：以 App Store 列示为准（建议使用最新稳定版 iOS）。  
- 设备兼容性：部分指标依赖 Apple Watch 或支持相应传感器的设备。

---

## 6. 已知问题
- 偶发的同步延迟或权限缓存问题，可通过重新授权与重启设备缓解。  
- 若遇到崩溃，请将复现步骤与时间点发送给我们。

---

## 7. 法律与政策
- 隐私政策：参见 `./privacy.md`  
- 使用条款（如有）：`./terms.md`（如后续新增）

---

## 8. 版本与更新
- 请在 App Store 查看最新版本与更新说明。  
- 重大变更将通过应用内或本页面提示。

