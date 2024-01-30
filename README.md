local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "Tubaro Br Hub|Scripts Hub V1.2", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})
local Tab = Window:MakeTab({
	Name = "Start",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})
OrionLib:MakeNotification({
	Name = "Super cool",
	Content = "Script Hub",
	Image = "rbxassetid://4483345998",
	Time = 5
})

local Tab = Window:MakeTab({
	Name = "blade ball hubs",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Bedol Hub",
	Callback = function()  
      		print("button pressed")      loadstring(game:HttpGet('https://raw.githubusercontent.com/nqxlOfc/Loaders/main/Blade_Ball.lua'))() 
    end
})
Tab:AddButton({
	Name = "Twilight ",
	Callback = function() 
      		print("button pressed")   loadstring(game:HttpGet('https://raw.githubusercontent.com/0x1s2s/twilightxd/main/twilightlol'))()   
   end
})
   
Tab:AddButton({
	Name = "Noname script ",
	Callback = function()  
      		print("button pressed")   loadstring(game:HttpGet("https://paste.gg/p/anonymous/0425151104df470cb8203508e256b40a/files/aff63dcd12b04bfe8f6d9851eb6b2d3e/raw"))()
    end
})

local Tab = Window:MakeTab({
	Name = "blox fruit",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Redz Hub",
	Callback = function()  
      		print("button pressed")    loadstring(game:HttpGet("https://raw.githubusercontent.com/REDzHUB/BloxFruits/main/redz9999"))()
    end
})

Tab:AddButton({
	Name = "Night Hub(Nao funcionando)",
	Callback = function()  
      		print("button pressed")    loadstring(game:HttpGet("https://raw.githubusercontent.com/NIGHTHUBONTOP/Main/main/NIGHT-HUB"))()
    end
})


Tab:AddButton({
	Name = "Zee Hub",
	Callback = function()  
      		print("button pressed")     loadstring(game:HttpGet("https://link.trwxz.com/LS-Zee-Hub-VIP"))()
     end
})

Tab:AddButton({
	Name = "M Tries",
	Callback = function()  
      		print("button pressed")    loadstring(game:HttpGet("https://raw.githubusercontent.com/Minhtriettt/Free-Script/main/MTriet-Hub.lua"))()
     end
})

local Tab = Window:MakeTab({
	Name = "Pet simulator 99",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Redz Hub(no key)",
	Callback = function()  
      		print("button pressed")    loadstring(game:HttpGet("https://raw.githubusercontent.com/REDzHUB/PetSimulator99/main/redz9999.lua"))()
    end
})

local Tab = Window:MakeTab({
	Name = "doors",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "King Hub",
	Callback = function()  
      		print("button pressed")     loadstring(game:HttpGetAsync("https://pastebin.com/raw/R8QMbhzv"))()
    end
})

local Tab = Window:MakeTab({
	Name = "Muscle legends",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Speed X hub",
	Callback = function()  
      		print("button pressed")     loadstring(game:HttpGet(('https://raw.githubusercontent.com/ahmadsgamer2/Script--Game/main/Muscle-Legends'),true))()
    end
})

local Tab = Window:MakeTab({
	Name = "Haze Piece",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Haze piece(Nao funcionando)",
	Callback = function()  
      		print("button pressed")                 loadstring(game:HttpGet("https://raw.githubusercontent.com/JuninhoOGado/ScriptsSite/main/Script230"))()        
    end
})


local Tab = Window:MakeTab({
	Name = "CMDS Admins",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
	})
	
Tab:AddButton({
	Name = "Infinity yield",
	Callback = function()  
      		print("button pressed")   loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
    end
})

-- Dropdown:Refresh(List<table>,true)
--Dropdown:Set("dropdown option")
OrionLib:Init()
-- destroying the interface: OrionLib:Destroy() 
