local mouse = game.Players.LocalPlayer:GetMouse()
local plr = game.Players.LocalPlayer
Character = game.Players.LocalPlayer
game.Players.LocalPlayer.PlayerGui.HUD.Bottom.SP.Visible = true
game.Players.LocalPlayer.PlayerGui.HUD.Bottom.SP.Text = "creado por te#3185 HELPER TSFxTrxz#9999"
 
    function invis2()
 
game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["Flash Strike"])
game.Players.LocalPlayer.Character["Flash Strike"]:Activate()
game.Workspace.Live[plr.Name].HumanoidRootPart.VanishParticle:Destroy()
end
 
 
      
    
      local player = game.Players.LocalPlayer
    player.Chatted:connect(function(cht)
        if cht:match("-invis") then
           invis2()
            invis()
        end end) 
        
        local mouse = game.Players.LocalPlayer:GetMouse()
local plr = game.Players.LocalPlayer
Character = game.Players.LocalPlayer
 
    function freeze2()
        mouse.KeyDown:Connect(function(key)
 
if key == 'k' then
game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["Trash???"])
game.Players.LocalPlayer.Character["Trash???"]:Activate()
game.Workspace.Live[plr.Name].HumanoidRootPart.VanishParticle:Destroy()
end
end)
mouse.KeyDown:connect(function(key)
    if key == 'k' then
        wait(0.5)
        game.Players.LocalPlayer.Character.Humanoid.Health = 0
        end end)
        game:GetService("StarterGui"):SetCore("SendNotification", {
        Title = "Trash script wolf900";
        Text = "Trash Activated, Pressk To Use";
        })
    end
      local player = game.Players.LocalPlayer
    player.Chatted:connect(function(cht)
        if cht:match("-trash") then
            freeze2()
            trash()
        end end)
        
   
   function dt2()
      game.Workspace.Live[plr.Name]["Dragon Throw"].Activator["Flip"]:Destroy()
   end
   local player = game.Players.LocalPlayer
   player.Chatted:connect(function(cht)
       if cht:match("-dt") then
           dt2()
           dt()
       end
       end)
    function ns2()
        
     game:GetService("StarterGui"):SetCore("SendNotification", {
        Title = "No Slow script wolf900";
        Text = "No Slow Activated, ";
        })
   
   
        
repeat wait()
 until game:IsLoaded()
   game.Players.LocalPlayer.PlayerGui:WaitForChild("HUD")
 
while wait() do
y = game.Players.LocalPlayer.Character
for i,v in pairs(y:GetChildren()) do
if v.Name == "Justice Combination" then
x = y:WaitForChild("Action")
if x then wait() x:Destroy() end end
if v.Name == "Action" then v:Destroy() end
if v.Name == "Attacking" then v:Destroy() end
if v.Name == "Using" then v:Destroy() end
if v.Name == "hyper" then v:Destroy() end
if v.Name == "Hyper" then v:Destroy() end
if v.Name == "heavy" then v:Destroy() end
if v.Name == "KiBlasted" then v:Destroy() end
if v.Name == "Tele" then v:Destroy() end
if v.Name == "tele" then v:Destroy() end
if v.Name == "Killed" then v:Destroy() end
if v.Name == "Slow" then v:Destroy() end
if v.Name == "Block" and v.Value == true then
v.Value = false end end end
 
      
end
      local player = game.Players.LocalPlayer
    player.Chatted:connect(function(cht)
        if cht:match("-ns") then
            ns2()
            ns()
            end end)  
 
function remove2()
game.Workspace.Live[plr.Name].RebirthWings.Handle:Destroy()
 end
 local player = game.Players.LocalPlayer
    player.Chatted:connect(function(cht)
        if cht:match("-rwings") then
            remove2()
            rwings()
            end end) 
 
function wolf2()
game.Workspace.Live[plr.Name].RealHalo.Handle:Destroy()
end
local player = game.Players.localPlayer
player.Chatted:connect(function(cht)
 if cht:match("rhalo") then
wolf2()
rhalo()
end end) 
 
function god2()
local Plr = game.Players.LocalPlayer
local GodModeBool = true

game:GetService("RunService").RenderStepped:connect(function()
if  GodModeBool  then
game.Workspace.Touchy.Part.CFrame = Plr.Character.HumanoidRootPart.CFrame + Vector3.new(0,0,1)
if Plr.PlayerGui:FindFirstChild("Popup") then
Plr.PlayerGui.Popup.Enabled = false
end
if not GodModeBool  then
return
end end end)
end
local player = game.Players.LocalPlayer
player.Chatted:connect(function(cht)
if cht:match("-gm") then
god2()
gm()
end end)
 
function cmds2()
print("-dt para bugear con tiro de dragon")
print("-trash bugear con el ataque basura")
print("-ns para activar no slow")
print("-invis para ser invisble necesitas el flash strike")
print("-rwings para remover las alas")
print("-rhalo para remover el halo")
print("-gm para activar el god mode")
print("-rj para hacer rejoin")
print("-beerus animation beerus")
print("-dc grab with dragon throw")
print("-hr hard reset")
print("-freeze press l to freeze")
print("-bc bugea a gente con el ataque bone crush")
print("-antiq antiqueue")
print("-destruction absoluta destruccion poca gente tiene el comando")
print("-hidelvl para borrar el nivel")
print("-vanish pareces el ultra instinto")
print("-gmbc godmode basico")
print("-vete es un comando para insultar")
print("-auradel borrar tu aura")
print("-antibug para cuando estes bug te desbugea")
print("-antibugv1 por si no te va el antibug normal pos este")
print("-autoaim primero le das ala p despues ala v y ya seleccionas al tipo")
print("-speed pulsa q")
print("-re respawn no funciona en freezers,nameks,majins,jirens")
print("-earth teleport para la tierra")
print("-namek teleport a namek")
print("-space teleport al space")
print("-future teleport al future")
print("-heaven teleport al heaven")
print("-queue teleport al queue")
print("-top teleport al top")
print("-automelee auto move spam")
end
local player = game.Players.LocalPlayer
player.Chatted:connect(function(cht)
if cht:match("-cmds") then
cmds2()
cmds()
end end)
function rj2()
game:GetService("TeleportService"):teleport(game.PlaceId)
end
local player = game.Players.LocalPlayer
player.Chatted:connect(function(cht)
if cht:match("-rj") then
rj2()
rj()
end end)
 
function wolf()
if not game:IsLoaded() then
game.Loaded:Wait()
end wait(0)
 
player = game.Players.LocalPlayer while wait() do
if game.Workspace.Live[player.Name].Animate.idle:FindFirstChild("Animation1") then
game.Workspace.Live[player.Name].Animate.idle:FindFirstChild("Animation1").AnimationId = "rbxassetid://1171558651"
if game.Workspace.Live[player.Name].Animate.walk:FindFirstChild("RunAnim") then
game.Workspace.Live[player.Name].Animate.walk:FindFirstChild("RunAnim").AnimationId = "rbxassetid://1171558651"
end end end
end
local player = game.Players.LocalPlayer
player.Chatted:connect(function(cht)
if cht:match("-beerus") then
wolf()
beerus()
end end)
 
function dc2()
game.Workspace.Live[plr.Name]["Dragon Crush"].Activator["Flip"]:Destroy()
end
local player = game.Players.LocalPlayer
player.Chatted:connect(function(cht)
if cht:match("-dc") then
dc2()
dc()
end end)
function lol()
game.Players.LocalPlayer.Character.Humanoid.Health = 0
end
local player = game.Players.LocalPlayer
player.Chatted:connect(function(cht)
if cht:match("-hr") then
lol()
hr()
end end)
 
function freeze3()
mouse.KeyDown:connect(function(key)
  if key == 'l' then
 
 
game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["Dragon Throw"])
game.Players.LocalPlayer.Character["Dragon Throw"]:Activate()
game.Workspace.Live[plr.Name]["Dragon Throw"].Activator["Flip"]:Destroy()
wait(0.5)
game:GetService("TeleportService"):teleport(game.PlaceId)
end end) end
local player = game.Players.LocalPlayer
player.Chatted:connect(function(cht)
if cht:match("-freeze") then
 game:GetService("StarterGui"):SetCore("SendNotification", {
        Title = "Freeze script wolf900";
        Text = "Freeze Activated, PressL To Use";
        })
freeze3()
freeze()
end end)
function kcao()
game:GetService("StarterGui"):SetCore("SendNotification", {
        Title = "Bone Crush script wolf900";
        Text = "Bone Crush Activated,";
        })
local plr = game.Players.LocalPlayer
       plr.Character["Bone Crush"].Activator.Crash:Destroy()
end
local player = game.Players.LocalPlayer
player.Chatted:connect(function(cht)
if cht:match("-bc") then
kcao()
bc()
end end)
function tusmuertos()
    
game.Workspace["Wormhole"].TouchInterest:Destroy()
end
local player = game.Players.LocalPlayer
player.Chatted:connect(function(cht)
if cht:match("-antiq") then
game:GetService("StarterGui"):SetCore("SendNotification", {
        Title = "Antiqueue Activated";
        Text = "AntiWormhole Activated";
        })
tusmuertos()
antiq()
end end)
destruction = true
function miss()
Move1 = "Energy Wave"
Move2 = "Double Sunday"
Move3 = "Destructo Disk"
Move4 = "Kamehameha"
Move5 = "Tribeam"
Move6 = "Burning Attack"
Move7 = "Big Bang Attack"
Move8 = "Hellzone Grenade"
Move9 = "Special Beam Cannon"
Move10 = "Galick Gun"
Move11 = "Spirit Ball"
Move12 = "Burning Blast"
Move13 = "Special Beam Cannon"
Move14 = "Heat Dome Attack"
Move15 = "Light Grenade"
Move16 = "Final Flash"
Move17 = "Giant Storm"
Move18 = "Warp Kamehameha"
Move19 = "Spirit Bomb"
Move20 = "Big Bang Kamehameha"
Move21 = "Sudden Storm"
Move22 = "Milky Cannon"
Move23 = "Demon Flash"
Move24 = "Super Nova"
Move25 = "Genocide Shell"
Move26 = "Breack Cannon"
Move27 = "Beam Scatter"
Move28 = "Final Shine"
Move29 = "Justice Flash"
Move30 = "Final Kame"
Move31 = "Pressure Gauge"
Move32 = "Divine Lasso"
Move33 = "Holy Wrath"
Move34 = "Super Death Beam"
Move35 = "Super Spirit Bomb"
Move36 = "Broly Kamehameha"
Move37 = "Gigantic Breath"
Move38 = "Planet Crusher"
Move39 = "Blaster Meteor"
Move40 = "Eraser Cannon"
Move41 = "Dark Beam"
Move42 = "Unrelenting Volley"
Move43 = "KKx4 Kamehameha"
Move44 = "Explosive Grip"
Move45 = "Buu Blaster"
Move46 = "Double Buster"
Move47 = "One-Hand Kamehame"
Move48 = "Flame Kamehameha"
Move49 = "Death Beam"
repeat
        game:GetService("RunService").RenderStepped:Wait()
        for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
            if
                v.Name == Move1 or v.Name == Move2 or v.Name == Move3 or v.Name == Move4 or v.Name == Move5 or
                    v.Name == Move6 or
                    v.Name == Move7 or
                    v.Name == Move8 or
                    v.Name == Move9 or
                    v.Name == Move10 or
                    v.Name == Move11 or
                    v.Name == Move12 or
                    v.Name == Move13 or
                    v.Name == Move14 or
                    v.Name == Move15 or
                    v.Name == Move16 or
                    v.Name == Move17 or
                    v.Name == Move18 or
                    v.Name == Move19 or 
                    v.Name == Move20 or
                    v.Name == Move21 or
                    v.Name == Move22 or
                    v.Name == Move23 or
                    v.Name == Move24 or
                    v.Name == Move25 or
                    v.Name == Move26 or
                    v.Name == Move27 or 
                    v.Name == Move28 or
                    v.Name == Move29 or
                    v.Name == Move30 or 
                    v.Name == Move31 or 
                    v.Name == Move32 or
                    v.Name == Move33 or
                    v.Name == Move34 or 
                    v.Name == Move35 or
                    v.Name == Move36 or
                    v.Name == Move37 or
                    v.Name == Move38 or
                    v.Name == Move39 or
                    v.Name == Move40 or
                    v.Name == Move41 or
                    v.Name == Move42 or
                    v.Name == Move43 or 
                    v.Name == Move44 or
                    v.Name == Move45 or
                    v.Name == Move46 or
                    v.Name == Move47 or
                    v.Name == Move48 or
                    v.Name == Move49 
                    
             then
                v.Parent = game:GetService("Workspace").Live[game.Players.LocalPlayer.Name]
                wait()
                v:Activate()
                v:Deactivate()
                v.Parent = game.Players.LocalPlayer.Backpack
            end
        end
 
    until rem
 
end
local player = game.Players.LocalPlayer
player.Chatted:connect(function(cht)
 if cht:match("-destruction") then
 
miss()
destruction()
end end)
function mequieres()
for i,v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do 
if v.Name:find("Lvl. ") or v.Name:find("Prestige:") then 
v:Destroy() 
end end
end
local player = game.Players.LocalPlayer
player.Chatted:connect(function(cht)
if cht:match("hidelvl") then
mequieres()
hidelvl()
end end)
function  vanish2()
while true do
wait()
game.Players.LocalPlayer.Backpack.ServerTraits.Vanish:FireServer()
end
end
local player = game.Players.LocalPlayer
player.Chatted:connect(function(cht)
 if cht:match("-vanish") then
vanish2()
vanish()
end end)
function creeper()
game.Workspace.Live[plr.Name].Stats["Ki-Resist"]:Destroy()
game.Workspace.Live[plr.Name].Stats["Phys-Resist"]:Destroy() end
local player = game.Players.LocalPlayer
player.Chatted:connect(function(cht)
if cht:match("-gmbc") then
creeper()
gmbc()
end end)
function minecraft()
-- Script generated by SimpleSpy - credits to exx#9394
wait(0.9)
local args = {
    [1] = "Noob Go Back To Fortnite",
    [2] = "All"
}
 
game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
 
-- Script generated by SimpleSpy - credits to exx#9394
wait(0.9)
local args = {
    [1] = "Your Mother Is A Man",
    [2] = "All"
}
game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
wait(0.9)
local args = {
    [1] = "You Cause Lung Cancer",
    [2] = "All"
}
game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
end
local player = game.Players.LocalPlayer
player.Chatted:connect(function(cht)
if cht:match("-vete") then
minecraft()
vete()
end end)
function aura2()
for i,v in pairs(game.Players.LocalPlayer.Character.HumanoidRootPart:GetChildren()) do 
if v.Name:find("Aura") or v.Name:find("Trail") or v.Name:find("SaiyanLoop") or v.Name:find("Lightning") then 
v:Destroy() 
end end
end
local player = game.Players.LocalPlayer
player.Chatted:connect(function(cht)
if cht:match("-auradel") then
aura2()
auradel()
end end)
function antibug2()
 
 
if not game:IsLoaded() then
game.Loaded:Wait()
end
 
local plr = game.Players.LocalPlayer
 
while wait() do
    pcall(function()
        game:GetService("Workspace").Live[plr.Name].LowerTorso.BodyVelocity:Destroy()
    end)
end
end
local player = game.Players.LocalPlayer
player.Chatted:connect(function(cht)
if cht:match("-antibug")
then
antibug2()
antibug()
end end)
function antibug3()
if not game:IsLoaded() then
game.Loaded:Wait()
end
 
local plr = game.Players.LocalPlayer
 
while wait() do
    pcall(function()
        game:GetService("Workspace").Live[plr.Name].LowerTorso.KnockBacked:Destroy()
    end)
end
end
local player = game.Players.LocalPlayer
player.Chatted:connect(function(cht)
if cht:match("-antibugv1") then
antibug3()
antibugv1()
end end)
function aim2()
game:GetService("StarterGui"):SetCore("SendNotification", {
        Title = "Pulsa p para desbloquear aimbot";
        Text = "Pulsa v para seleccionar";
        })
 
local plrs = game:GetService("Players")
local TeamBased = true ; local teambasedswitch = "p"
local presskeytoaim = true; local aimkey = "v"
local raycast = false
 
local espupdatetime = 5; autoesp = false
 
 
 
local lockaim = true; local lockangle = 5
 
 
 
--function findwat(folder, what)
--  for i, smth in pairs(folder:GetChildren()) do
--      if string.find(string.lower(tostring(smth)), string.lower(what)) then
--          return smth
--      end
--  end
--end
--
--local plrs = findwat(game, "Players")
 
 
 
 
local Gui = Instance.new("ScreenGui")
local Move = Instance.new("Frame")
local Main = Instance.new("Frame")
local st1 = Instance.new("TextLabel")
local st1_2 = Instance.new("TextLabel")
local st1_3 = Instance.new("TextLabel")
local Name = Instance.new("TextLabel")
--Properties:
 
-- Scripts:
 
 
local plrsforaim = {}
 
local lplr = game:GetService("Players").LocalPlayer
Move.Draggable = true
Gui.ResetOnSpawn = false
Gui.Name = "Chat"
Gui.DisplayOrder = 999
 
    Gui.Parent = plrs.LocalPlayer.PlayerGui
 
 
f = {}
 
 
 
local cam = game.Workspace.CurrentCamera
 
local mouse = lplr:GetMouse()
local switch = false
local key = "k"
local aimatpart = nil
mouse.KeyDown:Connect(function(a)
    if a == "t" then
        print("worked1")
        f.addesp()
    elseif a == "u" then
        if raycast == true then
            raycast = false
        else
            raycast = true
        end
    elseif a == "l" then
        if autoesp == false then
            autoesp = true
        else
            autoesp = false
        end
    end
    if a == "j" then
        if mouse.Target then
            mouse.Target:Destroy()
        end
    end
    if a == key then
        if switch == false then
            switch = true
        else
            switch = false
            if aimatpart ~= nil then
                aimatpart = nil
            end
        end
    elseif a == teambasedswitch then
        if TeamBased == true then
            TeamBased = false
            teambasedstatus.Text = tostring(TeamBased)
        else
            TeamBased = true
            teambasedstatus.Text = tostring(TeamBased)
        end
    elseif a == aimkey then
        if not aimatpart then
            local maxangle = math.rad(20)
            for i, plr in pairs(plrs:GetChildren()) do
                if plr.Name ~= lplr.Name and plr.Character and plr.Character.Head and plr.Character.Humanoid and plr.Character.Humanoid.Health > 1 then
                    if TeamBased == true then
                        if plr.Team.Name ~= lplr.Team.Name then
                            local an = checkfov(plr.Character.Head)
                            if an < maxangle then
                                maxangle = an
                                aimatpart = plr.Character.Head
                            end
                        end
                    else
                        local an = checkfov(plr.Character.Head)
                            if an < maxangle then
                                maxangle = an
                                aimatpart = plr.Character.Head
                            end
                            print(plr)
                    end
                    plr.Character.Humanoid.Died:Connect(function()
                        if aimatpart.Parent == plr.Character or aimatpart == nil then
                            aimatpart = nil
                        end
                    end)
                end
            end
        else
            aimatpart = nil
        end
    end
end)
 
function getfovxyz (p0, p1, deg)
    local x1, y1, z1 = p0:ToOrientation()
    local cf = CFrame.new(p0.p, p1.p)
    local x2, y2, z2 = cf:ToOrientation()
    --local d = math.deg
    if deg then
        --return Vector3.new(d(x1-x2), d(y1-y2), d(z1-z2))
    else
        return Vector3.new((x1-x2), (y1-y2), (z1-z2))
    end
end
 
function getaimbotplrs()
    plrsforaim = {}
    for i, plr in pairs(plrs:GetChildren()) do
        if plr.Character and plr.Character.Humanoid and plr.Character.Humanoid.Health > 0 and plr.Name ~= lplr.Name and plr.Character.Head then
            
            if TeamBased == true then
                if plr.Team.Name ~= lplr.Team.Name then
                    local cf = CFrame.new(game.Workspace.CurrentCamera.CFrame.p, plr.Character.Head.CFrame.p)
                    local r = Ray.new(cf, cf.LookVector * 10000)
                    local ign = {}
                    for i, v in pairs(plrs.LocalPlayer.Character:GetChildren()) do
                        if v:IsA("BasePart") then
                            table.insert(ign , v)
                        end
                    end
                    local obj = game.Workspace:FindPartOnRayWithIgnoreList(r, ign)
                    if obj.Parent == plr.Character and obj.Parent ~= lplr.Character then
                        table.insert(plrsforaim, obj)
                    end
                end
            else
                local cf = CFrame.new(game.Workspace.CurrentCamera.CFrame.p, plr.Character.Head.CFrame.p)
                local r = Ray.new(cf, cf.LookVector * 10000)
                local ign = {}
                for i, v in pairs(plrs.LocalPlayer.Character:GetChildren()) do
                    if v:IsA("BasePart") then
                        table.insert(ign , v)
                    end
                end
                local obj = game.Workspace:FindPartOnRayWithIgnoreList(r, ign)
                if obj.Parent == plr.Character and obj.Parent ~= lplr.Character then
                    table.insert(plrsforaim, obj)
                end
            end
            
            
        end
    end
end
 
function aimat(part)
    cam.CFrame = CFrame.new(cam.CFrame.p, part.CFrame.p)
end
function checkfov (part)
    local fov = getfovxyz(game.Workspace.CurrentCamera.CFrame, part.CFrame)
    local angle = math.abs(fov.X) + math.abs(fov.Y)
    return angle
end
 
game:GetService("RunService").RenderStepped:Connect(function()
    if aimatpart then
        aimat(aimatpart)
        if aimatpart.Parent == plrs.LocalPlayer.Character then
            aimatpart = nil
        end
    end
    
    
--  if switch == true then
--      local maxangle = 99999
--      
--      --print("Loop")
--      if true and raycast == false then
--          for i, plr in pairs(plrs:GetChildren()) do
--              if plr.Name ~= lplr.Name and plr.Character and plr.Character.Head and plr.Character.Humanoid and plr.Character.Humanoid.Health > 1 then
--                  if TeamBased then
--                      if plr.Team.Name ~= lplr.Team.Name or plr.Team.TeamColor ~= lplr.Team.TeamColor then
--                          local an = checkfov(plr.Character.Head)
--                          if an < maxangle then
--                              maxangle = an
--                              aimatpart = plr.Character.Head
--                              if an < lockangle then
--                                  break
--                              end
--                          end
--                      end
--                  else
--                      local an = checkfov(plr.Character.Head)
--                          if an < maxangle then
--                              maxangle = an
--                              aimatpart = plr.Character.Head
--                              if an < lockangle then
--                                  break
--                              end
--                          end
--                  end
--                  
--                  
--                  
--                  
--              end
--          end
--      elseif raycast == true then
--          
--      end
        
        if raycast == true and switch == false and not aimatpart then
            getaimbotplrs()
            aimatpart = nil
            local maxangle = 999
            for i, v in ipairs(plrsforaim) do
                if v.Parent ~= lplr.Character then
                    local an = checkfov(v)
                    if an < maxangle and v ~= lplr.Character.Head then
                        maxangle = an
                        aimatpart = v
                        print(v:GetFullName())
                        v.Parent.Humanoid.Died:connect(function()
                            aimatpart = nil
                        end)
                    end
                end
            end
        
    end
end)
delay(0, function()
    while wait(espupdatetime) do
        if autoesp == true then
            pcall(function()
            f.addesp()
            end)
        end
    end
end)
end
local player = game.Players.LocalPlayer
player.Chatted:connect(function(cht)
if cht:match("-autoaim") then
aim2()
autoaim()
end end)

function speed2()
 game:GetService("StarterGui"):SetCore("SendNotification", {
        Title = "speed mantiene la Q para obtener la velocidad";
        Text = "Mantiene la Q";
        })
down = false
velocity = Instance.new("BodyVelocity")
velocity.maxForce = Vector3.new(10000000, 0, 10000000)
---vv Use that to change the speed v
local speed    = 1000
gyro           = Instance.new("BodyGyro")
gyro.maxTorque = Vector3.new(10000000, 0, 10000000)

local hum = game.Players.LocalPlayer.Character.Humanoid

function onButton1Down(mouse)
down = true
velocity.Parent = game.Players.LocalPlayer.Character.UpperTorso
velocity.velocity = (hum.MoveDirection) * speed
gyro.Parent = game.Players.LocalPlayer.Character.UpperTorso
while down do
if not down then break end
velocity.velocity = (hum.MoveDirection) * speed
local refpos = gyro.Parent.Position + (gyro.Parent.Position - workspace.CurrentCamera.CoordinateFrame.p).unit * 5
gyro.cframe = CFrame.new(gyro.Parent.Position, Vector3.new(refpos.x, gyro.Parent.Position.y, refpos.z))
wait(0.1)
end
end

function onButton1Up(mouse)
velocity.Parent = nil
gyro.Parent = nil
down = false
end
--To Change the key in those 2 lines, replace the "q" with your desired key
function onSelected(mouse)
mouse.KeyDown:connect(function(k) if k:lower()=="q"then onButton1Down(mouse)end end)
mouse.KeyUp:connect(function(k) if k:lower()=="q"then onButton1Up(mouse)end end)
end

onSelected(game.Players.LocalPlayer:GetMouse())

end
local player = game.Players.LocalPlayer
player.Chatted:connect(function(cht)
if cht:match("-speed") then
speed2()
speed()
end end)
function respawn()
local args = {
[1] = workspace.FriendlyNPCs:FindFirstChild("Hair Stylist")
}
game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatStart:FireServer(unpack(args))
wait(0.3)
local A_1 = {
 [1] = "Yes"
       }
  game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance:FireServer(A_1)
  wait(1)
  local args = {
  [1] = "woah"
  }
  game:GetService("Players").LocalPlayer.Backpack.HairScript.RemoteEvent:FireServer(unpack(args))
  end
  local player = game.Players.LocalPlayer
  player.Chatted:connect(function(cht)
  if cht:match("-re") then
  respawn()
  re()
  end end)
  function elaz()
      local mouse = game.Players.LocalPlayer:GetMouse()
mouse.KeyDown:connect(function(key)
    if key == 'k' then

Move1 = "Rush"
Move2 = "Sledgehammer"
Move3 = "Wolf Fang Fist"
Move4 = "Final Blow"
Move5 = "Launcher"
Move6 = "Dirty Fireworks"
Move7 = "Mach Kick"
Move8 = "Bone Crush"
Move9 = "Recoome Kick"
Move10 = "Flip Kick"
Move11 = "Neo Wolf Fang Fist"
Move12 = "Combo Barrage"
Move13 = "Trash?"
Move14 = "Aerial Breaker"
Move15 = "Meteor Crash"
Move16 = "Dive Kick"
Move17 = "Spirit Breaking Cannon"
Move18 = "Super Rush"
Move19 = "Strike Of Revelation"
Move20 = "Double Launcher"
Move21 = "Dirty Fireworksx5"
Move22 = "Strong Kick"
Move23 = "Super Dragon Fist"
Move24 = "Sweep Kick"
Move25 = "Justice Combination"
Move26 = "Kaioken Assault"
Move27 = "Flash Strike"
Move28 = "Punisher Drive"
Move29 = "Strong Punch"
Move30 = "Second Bloom"
Move31 = "Kick Barrage"
Move32 = "Drop Kick"
Move33 = "Spirit Splash"
Move34 = "God Slicer"
Move35 = "Spirit Bomb Sword"
Move36 = "Arm Crash"
Move37 = "Power Impact"
Move38 = "Flash Counter"
Move39 = "Emperor's Edge"
Move40 = "Deadly Dance"
Move41 = "Wrathful Charge"
Move42 = "Anger Rush"
Move43 = "Trash???"
Move44 = "Vital Strike"
Move45 = "TS Molotov"
Move46 = "Flash Skewer"
repeat
        game:GetService("RunService").RenderStepped:Wait()
        for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
            if v.Name == Move1 or v.Name == Move2 or v.Name == Move3 or v.Name == Move4 or v.Name == Move5 or
                    v.Name == Move6 or
                    v.Name == Move7 or
                    v.Name == Move8 or
                    v.Name == Move9 or
                    v.Name == Move10 or
                    v.Name == Move11 or
                    v.Name == Move12 or
                    v.Name == Move13 or
                    v.Name == Move14 or
                    v.Name == Move15 or
                    v.Name == Move16 or
                    v.Name == Move17 or
                    v.Name == Move18 or
                    v.Name == Move19 or 
                    v.Name == Move20 or
                    v.Name == Move21 or
                    v.Name == Move22 or
                    v.Name == Move23 or
                    v.Name == Move24 or
                    v.Name == Move25 or
                    v.Name == Move26 or
                    v.Name == Move27 or 
                    v.Name == Move28 or
                    v.Name == Move29 or
                    v.Name == Move30 or 
                    v.Name == Move31 or 
                    v.Name == Move32 or
                    v.Name == Move33 or
                    v.Name == Move34 or 
                    v.Name == Move35 or
                    v.Name == Move36 or
                    v.Name == Move37 or
                    v.Name == Move38 or
                    v.Name == Move39 or
                    v.Name == Move40 or
                    v.Name == Move41 or
                    v.Name == Move42 or
                    v.Name == Move43 or 
                    v.Name == Move44 or
                    v.Name == Move45 or
                    v.Name == Move46 or
                    v.Name == Move47 or
                    v.Name == Move48 or
                    v.Name == Move49
                    
             then
                v.Parent = game:GetService("Workspace").Live[game.Players.LocalPlayer.Name]
                wait()
                v:Activate()
                v:Deactivate()
                v.Parent = game.Players.LocalPlayer.Backpack
            end
        end
 
    until rem

end; end);


end
local player = game.Players.LocalPlayer
 player.Chatted:connect(function(cht)
    if cht:match("-automelee") then
        elaz(game:GetService("StarterGui"):SetCore("SendNotification",{
Title = "Destruction",
Text = "press k to activate destruction",Duration=80}))
        automelee()
    end end)
    function teleport()
    game:GetService("TeleportService"):teleport(536102540)
end
local player = game.Players.LocalPlayer
player.Chatted:connect(function(cht)
    if cht:match("-earth") then
        game:GetService("StarterGui"):SetCore("SendNotification", {
        Title = "earth";
        Text = "Teletransportando a earth";
        })
    wait(1)
teleport()
earth() 
    end end)

function teleport2()
    game:GetService("TeleportService"):teleport(3565304751)
end
local player = game.Players.LocalPlayer
player.Chatted:connect(function(cht)
    if cht:match("-queue") then
        game:GetService("StarterGui"):SetCore("SendNotification", {
        Title = "Queue";
        Text = "Teletransportando al Queue";
        })
        wait(1)
teleport2()
queue() 
    end end)
    function teleport3()
    game:GetService("TeleportService"):teleport(2651456105)
end

    local player = game.Players.LocalPlayer
player.Chatted:connect(function(cht)
    if cht:match("-zaros") then
        game:GetService("StarterGui"):SetCore("SendNotification", {
        Title = "zaros";
        Text = "Teletransportando a Zaros";
        })
        wait(1)
teleport3()
zaros() 
end end)



    function teleport4()
    game:GetService("TeleportService"):teleport(3552157537)
end

    local player = game.Players.LocalPlayer
player.Chatted:connect(function(cht)
    if cht:match("-heaven") then
        teleport4()
        heaven()
        game:GetService("StarterGui"):SetCore("SendNotification", {
        Title = "Heaven";
        Text = "Teletransportando a heaven";
        })
    wait(1)
        teleport4()
        heaven()
end end)
if game.PlaceId == 536102540 then
        function teleport5()
    game:GetService("TweenService"):Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(2, Enum.EasingStyle.Linear),{CFrame = CFrame.new(2516.1403808594, 3945.7043457031, -2023.5339355469)}):Play()
end
    local player = game.Players.LocalPlayer
player.Chatted:connect(function(cht)
    if cht:match("-top") then
        game:GetService("StarterGui"):SetCore("SendNotification", {
        Title = "Top PAD";
        Text = "Teletransportando a top PAD";
        })
        wait(1)
        teleport5()
        top()
    end end)
    end
        function teleport6()
    game:GetService("TeleportService"):teleport(569994010)
end

    local player = game.Players.LocalPlayer
player.Chatted:connect(function(cht)
    if cht:match("-future") then
        game:GetService("StarterGui"):SetCore("SendNotification", {
        Title = "Future";
        Text = "Teletransportando a future";
        })
        wait(1)
        teleport6()
        futuro()
    end end)
    
    
        function teleport7()
    game:GetService("TeleportService"):teleport(2046990924)
end

    local player = game.Players.LocalPlayer
player.Chatted:connect(function(cht)
    if cht:match("-secret") then
        game:GetService("StarterGui"):SetCore("SendNotification", {
        Title = "Secret";
        Text = "Teletransportando a secret";
        })
        wait(1)
teleport7()
secret() 
end end)
function teleport8()
    game:GetService("TeleportService"):teleport(882399924)
end

 local player = game.Players.LocalPlayer
player.Chatted:connect(function(cht)
    if cht:match("-namek") then
        game:GetService("StarterGui"):SetCore("SendNotification", {
        Title = "Namek";
        Text = "Teletransportando a namek";
        })
        wait(1)
teleport8()
namek() 
end end)
function teleport9()
    game:GetService("TeleportService"):teleport(478132461)
end
local player = game.Players.LocalPlayer
player.Chatted:connect(function(cht)
    if cht:match("-space") then
        game:GetService("StarterGui"):SetCore("SendNotification", {
        Title = "space";
        Text = "Teletransportando a space";
        })
        wait(1)
teleport9()
space() 
end end)
function redspam()
game:GetService("StarterGui"):SetCore("SendNotification",{
    Title = "red spam",
    Text = "Press K For spam"
}
)
game:GetService("StarterGui"):SetCore("SendNotification",{
    Title = "red spam",
    Text = "IN BETA!!"
}
)

pcall(function()
game.Players.LocalPlayer:GetMouse().KeyDown:Connect(function(key)
if key == "k" then
old = game.Players.LocalPlayer.Character:FindFirstChild("HumanoidRootPart").CFrame -- stores cframe
local args = {
    [1] = true
}

game:GetService("Players").LocalPlayer.Backpack.ServerTraits:WaitForChild("EatSenzu"):FireServer(unpack(args))

local args = {
[1] = workspace.FriendlyNPCs:FindFirstChild("Hair Stylist")
}
game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatStart:FireServer(unpack(args))
wait(0.3)
local A_1 = {
 [1] = "Yes"
       }
  game:GetService("Players").LocalPlayer.Backpack.ServerTraits.ChatAdvance:FireServer(A_1)
  task.wait(0.8)
  local args = {
  [1] = "woah"
  }
  game:GetService("Players").LocalPlayer.Backpack.HairScript.RemoteEvent:FireServer(unpack(args))

game.Players.LocalPlayer.CharacterAdded:Wait() -- yields until character s added
while not game.Players.LocalPlayer.Character:FindFirstChild("Prestige") and task.wait() do
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = old
end
end
end)
end)
end

local player = game.Players.LocalPlayer
player.Chatted:Connect(function(cht)
if cht:match('-redspam') then
redspam()
redspam2()
end end)
