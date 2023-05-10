localplayer = game.Players.LocalPlayer
 Char = localplayer.Character or workspace:FindFirstChild(localplayer.Name)
         HRP = Char and Char:FindFirstChild("HumanoidRootPart")
        if not Char or not HRP then
           
        end
         p = HRP.Position
         hrd = game.Players.LocalPlayer.Character.HumanoidRootPart
         x = -261.22
         y = -44.06
       	 z = -1352.41
        hrd.CFrame = CFrame.new(p.x, 1000, p.z)
        wait(0.5)
         currentPos = Vector3.new(p.x, 1000, p.z)
         targetPos = Vector3.new(x, 1000, z)

         direction = (targetPos - currentPos).Unit
         distance = (targetPos - currentPos).Magnitude
         steps = math.floor(distance / 10) 
        for i = 1, steps do
            currentPos = currentPos + direction * 10
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
            task.wait()
        end

        
        currentPos = targetPos
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
        task.wait(0.1)
         p = hrd.Position
        
         currentPos = Vector3.new(x, 1000, z)
         targetPos = Vector3.new(x, y, z)

         direction = (targetPos - currentPos).Unit
         distance = (targetPos - currentPos).Magnitude
         steps = math.floor(distance / 10) 
        for i = 1, steps do
            currentPos = currentPos + direction * 10 
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
            task.wait()
        end
        
        currentPos = targetPos
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
        task.wait(2)

for i, v in pairs(game.Workspace:GetDescendants()) do
    if v.Name == "Laser" or v.Name == "GreenLaser" or v.Name == "GreenLasers" or v.Name == "Lasers" or v.Name == "VaultLasers" or v.Name == "NightLaser" or v.Name == "LaserDoor" or v.Name == "Lava" or v.Name == "Spotlight" or v.Name == "Flamethrowers" or v.Name == "Saws" or v.Name == "SpikeTraps" or v.Name == "Balls" or v.Name == "PressurePlates"  or v.Name == "LaserWalls" or v.Name == "WallBeam" or v.Name == "Detectors" or v.Name == "Turrets" then
        v:Destroy()
    end
end

local Noclip = nil
local Clip = nil

function noclip()
	Clip = false
	local function Nocl()
		if Clip == false and game.Players.LocalPlayer.Character ~= nil then
			for _,v in pairs(game.Players.LocalPlayer.Character:GetDescendants()) do
				if v:IsA('BasePart') and v.CanCollide and v.Name ~= floatName then
					v.CanCollide = false
				end
			end
		end
		wait(0.21)
	end
	Noclip = game:GetService('RunService').Stepped:Connect(Nocl)
end

function clip()
	if Noclip then Noclip:Disconnect() end
	Clip = true
end

noclip()


game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-267.71,-44.06,-1347.65)
task.wait()
 localplayer = game.Players.LocalPlayer
 Char = localplayer.Character or workspace:FindFirstChild(localplayer.Name)
         HRP = Char and Char:FindFirstChild("HumanoidRootPart")
        if not Char or not HRP then
           
        end
         p = HRP.Position
         hrd = game.Players.LocalPlayer.Character.HumanoidRootPart
         x = -278.97
         y = -49.3
       	 z = -1166.66
        hrd.CFrame = CFrame.new(p.x, -44.06, p.z)
        wait(0.5)
         currentPos = Vector3.new(p.x, -44.06, p.z)
         targetPos = Vector3.new(x, -44.06, z)

         direction = (targetPos - currentPos).Unit
         distance = (targetPos - currentPos).Magnitude
         steps = math.floor(distance / 10) 
        for i = 1, steps do
            currentPos = currentPos + direction * 10
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
            task.wait()
        end

        
        currentPos = targetPos
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
        task.wait(0.1)
         p = hrd.Position
        
         currentPos = Vector3.new(x, -44.06, z)
         targetPos = Vector3.new(x, y, z)

         direction = (targetPos - currentPos).Unit
         distance = (targetPos - currentPos).Magnitude
         steps = math.floor(distance / 10) 
        for i = 1, steps do
            currentPos = currentPos + direction * 10 
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
            task.wait()
        end
        
        currentPos = targetPos
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
        task.wait(2)
        local VirtualInputManager = game:GetService('VirtualInputManager')

function keyPress(Key, Press)
    VirtualInputManager:SendKeyEvent(Press, Key, false, game)
end

keyPress(Enum.KeyCode.E, true)
task.wait(5)
 local localplayer = game.Players.LocalPlayer
local Char = localplayer.Character or workspace:FindFirstChild(localplayer.Name)
        local HRP = Char and Char:FindFirstChild("HumanoidRootPart")
        if not Char or not HRP then
           
        end
        local p = HRP.Position
         x = -267.71
         y = -44.06
       	 z = -1347.65
        hrd.CFrame = CFrame.new(p.x, -44.06, p.z)
        wait(0.5)
        local currentPos = Vector3.new(p.x, -44.06, p.z)
        local targetPos = Vector3.new(x, -44.06, z)

        local direction = (targetPos - currentPos).Unit
        local distance = (targetPos - currentPos).Magnitude
        local steps = math.floor(distance / 10) 
        for i = 1, steps do
            currentPos = currentPos + direction * 10
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
            task.wait()
        end

        
        currentPos = targetPos
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
        task.wait(0.1)
        local p = hrd.Position
        
        local currentPos = Vector3.new(x, -44.06, z)
        local targetPos = Vector3.new(x, y, z)

        local direction = (targetPos - currentPos).Unit
        local distance = (targetPos - currentPos).Magnitude
        local steps = math.floor(distance / 10) 
        for i = 1, steps do
            currentPos = currentPos + direction * 10 
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
            task.wait()
        end
        
        currentPos = targetPos
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
        task.wait(0.5)
local localplayer = game.Players.LocalPlayer
local Char = localplayer.Character or workspace:FindFirstChild(localplayer.Name)
        local HRP = Char and Char:FindFirstChild("HumanoidRootPart")
        if not Char or not HRP then
           
        end
        local p = HRP.Position
        local hrd = game.Players.LocalPlayer.Character.HumanoidRootPart
        local x = -405.05
        local y = -49.4
        local z = -1359.01
        hrd.CFrame = CFrame.new(p.x, -44.06, p.z)
        wait(0.5)
        local currentPos = Vector3.new(p.x, -44.06, p.z)
        local targetPos = Vector3.new(x, -44.06, z)

        local direction = (targetPos - currentPos).Unit
        local distance = (targetPos - currentPos).Magnitude
        local steps = math.floor(distance / 10) 
        for i = 1, steps do
            currentPos = currentPos + direction * 10
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
            task.wait()
        end

        
        currentPos = targetPos
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
        task.wait(0.1)
        local p = hrd.Position
        
        local currentPos = Vector3.new(x, -44.06, z)
        local targetPos = Vector3.new(x, y, z)

        local direction = (targetPos - currentPos).Unit
        local distance = (targetPos - currentPos).Magnitude
        local steps = math.floor(distance / 10) 
        for i = 1, steps do
            currentPos = currentPos + direction * 10 
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
            task.wait()
        end
        
        currentPos = targetPos
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
        task.wait(2)
keyPress(Enum.KeyCode.E, true)
task.wait(5)
 local localplayer = game.Players.LocalPlayer
local Char = localplayer.Character or workspace:FindFirstChild(localplayer.Name)
        local HRP = Char and Char:FindFirstChild("HumanoidRootPart")
        if not Char or not HRP then
           
        end
        local p = HRP.Position
        local hrd = game.Players.LocalPlayer.Character.HumanoidRootPart
        local x = -266.12
        local y = -44.06
        local z = -1348.81
        hrd.CFrame = CFrame.new(p.x, -44.06, p.z)
        wait(0.5)
        local currentPos = Vector3.new(p.x, -44.06, p.z)
        local targetPos = Vector3.new(x, -44.06, z)

        local direction = (targetPos - currentPos).Unit
        local distance = (targetPos - currentPos).Magnitude
        local steps = math.floor(distance / 10) 
        for i = 1, steps do
            currentPos = currentPos + direction * 10
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
            task.wait()
        end

        
        currentPos = targetPos
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
        task.wait(0.1)
        local p = hrd.Position
        
        local currentPos = Vector3.new(x, -44.06, z)
        local targetPos = Vector3.new(x, y, z)

        local direction = (targetPos - currentPos).Unit
        local distance = (targetPos - currentPos).Magnitude
        local steps = math.floor(distance / 10) 
        for i = 1, steps do
            currentPos = currentPos + direction * 10 
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
            task.wait()
        end
        
        currentPos = targetPos
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
        task.wait()
        local localplayer = game.Players.LocalPlayer
local Char = localplayer.Character or workspace:FindFirstChild(localplayer.Name)
        local HRP = Char and Char:FindFirstChild("HumanoidRootPart")
        if not Char or not HRP then
           
        end
        local p = HRP.Position
        local hrd = game.Players.LocalPlayer.Character.HumanoidRootPart
        local x = -28.5
        local y = -44.06
        local z = -1332.73
        hrd.CFrame = CFrame.new(p.x, -44.06, p.z)
        wait(0.5)
        local currentPos = Vector3.new(p.x, -44.06, p.z)
        local targetPos = Vector3.new(x, -44.06, z)

        local direction = (targetPos - currentPos).Unit
        local distance = (targetPos - currentPos).Magnitude
        local steps = math.floor(distance / 10) 
        for i = 1, steps do
            currentPos = currentPos + direction * 10
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
            task.wait()
        end

        
        currentPos = targetPos
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
        task.wait(0.1)
        local p = hrd.Position
        
        local currentPos = Vector3.new(x, -44.06, z)
        local targetPos = Vector3.new(x, y, z)

        local direction = (targetPos - currentPos).Unit
        local distance = (targetPos - currentPos).Magnitude
        local steps = math.floor(distance / 10) 
        for i = 1, steps do
            currentPos = currentPos + direction * 10 
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
            task.wait()
        end
        
        currentPos = targetPos
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
        task.wait(2)
      keyPress(Enum.KeyCode.E, true)
task.wait(5)
        local localplayer = game.Players.LocalPlayer
local Char = localplayer.Character or workspace:FindFirstChild(localplayer.Name)
        local HRP = Char and Char:FindFirstChild("HumanoidRootPart")
        if not Char or not HRP then
           
        end
        local p = HRP.Position
        local hrd = game.Players.LocalPlayer.Character.HumanoidRootPart
        local x = -261.66
        local y = -44.06
        local z = -1348.9
        hrd.CFrame = CFrame.new(p.x, -44.06, p.z)
        wait(0.5)
        local currentPos = Vector3.new(p.x, -44.06, p.z)
        local targetPos = Vector3.new(x, -44.06, z)

        local direction = (targetPos - currentPos).Unit
        local distance = (targetPos - currentPos).Magnitude
        local steps = math.floor(distance / 10) 
        for i = 1, steps do
            currentPos = currentPos + direction * 10
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
            task.wait()
        end

        
        currentPos = targetPos
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
        task.wait(0.1)
        local p = hrd.Position
        
        local currentPos = Vector3.new(x, -44.06, z)
        local targetPos = Vector3.new(x, y, z)

        local direction = (targetPos - currentPos).Unit
        local distance = (targetPos - currentPos).Magnitude
        local steps = math.floor(distance / 10) 
        for i = 1, steps do
            currentPos = currentPos + direction * 10 
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
            task.wait()
        end
        
        currentPos = targetPos
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
        task.wait(10)
                local localplayer = game.Players.LocalPlayer
local Char = localplayer.Character or workspace:FindFirstChild(localplayer.Name)
        local HRP = Char and Char:FindFirstChild("HumanoidRootPart")
        if not Char or not HRP then
           
        end
        local p = HRP.Position
        local hrd = game.Players.LocalPlayer.Character.HumanoidRootPart
        local x = -258.12
        local y = -51.3
        local z = -1548.64
        hrd.CFrame = CFrame.new(p.x, -44.06, p.z)
        wait(0.5)
        local currentPos = Vector3.new(p.x, -44.06, p.z)
        local targetPos = Vector3.new(x, -44.06, z)

        local direction = (targetPos - currentPos).Unit
        local distance = (targetPos - currentPos).Magnitude
        local steps = math.floor(distance / 10) 
        for i = 1, steps do
            currentPos = currentPos + direction * 10
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
            task.wait()
        end

        
        currentPos = targetPos
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
        task.wait(0.1)
        local p = hrd.Position
        
        local currentPos = Vector3.new(x, -44.06, z)
        local targetPos = Vector3.new(x, y, z)

        local direction = (targetPos - currentPos).Unit
        local distance = (targetPos - currentPos).Magnitude
        local steps = math.floor(distance / 10) 
        for i = 1, steps do
            currentPos = currentPos + direction * 10 
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
            task.wait()
        end
        
        currentPos = targetPos
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
        task.wait()
                        local localplayer = game.Players.LocalPlayer
local Char = localplayer.Character or workspace:FindFirstChild(localplayer.Name)
        local HRP = Char and Char:FindFirstChild("HumanoidRootPart")
        if not Char or not HRP then
           
        end
        local p = HRP.Position
        local hrd = game.Players.LocalPlayer.Character.HumanoidRootPart
        local x = -307.46
        local y = -51.3
        local z = -1611.33
        hrd.CFrame = CFrame.new(p.x, -51.3, p.z)
        wait(0.5)
        local currentPos = Vector3.new(p.x, -51.3, p.z)
        local targetPos = Vector3.new(x, -51.3, z)

        local direction = (targetPos - currentPos).Unit
        local distance = (targetPos - currentPos).Magnitude
        local steps = math.floor(distance / 10) 
        for i = 1, steps do
            currentPos = currentPos + direction * 10
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
            task.wait()
        end

        
        currentPos = targetPos
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
        task.wait(0.1)
        local p = hrd.Position
        
        local currentPos = Vector3.new(x, -51.3, z)
        local targetPos = Vector3.new(x, y, z)

        local direction = (targetPos - currentPos).Unit
        local distance = (targetPos - currentPos).Magnitude
        local steps = math.floor(distance / 10) 
        for i = 1, steps do
            currentPos = currentPos + direction * 10 
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
            task.wait()
        end
        
        currentPos = targetPos
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
        task.wait()
                                local localplayer = game.Players.LocalPlayer
local Char = localplayer.Character or workspace:FindFirstChild(localplayer.Name)
        local HRP = Char and Char:FindFirstChild("HumanoidRootPart")
        if not Char or not HRP then
           
        end
        local p = HRP.Position
        local hrd = game.Players.LocalPlayer.Character.HumanoidRootPart
        local x = -446.7
        local y = -54
        local z = -1602.85
        hrd.CFrame = CFrame.new(p.x, -54, p.z)
        wait(0.5)
        local currentPos = Vector3.new(p.x, -54, p.z)
        local targetPos = Vector3.new(x, -54, z)

        local direction = (targetPos - currentPos).Unit
        local distance = (targetPos - currentPos).Magnitude
        local steps = math.floor(distance / 10) 
        for i = 1, steps do
            currentPos = currentPos + direction * 10
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
            task.wait()
        end

        
        currentPos = targetPos
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
        task.wait(0.1)
        local p = hrd.Position
        
        local currentPos = Vector3.new(x, -54, z)
        local targetPos = Vector3.new(x, y, z)

        local direction = (targetPos - currentPos).Unit
        local distance = (targetPos - currentPos).Magnitude
        local steps = math.floor(distance / 10) 
        for i = 1, steps do
            currentPos = currentPos + direction * 10 
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
            task.wait()
        end
        
        currentPos = targetPos
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
        task.wait()
        localplayer = game.Players.LocalPlayer
 Char = localplayer.Character or workspace:FindFirstChild(localplayer.Name)
         HRP = Char and Char:FindFirstChild("HumanoidRootPart")
        if not Char or not HRP then
           
        end
         p = HRP.Position
         hrd = game.Players.LocalPlayer.Character.HumanoidRootPart
         x = -469.23
         y = -51.1
       	 z = -1455.5
        hrd.CFrame = CFrame.new(p.x, -53, p.z)
        wait(0.5)
         currentPos = Vector3.new(p.x, -53, p.z)
         targetPos = Vector3.new(x, -53, z)

         direction = (targetPos - currentPos).Unit
         distance = (targetPos - currentPos).Magnitude
         steps = math.floor(distance / 10) 
        for i = 1, steps do
            currentPos = currentPos + direction * 10
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
            task.wait()
        end

        
        currentPos = targetPos
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
        task.wait(0.1)
         p = hrd.Position
        
         currentPos = Vector3.new(x, -53, z)
         targetPos = Vector3.new(x, y, z)

         direction = (targetPos - currentPos).Unit
         distance = (targetPos - currentPos).Magnitude
         steps = math.floor(distance / 10) 
        for i = 1, steps do
            currentPos = currentPos + direction * 10 
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
            task.wait()
        end
        
        currentPos = targetPos
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
        task.wait(2)
repeat task.wait() until game.Workspace.Heists.Pyramid.Level2.RoofTrap.Door.Position.Y > -36
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-439.64,-51.3,-1392.26)
	task.wait(0.5)
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-446.53,-46.92,-1387.25)
	task.wait(0.5)
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-456.88,-51.30,-1342.74)
	task.wait(0.5)
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-451.55,-51.20,-1313.45)
	task.wait(0.5)
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-471.64,-51.20,-1285.07)
	task.wait(0.5)
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-474.23,-46.79,-1282.22)
	task.wait(0.5)
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-482.17,-51.20,-1260.06)	
	task.wait(0.5)
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-483.30,-51.20,-1210)	
	task.wait(0.5)
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-480.23,-51.20,-1153.73)
	task.wait(0.5)
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-479.22,-51.20,-1137.83)
	task.wait(0.5)
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-478.68,-51.20,-1107.38)
	task.wait(0.5)
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-472.30,-51.30,-1042.75)
	task.wait(0.5)
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-460.28,-51.24,-976.62)
	task.wait(0.5)
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-458.62,-51.20,-961.58)
	task.wait(0.5)
	task.wait(1)
		local VirtualInputManager = game:GetService('VirtualInputManager')

function keyPress(Key, Press)
    VirtualInputManager:SendKeyEvent(Press, Key, false, game)
end
task.wait(1)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-431.07,-51.08,-974.73)
task.wait()
keyPress(Enum.KeyCode.E, true)
wait(6)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-421.17,-47.80,-973.50)
task.wait()
keyPress(Enum.KeyCode.E, true)
wait(6)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-431.07,-51.08,-974.73)
task.wait()
keyPress(Enum.KeyCode.E, true)
wait(6)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-421.17,-47.80,-973.50)
task.wait()
keyPress(Enum.KeyCode.E, true)
wait(6)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-431.07,-51.08,-974.73)
task.wait()
keyPress(Enum.KeyCode.E, true)
wait(6)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-421.17,-47.80,-973.50)
task.wait()
keyPress(Enum.KeyCode.E, true)
wait(6)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-431.07,-51.08,-974.73)
task.wait()
keyPress(Enum.KeyCode.E, true)
wait(6)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-421.17,-47.80,-973.50)
task.wait()
keyPress(Enum.KeyCode.E, true)
wait(6)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-431.07,-51.08,-974.73)
task.wait()
keyPress(Enum.KeyCode.E, true)
wait(6)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-431.07,-2,-974.73)
task.wait()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-419.15,-2,-938.20)
task.wait(1)
loadstring(game:HttpGet('https://raw.githubusercontent.com/ttjy9808/tp-to-criminal-base2/main/README.md'))()
task.wait(3)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(121.9,26.48,-178.06)
