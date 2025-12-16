--Inicializando a Biblioteca
local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/jensonhirst/Orion/main/source')))()

--Criando uma janela
local Window = OrionLib:MakeWindow({Name = "Title of the library", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})

--Criando uma aba
local TabLevel = Window:MakeTab({
	Name = "Quest&Level",
	Icon = "rbxassetid://10723407389",
	PremiumOnly = false
})

--Criando uma aba
local TabSea = Window:MakeTab({
	Name = "Sea",
	Icon = "rbxassetid://10709761530",
	PremiumOnly = false
})

--Criando uma aba
local Tab = Window:MakeTab({
	Name = "Reca",
	Icon = "rbxassetid://10747372167",
	PremiumOnly = false
})

--Criando uma aba
local Tab = Window:MakeTab({
	Name = "Teleport",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

--Criando uma aba
local Tab = Window:MakeTab({
	Name = "Status",
	Icon = "rbxassetid://10709770317",
	PremiumOnly = false
})

--Criando uma aba
local Tab = Window:MakeTab({
	Name = "Configurações",
	Icon = "rbxassetid://10734950309",
	PremiumOnly = false
})

--Criando uma alternância de caixa de seleção
TabLevel:AddToggle({
	Name = "This is a toggle!",
	Default = false,
	Callback = function(Value)
		print(Value)
	end    
})

--Criando uma alternância de caixa de seleção
TabSea:AddToggle({
	Name = "This is a toggle!",
	Default = false,
	Callback = function(Value)
		print(Value)
	end    
}) 
