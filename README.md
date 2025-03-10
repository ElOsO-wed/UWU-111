-- Crear ScreenGui
local screenGui = Instance.new("ScreenGui")
screenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

-- Crear fondo negro (cubre toda la pantalla)
local background = Instance.new("Frame")
background.Parent = screenGui
background.Size = UDim2.new(1, 0, 1, 0) -- Ocupa toda la pantalla
background.Position = UDim2.new(0, 0, 0, 0)
background.BackgroundColor3 = Color3.fromRGB(0, 0, 0) -- Negro

-- Crear texto de créditos
local textLabel = Instance.new("TextLabel")
textLabel.Parent = background
textLabel.Size = UDim2.new(1, 0, 1, 0) -- Ocupa toda la pantalla
textLabel.Position = UDim2.new(0, 0, 0, 0)
textLabel.Font = Enum.Font.LuckiestGuy
textLabel.Text = "Made BY: YANSER_EXPLOIT\nHELPER: ELOSO"
textLabel.TextColor3 = Color3.fromRGB(255, 255, 255) -- Texto blanco
textLabel.BackgroundTransparency = 1 -- Hace que el fondo del texto sea transparente
textLabel.TextScaled = true
textLabel.TextWrapped = true

-- Esperar 5 segundos y eliminar el mensaje
task.wait(5)
screenGui:Destroy()

-- Ejecutar el GUI original
local function runGui()
    loadstring([[ 
        -- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local TextButton = Instance.new("TextButton")
local UICorner = Instance.new("UICorner")
local Frame = Instance.new("Frame")
local UICorner_2 = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")
local UICorner_3 = Instance.new("UICorner")
local TextLabel_2 = Instance.new("TextLabel")
local UICorner_4 = Instance.new("UICorner")
local TextButton_2 = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local TextButton_3 = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local TextButton_4 = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local TextButton_5 = Instance.new("TextButton")
local UICorner_8 = Instance.new("UICorner")
local TextLabel_3 = Instance.new("TextLabel")
local TextButton_6 = Instance.new("TextButton")
local UICorner_9 = Instance.new("UICorner")
local TextButton_7 = Instance.new("TextButton")
local UICorner_10 = Instance.new("UICorner")
local TextButton_8 = Instance.new("TextButton")
local UICorner_11 = Instance.new("UICorner")

--Properties:

ScreenGui.Parent = game.CoreGui
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
ScreenGui.ResetOnSpawn = false

TextButton.Parent = ScreenGui
TextButton.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton.BorderSizePixel = 0
TextButton.Position = UDim2.new(0.913880467, 0, 0, 0)
TextButton.Size = UDim2.new(0, 78, 0, 32)
TextButton.Font = Enum.Font.LuckiestGuy
TextButton.Text = "Abrir"
TextButton.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton.TextScaled = true
TextButton.TextSize = 14.000
TextButton.TextStrokeTransparency = 0.000
TextButton.TextWrapped = true

UICorner.Parent = TextButton

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0, 0, 0.0269012451, 0)
Frame.Size = UDim2.new(0, 205, 0, 335)
Frame.Visible = false
Frame.Active = true
Frame.Draggable = true

UICorner_2.Parent = Frame

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Size = UDim2.new(0, 205, 0, 32)
TextLabel.Font = Enum.Font.LuckiestGuy
TextLabel.Text = "simulador de  bomba espiritual"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextStrokeTransparency = 0.000
TextLabel.TextWrapped = true

UICorner_3.Parent = TextLabel

TextLabel_2.Parent = Frame
TextLabel_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.BorderSizePixel = 0
TextLabel_2.Position = UDim2.new(0, 0, 0.884476542, 0)
TextLabel_2.Size = UDim2.new(0, 205, 0, 32)
TextLabel_2.Font = Enum.Font.LuckiestGuy
TextLabel_2.Text = "Made BY: YANSER_EXPLOIT   HELPER ELOSO"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextScaled = true
TextLabel_2.TextSize = 14.000
TextLabel_2.TextStrokeTransparency = 0.000
TextLabel_2.TextWrapped = true

UICorner_4.Parent = TextLabel_2

TextButton_2.Parent = Frame
TextButton_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.BorderSizePixel = 0
TextButton_2.Position = UDim2.new(0, 0, 0.105852544, 0)
TextButton_2.Size = UDim2.new(0, 205, 0, 40)
TextButton_2.Font = Enum.Font.Creepster
TextButton_2.Text = "Auto power 90b "
TextButton_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_2.TextScaled = true
TextButton_2.TextSize = 14.000
TextButton_2.TextWrapped = true
TextButton_2.MouseButton1Click:Connect(function()
	while true do
		wait(0.1)
		game:GetService("ReplicatedStorage").Remotes.AddWheelSpinValue:FireServer("Power",90000000000)
	end	
	end)

UICorner_5.Parent = TextButton_2

TextButton_3.Parent = Frame
TextButton_3.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_3.BorderSizePixel = 0
TextButton_3.Position = UDim2.new(-0.00487804879, 0, 0.221477509, 0)
TextButton_3.Size = UDim2.new(0, 205, 0, 40)
TextButton_3.Font = Enum.Font.Creepster
TextButton_3.Text = "Tp ramdo player"
TextButton_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_3.TextScaled = true
TextButton_3.TextSize = 14.000
TextButton_3.TextWrapped = true
TextButton_3.MouseButton1Click:Connect(function()
	-- Servicios y variables
	local Players = game:GetService("Players")
	local UserInputService = game:GetService("UserInputService")
	local VirtualUser = game:GetService("VirtualUser") -- Simula clics
	local attacker = Players.LocalPlayer
	local distanceBehind = 6 -- Distancia detrás del enemigo
	local attacking = false -- Estado del ataque
	local dragging = false -- Control para arrastrar el botón
	local dragOffset = Vector2.new()

	-- Crear GUI
	local screenGui = Instance.new("ScreenGui")
	screenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

	local button = Instance.new("TextButton")
	button.Parent = screenGui
	button.Size = UDim2.new(0, 200, 0, 50)
	button.Position = UDim2.new(0.5, -100, 0.9, 0)
	button.Text = "Activar Auto-Ataque"
	button.BackgroundColor3 = Color3.fromRGB(0, 255, 0)
	button.TextScaled = true
	button.Draggable = false -- Esta propiedad ya no funciona en scripts modernos, lo haremos manualmente

	-- Función para obtener un jugador aleatorio
	local function getRandomPlayer()
		local players = {}
		for _, player in pairs(Players:GetPlayers()) do
			if player ~= attacker then
				table.insert(players, player)
			end
		end
		if #players > 0 then
			return players[math.random(1, #players)]
		end
		return nil
	end

	-- Función para teletransportarse detrás de la cabeza del objetivo
	local function teleportBehind(targetPlayer)
		local targetCharacter = targetPlayer.Character
		if targetCharacter and targetCharacter:FindFirstChild("Head") and attacker.Character then
			local head = targetCharacter.Head.Position
			attacker.Character:SetPrimaryPartCFrame(CFrame.new(head) * CFrame.new(0, 0, -distanceBehind))
		end
	end

	-- Función para seguir la cabeza del jugador objetivo
	local function followPlayer(targetPlayer)
		while attacking and targetPlayer and targetPlayer.Character and targetPlayer.Character:FindFirstChild("Head") do
			local headPosition = targetPlayer.Character.Head.Position
			local behindHead = headPosition - (targetPlayer.Character.Head.CFrame.LookVector * distanceBehind)

			if attacker.Character then
				attacker.Character:SetPrimaryPartCFrame(CFrame.new(behindHead))
			end

			-- Simular clic automático de ataque
			VirtualUser:Button1Down(Vector2.new()) -- Simula presionar clic izquierdo
			wait(0.1) -- Espera un poco antes de moverse de nuevo
		end
	end

	-- Función para esperar hasta que el objetivo sea eliminado
	local function waitUntilTargetIsDead(targetPlayer)
		local targetCharacter = targetPlayer.Character
		if targetCharacter and targetCharacter:FindFirstChild("Humanoid") then
			while targetCharacter.Humanoid.Health > 0 do
				wait(1)
			end
		end
	end

	-- Función principal de ataque
	local function attack()
		while attacking do
			local targetPlayer = getRandomPlayer()
			if targetPlayer then
				teleportBehind(targetPlayer)
				followPlayer(targetPlayer)
				waitUntilTargetIsDead(targetPlayer)
			else
				print("No hay jugadores disponibles para atacar.")
			end
			wait(1)
		end
	end

	-- Evento del botón para activar/desactivar el ataque
	button.MouseButton1Click:Connect(function()
		attacking = not attacking

		if attacking then
			button.Text = "Desactivar Auto-Ataque"
			button.BackgroundColor3 = Color3.fromRGB(255, 0, 0) -- Rojo (desactivar)
			attack()
		else
			button.Text = "Activar Auto-Ataque"
			button.BackgroundColor3 = Color3.fromRGB(0, 255, 0) -- Verde (activar)
		end
	end)

	-- Eventos para mover el botón (arrastrar)
	button.InputBegan:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton1 then
			dragging = true
			dragOffset = Vector2.new(input.Position.X - button.AbsolutePosition.X, input.Position.Y - button.AbsolutePosition.Y)
		end
	end)

	UserInputService.InputChanged:Connect(function(input)
		if dragging and input.UserInputType == Enum.UserInputType.MouseMovement then
			button.Position = UDim2.new(0, input.Position.X - dragOffset.X, 0, input.Position.Y - dragOffset.Y)
		end
	end)

	UserInputService.InputEnded:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton1 then
			dragging = false
		end
	end)

end)

UICorner_6.Parent = TextButton_3

TextButton_4.Parent = Frame
TextButton_4.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_4.BorderSizePixel = 0
TextButton_4.Position = UDim2.new(-0.00487804879, 0, 0.736556709, 0)
TextButton_4.Size = UDim2.new(0, 205, 0, 40)
TextButton_4.Font = Enum.Font.Creepster
TextButton_4.Text = "Rejoin"
TextButton_4.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_4.TextScaled = true
TextButton_4.TextSize = 14.000
TextButton_4.TextWrapped = true
TextButton_4.MouseButton1Click:Connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/Jelly-plays/Rejoin-script/main/obf_L744By559M18BbuseSG6en8r1zL31daK9060LV7WyvmS4bQp92aONWfwRE36FdcZ.lua.txt"))();
end)

UICorner_7.Parent = TextButton_4

TextButton_5.Parent = Frame
TextButton_5.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_5.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_5.BorderSizePixel = 0
TextButton_5.Position = UDim2.new(-0.00975609757, 0, 0.614772081, 0)
TextButton_5.Size = UDim2.new(0, 205, 0, 40)
TextButton_5.Font = Enum.Font.Creepster
TextButton_5.Text = "Destruir"
TextButton_5.TextColor3 = Color3.fromRGB(255, 0, 0)
TextButton_5.TextScaled = true
TextButton_5.TextSize = 14.000
TextButton_5.TextWrapped = true
TextButton_5.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer:Kick("Wow que anti cheat tiene el serve porfavor reunete nueva mente")
end)

UICorner_8.Parent = TextButton_5

TextLabel_3.Parent = Frame
TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
TextLabel_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.BorderSizePixel = 0
TextLabel_3.Position = UDim2.new(0.00487804879, 0, 0.566825211, 0)
TextLabel_3.Size = UDim2.new(0, 204, 0, 16)
TextLabel_3.Font = Enum.Font.LuckiestGuy
TextLabel_3.Text = "Helper: ELOSO"
TextLabel_3.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.TextScaled = true
TextLabel_3.TextSize = 14.000
TextLabel_3.TextWrapped = true

TextButton_6.Parent = Frame
TextButton_6.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_6.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_6.BorderSizePixel = 0
TextButton_6.Position = UDim2.new(-0.00975609757, 0, 0.337941885, 0)
TextButton_6.Size = UDim2.new(0, 205, 0, 40)
TextButton_6.Font = Enum.Font.Creepster
TextButton_6.Text = "Tp asia la zona del rey"
TextButton_6.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_6.TextScaled = true
TextButton_6.TextSize = 14.000
TextButton_6.TextWrapped = true
TextButton_6.MouseButton1Click:Connect(function()
	-- Script de Teletransporte en secuencia activado por el jugador
	local Players = game:GetService("Players")
	local player = Players.LocalPlayer -- Obtener el jugador local
	local character = player.Character or player.CharacterAdded:Wait() -- Asegurarse de que el personaje estÃ¡ disponible
	local humanoid = character:WaitForChild("Humanoid") -- Esperar a que el humanoide estÃ© disponible

	-- Definir las posiciones de teletransporte en orden
	local teleportPositions = {
		Vector3.new(759, 976, -668),   -- Primera posiciÃ³n
	}

	-- FunciÃ³n para teletransportar al jugador
	local function teleportToPositions()
		for _, position in ipairs(teleportPositions) do
			-- Teletransportar al jugador a cada posiciÃ³n de la lista
			character:SetPrimaryPartCFrame(CFrame.new(position))

			-- Esperar unos segundos antes de ir a la siguiente posiciÃ³n (ajustable)
			wait(1)
		end
	end

	-- Llamar a la funciÃ³n de teletransporte
	teleportToPositions()
end)

UICorner_9.Parent = TextButton_6

TextButton_7.Parent = Frame
TextButton_7.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_7.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_7.BorderSizePixel = 0
TextButton_7.Position = UDim2.new(-0.00975609757, 0, 0.439434409, 0)
TextButton_7.Size = UDim2.new(0, 205, 0, 40)
TextButton_7.Font = Enum.Font.Creepster
TextButton_7.Text = "Dar 50 giros"
TextButton_7.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_7.TextScaled = true
TextButton_7.TextSize = 14.000
TextButton_7.TextWrapped = true
TextButton_7.MouseButton1Click:Connect(function()
	game:GetService("ReplicatedStorage").Remotes.AddWheelSpinValue:FireServer("Spins",50)
end)

UICorner_10.Parent = TextButton_7

TextButton_8.Parent = ScreenGui
TextButton_8.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_8.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_8.BorderSizePixel = 0
TextButton_8.Position = UDim2.new(0.880445778, 0, 0, 0)
TextButton_8.Size = UDim2.new(0, 33, 0, 28)
TextButton_8.Font = Enum.Font.LuckiestGuy
TextButton_8.Text = "Cerarr"
TextButton_8.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_8.TextScaled = true
TextButton_8.TextSize = 14.000
TextButton_8.TextStrokeTransparency = 0.000
TextButton_8.TextWrapped = true

UICorner_11.Parent = TextButton_8

-- Scripts:

local function UGPUNH_fake_script() -- TextButton.LocalScript 
	local script = Instance.new('LocalScript', TextButton)

	local button = script.Parent -- Botón
	local frame = script.Parent.Parent:FindFirstChild("Frame") -- Frame a mostrar/ocultar
	local dragging = false
	local offset = Vector2.new(0, 0)
	
	if not frame then
		warn("No se encontró el Frame. Asegúrate de que el nombre sea correcto.")
		return
	end
	
	-- Estado inicial
	button.Text = "Abrir"
	button.Draggable = false -- Esta propiedad no funciona en scripts modernos, haremos el drag manualmente
	
	-- Evento para mostrar/ocultar el frame
	button.MouseButton1Click:Connect(function()
		if frame.Visible then
			frame.Visible = false
			button.Text = "Abrir"
		else
			frame.Visible = true
			button.Text = "Cerrar"
		end
	end)
	
	-- Función para iniciar el arrastre
	button.InputBegan:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton1 then
			dragging = true
			offset = Vector2.new(input.Position.X - button.AbsolutePosition.X, input.Position.Y - button.AbsolutePosition.Y)
		end
	end)
	
	-- Función para mover el botón mientras se arrastra
	game:GetService("UserInputService").InputChanged:Connect(function(input)
		if dragging and input.UserInputType == Enum.UserInputType.MouseMovement then
			button.Position = UDim2.new(0, input.Position.X - offset.X, 0, input.Position.Y - offset.Y)
		end
	end)
	
	-- Función para soltar el botón
	game:GetService("UserInputService").InputEnded:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton1 then
			dragging = false
		end
	end)
	
end
coroutine.wrap(UGPUNH_fake_script)()
local function XAOGAH_fake_script() -- TextButton_8.LocalScript 
	local script = Instance.new('LocalScript', TextButton_8)

	local button = script.Parent -- Botón
	local frame = script.Parent.Parent:FindFirstChild("Frame") -- Frame a mostrar/ocultar
	local dragging = false
	local offset = Vector2.new(0, 0)
	
	if not frame then
		warn("No se encontró el Frame. Asegúrate de que el nombre sea correcto.")
		return
	end
	
	-- Estado inicial
	button.Text = "Abrir"
	button.Draggable = false -- Esta propiedad no funciona en scripts modernos, haremos el drag manualmente
	
	-- Evento para mostrar/ocultar el frame
	button.MouseButton1Click:Connect(function()
		if frame.Visible then
			frame.Visible = false
			button.Text = "Abrir"
		else
			frame.Visible = true
			button.Text = "Cerrar"
		end
	end)
	
	-- Función para iniciar el arrastre
	button.InputBegan:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton1 then
			dragging = true
			offset = Vector2.new(input.Position.X - button.AbsolutePosition.X, input.Position.Y - button.AbsolutePosition.Y)
		end
	end)
	
	-- Función para mover el botón mientras se arrastra
	game:GetService("UserInputService").InputChanged:Connect(function(input)
		if dragging and input.UserInputType == Enum.UserInputType.MouseMovement then
			button.Position = UDim2.new(0, input.Position.X - offset.X, 0, input.Position.Y - offset.Y)
		end
	end)
	
	-- Función para soltar el botón
	game:GetService("UserInputService").InputEnded:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton1 then
			dragging = false
		end
	end)
	
end
coroutine.wrap(XAOGAH_fake_script)()
local function JKATVWQ_fake_script() -- TextButton_8.LocalScript 
	local script = Instance.new('LocalScript', TextButton_8)

	local button = script.Parent -- Referencia al botón
	local screenGui = button.Parent -- Asumiendo que el botón está dentro de ScreenGui
	
	button.MouseButton1Click:Connect(function()
		for _, child in pairs(screenGui:GetChildren()) do
			if child:IsA("TextButton") then
				child:Destroy() -- Destruye todos los botones dentro de ScreenGui
			end
		end
	end)
	
end
coroutine.wrap(JKATVWQ_fake_script)()

    ]])()
end

runGui() -- Ejecutar el GUI después de eliminar el mensaje
