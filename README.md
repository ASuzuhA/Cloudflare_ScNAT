# Cloudflare_AutoNAT
首先声明，此项目是借用CloudflareST做核心筛选工作，IP质量得以保证，在此为基础编写程序以实现自动化与端口转发，
［Cloudflare_AutoNAT］:在[XUI2/CloudflareSpeedtest](https://github.com/XIU2/CloudflareSpeedTest)作为优选IP基础，做出的自动化方案,,定时筛选优选IP，并自动更换最优IP。Cloudflare_AutoNAT会帮忙筛选最优ip并进行端口转发，无需自行筛选更换，Clouflare_AutoNAT为此为目的开发，目前只支持Linux版本，，（毕竟才刚刚开始嘛）


# 免责声明
CFnat 相关项目仅供教育、研究和安全测试目的而设计和开发。本项目旨在为安全研究人员、学术界人士及技术爱好者提供一个探索和实践网络通信技术的工具。
在下载和使用本项目代码时，使用者必须严格遵守其所适用的法律和规定。使用者有责任确保其行为符合所在地区的法律框架、规章制度及其他相关规定。


### 使用条款

- **教育与研究用途**：本软件仅可用于网络技术和编程领域的学习、研究和安全测试。
- **禁止非法使用**：严禁将 **CFnat-Windows-GUI** 用于任何非法活动或违反使用者所在地区法律法规的行为。
- **使用时限**：基于学习和研究目的，建议用户在完成研究或学习后，或在安装后的**24小时内，删除本软件及所有相关文件。**
- **免责声明**：**CFnat-Windows-GUI** 的创建者和贡献者不对因使用或滥用本软件而导致的任何损害或法律问题负责。
- **用户责任**：**用户对使用本软件的方式以及由此产生的任何后果完全负责。**
- **无技术支持**：本软件的创建者不提供任何技术支持或使用协助。
- **知情同意**：使用 **CFnat-Windows-GUI** 即表示您已阅读并理解本免责声明，并同意受其条款的约束。

**请记住**：本软件的主要目的是促进学习、研究和安全测试。作者不支持或认可任何其他用途。使用者应当在合法和负责任的前提下使用本工具。

---
****
## \# 快速使用

### 下载运行
1. 下载编译好的可执行文件（ [Github Releases]([https://github.com/ASuzuhA/Cloudflare_AutoNAT/releases)
<summary><code><strong>「 点击查看 Linux 系统下的使用示例 」</strong></code></summary>

****

以下命令仅为示例，版本号和文件名请前往 [**Releases**](https://github.com/XIU2/CloudflareSpeedTest/releases) 查看。

``` yaml
# 如果是第一次使用，则建议创建新文件夹（后续更新时，跳过该步骤）
mkdir CAT

