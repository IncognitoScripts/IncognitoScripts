if game.PlaceId == 6403373529 then
local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "Incognito Hub", HidePremium = false, 
IntroText = "Incognito Hub", SaveConfig = true, ConfigFolder = "Incognito Hub"})

local Tab = Window:MakeTab({
	Name = "Main",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = Tab:AddSection({
	Name = "Mini glove abuser (Works everywhere even in lobby)"
})

OrionLib:MakeNotification({
	Name = "Made by Incognito Scripts",
	Content = "Subscribe to my channel! @IncognitoScripts",
	Image = "rbxassetid://4483345998",
	Time = 5
})

Tab:AddButton({
	Name = "Diamond Enable/Disable",
	Callback = function()
      		game:GetService("ReplicatedStorage").Rockmode:FireServer()

  	end    
})

Tab:AddButton({
	Name = "zzZZZ Enable/Disable",
	Callback = function()
      		game:GetService("ReplicatedStorage").ZZZZZZZSleep:FireServer()

  	end    
})


Tab:AddButton({
	Name = "Ghost Activate",
	Callback = function()
      		game:GetService("ReplicatedStorage").Ghostinvisibilityactivated:FireServer()

  	end    
})

Tab:AddButton({
	Name = "Ghost Deactivate",
	Callback = function()
      		game:GetService("ReplicatedStorage").Ghostinvisibilitydeactivated:FireServer()

  	end    
})

Tab:AddButton({
	Name = "Cloud Ability",
	Callback = function()
      		game:GetService("ReplicatedStorage").CloudAbility:FireServer()

  	end    
})

local Tab = Window:MakeTab({
	Name = "Teleport",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = Tab:AddSection({
	Name = "Teleports"
})

Tab:AddButton({
	Name = "Lobby",
	Callback = function()
      		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-793, 328, -2)
  	end    
})

Tab:AddButton({
	Name = "Arena",
	Callback = function()
      		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(0, -5, 0)
  	end    
})

Tab:AddButton({
	Name = "Tournament",
	Callback = function()
      		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3410, 84, 0)
  	end    
})

local Tab = Window:MakeTab({
	Name = "Credit",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = Tab:AddSection({
	Name = "Credits"
})

Tab:AddButton({
	Name = "Youtube: @IncognitoScripts",
	Callback = function()
      		print("Incognito Scripts")
  	end    
})

end
