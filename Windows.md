<!--
 * @Author       : ★ SEOer.Vip ★
 * @FilePath     : /VipSEOer/Windows.md
 * @Copyright    : Https://Blog.SEOer.Vip/
 * @Description  : Windows@ThinkBook 16 G4+ IAP(YX03Z99X)
-->

Windows@ThinkBook 16 G4+ IAP(YX03Z99X)
===================================================================================================

- DiskGenius 磁盘分区
    - 快速分区：选择 GPT 格式，ESP / MSR 分区默认设置（C盘：200G）
    - 物理扇区：4096 Bytes 对齐
- Windows11 开机跳过联网
    - Shift + F10
    - `OOBE\BYPASSNRO`
- Windows DNS <https://1.1.1.1/zh-Hans/dns/>
    - IPv4：1.1.1.1 / 1.0.0.1
    - IPv6：2606:4700:4700::1111 / 2606:4700:4700::1001
- Windows Images Icon | CMD：`SET /?`
    - %SystemRoot%\System32\shell32.dll
    - %SystemRoot%\System32\imageres.dll
- Windows Update Clear History
    - %SystemRoot%\SoftwareDistribution\Download
    - %SystemRoot%\SoftwareDistribution\DataStore
    - %SystemRoot%\SoftwareDistribution\ReportingEvents.log
    - %SystemRoot%\SoftwareDistribution\PostRebootEventCache.V2
    - %ProgramData%\USOPrivate\UpdateStore\store.db
    - %ProgramData%\USOPrivate\UpdateStore\store.bak
- Windows Defender Clear History
    - %ProgramData%\Microsoft\Windows Defender\Scans\History\Service\DetectionHistory
- Windows PHP Path | `php -v`
    - D:\PHPStudy\Extensions\php\php7.4.3nts
    - D:\PHPStudy\Extensions\php\php7.4.3nts\ext
- 微软拼音输入法 + 用户自定义短语 <UserDefinedPhrase.dat>
    - `dui`     `✓`
    - `cuo`     `✗`
    - `dyh`     `「」`
    - `syh`     `『』`
    - `sj`      `%yyyy%-%MM%-%dd% %HH%:%mm%:%ss%`

Windows CMD ＆ PowerShell
---------------------------------------------------------------------------------------------------

- 选项：
    - 光标大小：小(S)
    - 命令记录：
        - 缓冲区大小：50
        - 缓冲区数量：4
    - 编辑选项：
        - [✓]插入模式
        - [✓]启用 Ctrl 键快捷方式
        - [✓]粘贴时筛选剪贴板内容
    - 文本选择：
        - [✓]启用对选定内容自动换行
        - [✓]扩展的文本选择键
    - 默认代码页：`CHCP 936 | 65001`
- 字体：
    - 大小：18
    - 字体：`Yahei Mono`
- 布局：
    - 屏幕缓冲区大小：
        - 宽带：160
        - 高度：9999
        - [✓]调整大小时对输出的文本换行
    - 窗口大小：
        - 宽度：160
        - 高度：40
        - 窗口位置：[✓]由系统定位窗口
