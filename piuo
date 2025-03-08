local redzlib = loadstring(game:HttpGet("https://raw.githubusercontent.com/AnhDzaiScript/GiaoDien/refs/heads/main/AnhTuanIOS"))()
local Window = redzlib:MakeWindow({
  Title = "Tuấn Anh IOS Hub",
  SubTitle = "discord.gg/gRn2S6m4YS",
})

local AFKOptions = {}

local Discord = Window:MakeTab({"Discode", "info"})
Discord:AddDiscordInvite({
  Name = "Tham Gia Discode",
  Description = "Discode Đây Cu",
  Logo = "rbxassetid://96079961519347",
  Invite = "https://discord.gg/gRn2S6m4YS"
})
local Discord = Window:MakeTab({"Facebook", "info"})
Discord:AddDiscordInvite({
  Name = "Tuấn Anh",
  Description = "Phở Bò Đó Cu",
  Logo = "rbxassetid://96079961519347",
  Invite = "https://www.facebook.com/tuanangg10"
  })
local Tab = Window:MakeTab({"Script Hot Nhất",
	Icon = "rbxassetid://10723407389",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Redz Hub",
	Callback = function()
       loadstring(game:HttpGet("https://raw.githubusercontent.com/realredz/BloxFruits/refs/heads/main/Source.lua"))(Settings)
  	end    
})
Tab:AddButton({
	Name = "w-azure",
	Callback = function()
       loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/3b2169cf53bc6104dabe8e19562e5cc2.lua"))()
  	end    
})
Tab:AddButton("TuanAnhIOS_Button", {
    Title = "Auto Nhặt Rương",
    Description = "Bật Tắt Chest TAnhDzai✅",
    Callback = function(value)
        _G.TuanAnhIOS_Enabled = value

        if value then
            -- Bật script (chạy trên luồng riêng)
            ScriptThread = task.spawn(function()
                loadstring(game:HttpGet("https://raw.githubusercontent.com/AnhDzaiScript/AutoChest/refs/heads/main/AutoChestTuanAnhIOS.Lua"))()
            end)
        else
            -- Dừng script bằng cách hủy luồng
            if ScriptThread then
                task.cancel(ScriptThread)
                ScriptThread = nil
            end
        end
    end
})
Tab:AddButton({
	Name = "Xero Hub",
	Callback = function()
     loadstring(game:HttpGet("https://raw.githubusercontent.com/Xero2409/XeroHub/refs/heads/main/main.lua"))()
  	end    
})
Tab:AddButton({
	Name = "Zenith Hub",
	Callback = function()
       loadstring(game:HttpGet("https://raw.githubusercontent.com/Efe0626/RaitoHub/main/Script"))()
  	end    
})
Tab:AddButton({
	Name = "Bắp Red Hub",
	Callback = function()
       loadstring(game:HttpGet("https://raw.githubusercontent.com/LuaCrack/BapRed/main/BapRedHub"))()
  	end    
})
Tab:AddButton({
	Name = "Trẩu Roblox",
	Callback = function()
       loadstring(game:HttpGet("https://raw.githubusercontent.com/LuaCrack/TrauHub/refs/heads/main/TrauV1"))()
  	end    
})
Tab:AddButton({
	Name = "Zis Hub",
	Callback = function()
       loadstring(game:HttpGet("https://raw.githubusercontent.com/giaotrinhhoc/ZisRb/refs/heads/main/ZisRbV5"))()
  	end    
})
Tab:AddButton({
	Name = "Quantum Hub",
	Callback = function()
       loadstring(game:HttpGet("https://raw.githubusercontent.com/Trustmenotcondom/QTONYX/refs/heads/main/QuantumOnyx.lua"))()
  	end    
})
Tab:AddButton({
	Name = "Cokka Hub",
	Callback = function()
       loadstring(game:HttpGet"https://raw.githubusercontent.com/UserDevEthical/Loadstring/main/CokkaHub.lua")()
  	end    
})
Tab:AddButton({
	Name = "HoHo Hub Phải Get Key",
	Callback = function()
       loadstring(game:HttpGet("https://raw.githubusercontent.com/acsu123/HOHO_H/main/Loading_UI"))()
  	end    
})
local Tab4 = Window:MakeTab({"Script Premium Free",
	Icon = "rbxassetid://10709761889",
	PremiumOnly = false
})
Tab4:AddButton({
	Name = "Cụt Tay Hub Auto Mirage",
	Callback = function()
         repeat wait(5) until game:IsLoaded()
         loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/a1498369f289af2671cca90085f23fb8.lua"))()
end
})
Tab4:AddButton({
	Name = "KaiTan Premium",
	Callback = function()
         repeat wait(5) until game:IsLoaded()
         loadstring(game:HttpGet("https://raw.githubusercontent.com/simple-hubs/contents/refs/heads/main/bloxfruit-kaitan-main.lua"))()
end
})
Tab4:AddButton({
	Name = "Auto Bounty Xero Hub",
	Callback = function()
         repeat wait(5) until game:IsLoaded()
         loadstring(game:HttpGet("https://raw.githubusercontent.com/pisovn/OisiRoblox1/refs/heads/main/AutoBountyXero"))()
end
})
Tab4:AddButton({
	Name = "Fix Lag Premium",
	Callback = function()
         repeat wait(5) until game:IsLoaded()
         loadstring(game:HttpGet("https://raw.githubusercontent.com/TurboLite/Script/main/FixLag.lua"))()
end
})
Tab4:AddButton({
	Name = "Aim Buddy Gun|Key:Kao",
	Callback = function()
         repeat wait(5) until game:IsLoaded()
         loadstring(game:HttpGet("https://raw.githubusercontent.com/Kaodontsuyy/BloxFruit/refs/heads/main/Kaohub.lua"))()
end
})
local Tab4 = Window:MakeTab({"Script Banana |Maru",
	Icon = "rbxassetid://10709761889",
	PremiumOnly = false
})
Tab4:AddButton({
	Name = "Maru Hub✅",
	Callback = function()
         repeat wait(5) until game:IsLoaded()
         loadstring(game:HttpGet("https://raw.githubusercontent.com/AnhDzaiScript/ScriptMaru/refs/heads/main/MaruHubPremium.Lua"))()
end
})
Tab4:AddButton({
	Name = "Banana Hub✅",
	Callback = function()
         repeat wait(5) until game:IsLoaded()
         loadstring(game:HttpGet("https://raw.githubusercontent.com/AnhDzaiScript/ScriptMaru/refs/heads/main/MaruHubPremium.Lua"))()
end
})
