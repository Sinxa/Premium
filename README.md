-- Gui to Lua
-- Version: 3.2
 
-- Instances:
 
local SINX = Instance.new("ScreenGui")
local LoginPage = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local Yuh = Instance.new("Frame")
local Key = Instance.new("TextBox")
local UICorner_2 = Instance.new("UICorner")
local Login = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local Discord = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local Link = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")
local Main = Instance.new("Frame")
local Menu = Instance.new("Frame")
local TextLabel_2 = Instance.new("TextLabel")
local SilentAim = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local Headless = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
 
--Properties:
 
SINX.Name = "SINX"
SINX.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
SINX.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
 
LoginPage.Name = "LoginPage"
LoginPage.Parent = SINX
LoginPage.BackgroundColor3 = Color3.fromRGB(56, 56, 56)
LoginPage.Position = UDim2.new(0.0648484826, 0, 0.0872235894, 0)
LoginPage.Size = UDim2.new(0, 295, 0, 495)
LoginPage.Active = true
LoginPage.Draggable = true
 
UICorner.Parent = LoginPage
 
Yuh.Name = "Yuh"
Yuh.Parent = LoginPage
Yuh.BackgroundColor3 = Color3.fromRGB(184, 184, 184)
Yuh.BorderSizePixel = 0
Yuh.Position = UDim2.new(-5.13605773e-05, 0, 0.832814693, 0)
Yuh.Size = UDim2.new(0, 295, 0, 18)
 
Key.Name = "Key"
Key.Parent = LoginPage
Key.BackgroundColor3 = Color3.fromRGB(184, 184, 184)
Key.BorderSizePixel = 0
Key.Position = UDim2.new(0.0644067824, 0, 0.331313133, 0)
Key.Size = UDim2.new(0, 257, 0, 74)
Key.Font = Enum.Font.SourceSans
Key.PlaceholderColor3 = Color3.fromRGB(0, 0, 0)
Key.PlaceholderText = "KEY HERE"
Key.Text = ""
Key.TextColor3 = Color3.fromRGB(0, 0, 0)
Key.TextScaled = true
Key.TextSize = 14.000
Key.TextWrapped = true
 
UICorner_2.Parent = Key
 
Login.Name = "Login"
Login.Parent = LoginPage
Login.BackgroundColor3 = Color3.fromRGB(184, 184, 184)
Login.Position = UDim2.new(0.159322038, 0, 0.529292941, 0)
Login.Size = UDim2.new(0, 200, 0, 50)
Login.Font = Enum.Font.SourceSans
Login.Text = "Login"
Login.TextColor3 = Color3.fromRGB(0, 0, 0)
Login.TextScaled = true
Login.TextSize = 14.000
Login.TextWrapped = true
Login.MouseButton1Down:Connect(function()
	if Key.Text == "aijhdfakjsdhfksjadhfjkalsdfhMADDOXUGLYdasdhasfhsfhaskfdhsadkfhYUHHH" then
		LoginPage.Visible = false
		Main.Visible = true
	end
end)
 
UICorner_3.CornerRadius = UDim.new(1, 1)
UICorner_3.Parent = Login
 
Discord.Name = "Discord"
Discord.Parent = LoginPage
Discord.BackgroundColor3 = Color3.fromRGB(184, 184, 184)
Discord.Position = UDim2.new(0.159322038, 0, 0.137373745, 0)
Discord.Size = UDim2.new(0, 200, 0, 50)
Discord.Font = Enum.Font.SourceSans
Discord.Text = "Discord"
Discord.TextColor3 = Color3.fromRGB(0, 0, 0)
Discord.TextScaled = true
Discord.TextSize = 14.000
Discord.TextWrapped = true
Discord.MouseButton1Down:Connect(function()
	setclipboard(Link.Text)
	Discord.Text = "COPIED!"
	wait(0.5)
	Discord.Text = "Discord"
end)
 
UICorner_4.CornerRadius = UDim.new(1, 1)
UICorner_4.Parent = Discord
 
Link.Name = "Link"
Link.Parent = LoginPage
Link.BackgroundColor3 = Color3.fromRGB(184, 184, 184)
Link.BackgroundTransparency = 1.000
Link.Position = UDim2.new(0.159322038, 0, 0.0484848619, 0)
Link.Size = UDim2.new(0, 200, 0, 50)
Link.Font = Enum.Font.SourceSans
Link.Text = "https://discord.gg/7wPkzJjZkt"
Link.TextColor3 = Color3.fromRGB(0, 0, 0)
Link.TextSize = 1.000
Link.TextTransparency = 1.000
Link.TextWrapped = true
 
UICorner_5.CornerRadius = UDim.new(1, 1)
UICorner_5.Parent = Link
 
TextLabel.Parent = LoginPage
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.Position = UDim2.new(0.159322038, 0, 0.884848475, 0)
TextLabel.Size = UDim2.new(0, 200, 0, 50)
TextLabel.Font = Enum.Font.Roboto
TextLabel.Text = "SINX"
TextLabel.TextColor3 = Color3.fromRGB(184, 184, 184)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true
 
Main.Name = "Main"
Main.Parent = SINX
Main.BackgroundColor3 = Color3.fromRGB(36, 36, 36)
Main.BorderSizePixel = 0
Main.Position = UDim2.new(0.420121223, 0, 0.135135144, 0)
Main.Size = UDim2.new(0, 594, 0, 25)
Main.Visible = false
Main.Active = true
 
Menu.Name = "Menu"
Menu.Parent = Main
Menu.BackgroundColor3 = Color3.fromRGB(56, 56, 56)
Menu.BorderSizePixel = 0
Menu.Position = UDim2.new(0, 0, 0.969228208, 0)
Menu.Size = UDim2.new(0, 594, 0, 343)
 
TextLabel_2.Parent = Main
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.BorderSizePixel = 0
TextLabel_2.Position = UDim2.new(0.445762724, 0, -2.93438262e-07, 0)
TextLabel_2.Size = UDim2.new(0, 64, 0, 25)
TextLabel_2.Font = Enum.Font.Oswald
TextLabel_2.Text = "SINX"
TextLabel_2.TextColor3 = Color3.fromRGB(184, 184, 184)
TextLabel_2.TextScaled = true
TextLabel_2.TextSize = 14.000
TextLabel_2.TextWrapped = true
 
SilentAim.Name = "SilentAim"
SilentAim.Parent = Main
SilentAim.BackgroundColor3 = Color3.fromRGB(36, 36, 36)
SilentAim.Position = UDim2.new(0.0135250818, 0, 1.34769201, 0)
SilentAim.Size = UDim2.new(0, 200, 0, 86)
SilentAim.Font = Enum.Font.Nunito
SilentAim.Text = "SilentAim"
SilentAim.TextColor3 = Color3.fromRGB(184, 184, 184)
SilentAim.TextSize = 50.000
SilentAim.TextWrapped = true
SilentAim.MouseButton1Down:Connect(function()
	_G.Prediction =  (  .18  )
 
	_G.FOV =  (  300  )
 
	_G.AimKey =  (  "c"  )
 
 
--[[
	Do not edit anything under this.
]]
 
	local SilentAim = true
	local LocalPlayer = game:GetService("Players").LocalPlayer
	local Players = game:GetService("Players")
	local Mouse = LocalPlayer:GetMouse()
	local Camera = game:GetService("Workspace").CurrentCamera
	hookmetamethod = hookmetamethod
	Drawing = Drawing
 
	local FOV_CIRCLE = Drawing.new("Circle")
	FOV_CIRCLE.Visible = true
	FOV_CIRCLE.Filled = false
	FOV_CIRCLE.Thickness = 1
	FOV_CIRCLE.Transparency = 1
	FOV_CIRCLE.Color = Color3.new(0, 1, 0)
	FOV_CIRCLE.Radius = _G.FOV
	FOV_CIRCLE.Position = Vector2.new(Camera.ViewportSize.X / 2, Camera.ViewportSize.Y / 2)
 
	Options = {
		Torso = "HumanoidRootPart";
		Head = "Head";
	}
 
	local function MoveFovCircle()
		pcall(function()
			local DoIt = true
			spawn(function()
				while DoIt do task.wait()
					FOV_CIRCLE.Position = Vector2.new(Mouse.X, (Mouse.Y + 36))
				end
			end)
		end)
	end coroutine.wrap(MoveFovCircle)()
 
	Mouse.KeyDown:Connect(function(KeyPressed)
		if KeyPressed == (_G.AimKey:lower()) then
			if SilentAim == false then
				FOV_CIRCLE.Color = Color3.new(0, 1, 0)
				SilentAim = true
			elseif SilentAim == true then
				FOV_CIRCLE.Color = Color3.new(1, 0, 0)
				SilentAim = false
			end
		end
	end)
 
	local oldIndex = nil 
	oldIndex = hookmetamethod(game, "__index", function(self, Index)
		if self == Mouse and (Index == "Hit") then 
			local Distance = 9e9
			local Targete = nil
			if SilentAim then
 
				for _, v in pairs(Players:GetPlayers()) do 
					if v ~= LocalPlayer and v.Character and v.Character:FindFirstChild("HumanoidRootPart") and v.Character:FindFirstChild("Humanoid") and v.Character:FindFirstChild("Humanoid").Health > 0 then
						local Enemy = v.Character	
						local CastingFrom = CFrame.new(Camera.CFrame.Position, Enemy[Options.Torso].CFrame.Position) * CFrame.new(0, 0, -4)
						local RayCast = Ray.new(CastingFrom.Position, CastingFrom.LookVector * 9000)
						local World, ToSpace = workspace:FindPartOnRayWithIgnoreList(RayCast, {LocalPlayer.Character:FindFirstChild("Head")})
						local RootWorld = (Enemy[Options.Torso].CFrame.Position - ToSpace).magnitude
						if RootWorld < 4 then
							local RootPartPosition, Visible = Camera:WorldToScreenPoint(Enemy[Options.Torso].Position)
							if Visible then
								local Real_Magnitude = (Vector2.new(Mouse.X, Mouse.Y) - Vector2.new(RootPartPosition.X, RootPartPosition.Y)).Magnitude
								if Real_Magnitude < Distance and Real_Magnitude < FOV_CIRCLE.Radius then
									Distance = Real_Magnitude
									Targete = Enemy
								end
							end
						end
					end
				end
			end
 
			if Targete ~= nil and Targete[Options.Torso] and Targete:FindFirstChild("Humanoid").Health > 0 then
				if SilentAim then
					local ShootThis = Targete[Options.Torso] -- or Options.Head
					local Predicted_Position = ShootThis.CFrame + (ShootThis.Velocity * _G.Prediction + Vector3.new(0,-1,0)) --  (-1) = Less blatant
					return ((Index == "Hit" and Predicted_Position))
				end
			end
 
		end
		return oldIndex(self, Index)
	end)
end)
 
UICorner_6.CornerRadius = UDim.new(0, 100)
UICorner_6.Parent = SilentAim
 
Headless.Name = "Headless"
Headless.Parent = Main
Headless.BackgroundColor3 = Color3.fromRGB(36, 36, 36)
Headless.Position = UDim2.new(0.648205221, 0, 1.34769201, 0)
Headless.Size = UDim2.new(0, 200, 0, 86)
Headless.Font = Enum.Font.Nunito
Headless.Text = "SA invisible"
Headless.TextColor3 = Color3.fromRGB(184, 184, 184)
Headless.TextSize = 50.000
Headless.TextWrapped = true
Headless.MouseButton1Down:Connect(function()
	_G.Prediction =  (  .18  )
 
	_G.FOV =  (  300  )
 
	_G.AimKey =  (  "c"  )
 
 
--[[
	Do not edit anything under this.
]]
 
	local SilentAim = true
	local LocalPlayer = game:GetService("Players").LocalPlayer
	local Players = game:GetService("Players")
	local Mouse = LocalPlayer:GetMouse()
	local Camera = game:GetService("Workspace").CurrentCamera
	hookmetamethod = hookmetamethod
	Drawing = Drawing
 
	local FOV_CIRCLE = Drawing.new("Circle")
	FOV_CIRCLE.Visible = false
	FOV_CIRCLE.Filled = false
	FOV_CIRCLE.Thickness = 1
	FOV_CIRCLE.Transparency = 1
	FOV_CIRCLE.Color = Color3.new(0, 1, 0)
	FOV_CIRCLE.Radius = _G.FOV
	FOV_CIRCLE.Position = Vector2.new(Camera.ViewportSize.X / 2, Camera.ViewportSize.Y / 2)
 
	Options = {
		Torso = "HumanoidRootPart";
		Head = "Head";
	}
 
	local function MoveFovCircle()
		pcall(function()
			local DoIt = true
			spawn(function()
				while DoIt do task.wait()
					FOV_CIRCLE.Position = Vector2.new(Mouse.X, (Mouse.Y + 36))
				end
			end)
		end)
	end coroutine.wrap(MoveFovCircle)()
 
	Mouse.KeyDown:Connect(function(KeyPressed)
		if KeyPressed == (_G.AimKey:lower()) then
			if SilentAim == false then
				FOV_CIRCLE.Color = Color3.new(0, 1, 0)
				SilentAim = true
			elseif SilentAim == true then
				FOV_CIRCLE.Color = Color3.new(1, 0, 0)
				SilentAim = false
			end
		end
	end)
 
	local oldIndex = nil 
	oldIndex = hookmetamethod(game, "__index", function(self, Index)
		if self == Mouse and (Index == "Hit") then 
			local Distance = 9e9
			local Targete = nil
			if SilentAim then
 
				for _, v in pairs(Players:GetPlayers()) do 
					if v ~= LocalPlayer and v.Character and v.Character:FindFirstChild("HumanoidRootPart") and v.Character:FindFirstChild("Humanoid") and v.Character:FindFirstChild("Humanoid").Health > 0 then
						local Enemy = v.Character	
						local CastingFrom = CFrame.new(Camera.CFrame.Position, Enemy[Options.Torso].CFrame.Position) * CFrame.new(0, 0, -4)
						local RayCast = Ray.new(CastingFrom.Position, CastingFrom.LookVector * 9000)
						local World, ToSpace = workspace:FindPartOnRayWithIgnoreList(RayCast, {LocalPlayer.Character:FindFirstChild("Head")})
						local RootWorld = (Enemy[Options.Torso].CFrame.Position - ToSpace).magnitude
						if RootWorld < 4 then
							local RootPartPosition, Visible = Camera:WorldToScreenPoint(Enemy[Options.Torso].Position)
							if Visible then
								local Real_Magnitude = (Vector2.new(Mouse.X, Mouse.Y) - Vector2.new(RootPartPosition.X, RootPartPosition.Y)).Magnitude
								if Real_Magnitude < Distance and Real_Magnitude < FOV_CIRCLE.Radius then
									Distance = Real_Magnitude
									Targete = Enemy
								end
							end
						end
					end
				end
			end
 
			if Targete ~= nil and Targete[Options.Torso] and Targete:FindFirstChild("Humanoid").Health > 0 then
				if SilentAim then
					local ShootThis = Targete[Options.Torso] -- or Options.Head
					local Predicted_Position = ShootThis.CFrame + (ShootThis.Velocity * _G.Prediction + Vector3.new(0,-1,0)) --  (-1) = Less blatant
					return ((Index == "Hit" and Predicted_Position))
				end
			end
 
		end
		return oldIndex(self, Index)
	end)
end)
 
UICorner_7.CornerRadius = UDim.new(0, 100)
UICorner_7.Parent = Headless
 
-- Scripts:
 
local function ZSZNG_fake_script() -- Main.Dragify 
	local script = Instance.new('LocalScript', Main)
 
	local UIS = game:GetService("UserInputService")
	function dragify(Frame)
	    dragToggle = nil
	    local dragSpeed = 0.50
	    dragInput = nil
	    dragStart = nil
	    local dragPos = nil
	    function updateInput(input)
	        local Delta = input.Position - dragStart
	        local Position = UDim2.new(startPos.X.Scale, startPos.X.Offset + Delta.X, startPos.Y.Scale, startPos.Y.Offset + Delta.Y)
	        game:GetService("TweenService"):Create(Frame, TweenInfo.new(0.30), {Position = Position}):Play()
	    end
	    Frame.InputBegan:Connect(function(input)
	        if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) and UIS:GetFocusedTextBox() == nil then
	            dragToggle = true
	            dragStart = input.Position
	            startPos = Frame.Position
	            input.Changed:Connect(function()
	                if input.UserInputState == Enum.UserInputState.End then
	                    dragToggle = false
	                end
	            end)
	        end
	    end)
	    Frame.InputChanged:Connect(function(input)
	        if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
	            dragInput = input
	        end
	    end)
	    game:GetService("UserInputService").InputChanged:Connect(function(input)
	        if input == dragInput and dragToggle then
	            updateInput(input)
	        end
	    end)
	end
 
	dragify(script.Parent)
end
coroutine.wrap(ZSZNG_fake_script)()
 
