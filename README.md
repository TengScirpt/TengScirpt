local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "Charmed:REBRON SCRIPT BY TengSCRIPT", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})


local Tab1 = Window:MakeTab({
	Name = "CHARACTERS!!",
	Icon = "0",
	PremiumOnly = false
})


local Section1 = Tab1:AddSection({
	Name = "CHARACTER"
})


Tab1:AddButton({
	Name = "Prue",
	Callback = function()
      		game.ReplicatedStorage.Change:FireServer("Prue")
  	end    
})

Tab1:AddButton({
	Name = "Paige",
	Callback = function()
      		game.ReplicatedStorage.Change:FireServer("Paige")
  	end    
})

Tab1:AddButton({
	Name = "Phoebe",
	Callback = function()
      		game.ReplicatedStorage.Change:FireServer("Phoebe")
  	end    
})

Tab1:AddButton({
	Name = "Piper",
	Callback = function()
      		game.ReplicatedStorage.Change:FireServer("Piper")
  	end    
})

Tab1:AddButton({
	Name = "Billie",
	Callback = function()
      		game.ReplicatedStorage.Change:FireServer("Billie")
  	end    
})

Tab1:AddButton({
	Name = "Christy",
	Callback = function()
      		game.ReplicatedStorage.Change:FireServer("Christy")
  	end    
})

Tab1:AddButton({
	Name = "Chris",
	Callback = function()
      		game.ReplicatedStorage.Change:FireServer("Chris")
  	end    
})

Tab1:AddButton({
	Name = "Bianca",
	Callback = function()
      		game.ReplicatedStorage.Change:FireServer("Bianca")
  	end    
})

Tab1:AddButton({
	Name = "Wyatt",
	Callback = function()
      		game.ReplicatedStorage.Change:FireServer("Wyatt")
  	end    
})


Tab1:AddButton({
	Name = "Ava",
	Callback = function()
      		game.ReplicatedStorage.Change:FireServer("Ava")
  	end    
})

Tab1:AddButton({
	Name = "Evil Enchantress",
	Callback = function()
      		game.ReplicatedStorage.Change:FireServer("Evil Enchantress")
  	end    
})

Tab1:AddButton({
	Name = "Sea Hag",
	Callback = function()
      		game.ReplicatedStorage.Change:FireServer("Sea Hag")
  	end    
})


Tab1:AddButton({
	Name = "P.Baxtar",
	Callback = function()
      		game.ReplicatedStorage.Change:FireServer("P Baxtar")
  	end    
})

Tab1:AddButton({
	Name = "P.Bowen",
	Callback = function()
      		game.ReplicatedStorage.Change:FireServer("P Bowen")
  	end    
})

Tab1:AddButton({
	Name = "P.Russell",
	Callback = function()
      		game.ReplicatedStorage.Change:FireServer("P Russell")
  	end    
})


Tab1:AddButton({
	Name = "Tuatha",
	Callback = function()
      		game.ReplicatedStorage.Change:FireServer("Tuatha")
  	end    
})


Tab1:AddButton({
	Name = "Margo",
	Callback = function()
      		game.ReplicatedStorage.Change:FireServer("Margo")
  	end    
})


Tab1:AddButton({
	Name = "Mitzy",
	Callback = function()
      		game.ReplicatedStorage.Change:FireServer("Mitzy")
  	end    
})

Tab1:AddButton({
	Name = "Mabel",
	Callback = function()
      		game.ReplicatedStorage.Change:FireServer("Mabel")
  	end    
})

local Tab2 = Window:MakeTab({
	Name = "Powers/Spells",
	Icon = "0",
	PremiumOnly = false
})


Tab2:AddButton({
	Name = "Hollow Spell",
	Callback = function()
         game.Workspace.Locations.Spells.Hollow.Piper.Value = true
         game.Workspace.Locations.Spells.Hollow.Paige.Value = true
         game.Workspace.Locations.Spells.Hollow.Prue.Value = true
         game.Workspace.Locations.Spells.Hollow.Phoebe.Value = true
  	end    
})

Tab2:AddButton({
	Name = "Become Evill Phoebe",
	Callback = function()
        game.ReplicatedStorage.Events.Misc.TurnEvilPhoebe:FireServer()
  	end    
})


local Tab3 = Window:MakeTab({
	Name = "No Hunger!",
	Icon = "0",
	PremiumOnly = false
})


Tab2:AddButton({
	Name = "Feed",
	Callback = function()
        game.Players.LocalPlayer.HungerVal.Value =  game.Players.LocalPlayer.HungerVal.Value + 1000
  	end    
})




