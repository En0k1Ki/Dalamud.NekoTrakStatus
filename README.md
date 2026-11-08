# Dalamud.NekoTrakStatus
NekoTrak Status（FF14 卫月插件）
把 FF14 游戏内状态实时输出给 NekoTrak（Steam 状态类桌宠，原 FlowTrak）。

本插件由 goaaats/Dalamud.RichPresence 改造而来
使用方式：在游戏内安装并启用插件后 回到NekoTrak并找到 设置-行为-丰富状态-添加一个新的状态为 ${cmd /c type "%AppData%\NekoTrak\ff14_status.txt"} 并将下方的终端程序从默认的CMD更改为PowerShell
