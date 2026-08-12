

# XUnity-TextMeshPro-Font-AssetBundles
**仅用于XUnity.AutoTranslator插件的TextMeshPro字体**   
**TextMeshPro fonts for XUnity.AutoTranslator plugin only**

# 所有TextMeshPro字体未经测试，请自行测试

# 用法：
**配置 XUnity.AutoTranslator**  
**BepInEx**  
导航到BepInEx/config/AutoTranslatorConfig.ini  
[Behaviour]  
OverrideFontTextMeshPro=TMP字体2  
FallbackFontTextMeshPro=TMP字体1  

**BepInEx-Unity.IL2CPP**  
导航到BepInEx/config/AutoTranslatorConfig.ini  
[Behaviour]  
OverrideFontTextMeshPro=TMP字体2  
FallbackFontTextMeshPro=TMP字体1

**ReiPatcher**  
导航到AutoTranslator/Config.ini  
[Behaviour]  
OverrideFontTextMeshPro=TMP字体2  
FallbackFontTextMeshPro=TMP字体1

**MelonLoader**  
导航到AutoTranslator/Config.ini  
[Behaviour]  
OverrideFontTextMeshPro=TMP字体2  
FallbackFontTextMeshPro=TMP字体1

> **提示**：配置中的 `TMP字体1` 和 `TMP字体2` 为占位符，请替换为实际的字体 AssetBundle 文件名（不含扩展名）。
