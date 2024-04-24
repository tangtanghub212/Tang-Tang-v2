local Library = loadstring(game:HttpGet("https://pastebin.com/raw/vff1bQ9F"))() local Window = Library.CreateLib("TangTang v2", "Ocean") local Tab = Window:NewTab("หน้าแรก") local Section = Tab:NewSection("หน้าแรก") Section:NewToggle("วิ่งไว op", "ควย", function(state) if state then game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 30 else game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 10 end end) Section:NewButton("Fling ดีนะอันนี้", "troll", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/0Ben1/fe./main/Fling%20GUI"))()


end) Section:NewButton("ถือของไม่ตก", "บิด", function() loadstring(game:HttpGet("https://pastebin.com/raw/KbSCJFhZ"))(); end) Section:NewButton("Nameless admin op", "op", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/FilteringEnabled/NamelessAdmin/main/Source"))();
end) Section:NewButton("infinite yield", "ควย", function() loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))() end) Section:NewButton("ฟรี headless", "บิด", function()
    loadstring(game:HttpGet('https://pastebin.com/raw/H5yx10Jq'))()
end) Section:NewButton("สว่าง", "บิด", function() game:GetService("Lighting").Brightness = 2 game:GetService("Lighting").ClockTime = 14 game:GetService("Lighting").FogEnd = 100000 game:GetService("Lighting").GlobalShadows = false game:GetService("Lighting").OutdoorAmbient = Color3.fromRGB(128, 128, 128) end) Section:NewButton("บิน", "V3", function() loadstring(game:HttpGet('https://pastebin.com/raw/YSL3xKYU'))() end) Section:NewButton("เดินบนกำแพง", "troll", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/zXk4Rq2r"))()
end) local Tab = Window:NewTab("สคริปบล็อกฟุต") local Section = Tab:NewSection("สคริปบล็อกฟุต") Section:NewButton("Fries hub", "บิด", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/Frieshup/FriesHup/main/Update1'))()
end) Section:NewButton("winter hub", "บิด", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Yatsuraa/Yuri/main/Winterhub_V2.lua"))()
end) Section:NewButton("relz hub", "บิด", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/farghii/relzhub/main/execute.hack", true))()
end) local Tab = Window:NewTab("รวมเเมพ") local Section = Tab:NewSection("บิด") Section:NewButton("รวมแมพต่างๆ", "บิด", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/SmartModBoy/VortexAblity/main/SV'))()
end) Section:NewButton("Infinite Jump", "Idk ", function()     loadstring(game:HttpGet(('https://pastebin.com/raw/V3DKCQTT'),true))() starterGui:SetCore("SendNotification",{ Title = "Message", Text = "Successfully Executed" }) end) Section:NewButton("Keyboard", "For Hide UI", function()     loadstring(game:HttpGet("https://raw.githubusercontent.com/advxzivhsjjdhxhsidifvsh/mobkeyboard/main/main.txt", true))() starterGui:SetCore("SendNotification",{ Title = "Message", Text = "Successfully Executed" }) end) Section:NewButton("ท่าทางรวมทุกท่า", "บิด", function()
    loadstring(game:HttpGet("https://scriptblox.com/raw/Brookhaven-RP-all-emotes-6849"))()


end) local Tab = Window:NewTab("วาปไปหาผู้เล่น") local Section = Tab:NewSection("ผู้เล่น") players = {} for i,v in pairs(game:GetService("Players"):GetChildren()) do table.insert(players,v.Name) end Section:NewDropdown("ชื่อผู้เล่น", " ", players, function(abc) Select = abc end)Section:NewButton("วาปไป", "ควยย", function() game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[Select].Character.HumanoidRootPart.CFrame end) 
 local Tab = Window:NewTab("ตั้งค่า") local Section = Tab:NewSection("ปุ่มเปิดปิด UI") Section:NewKeybind("ปุ่มเปิดปิด UI", "KeybindInfo", Enum.KeyCode.T, function()     Library:ToggleUI() end)
