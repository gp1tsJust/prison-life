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
local BTools = Instance.new("TextButton")
local M9 = Instance.new("TextButton")
local Keycard = Instance.new("TextButton")
local uinnmia = Instance.new("TextButton")
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

BTools.Name = "BTools"
BTools.Parent = Container
BTools.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
BTools.Position = UDim2.new(0.973684192, 0, 2.63333344, 0)
BTools.Size = UDim2.new(0, 200, 0, 50)
BTools.Font = Enum.Font.SourceSans
BTools.Text = "BTools"
BTools.TextColor3 = Color3.fromRGB(0, 0, 0)
BTools.TextSize = 25.000

M9.Name = "M9"
M9.Parent = Container
M9.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
M9.Size = UDim2.new(0, 200, 0, 50)
M9.Font = Enum.Font.SourceSans
M9.Text = "M9"
M9.TextColor3 = Color3.fromRGB(0, 0, 0)
M9.TextSize = 25.000

Keycard.Name = "Key card"
Keycard.Parent = Container
Keycard.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Keycard.Size = UDim2.new(0, 200, 0, 50)
Keycard.Font = Enum.Font.SourceSans
Keycard.Text = "Key Card"
Keycard.TextColor3 = Color3.fromRGB(0, 0, 0)
Keycard.TextSize = 25.000

uinnmia.Name = "ui nn mia"
uinnmia.Parent = Container
uinnmia.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
uinnmia.Size = UDim2.new(0, 200, 0, 50)
uinnmia.Font = Enum.Font.SourceSans
uinnmia.Text = "Telly Hub (dont my script)"
uinnmia.TextColor3 = Color3.fromRGB(0, 0, 0)
uinnmia.TextSize = 20.000

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

local function NZBWVM_fake_script() -- pomp.Script 
	local script = Instance.new('Script', pomp)

	function Click(mouse)
	
		-- Script generated by R2Sv2
		-- R2Sv2 developed by Luckyxero
	
		local A_1 = game:GetService("Workspace")["Prison_ITEMS"].giver["Remington 870"].ITEMPICKUP
		local Event = game:GetService("Workspace").Remote.ItemHandler
		Event:InvokeServer(A_1)
	
		
	end
	
	
	script.Parent.MouseButton1Down:connect(Click)
	
end
coroutine.wrap(NZBWVM_fake_script)()
local function JEUJIW_fake_script() -- ak.Script 
	local script = Instance.new('Script', ak)

	function Click(mouse)
	
		-- Script generated by R2Sv2
		-- R2Sv2 developed by Luckyxero
	
		local A_1 = game:GetService("Workspace")["Prison_ITEMS"].giver["AK-47"].ITEMPICKUP
		local Event = game:GetService("Workspace").Remote.ItemHandler
		Event:InvokeServer(A_1)
	
		
	end
	
	
	script.Parent.MouseButton1Down:connect(Click)
	
end
coroutine.wrap(JEUJIW_fake_script)()
local function VWAJB_fake_script() -- iy.Script 
	local script = Instance.new('Script', iy)

	function Click(mouse)
	
		loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
	
	end
	
	
	script.Parent.MouseButton1Down:connect(Click)
end
coroutine.wrap(VWAJB_fake_script)()
local function DBNRCF_fake_script() -- walkspeed.Script 
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
coroutine.wrap(DBNRCF_fake_script)()
local function PGGDKF_fake_script() -- hump.Script 
	local script = Instance.new('Script', hump)

	function Click(mouse)
	
		local plr = game.Players.LocalPlayer
	
		plr.Character.Humanoid.JumpPower = 150 --Change to JumpPower number
	
	end
	
	
	script.Parent.MouseButton1Down:connect(Click)
end
coroutine.wrap(PGGDKF_fake_script)()
local function BCGG_fake_script() -- BTools.Script 
	local script = Instance.new('Script', BTools)

	function Click(mouse)
	
		-- Made by ILoveCats9030
		-- Version: 1.3
		-- Instances:
	
		local ScreenGui = Instance.new("ScreenGui")
		local main = Instance.new("Frame")
		local Text = Instance.new("TextLabel")
		local BT = Instance.new("TextButton")
	
		--Properties:
	
		ScreenGui.Parent = game.CoreGui
	
		main.Name = "main"
		main.Parent = ScreenGui
		main.BackgroundColor3 = Color3.fromRGB(62, 62, 62)
		main.BorderColor3 = Color3.fromRGB(0, 0, 0)
		main.BorderSizePixel = 5
		main.Position = UDim2.new(0.0198598132, 0, 0.687250972, 0)
		main.Size = UDim2.new(0, 207, 0, 146)
		main.Active = true
	
		Text.Name = "Text"
		Text.Parent = ScreenGui
		Text.BackgroundColor3 = Color3.fromRGB(157, 157, 157)
		Text.Position = UDim2.new(0.0292056073, 0, 0.699203134, 0)
		Text.Size = UDim2.new(0, 190, 0, 34)
		Text.Font = Enum.Font.SciFi
		Text.Text = "Btools script"
		Text.TextColor3 = Color3.fromRGB(0, 0, 0)
		Text.TextSize = 14.000
	
		BT.Name = "BT"
		BT.Parent = ScreenGui
		BT.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
		BT.Position = UDim2.new(0.0443925261, 0, 0.860557795, 0)
		BT.Size = UDim2.new(0, 164, 0, 40)
		BT.Style = Enum.ButtonStyle.RobloxRoundDefaultButton
		BT.Font = Enum.Font.Highway
		BT.Text = "Btools"
		BT.TextColor3 = Color3.fromRGB(0, 0, 0)
		BT.TextScaled = true
		BT.TextSize = 14.000
		BT.TextWrapped = true
		BT.MouseButton1Down:connect(function()
			local tool1 = Instance.new("HopperBin",game.Players.LocalPlayer.Backpack)
			local tool2 = Instance.new("HopperBin",game.Players.LocalPlayer.Backpack)
			local tool3 = Instance.new("HopperBin",game.Players.LocalPlayer.Backpack)
			local tool4 = Instance.new("HopperBin",game.Players.LocalPlayer.Backpack)
			local tool5 = Instance.new("HopperBin",game.Players.LocalPlayer.Backpack)
			tool1.BinType = "Clone"
			tool2.BinType = "GameTool"
			tool3.BinType = "Hammer"
			tool4.BinType = "Script"
			tool5.BinType = "Grab"
		end)
	
	end
	
	
	script.Parent.MouseButton1Down:connect(Click)
end
coroutine.wrap(BCGG_fake_script)()
local function SSAIYZF_fake_script() -- M9.Script 
	local script = Instance.new('Script', M9)

	function Click(mouse)
	
		-- Script generated by R2Sv2
		-- R2Sv2 developed by Luckyxero
	
		local A_1 = game:GetService("Workspace")["Prison_ITEMS"].giver.M9.ITEMPICKUP
		local Event = game:GetService("Workspace").Remote.ItemHandler
		Event:InvokeServer(A_1)
	
	
	end
	
	
	script.Parent.MouseButton1Down:connect(Click)
end
coroutine.wrap(SSAIYZF_fake_script)()
local function ZTVZYA_fake_script() -- Keycard.Script 
	local script = Instance.new('Script', Keycard)

	function Click(mouse)
	
		local A_1 = game:GetService("Workspace")["Prison_ITEMS"].single["Key card"].ITEMPICKUP
		local Event = game:GetService("Workspace").Remote.ItemHandler
		Event:InvokeServer(A_1)
	
	
	end
	
	
	script.Parent.MouseButton1Down:connect(Click)
end
coroutine.wrap(ZTVZYA_fake_script)()
local function SUFU_fake_script() -- uinnmia.Script 
	local script = Instance.new('Script', uinnmia)

	function Click(mouse)
	
		loadstring(game:HttpGet(("https://raw.githubusercontent.com/gp1tsJust/per-pris/main/README.md"), true))()
	
	end
	
	
	script.Parent.MouseButton1Down:connect(Click)
end
coroutine.wrap(SUFU_fake_script)()
local function MHRP_fake_script() -- Toggle.LocalScript 
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
coroutine.wrap(MHRP_fake_script)()
local function JKELW_fake_script() -- UI_2.LocalScript 
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
coroutine.wrap(JKELW_fake_script)()
