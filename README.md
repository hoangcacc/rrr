getgenv().Config = {
    ["Team"] = "Pirates", --// Marines, Pirates
    ["Webhook"] = {
        ["Enable"] = true, --// Enable if you have Webhook Url
        ["Url"] = "https://discord.com/api/webhooks/1140598328514588793/3UV0SPlJMYg5jd7bOg57I7Mua3yrFj74iGh6uAzYgIT6dNOAeObO7wgm6GHU9ps6_YcA" --// Your webhook url
    },
    ["Skip"] = {
        ["V4"] = false, --// Skip V4
        ["Fruit"] = { --// Skip Fruit
            "Portal-Portal"
        }
    },
    ["Chat"] = {
        ["Enable"] = true, --// Enable Chat
        ["Content"] = {"hoang dzvcl"} --// Content
    },
    ["Misc"] = {
        ["Hide If Low Health"] = true, --// Run
        ["Hide Health"] = {5000,7000}, --// Health for run
        ["Lock Camera"] = true, --// Lock Cam to target
        ["FPS Boost"] = true, --// Booster FPS
        ["White Screen"] = false, --// White Screen
        ["Bypass TP"] = true, --// Bypass TP 1 -> 2 hit
        ["Spam All Skill On V4"] = true, --// If you have v4, warn: change your weapon setting
        ["Gun Method"] = false --// Enable if you use gun
    },
    --// Copy Next
    ["Weapons"] = {
        ["Melee"] = {
            ["Enable"] = true,
            ["Delay"] = 1.50,
            ["Skills"] = {
                ["Z"] = {["Enable"] = true, ["HoldTime"] = 0.5},
                ["X"] = {["Enable"] = true, ["HoldTime"] = 0},
                ["C"] = {["Enable"] = true, ["HoldTime"] = 0},
                ["V"] = {["Enable"] = false, ["HoldTime"] = 0}
            }
        },
        ["Blox Fruit"] = {
            ["Enable"] = false,
            ["Delay"] = 3,
            ["Skills"] = {
                ["Z"] = {["Enable"] = true, ["HoldTime"] = 0},
                ["X"] = {["Enable"] = true, ["HoldTime"] = 0},
                ["C"] = {["Enable"] = true, ["HoldTime"] = 0},
                ["V"] = {["Enable"] = true, ["HoldTime"] = 0},
                ["F"] = {["Enable"] = false, ["HoldTime"] = 0}
            }
        },
        --// Copy Next
        ["Sword"] = {
            ["Enable"] = true,
            ["Delay"] = 1.5,
            ["Skills"] = {
                ["Z"] = {["Enable"] = true, ["HoldTime"] = 0.5},
                ["X"] = {["Enable"] = true, ["HoldTime"] = 0}
            } 
        },      
        ["Gun"] = {
            ["Enable"] = false,
            ["Delay"] = 0.7,
            ["Skills"] = {
                ["Z"] = {["Enable"] = true, ["HoldTime"] = 0.1},
                ["X"] = {["Enable"] = true, ["HoldTime"] = 0.3}
            } 
        }
    }
}
repeat wait() until game:IsLoaded()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Minhtriettt/Hunt/main/AutoBountyV2.lua"))()
