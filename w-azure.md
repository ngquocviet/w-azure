script_key = "yaZrloRMqzXCKMnKJnKmlsdrxSuQeSgQ"
getgenv().Setting = {
    AutoSkipWave=true,
    AutoClaimQuest = true,
    CapFps = true,
    FpsBoost = true,
    WebhookUrl = "",
    OneClickNewSetting = { 
        Enable = true,
        Feed = true,
        Leave=false,
        AllChapter = false,
        IgnoreEquipBest = false,
        LeaveWave = true,
        RequiredLevel = 20,
        AllUnitsToGo = {"Electric Cyborg","Beast Sorcerer","Warrior Princess","Admiral Of Lava","Strongest Swordsman"},
        SnipeBannerUnits = {"Admiral Of Lava","Strongest Swordsman"}, --Snipe Unit Must Be In All Units To Use
        TradingSnipe = false,
        ForceInf = false, --Ignore Level, Unit
        AnyUnitMythical_Secret = {
            StartInfinite=true,
            Feed=true,
            IgnoreLevel = false
        },
        TradingSnipeUnits = {"Electric Cyborg"},
        MaxGemUnit = 1000,
    },
}
if getgenv().Loaded  then
    return 
end
loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/57d5eebd9b111f1639a5970102487168.lua"))()
