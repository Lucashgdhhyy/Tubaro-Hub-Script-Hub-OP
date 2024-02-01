local ArrayField = loadstring(game:HttpGet("https://raw.githubusercontent.com/Hosvile/Refinement/main/MC%3AArrayfield%20Library"))()
--Documentation url: https://docs.sirius.menu/community/arrayfield

local Window = ArrayField:CreateWindow({
        Name = "Tubaro Hub",
        LoadingTitle = "Tubaro Hub",
        LoadingSubtitle = "By LK Team",
        ConfigurationSaving = {
            Enabled = false,
            FolderName = nil, -- Create a custom folder for your hub/game
            FileName = "Tubaro Hub Script Hub"
        },
        Discord = {
            Enabled = false,
            Invite = "sirius", -- The Discord invite code, do not include discord.gg/
            RememberJoins = true -- Set this to false to make them join the discord every time they load it up
        },
        KeySystem = false, -- Set this to true to use our key system
        KeySettings = {
            Title = "Tubaro Key system",
            Subtitle = "Key system",
            Note = "Hello Thank you for use my script",
            FileName = "Tubaro Hub Key System",
            SaveKey = false,
            GrabKeyFromSite = true, -- If this is true, set Key below to the RAW site you would like ArrayField to get the key from
            Key = {"tubaro",'LkHub'},
            Actions = { 
                [1] = { 
                    Text = 'Copy you key',
                    OnPress = function()             

                    end,
                }
            },
        }
    })
    local Tab = Window:CreateTab("Blade Ball", 4483362458) -- Title, Image  

local Button = Tab:CreateButton({
        Name = "Bedol Hub",
        Info = {
            Title = 'Bedol Hub',
            Description = 'Bedol Hub.',
        },
        Interact = 'Execute',
        Callback = function()        loadstring(game:HttpGet('https://raw.githubusercontent.com/nqxlOfc/Loaders/main/Blade_Ball.lua'))()          
            print('Pressed')
        end,
    })
  
local Button = Tab:CreateButton({
        Name = "Twilight Hub",
        Info = {
            Title = 'Twilight',
            Description = 'Bedol Hub.',
        },
        Interact = 'Execute',
        Callback = function()        loadstring(game:HttpGet('https://raw.githubusercontent.com/0x1s2s/twilightxd/main/twilightlol'))()        
            print('Pressed')
        end,
    })

 local Tab = Window:CreateTab("Blox Fruit", 4483362458) -- Title, Image 


local Button = Tab:CreateButton({
        Name = "Redz Hub",
        Info = {
            Title = 'Redz Hub',
            Description = '.',
        },
        Interact = 'Execute',
        Callback = function()        loadstring(game:HttpGet("https://raw.githubusercontent.com/REDzHUB/BloxFruits/main/redz9999"))()
            print('Pressed')
        end,
    })


