-- Gui to Lua
-- Version: 3.2

-- Instances:

local UI = Instance.new("ScreenGui")
local UI_2 = Instance.new("Frame")
local BackGround = Instance.new("Frame")
local Container = Instance.new("Frame")
local UIGridLayout = Instance.new("UIGridLayout")
local Padding = Instance.new("UIPadding")
local pomp = Instance.new("TextButton")
local ak = Instance.new("TextButton")
local iy = Instance.new("TextButton")
local walkspeed = Instance.new("TextButton")
local hump = Instance.new("TextButton")
local UnderLine = Instance.new("Frame")
local Toggle = Instance.new("TextButton")
local Window = Instance.new("TextLabel")

--Properties:

UI.Name = "UI"
UI.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
UI.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

UI_2.Name = "UI"
UI_2.Parent = UI
UI_2.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
UI_2.BorderSizePixel = 0
UI_2.Position = UDim2.new(0, 15, 0, 15)
UI_2.Size = UDim2.new(0, 190, 0, 30)

BackGround.Name = "BackGround"
BackGround.Parent = UI_2
BackGround.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
BackGround.BorderSizePixel = 0
BackGround.Position = UDim2.new(0, 0, 1, 0)
BackGround.Size = UDim2.new(0, 190, 0, 200)

Container.Name = "Container"
Container.Parent = UI_2
Container.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
Container.BorderSizePixel = 0
Container.Position = UDim2.new(-0.0263157897, 0, 0.966666639, 0)
Container.Size = UDim2.new(0, 912, 0, 532)

UIGridLayout.Parent = Container
UIGridLayout.SortOrder = Enum.SortOrder.LayoutOrder
UIGridLayout.CellSize = UDim2.new(0, 180, 0, 40)

Padding.Name = "Padding"
Padding.Parent = Container
Padding.PaddingLeft = UDim.new(0, 5)
Padding.PaddingTop = UDim.new(0, 5)

pomp.Name = "pomp"
pomp.Parent = Container
pomp.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
pomp.Position = UDim2.new(0.0235798508, 0, 0.0734557584, 0)
pomp.Size = UDim2.new(0, 200, 0, 50)
pomp.Font = Enum.Font.SourceSans
pomp.Text = "Regminton 870"
pomp.TextColor3 = Color3.fromRGB(0, 0, 0)
pomp.TextSize = 25.000

ak.Name = "ak"
ak.Parent = Container
ak.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ak.Size = UDim2.new(0, 200, 0, 50)
ak.Font = Enum.Font.SourceSans
ak.Text = "AK-47"
ak.TextColor3 = Color3.fromRGB(0, 0, 0)
ak.TextSize = 25.000

iy.Name = "iy"
iy.Parent = Container
iy.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
iy.Size = UDim2.new(0, 200, 0, 50)
iy.Font = Enum.Font.SourceSans
iy.Text = "Infinity yield"
iy.TextColor3 = Color3.fromRGB(0, 0, 0)
iy.TextSize = 25.000

walkspeed.Name = "walk speed"
walkspeed.Parent = Container
walkspeed.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
walkspeed.Size = UDim2.new(0, 200, 0, 50)
walkspeed.Font = Enum.Font.SourceSans
walkspeed.Text = "Walk speed"
walkspeed.TextColor3 = Color3.fromRGB(0, 0, 0)
walkspeed.TextSize = 25.000

hump.Name = "hump"
hump.Parent = Container
hump.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
hump.Size = UDim2.new(0, 200, 0, 50)
hump.Font = Enum.Font.SourceSans
hump.Text = "Jump power"
hump.TextColor3 = Color3.fromRGB(0, 0, 0)
hump.TextSize = 25.000

UnderLine.Name = "UnderLine"
UnderLine.Parent = UI_2
UnderLine.BackgroundColor3 = Color3.fromRGB(255, 25, 25)
UnderLine.BorderSizePixel = 0
UnderLine.Position = UDim2.new(0, 0, 1, -1)
UnderLine.Size = UDim2.new(1, 0, 0, 1)

Toggle.Name = "Toggle"
Toggle.Parent = UI_2
Toggle.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Toggle.BackgroundTransparency = 1.000
Toggle.Position = UDim2.new(1, -25, 0, 0)
Toggle.Size = UDim2.new(0, 25, 1, 0)
Toggle.Font = Enum.Font.SourceSans
Toggle.Text = "-"
Toggle.TextColor3 = Color3.fromRGB(255, 0, 0)
Toggle.TextSize = 17.000

Window.Name = "Window"
Window.Parent = UI_2
Window.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Window.BackgroundTransparency = 1.000
Window.Size = UDim2.new(0.868421078, 0, 1, 0)
Window.Font = Enum.Font.SourceSans
Window.Text = "1tsJusthub (prison life)"
Window.TextColor3 = Color3.fromRGB(255, 0, 4)
Window.TextSize = 17.000

-- Scripts:

local function JRELDK_fake_script() -- pomp.Script 
	local script = Instance.new('Script', pomp)

	function Click(mouse)
	
		game.Workspace.Prison_ITEMS.giver["Remington 870"].ITEMPICKUP.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
	
	end
	
	
	script.Parent.MouseButton1Down:connect(Click)
	
end
coroutine.wrap(JRELDK_fake_script)()
local function FZXJ_fake_script() -- ak.Script 
	local script = Instance.new('Script', ak)

	function Click(mouse)
	
		game.Workspace.Prison_ITEMS.giver["AK-47"].ITEMPICKUP.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
	
	end
	
	
	script.Parent.MouseButton1Down:connect(Click)
	
end
coroutine.wrap(FZXJ_fake_script)()
local function WVUWQCV_fake_script() -- iy.Script 
	local script = Instance.new('Script', iy)

	function Click(mouse)
	
		loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
	
	end
	
	
	script.Parent.MouseButton1Down:connect(Click)
end
coroutine.wrap(WVUWQCV_fake_script)()
local function MCXNLVK_fake_script() -- walkspeed.Script 
	local script = Instance.new('Script', walkspeed)

	function Click(mouse)
	
		---credits to https://www.youtube.com/channel/UCxNvCRWwg44MlvOlmDPo9SQ (crispy riley)
	
		local ScreenGui = Instance.new("ScreenGui")
		local main = Instance.new("Frame")
		local label = Instance.new("TextLabel")
		local walkspeed50 = Instance.new("TextButton")
		local walkspeed100 = Instance.new("TextButton")
		local walkspeed200 = Instance.new("TextButton")
		local walkspeed500 = Instance.new("TextButton")
		local walkspeed1000 = Instance.new("TextButton")
		local walkspeed250 = Instance.new("TextButton")
	
		--Properties:
	
		ScreenGui.Parent = game.CoreGui
		ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
	
		main.Name = "main"
		main.Parent = ScreenGui
		main.BackgroundColor3 = Color3.fromRGB(16, 16, 16)
		main.Position = UDim2.new(0.502050519, 0, 0.416614413, 0)
		main.Size = UDim2.new(0, 385, 0, 196)
		main.Active = true
		main.Draggable =true
	
		label.Name = "label"
		label.Parent = main
		label.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
		label.BackgroundTransparency = 1.000
		label.BorderColor3 = Color3.fromRGB(0, 0, 0)
		label.Position = UDim2.new(-0.00259740255, 0, 0, 0)
		label.Size = UDim2.new(0, 384, 0, 50)
		label.Font = Enum.Font.SourceSans
		label.Text = "WALK SPEED GUI CREDITS TO 1tsJustgp (YT CHANNEL)"
		label.TextColor3 = Color3.fromRGB(0, 255, 255)
		label.TextSize = 14.000
		label.TextStrokeColor3 = Color3.fromRGB(3, 255, 247)
	
		walkspeed50.Name = "walk speed 50"
		walkspeed50.Parent = main
		walkspeed50.BackgroundColor3 = Color3.fromRGB(85, 85, 255)
		walkspeed50.BorderSizePixel = 0
		walkspeed50.Position = UDim2.new(0, 0, 0.270531386, 0)
		walkspeed50.Size = UDim2.new(0, 200, 0, 50)
		walkspeed50.Font = Enum.Font.SourceSans
		walkspeed50.Text = "Walk speed 50"
		walkspeed50.TextColor3 = Color3.fromRGB(0, 0, 0)
		walkspeed50.TextSize = 14.000
		walkspeed50.MouseButton1Down:connect(function()
			local plr = game.Players.LocalPlayer
			local char = plr.Character
	
			char.Humanoid.WalkSpeed =50
		end)
		walkspeed100.Name = "walk speed 100"
		walkspeed100.Parent = main
		walkspeed100.BackgroundColor3 = Color3.fromRGB(85, 85, 255)
		walkspeed100.Position = UDim2.new(0.519480526, 0, 0.270531386, 0)
		walkspeed100.Size = UDim2.new(0, 185, 0, 50)
		walkspeed100.Font = Enum.Font.SourceSans
		walkspeed100.Text = "Walk speed 100"
		walkspeed100.TextColor3 = Color3.fromRGB(0, 0, 0)
		walkspeed100.TextSize = 14.000
		walkspeed100.MouseButton1Down:connect(function()
			local plr = game.Players.LocalPlayer
			local char = plr.Character
	
			char.Humanoid.WalkSpeed =100
		end)
		walkspeed200.Name = "walk speed 200"
		walkspeed200.Parent = main
		walkspeed200.BackgroundColor3 = Color3.fromRGB(85, 85, 255)
		walkspeed200.Position = UDim2.new(0, 0, 0.512077272, 0)
		walkspeed200.Size = UDim2.new(0, 200, 0, 50)
		walkspeed200.Font = Enum.Font.SourceSans
		walkspeed200.Text = "Walk speed 200"
		walkspeed200.TextColor3 = Color3.fromRGB(0, 0, 0)
		walkspeed200.TextSize = 14.000
		walkspeed200.MouseButton1Down:connect(function()
			local plr = game.Players.LocalPlayer
			local char = plr.Character
	
			char.Humanoid.WalkSpeed =200
		end)
	
		walkspeed500.Name = "walk speed 500"
		walkspeed500.Parent = main
		walkspeed500.BackgroundColor3 = Color3.fromRGB(85, 85, 255)
		walkspeed500.Position = UDim2.new(-0.00259740255, 0, 0.758454084, 0)
		walkspeed500.Size = UDim2.new(0, 201, 0, 50)
		walkspeed500.Font = Enum.Font.SourceSans
		walkspeed500.Text = "Walk speed 500"
		walkspeed500.TextColor3 = Color3.fromRGB(0, 0, 0)
		walkspeed500.TextSize = 14.000
		walkspeed500.MouseButton1Down:connect(function()
			local plr = game.Players.LocalPlayer
			local char = plr.Character
	
			char.Humanoid.WalkSpeed =500
		end)
	
		walkspeed1000.Name = "walk speed 1000"
		walkspeed1000.Parent = main
		walkspeed1000.BackgroundColor3 = Color3.fromRGB(85, 85, 255)
		walkspeed1000.Position = UDim2.new(0.519480526, 0, 0.753623188, 0)
		walkspeed1000.Size = UDim2.new(0, 184, 0, 50)
		walkspeed1000.Font = Enum.Font.SourceSans
		walkspeed1000.Text = "Walk speed 1000"
		walkspeed1000.TextColor3 = Color3.fromRGB(0, 0, 0)
		walkspeed1000.TextSize = 14.000
		walkspeed1000.MouseButton1Down:connect(function()
			local plr = game.Players.LocalPlayer
			local char = plr.Character
	
			char.Humanoid.WalkSpeed =1000
		end)
		walkspeed250.Name = "walk speed 250"
		walkspeed250.Parent = main
		walkspeed250.BackgroundColor3 = Color3.fromRGB(85, 85, 255)
		walkspeed250.BorderColor3 = Color3.fromRGB(85, 85, 255)
		walkspeed250.Position = UDim2.new(0.519480526, 0, 0.512077272, 0)
		walkspeed250.Size = UDim2.new(0, 184, 0, 50)
		walkspeed250.Font = Enum.Font.SourceSans
		walkspeed250.Text = "Walk speed 250"
		walkspeed250.TextColor3 = Color3.fromRGB(0, 0, 0)
		walkspeed250.TextSize = 14.000
		walkspeed250.MouseButton1Down:connect(function()
			local plr = game.Players.LocalPlayer
			local char = plr.Character
	
			char.Humanoid.WalkSpeed =250
		end)
	
	end
	
	
	script.Parent.MouseButton1Down:connect(Click)
end
coroutine.wrap(MCXNLVK_fake_script)()
local function IIKXX_fake_script() -- hump.Script 
	local script = Instance.new('Script', hump)

	function Click(mouse)
	
		local plr = game.Players.LocalPlayer
	
		plr.Character.Humanoid.JumpPower = 100 --Change to JumpPower number
	
	end
	
	
	script.Parent.MouseButton1Down:connect(Click)
end
coroutine.wrap(IIKXX_fake_script)()
local function ILNKEUJ_fake_script() -- Toggle.LocalScript 
	local script = Instance.new('LocalScript', Toggle)

	local back = script.Parent.Parent.BackGround
	local con = script.Parent.Parent.Container
	
	local window = {
			count = 0;
			toggles = {},
			closed = false;
		}
		script.Parent.MouseButton1Click:connect(function()
			window.closed = not window.closed
			script.Parent.Text = (window.closed and "+" or "-")
			if script.Parent.Text == "+" then
				back:TweenSize(UDim2.new(0, 190,0, 0), "Out", "Sine", 0.5)
				con:TweenSize(UDim2.new(0, 190,0, 0), "Out", "Sine", 0.5)
				wait(0.1) do
				con.Visible = false
				end
			else
				back:TweenSize(UDim2.new(0, 912,0, 532), "Out", "Sine", 0.5)
				con:TweenSize(UDim2.new(0, 912,0, 532), "Out", "Sine", 0.5)
				wait(0.2) do
				con.Visible = true
				end
				end
			
		end)
	
end
coroutine.wrap(ILNKEUJ_fake_script)()
local function LSZWB_fake_script() -- UI_2.LocalScript 
	local script = Instance.new('LocalScript', UI_2)

	local dragger = {}; 
	local resizer = {};
	
	do
		local mouse = game:GetService("Players").LocalPlayer:GetMouse();
		local inputService = game:GetService('UserInputService');
		local heartbeat = game:GetService("RunService").Heartbeat;
		-- // credits to Ririchi / Inori for this cute drag function :)
		function dragger.new(frame)
		    local s, event = pcall(function()
		    	return frame.MouseEnter
		    end)
	
		    if s then
		    	frame.Active = true;
	
		    	event:connect(function()
		    		local input = frame.InputBegan:connect(function(key)
		    			if key.UserInputType == Enum.UserInputType.MouseButton1 then
		    				local objectPosition = Vector2.new(mouse.X - frame.AbsolutePosition.X, mouse.Y - frame.AbsolutePosition.Y);
		    				while heartbeat:wait() and inputService:IsMouseButtonPressed(Enum.UserInputType.MouseButton1) do
		    					frame:TweenPosition(UDim2.new(0, mouse.X - objectPosition.X + (frame.Size.X.Offset * frame.AnchorPoint.X), 0, mouse.Y - objectPosition.Y + (frame.Size.Y.Offset * frame.AnchorPoint.Y)), 'Out', 'Quad', 0.1, true);
		    				end
		    			end
		    		end)
	
		    		local leave;
		    		leave = frame.MouseLeave:connect(function()
		    			input:disconnect();
		    			leave:disconnect();
		    		end)
		    	end)
		    end
		end
		
		function resizer.new(p, s)
			p:GetPropertyChangedSignal('AbsoluteSize'):connect(function()
				s.Size = UDim2.new(s.Size.X.Scale, s.Size.X.Offset, s.Size.Y.Scale, p.AbsoluteSize.Y);
			end)
		end
	end
	script.Parent.Active = true
	script.Parent.Draggable = true
end
coroutine.wrap(LSZWB_fake_script)()
