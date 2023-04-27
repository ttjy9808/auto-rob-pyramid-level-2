localplayer = game.Players.LocalPlayer
 Char = localplayer.Character or workspace:FindFirstChild(localplayer.Name)
         HRP = Char and Char:FindFirstChild("HumanoidRootPart")
        if not Char or not HRP then
           
        end
         p = HRP.Position
         hrd = game.Players.LocalPlayer.Character.HumanoidRootPart
         x = -3098.3
         y = -30.06
       	 z = -624.18
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

 local localplayer = game.Players.LocalPlayer
local Char = localplayer.Character or workspace:FindFirstChild(localplayer.Name)
        local HRP = Char and Char:FindFirstChild("HumanoidRootPart")
        if not Char or not HRP then
           
        end
        local p = HRP.Position
        local hrd = game.Players.LocalPlayer.Character.HumanoidRootPart
        local x = -3095.06
        local y = -27.76
        local z = -620.61
        hrd.CFrame = CFrame.new(p.x, -27.76, p.z)
        wait(0.5)
        local currentPos = Vector3.new(p.x, -27.76, p.z)
        local targetPos = Vector3.new(x, -27.76, z)

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
        
        local currentPos = Vector3.new(x, -27.76, z)
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
        task.wait(0.1)
        local p = hrd.Position
        
        local currentPos = Vector3.new(x, -27.76, z)
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
         x = -2931.5
         y = -33
       	 z = -541.56
        hrd.CFrame = CFrame.new(p.x, -27.76, p.z)
        wait(0.5)
         currentPos = Vector3.new(p.x, -27.76, p.z)
         targetPos = Vector3.new(x, -27.76, z)

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
        
         currentPos = Vector3.new(x, -27.76, z)
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
        local hrd = game.Players.LocalPlayer.Character.HumanoidRootPart
        local x = -3094.47
        local y = -27.76
        local z = -622.14
        hrd.CFrame = CFrame.new(p.x, -27.76, p.z)
        wait(0.5)
        local currentPos = Vector3.new(p.x, -27.76, p.z)
        local targetPos = Vector3.new(x, -27.76, z)

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
        
        local currentPos = Vector3.new(x, -27.76, z)
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
        local x = -3154.79
        local y = -33.1
        local z = -496.27
        hrd.CFrame = CFrame.new(p.x, -27.76, p.z)
        wait(0.5)
        local currentPos = Vector3.new(p.x, -27.76, p.z)
        local targetPos = Vector3.new(x, -27.76, z)

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
        
        local currentPos = Vector3.new(x, -27.76, z)
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
        task.wait(1)
keyPress(Enum.KeyCode.E, true)
task.wait(5)
 local localplayer = game.Players.LocalPlayer
local Char = localplayer.Character or workspace:FindFirstChild(localplayer.Name)
        local HRP = Char and Char:FindFirstChild("HumanoidRootPart")
        if not Char or not HRP then
           
        end
        local p = HRP.Position
        local hrd = game.Players.LocalPlayer.Character.HumanoidRootPart
        local x = -3094.47
        local y = -27.76
        local z = -622.14
        hrd.CFrame = CFrame.new(p.x, -27.76, p.z)
        wait(0.5)
        local currentPos = Vector3.new(p.x, -27.76, p.z)
        local targetPos = Vector3.new(x, -27.76, z)

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
        
        local currentPos = Vector3.new(x, -27.76, z)
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
        local x = -3094.47
        local y = -27.76
        local z = -622.14
        hrd.CFrame = CFrame.new(p.x, -27.76, p.z)
        wait(0.5)
        local currentPos = Vector3.new(p.x, -27.76, p.z)
        local targetPos = Vector3.new(x, -27.76, z)

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
        
        local currentPos = Vector3.new(x, -27.76, z)
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
        local x = -2991.84
        local y = -33
        local z = -835.77
        hrd.CFrame = CFrame.new(p.x, -27.76, p.z)
        wait(0.5)
        local currentPos = Vector3.new(p.x, -27.76, p.z)
        local targetPos = Vector3.new(x, -27.76, z)

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
        
        local currentPos = Vector3.new(x, -27.76, z)
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
        task.wait(1)
      keyPress(Enum.KeyCode.E, true)
task.wait(5)
        local localplayer = game.Players.LocalPlayer
local Char = localplayer.Character or workspace:FindFirstChild(localplayer.Name)
        local HRP = Char and Char:FindFirstChild("HumanoidRootPart")
        if not Char or not HRP then
           
        end
        local p = HRP.Position
        local hrd = game.Players.LocalPlayer.Character.HumanoidRootPart
        local x = -3094.47
        local y = -27.76
        local z = -622.14
        hrd.CFrame = CFrame.new(p.x, -27.76, p.z)
        wait(0.5)
        local currentPos = Vector3.new(p.x, -27.76, p.z)
        local targetPos = Vector3.new(x, -27.76, z)

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
        
        local currentPos = Vector3.new(x, -27.76, z)
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
        local x = -3270.34
        local y = -35
        local z = -706.95
        hrd.CFrame = CFrame.new(p.x, -27.76, p.z)
        wait(0.5)
        local currentPos = Vector3.new(p.x, -27.76, p.z)
        local targetPos = Vector3.new(x, -27.76, z)

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
        
        local currentPos = Vector3.new(x, -27.76, z)
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
        local x = -3357.89
        local y = -27
        local z = -674.7
        hrd.CFrame = CFrame.new(p.x, -34.99, p.z)
        wait(0.5)
        local currentPos = Vector3.new(p.x, -34.99, p.z)
        local targetPos = Vector3.new(x, -34.99, z)

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
        
        local currentPos = Vector3.new(x, -34.99, z)
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
        local x = -3405.18
        local y = -37.7
        local z = -553.24
        hrd.CFrame = CFrame.new(p.x, -6, p.z)
        wait(0.5)
        local currentPos = Vector3.new(p.x, -6, p.z)
        local targetPos = Vector3.new(x, -6, z)

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
        
        local currentPos = Vector3.new(x, -6, z)
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
         x = -3269.64
         y = -34.8
       	 z = -473.55
        hrd.CFrame = CFrame.new(p.x, -3, p.z)
        wait(0.5)
         currentPos = Vector3.new(p.x, -27.76, p.z)
         targetPos = Vector3.new(x, -27.76, z)

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
        
         currentPos = Vector3.new(x, -27.76, z)
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
repeat task.wait() until game.Workspace.Heists.Pyramid.Level2.RoofTrap.Door.Position.Y > -18.916236877441406
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-3200.69970703125, -34.97478103637695, -476.39947509765625)
	task.wait(0.5)
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-3198.41650390625, -23.371816635131836, -467.68878173828125)
	task.wait(0.5)
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-3160.27587890625, -34.97908020019531, -442.07513427734375)
	task.wait(0.5)
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-3131.61376953125, -34.899078369140625, -436.4435729980469)
	task.wait(0.5)
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-3115.545654296875, -34.899078369140625, -407.427734375)
	task.wait(0.5)
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-3111.57470703125, -23.34929656982422, -403.7622375488281)
	task.wait(0.5)
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-3096.9404296875, -34.899078369140625, -388.6240539550781)	
	task.wait(0.5)
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2991.98974609375, -34.899078369140625, -349.51629638671875)
	task.wait(0.5)
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2896.046142578125, -34.99907684326172, -318.60601806640625)
	task.wait(0.5)
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2805.063232421875, -34.342620849609375, -295.623291015625)
	task.wait(0.5)
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2810.429443359375, -34.89299774169922, -327.98675537109375)
	task.wait(1)
		local VirtualInputManager = game:GetService('VirtualInputManager')

function keyPress(Key, Press)
    VirtualInputManager:SendKeyEvent(Press, Key, false, game)
end
task.wait(1)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2810.429443359375, -34.89299774169922, -327.98675537109375)
task.wait()
keyPress(Enum.KeyCode.E, true)
wait(6)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2806.060791015625, -31.192115783691406, -337.8108825683594)
task.wait()
keyPress(Enum.KeyCode.E, true)
wait(6)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2810.429443359375, -34.89299774169922, -327.98675537109375)
task.wait()
keyPress(Enum.KeyCode.E, true)
wait(6)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2806.060791015625, -31.192115783691406, -337.8108825683594)
task.wait()
keyPress(Enum.KeyCode.E, true)
wait(6)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2810.429443359375, -34.89299774169922, -327.98675537109375)
task.wait()
keyPress(Enum.KeyCode.E, true)
wait(6)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2806.060791015625, -31.192115783691406, -337.8108825683594)
task.wait()
keyPress(Enum.KeyCode.E, true)
wait(6)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2810.429443359375, -34.89299774169922, -327.98675537109375)
task.wait()
keyPress(Enum.KeyCode.E, true)
wait(6)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2806.060791015625, -31.192115783691406, -337.8108825683594)
task.wait()
keyPress(Enum.KeyCode.E, true)
wait(6)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2810.429443359375, -34.89299774169922, -327.98675537109375)
task.wait()
keyPress(Enum.KeyCode.E, true)
wait(6)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2774.34,18.47,-322.68)
task.wait()
loadstring(game:HttpGet('https://raw.githubusercontent.com/ttjy9808/tp-to-criminal-base/main/README.md'))()
task.wait(5)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(121.9,26.48,-178.06)
