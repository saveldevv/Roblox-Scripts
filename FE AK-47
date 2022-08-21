function sandbox(var,func)
	local env = getfenv(func)
	local newenv = setmetatable({},{
		__index = function(self,k)
			if k=="script" then
				return var
			else
				return env[k]
			end
		end,
	})
	setfenv(func,newenv)
	return func
end
cors = {}
mas = Instance.new("Model",game:GetService("Lighting"))
Tool0 = Instance.new("Tool")
NumberValue1 = Instance.new("NumberValue")
NumberValue2 = Instance.new("NumberValue")
StringValue3 = Instance.new("StringValue")
NumberValue4 = Instance.new("NumberValue")
StringValue5 = Instance.new("StringValue")
NumberValue6 = Instance.new("NumberValue")
NumberValue7 = Instance.new("NumberValue")
NumberValue8 = Instance.new("NumberValue")
StringValue9 = Instance.new("StringValue")
Script10 = Instance.new("Script")
LocalScript11 = Instance.new("LocalScript")
NumberValue12 = Instance.new("NumberValue")
StringValue13 = Instance.new("StringValue")
NumberValue14 = Instance.new("NumberValue")
NumberValue15 = Instance.new("NumberValue")
NumberValue16 = Instance.new("NumberValue")
ScreenGui17 = Instance.new("ScreenGui")
Frame18 = Instance.new("Frame")
Frame19 = Instance.new("Frame")
TextLabel20 = Instance.new("TextLabel")
Frame21 = Instance.new("Frame")
TextLabel22 = Instance.new("TextLabel")
TextLabel23 = Instance.new("TextLabel")
TextLabel24 = Instance.new("TextLabel")
Frame25 = Instance.new("Frame")
ImageLabel26 = Instance.new("ImageLabel")
ImageLabel27 = Instance.new("ImageLabel")
ImageLabel28 = Instance.new("ImageLabel")
ImageLabel29 = Instance.new("ImageLabel")
Frame30 = Instance.new("Frame")
TextLabel31 = Instance.new("TextLabel")
ImageLabel32 = Instance.new("ImageLabel")
Frame33 = Instance.new("Frame")
TextLabel34 = Instance.new("TextLabel")
LocalScript35 = Instance.new("LocalScript")
LocalScript36 = Instance.new("LocalScript")
LocalScript37 = Instance.new("LocalScript")
Model38 = Instance.new("Model")
Part39 = Instance.new("Part")
SpecialMesh40 = Instance.new("SpecialMesh")
Part41 = Instance.new("Part")
SpecialMesh42 = Instance.new("SpecialMesh")
Model43 = Instance.new("Model")
Part44 = Instance.new("Part")
SpecialMesh45 = Instance.new("SpecialMesh")
Part46 = Instance.new("Part")
SpecialMesh47 = Instance.new("SpecialMesh")
Part48 = Instance.new("Part")
SpecialMesh49 = Instance.new("SpecialMesh")
Part50 = Instance.new("Part")
SpecialMesh51 = Instance.new("SpecialMesh")
Part52 = Instance.new("Part")
SpecialMesh53 = Instance.new("SpecialMesh")
Part54 = Instance.new("Part")
SpecialMesh55 = Instance.new("SpecialMesh")
Part56 = Instance.new("Part")
Sound57 = Instance.new("Sound")
Sound58 = Instance.new("Sound")
Sound59 = Instance.new("Sound")
ParticleEmitter60 = Instance.new("ParticleEmitter")
SpotLight61 = Instance.new("SpotLight")
BlockMesh62 = Instance.new("BlockMesh")
ParticleEmitter63 = Instance.new("ParticleEmitter")
Part64 = Instance.new("Part")
SpecialMesh65 = Instance.new("SpecialMesh")
Part66 = Instance.new("Part")
SpecialMesh67 = Instance.new("SpecialMesh")
Part68 = Instance.new("Part")
Sound69 = Instance.new("Sound")
Sound70 = Instance.new("Sound")
Sound71 = Instance.new("Sound")
Sound72 = Instance.new("Sound")
Sound73 = Instance.new("Sound")
Sound74 = Instance.new("Sound")
Sound75 = Instance.new("Sound")
Sound76 = Instance.new("Sound")
Sound77 = Instance.new("Sound")
Sound78 = Instance.new("Sound")
Sound79 = Instance.new("Sound")
Sound80 = Instance.new("Sound")
Sound81 = Instance.new("Sound")
SpecialMesh82 = Instance.new("SpecialMesh")
Part83 = Instance.new("Part")
SpecialMesh84 = Instance.new("SpecialMesh")
Part85 = Instance.new("Part")
SpecialMesh86 = Instance.new("SpecialMesh")
Part87 = Instance.new("Part")
SpecialMesh88 = Instance.new("SpecialMesh")
Part89 = Instance.new("Part")
SpecialMesh90 = Instance.new("SpecialMesh")
Tool0.Name = "AK"
Tool0.Parent = mas
Tool0.ToolTip = "Made in Germany"
NumberValue1.Name = "Ammo"
NumberValue1.Parent = Tool0
NumberValue1.Value = 10000
NumberValue2.Name = "BulletSpeed"
NumberValue2.Parent = Tool0
NumberValue2.Value = 800
StringValue3.Name = "BulletType"
StringValue3.Parent = Tool0
StringValue3.Value = "5.45x39mm"
NumberValue4.Name = "GLAmmo"
NumberValue4.Parent = Tool0
NumberValue4.Value = 10000
StringValue5.Name = "GName"
StringValue5.Parent = Tool0
StringValue5.Value = "AK74m"
NumberValue6.Name = "MagSize"
NumberValue6.Parent = Tool0
NumberValue6.Value = 30
NumberValue7.Name = "Mags"
NumberValue7.Parent = Tool0
NumberValue7.Value = 90
NumberValue8.Name = "RPM"
NumberValue8.Parent = Tool0
NumberValue8.Value = 545
StringValue9.Name = "Type"
StringValue9.Parent = Tool0
StringValue9.Value = "Primary"
Script10.Name = "Weld"
Script10.Parent = Tool0
table.insert(cors,sandbox(Script10,function()
function Weld(x,y,Name)
	local W = Instance.new("Weld")
	W.Name = Name
	W.Part0 = x
	W.Part1 = y
	local CJ = CFrame.new(x.Position)
	local C0 = x.CFrame:inverse()*CJ
	local C1 = y.CFrame:inverse()*CJ
	W.C0 = C0
	W.C1 = C1
	W.Parent = x
end



function Get(A)
	 if  A.Name == "Slide" then
		Weld(script.Parent.Handle, A,"Slide")
		A.Anchored = false
	elseif A.className == "Part" or A.className == "UnionOperation" or A.className == "MeshPart" and not A.Name == "Bolt" then
		Weld(script.Parent.Handle, A,"Weld")
		A.Anchored = false
	else
		local C = A:GetChildren()
		for i=1, #C do
		Get(C[i])
		end
	end
end

function Finale()
	Get(script.Parent)
end



Finale()
end))
LocalScript11.Name = "GunScript"
LocalScript11.Parent = Tool0
table.insert(cors,sandbox(LocalScript11,function()

wait(1)


local Tool = script.Parent


local Player = game.Players.LocalPlayer
local Character = Player.Character
local Torso = Character.Torso
local Neck = Torso:WaitForChild("Neck")
local Humanoid = Character.Humanoid
local Mouse = Player:GetMouse()

local Camera = game.Workspace.CurrentCamera


local GunSetup = {
	
	Name = "M4A1";
	Ammo = script.Ammo.Value;
	RPM = 966;
	BurstRPM = 966;
	FireMode = "Automatic";
	BkFM = "Automatic";
	BurstFire = 3;
	SwitchableModes = {
		Burst = true;
		Single = true;
		Automatic = true;
		
	};
	
	
	GrenadeLauncher = false;	
	M203Ammo = 1;	 -- 1 For HEGrenade, 2 For SmokeGrenade
	GLFirerate = 2;		
	
	AnimSpeed = 1;	
	
	Chamber = true;
	CanBreak = false;
	CanSeeMag = true;
	FastReload = true;

	BType = "5.56x45mm";
	BSpeed = 884;
	ATK = true; 
	BDrop = 90;
	BSpread = 0;

	LimbsDamage = {25,35}; 
	TorsoDamage = {45,50};
	HeadDamage = {10000000,10000000000};

	HelmetDamage = 640000;
	VestDamage = 41;
	
	Recoil = {42,55};
	Aimpart = Tool.AimPart;
	FOV1 = 40;
	FOV2 = 35;
	
	RightPos = CFrame.new(-0.575, -0.465, -1.185) * CFrame.Angles(math.rad(-90), math.rad(0), math.rad(0));
	LeftPos = CFrame.new(1.123,0.25,-1.795) * CFrame.Angles(math.rad(-120),math.rad(46.5),math.rad(15));
	----------------------
	
	LeftAimPosition = CFrame.new(1,-0.25,-1.1) * CFrame.Angles(math.rad(-110),math.rad(48.5),math.rad(2));
	LeftAim2Position = CFrame.new(1,0.25,-1.5) * CFrame.Angles(math.rad(-120),math.rad(25),math.rad(-15))

	}

local Recoilup = 0

local Recoil = math.random(GunSetup.Recoil[1],GunSetup.Recoil[2])/60
local RecoilG
local Firerate = 1/(GunSetup.RPM/60)
local BURSTFirerate = 1/(GunSetup.BurstRPM/60)
local GLFirerate = GunSetup.GLFirerate
local Ammo = GunSetup.Ammo
local GLAmmo = script.GLAmmo
local MaxAmmo = script.MaxAmmo
local StoredAmmo = script.StoredAmmo
local EnableCycleSight = true
local EnableFireMode = true
local AimPartMode = 1

local slideback = false
local Checando = false
local Emperrado = false
local Chambered = false
local MagOut = false
local GLChambered = false

local Animando = false

_G.Sprinting = false

local Safemode = false

local MouseHeld

local Equipped = false
local Sprinting = false
local Shooting = false
local Aiming = false
local Reloading = false
local GLReloading = false

pos =  0.0006
neg = -0.0006

local shell
local AmmoGui 

local RAW
local LAW



local arms

local Shell = Tool:WaitForChild("Shells"):WaitForChild("Shell")

	local function GetAmmo()
		AmmoGui.Frame.AText.Text = Ammo
		return Ammo
	end

local uis = game:GetService("UserInputService")

local RG = Character["Right Arm"]:FindFirstChild("RightGrip")


---------------------------------------------------------------------------------------
---------------- [ Tween Module ] --------------------------------------------------------
---------------------------------------------------------------------------------------

function tweenFoV(goal, frames)
 coroutine.resume(coroutine.create(function()
  SFn = SFn and SFn + 1 or 0 
  local SFn_S = SFn
  for i = 1, frames do
   if SFn ~= SFn_S then break end
   Camera.FieldOfView = Camera.FieldOfView + (goal - Camera.FieldOfView) * (i / frames)
   game:GetService("RunService").RenderStepped:wait()
  end
 end))
end


--[[
	
	tweenJoint Function Parameters:
	
	Object Joint - This has to be a weld with a C0 and C1 property
	
	CFrame newC0 - This is what the new C0 of the weld will be. You can put nil if you don't want to effect the C0
	
	CFrame newC1 - This is what the new C1 of the weld will be. You can put nil if you don't want to effect the C1
	
	function Alpha - This is an alpha function that takes an input parameter of a number between 0 and 90 and returns a number between 0 and 1.
		For example, function(X) return math.sin(math.rad(X)) end
		
	float Duration - This is how long the tweening takes to complete
	
--]]
local RS = game:GetService("RunService")

function tweenJoint(Joint, newC0, newC1, Alpha, Duration)
	spawn(function()
		local newCode = math.random(-1e9, 1e9) --This creates a random code between -1000000000 and 1000000000
		local tweenIndicator = nil
		if (not Joint:findFirstChild("tweenCode")) then --If the joint isn't being tweened, then
			tweenIndicator = Instance.new("IntValue")
			tweenIndicator.Name = "tweenCode"
			tweenIndicator.Value = newCode
			tweenIndicator.Parent = Joint
		else
			tweenIndicator = Joint.tweenCode
			tweenIndicator.Value = newCode --If the joint is already being tweened, this will change the code, and the tween loop will stop
		end
		--local tweenIndicator = createTweenIndicator:InvokeServer(Joint, newCode)
		if Duration <= 0 then --If the duration is less than or equal to 0 then there's no need for a tweening loop
			if newC0 then Joint.C0 = newC0 end
			if newC1 then Joint.C1 = newC1 end
		else
			local Increment = 1.5 / Duration
			local startC0 = Joint.C0
			local startC1 = Joint.C1
			local X = 0
			while true do
				RS.RenderStepped:wait() --This makes the for loop step every 1/60th of a second
				local newX = X + Increment
				X = (newX > 90 and 90 or newX)
				if tweenIndicator.Value ~= newCode then break end --This makes sure that another tween wasn't called on the same joint
				if (not Equipped) then break end --This stops the tween if the tool is deselected
				if newC0 then Joint.C0 = startC0:lerp(newC0, Alpha(X)) end
				if newC1 then Joint.C1 = startC1:lerp(newC1, Alpha(X)) end
				--if newC0 then lerpCF:InvokeServer(Joint, "C0", startC0, newC0, Alpha(X)) end
				--if newC1 then lerpCF:InvokeServer(Joint, "C1", startC1, newC1, Alpha(X)) end
				if X == 90 then break end
			end
		end
		if tweenIndicator.Value == newCode then --If this tween functions was the last one called on a joint then it will remove the code
			tweenIndicator:Destroy()
		end
		--deleteTweenIndicator:InvokeServer(tweenIndicator, newCode)
	end)
end


-------------Motor6Ding Section------------------------
Tool.Equipped:connect(function()
	if Humanoid.Health > 0 then
	RAW = Instance.new("Motor6D")
	RAW.Name= "RightWeld"
	RAW.Part0 =Player.Character["Right Arm"]
	RAW.Part1 = Character["Head"]
	RAW.Parent=Player.Character["Right Arm"]
--	Player.CameraMode="LockFirstPerson"
	Torso:WaitForChild("Right Shoulder").Part1 = nil
	if Reloading then
		Reloading = false
	end
	if GLReloading then
		GLReloading = false
	end
	LAW = Instance.new("Motor6D")
	LAW.Name= "LeftWeld"
	LAW.Part0 = Player.Character["Left Arm"]
	LAW.Part1 = Character["Head"]
	LAW.Parent = Player.Character["Left Arm"]
	LAW.C0 = GunSetup.LeftPos
	RAW.C0 = GunSetup.RightPos
	Torso:WaitForChild("Left Shoulder").Part1 = nil
	LAW.C1 = CFrame.new()
	RAW.C1 = CFrame.new()	


	
	uis.MouseIconEnabled = false
	AmmoGui = script.AmmoGui:Clone()
	AmmoGui.Parent = Player.PlayerGui
	AmmoGui.Frame.Visible = false

	
	
	Equipped = true
	game:GetService('RunService').RenderStepped:connect(function()
		RAW.C1 = CFrame.new() * CFrame.new((Recoilup/4),0,(Recoilup*2))
		LAW.C1 = CFrame.new() * CFrame.new((Recoilup/4),0,(Recoilup*2))
		if not Equipped then
			IdleOrSteadyAnim()
			Reloading = false
			GLReloading = false
		end
		if AmmoGui:FindFirstChild("Frame") then
			AmmoGui.Frame.FText.Text = GunSetup.FireMode
			AmmoGui.Frame.SAText.Text = ""..math.ceil(StoredAmmo.Value/math.ceil(GunSetup.Ammo)).." MAGS"
			AmmoGui.Frame.Btext.Text = GunSetup.BType
			
			if 	Safemode then
				AmmoGui.Frame.A.Visible = true
			else
				AmmoGui.Frame.A.Visible = false
			end
			
			if 	Chambered then
				AmmoGui.Frame.B.Visible = false
			else
				AmmoGui.Frame.B.Visible = true
			end

			if GunSetup.GrenadeLauncher	and GLChambered then
				AmmoGui.Frame.E.Visible = false
			elseif GunSetup.GrenadeLauncher	and not GLChambered then
				AmmoGui.Frame.E.Visible = true
			else
				AmmoGui.Frame.E.Visible = false
			end

			if 	Emperrado then
				AmmoGui.Frame.C.Visible = true
			else
				AmmoGui.Frame.C.Visible = false
			end
		

			if 	slideback then
				AmmoGui.Frame.D.Visible = true
			else
				AmmoGui.Frame.D.Visible = false
			end


			if GunSetup.FireMode == "M203" then
				AmmoGui.Frame.NText.Text = "M203"
				AmmoGui.Frame.SAText.Text = GLAmmo.Value
				AmmoGui.Frame.AText.Text = Ammo .." Bullets"
			end
			
		
			if StoredAmmo.Value > MaxAmmo.Value then
				StoredAmmo.Value = MaxAmmo.Value
			end
			
			if GunSetup.FireMode ~= "M203" then
				AmmoGui.Frame.NText.Text = GunSetup.Name
				AmmoGui.Frame.AText.Text = Ammo .." Bullets"
			end
		end
	end)	
	end
end)








---------- Animations ------------------

function SprintAnim()
	Humanoid.WalkSpeed = 24	
	tweenJoint(RAW,  CFrame.new(-0.75, 0.125, -1.3) * CFrame.Angles(math.rad(-80), math.rad(-55), math.rad(0)) , nil, function(X) return math.sin(math.rad(X)) end, 0.25 * GunSetup.AnimSpeed)
	tweenJoint(LAW,  CFrame.new(1.25,0.85,-1.125) * CFrame.Angles(math.rad(-85),math.rad(-10.5),math.rad(-10)) , nil, function(X) return math.sin(math.rad(X)) end, 0.25 * GunSetup.AnimSpeed)
	_G.Sprinting = true
end

function SafetyAnim()
	tweenJoint(RAW,  CFrame.new(-0.75, 0.125, -1.3) * CFrame.Angles(math.rad(-80), math.rad(-55), math.rad(0)) , nil, function(X) return math.sin(math.rad(X)) end, 0.25 * GunSetup.AnimSpeed)
	tweenJoint(LAW,  CFrame.new(1.25,0.85,-1.125) * CFrame.Angles(math.rad(-85),math.rad(-10.5),math.rad(-10)) , nil, function(X) return math.sin(math.rad(X)) end, 0.25 * GunSetup.AnimSpeed)
end





function IdleOrSteadyAnim()
	tweenJoint(RAW, GunSetup.RightPos , nil, function(X) return math.sin(math.rad(X)) end, 0.225 * GunSetup.AnimSpeed)
	tweenJoint(LAW,  GunSetup.LeftPos , nil, function(X) return math.sin(math.rad(X)) end, 0.215 * GunSetup.AnimSpeed)
end







function ReloadAnim()
	if Equipped then
			
			tweenJoint(RAW,  CFrame.new(-0.875, -0.465, -1.15) * CFrame.Angles(math.rad(-95), math.rad(-2), math.rad(7.5)) , nil, function(X) return math.sin(math.rad(X)) end, 0.425 * GunSetup.AnimSpeed)
			tweenJoint(LAW,  CFrame.new(1.195,-0.35,-1.48) * CFrame.Angles(math.rad(-100),math.rad(75),math.rad(0)) , nil, function(X) return math.sin(math.rad(X)) end, 0.375 * GunSetup.AnimSpeed)
			
			wait(0.55 * GunSetup.AnimSpeed)
			tweenJoint(RAW, CFrame.new(-0.975, -0.365, -1.2) * CFrame.Angles(math.rad(-85), math.rad(-2), math.rad(9)) , nil, function(X) return math.sin(math.rad(X)) end, 0.525 * GunSetup.AnimSpeed)
			tweenJoint(LAW,  CFrame.new(1.195,1.4,-0.5) * CFrame.Angles(math.rad(0),math.rad(25),math.rad(0)) , nil, function(X) return math.sin(math.rad(X)) end, 0.375 * GunSetup.AnimSpeed)
			Tool.Handle.MagOut:Play()	
			
			local MagC = Tool:WaitForChild("Mag"):clone()
				Tool.Mag.Transparency = 1
				MagC.Parent = Tool
				MagC.Name = "MagC"
				MagC.Transparency = 0
				
			
			local MagCW = Instance.new("Motor6D")
				MagCW.Part0 = MagC
				MagCW.Part1 = Player.Character["Left Arm"]
				MagCW.Parent = MagC
				MagCW.C1 = MagC.CFrame:toObjectSpace(Tool.Mag.CFrame)
				
			wait(0.75 * (GunSetup.AnimSpeed/1))
			
			if (StoredAmmo.Value - (GunSetup.Ammo - Ammo)) < 0 then
				Ammo = Ammo + StoredAmmo.Value
				StoredAmmo.Value = 0
			elseif Ammo <= 0 then
				StoredAmmo.Value = StoredAmmo.Value - (GunSetup.Ammo - Ammo)
				Ammo = GunSetup.Ammo
				Chambered = false
			elseif Ammo > 0 and Chambered and GunSetup.Chamber then
				StoredAmmo.Value = StoredAmmo.Value - (GunSetup.Ammo - Ammo)
				Ammo = GunSetup.Ammo + 1
			elseif Ammo > 0 and Chambered and not GunSetup.Chamber then
				StoredAmmo.Value = StoredAmmo.Value - (GunSetup.Ammo - Ammo)
				Ammo = GunSetup.Ammo
			end
		
			Tool.Handle.MagIn:Play()
			
			tweenJoint(RAW,  CFrame.new(-0.875, -0.465, -1.15) * CFrame.Angles(math.rad(-95), math.rad(-2), math.rad(7.5)) , nil, function(X) return math.sin(math.rad(X)) end, 0.325 * GunSetup.AnimSpeed)
			tweenJoint(LAW,  CFrame.new(1.195,-0.35,-1.48) * CFrame.Angles(math.rad(-100),math.rad(75),math.rad(0)) , nil, function(X) return math.sin(math.rad(X)) end, 0.275 * GunSetup.AnimSpeed)
			
			wait(0.15 * GunSetup.AnimSpeed)
			MagC:Destroy()
			Tool.Mag.Transparency = 0
			wait(0.35 * GunSetup.AnimSpeed)
			
	end
end


function SeeMag()
	if Equipped then
			Animando = true
			tweenJoint(RAW,  CFrame.new(0.213, -0.265, -1.25) * CFrame.Angles(math.rad(-90), math.rad(7.5), math.rad(-50.5)) , nil, function(X) return math.sin(math.rad(X)) end, 0.325 * GunSetup.AnimSpeed)
			tweenJoint(LAW,  CFrame.new(2.195,-0.825,-1.08) * CFrame.Angles(math.rad(-100),math.rad(75),math.rad(-41)) , nil, function(X) return math.sin(math.rad(X)) end, 0.375 * GunSetup.AnimSpeed)
			
			wait(1.125 * (GunSetup.AnimSpeed/2))
			tweenJoint(RAW,  CFrame.new(-0.875, -0.465, -1.15) * CFrame.Angles(math.rad(-95), math.rad(-2), math.rad(7.5)) , nil, function(X) return math.sin(math.rad(X)) end, 0.425 * GunSetup.AnimSpeed)
			tweenJoint(LAW,  CFrame.new(1.195,-0.35,-1.48) * CFrame.Angles(math.rad(-100),math.rad(75),math.rad(0)) , nil, function(X) return math.sin(math.rad(X)) end, 0.375 * GunSetup.AnimSpeed)
			
			wait(0.55 * GunSetup.AnimSpeed)
			tweenJoint(RAW, CFrame.new(-0.975, -0.365, -1.2) * CFrame.Angles(math.rad(-85), math.rad(-2), math.rad(9)) , nil, function(X) return math.sin(math.rad(X)) end, 0.525 * GunSetup.AnimSpeed)
			tweenJoint(LAW,  CFrame.new(1.195,1.4,-0.5) * CFrame.Angles(math.rad(0),math.rad(25),math.rad(0)) , nil, function(X) return math.sin(math.rad(X)) end, 0.375 * GunSetup.AnimSpeed)
			Tool.Handle.MagOut:Play()	
			
			local MagC = Tool:WaitForChild("Mag"):clone()
				Tool.Mag.Transparency = 1
				MagC.Parent = Tool
				MagC.Name = "MagC"
				MagC.Transparency = 0
			
			local MagCW = Instance.new("Motor6D")
				MagCW.Part0 = MagC
				MagCW.Part1 = Player.Character["Left Arm"]
				MagCW.Parent = MagC
				MagCW.C1 = MagC.CFrame:toObjectSpace(Tool.Mag.CFrame)
				
			wait(0.75 * (GunSetup.AnimSpeed/1))
		
			
			tweenJoint(RAW,  CFrame.new(-0.875, -0.465, -1.15) * CFrame.Angles(math.rad(-95), math.rad(-2), math.rad(7.5)) , nil, function(X) return math.sin(math.rad(X)) end, 0.325 * GunSetup.AnimSpeed)
			tweenJoint(LAW,  CFrame.new(1.195,-0.35,-1.48) * CFrame.Angles(math.rad(-100),math.rad(45),math.rad(0)) , nil, function(X) return math.sin(math.rad(X)) end, 0.275 * GunSetup.AnimSpeed)
			wait(0.12 * (GunSetup.AnimSpeed/1))
			Animando = false			

			--[[wait(0.15 * GunSetup.AnimSpeed)
			MagC:Destroy()
			Tool.Mag.Transparency = 0
			wait(0.35 * GunSetup.AnimSpeed)]]
			
	end
end

function UNSeeMag()
	if Equipped then
			Animando = true
			local MagC = Tool:WaitForChild("MagC")
			
			local MagCW = script.Parent.MagC.Motor6D
				
			wait(0.75 * (GunSetup.AnimSpeed/1))
			
			tweenJoint(RAW,  CFrame.new(-0.875, -0.465, -1.15) * CFrame.Angles(math.rad(-95), math.rad(-2), math.rad(7.5)) , nil, function(X) return math.sin(math.rad(X)) end, 0.325 * GunSetup.AnimSpeed)
			tweenJoint(LAW,  CFrame.new(1.195,-0.35,-1.48) * CFrame.Angles(math.rad(-100),math.rad(75),math.rad(0)) , nil, function(X) return math.sin(math.rad(X)) end, 0.275 * GunSetup.AnimSpeed)
			
			wait(0.15 * GunSetup.AnimSpeed)
			Tool.Handle.MagIn:Play()
			MagC:Destroy()
			Tool.Mag.Transparency = 0
			wait(0.35 * GunSetup.AnimSpeed)
			tweenJoint(RAW,  CFrame.new(0.213, -0.265, -1.25) * CFrame.Angles(math.rad(-90), math.rad(7.5), math.rad(-50.5)) , nil, function(X) return math.sin(math.rad(X)) end, 0.325 * GunSetup.AnimSpeed)
			tweenJoint(LAW,  CFrame.new(1.25,0.55,-1.08) * CFrame.Angles(math.rad(-100),math.rad(25),math.rad(-41)) , nil, function(X) return math.sin(math.rad(X)) end, 0.375 * GunSetup.AnimSpeed)
			wait(0.12 * (GunSetup.AnimSpeed/1))
			Animando = false
	end
end


function CheckAnim()
	if Equipped then
			Animando = true
			tweenJoint(RAW,  CFrame.new(0.213, -0.265, -1.25) * CFrame.Angles(math.rad(-90), math.rad(7.5), math.rad(-50.5)) , nil, function(X) return math.sin(math.rad(X)) end, 0.325 * GunSetup.AnimSpeed)
			tweenJoint(LAW,  CFrame.new(1.25,0.55,-1.08) * CFrame.Angles(math.rad(-100),math.rad(25),math.rad(-41)) , nil, function(X) return math.sin(math.rad(X)) end, 0.375 * GunSetup.AnimSpeed)
			wait(0.20 * (GunSetup.AnimSpeed/1))
			Animando = false
			
	end
end



function ChamberAnim()
	if Equipped then
			Animando = true
			tweenJoint(RAW,  CFrame.new(0.213, -0.265, -1.25) * CFrame.Angles(math.rad(-90), math.rad(7.5), math.rad(-50.5)) , nil, function(X) return math.sin(math.rad(X)) end, 0.325 * GunSetup.AnimSpeed)
			tweenJoint(LAW,  CFrame.new(0.75,-0.6,-0.85) * CFrame.Angles(math.rad(-140),math.rad(70),math.rad(40)) , nil, function(X) return math.sin(math.rad(X)) end, 0.375 * GunSetup.AnimSpeed)
			wait(0.15 * (GunSetup.AnimSpeed/2))
			Tool.Handle.MagIn:Play()
			tweenJoint(RAW,  CFrame.new(0.213, -0.265, -1.25) * CFrame.Angles(math.rad(-90), math.rad(7.5), math.rad(-50.5)) , nil, function(X) return math.sin(math.rad(X)) end, 0.325 * GunSetup.AnimSpeed)
			tweenJoint(LAW,  CFrame.new(0.195,-0.8,-0.85) * CFrame.Angles(math.rad(-140),math.rad(70),math.rad(40)) , nil, function(X) return math.sin(math.rad(X)) end, 0.375 * GunSetup.AnimSpeed)
			wait(0.12 * (GunSetup.AnimSpeed/1))
			Animando = false
	end
end


function ChamberBKAnim()
	if Equipped then
			Animando = true
			tweenJoint(RAW,  CFrame.new(0.213, -0.265, -1.25) * CFrame.Angles(math.rad(-90), math.rad(7.5), math.rad(-50.5)) , nil, function(X) return math.sin(math.rad(X)) end, 0.325 * GunSetup.AnimSpeed)
			tweenJoint(LAW,  CFrame.new(0.195,-0.8,-0.85) * CFrame.Angles(math.rad(-140),math.rad(70),math.rad(40)) , nil, function(X) return math.sin(math.rad(X)) end, 0.375 * GunSetup.AnimSpeed)
			wait(0.15 * (GunSetup.AnimSpeed/2))
			Tool.Handle.MagIn:Play()
			tweenJoint(RAW,  CFrame.new(0.213, -0.265, -1.25) * CFrame.Angles(math.rad(-90), math.rad(7.5), math.rad(-50.5)) , nil, function(X) return math.sin(math.rad(X)) end, 0.325 * GunSetup.AnimSpeed)
			tweenJoint(LAW,  CFrame.new(0.75,-0.6,-0.85) * CFrame.Angles(math.rad(-140),math.rad(70),math.rad(40)) , nil, function(X) return math.sin(math.rad(X)) end, 0.375 * GunSetup.AnimSpeed)
			wait(0.12 * (GunSetup.AnimSpeed/1))
			Animando = false
			
	end
end




function FastReloadAnim()
	if Equipped then
			tweenJoint(RAW,  CFrame.new(0.213, -0.265, -1.25) * CFrame.Angles(math.rad(-90), math.rad(7.5), math.rad(-50.5)) , nil, function(X) return math.sin(math.rad(X)) end, 0.325 * GunSetup.AnimSpeed)
			tweenJoint(LAW,  CFrame.new(1.25,0.55,-1.08) * CFrame.Angles(math.rad(-100),math.rad(25),math.rad(-41)) , nil, function(X) return math.sin(math.rad(X)) end, 0.375 * GunSetup.AnimSpeed)
			
			wait(1.125 * (GunSetup.AnimSpeed/2))
			tweenJoint(RAW,  CFrame.new(-0.875, -0.465, -1.15) * CFrame.Angles(math.rad(-95), math.rad(-2), math.rad(7.5)) , nil, function(X) return math.sin(math.rad(X)) end, 0.425 * GunSetup.AnimSpeed)
			tweenJoint(LAW,  CFrame.new(1.195,-0.35,-1.48) * CFrame.Angles(math.rad(-100),math.rad(75),math.rad(0)) , nil, function(X) return math.sin(math.rad(X)) end, 0.375 * GunSetup.AnimSpeed)
			
			wait(0.55 * GunSetup.AnimSpeed)
			tweenJoint(RAW, CFrame.new(-0.975, -0.365, -1.2) * CFrame.Angles(math.rad(-85), math.rad(-2), math.rad(9)) , nil, function(X) return math.sin(math.rad(X)) end, 0.525 * GunSetup.AnimSpeed)
			tweenJoint(LAW,  CFrame.new(1.195,1.4,-0.5) * CFrame.Angles(math.rad(0),math.rad(25),math.rad(0)) , nil, function(X) return math.sin(math.rad(X)) end, 0.375 * GunSetup.AnimSpeed)
			Tool.Handle.MagOut:Play()	
			
			local MagC = Tool:WaitForChild("Mag"):clone()
				Tool.Mag.Transparency = 1
				MagC.Parent = Tool
				MagC.Name = "MagC"
				MagC.Transparency = 0
			
			local MagCW = Instance.new("Motor6D")
				MagCW.Part0 = MagC
				MagCW.Part1 = Player.Character["Left Arm"]
				MagCW.Parent = MagC
				MagCW.C1 = MagC.CFrame:toObjectSpace(Tool.Mag.CFrame)
				
			wait(0.75 * (GunSetup.AnimSpeed/1))
			
			if (StoredAmmo.Value - (GunSetup.Ammo - Ammo)) < 0 then
				Ammo = Ammo + StoredAmmo.Value
				StoredAmmo.Value = 0
			elseif Ammo <= 0 then
				StoredAmmo.Value = StoredAmmo.Value - (GunSetup.Ammo - Ammo)
				Ammo = GunSetup.Ammo
				Chambered = false
			elseif Ammo > 0 and Chambered and GunSetup.Chamber then
				StoredAmmo.Value = StoredAmmo.Value - (GunSetup.Ammo - Ammo)
				Ammo = GunSetup.Ammo + 1
			elseif Ammo > 0 and Chambered and not GunSetup.Chamber then
				StoredAmmo.Value = StoredAmmo.Value - (GunSetup.Ammo - Ammo)
				Ammo = GunSetup.Ammo
			end
		
			Tool.Handle.MagIn:Play()
			
			tweenJoint(RAW,  CFrame.new(-0.875, -0.465, -1.15) * CFrame.Angles(math.rad(-95), math.rad(-2), math.rad(7.5)) , nil, function(X) return math.sin(math.rad(X)) end, 0.325 * GunSetup.AnimSpeed)
			tweenJoint(LAW,  CFrame.new(1.195,-0.35,-1.48) * CFrame.Angles(math.rad(-100),math.rad(75),math.rad(0)) , nil, function(X) return math.sin(math.rad(X)) end, 0.275 * GunSetup.AnimSpeed)
			
			wait(0.15 * GunSetup.AnimSpeed)
			MagC:Destroy()
			Tool.Mag.Transparency = 0
			wait(0.35 * GunSetup.AnimSpeed)
			
	end
end

function FastBolt()

			tweenJoint(RAW,  CFrame.new(0.213, -0.265, -1.25) * CFrame.Angles(math.rad(-90), math.rad(7.5), math.rad(-50.5)) , nil, function(X) return math.sin(math.rad(X)) end, 0.325 * GunSetup.AnimSpeed)
			tweenJoint(LAW,  CFrame.new(0.75,-0.6,-0.85) * CFrame.Angles(math.rad(-140),math.rad(70),math.rad(40)) , nil, function(X) return math.sin(math.rad(X)) end, 0.375 * GunSetup.AnimSpeed)
			wait(0.55 * (GunSetup.AnimSpeed/2))
			tweenJoint(RAW,  CFrame.new(0.213, -0.265, -1.25) * CFrame.Angles(math.rad(-90), math.rad(7.5), math.rad(-50.5)) , nil, function(X) return math.sin(math.rad(X)) end, 0.325 * GunSetup.AnimSpeed)
			tweenJoint(LAW,  CFrame.new(0.75,-0.6,-0.85) * CFrame.Angles(math.rad(-140),math.rad(70),math.rad(40)) , nil, function(X) return math.sin(math.rad(X)) end, 0.375 * GunSetup.AnimSpeed)	
			wait(0.3 * (GunSetup.AnimSpeed/2))
			Tool.Handle.MagIn:Play()
			tweenJoint(RAW,  CFrame.new(0.213, -0.265, -1.25) * CFrame.Angles(math.rad(-90), math.rad(7.5), math.rad(-50.5)) , nil, function(X) return math.sin(math.rad(X)) end, 0.325 * GunSetup.AnimSpeed)
			tweenJoint(LAW,  CFrame.new(0.195,-0.8,-0.85) * CFrame.Angles(math.rad(-140),math.rad(70),math.rad(40)) , nil, function(X) return math.sin(math.rad(X)) end, 0.375 * GunSetup.AnimSpeed)

			slideback = true
			Emperrado = false
		if Ammo > 0 and Chambered then
			EjectShells()
			Ammo = Ammo - 1
			print(Ammo)
		end

			wait(0.75 * (GunSetup.AnimSpeed/2))
			Tool.Handle.MagIn:Play()
			tweenJoint(RAW,  CFrame.new(0.213, -0.265, -1.25) * CFrame.Angles(math.rad(-90), math.rad(7.5), math.rad(-50.5)) , nil, function(X) return math.sin(math.rad(X)) end, 0.325 * GunSetup.AnimSpeed)
			tweenJoint(LAW,  CFrame.new(0.75,-0.6,-0.85) * CFrame.Angles(math.rad(-140),math.rad(70),math.rad(40)) , nil, function(X) return math.sin(math.rad(X)) end, 0.375 * GunSetup.AnimSpeed)
	
		slideback = false
		Chambered = true

			wait(0.25 * (GunSetup.AnimSpeed/2))
			tweenJoint(RAW, GunSetup.RightPos , nil, function(X) return math.sin(math.rad(X)) end, 0.225 * GunSetup.AnimSpeed)
			tweenJoint(LAW,  GunSetup.LeftPos , nil, function(X) return math.sin(math.rad(X)) end, 0.215 * GunSetup.AnimSpeed)

end


function GLReloadAnim()
	if Equipped then
			
			
			tweenJoint(RAW, CFrame.new(-0.975, -0.365, -1.2) * CFrame.Angles(math.rad(-85), math.rad(-2), math.rad(9)) , nil, function(X) return math.sin(math.rad(X)) end, 0.525 * GunSetup.AnimSpeed)
			tweenJoint(LAW,  CFrame.new(1,0,-1.795) * CFrame.Angles(math.rad(-120),math.rad(45),math.rad(5)) , nil, function(X) return math.sin(math.rad(X)) end, 0.375 * GunSetup.AnimSpeed)
		
			wait(0.25 * (GunSetup.AnimSpeed/1))

			tweenJoint(RAW,  CFrame.new(-0.875, -0.465, -1.15) * CFrame.Angles(math.rad(-95), math.rad(-2), math.rad(7.5)) , nil, function(X) return math.sin(math.rad(X)) end, 0.425 * GunSetup.AnimSpeed)
			tweenJoint(LAW,  CFrame.new(1.195,1.4,-0.5) * CFrame.Angles(math.rad(0),math.rad(25),math.rad(0)) , nil, function(X) return math.sin(math.rad(X)) end, 0.375 * GunSetup.AnimSpeed)
			

			wait(0.75 * (GunSetup.AnimSpeed/1))
			
		
			Tool.Handle.MagOut:Play()
			
			tweenJoint(RAW, CFrame.new(-0.975, -0.365, -1.2) * CFrame.Angles(math.rad(-85), math.rad(-2), math.rad(9)) , nil, function(X) return math.sin(math.rad(X)) end, 0.525 * GunSetup.AnimSpeed)
			tweenJoint(LAW,  CFrame.new(1,0,-1.795) * CFrame.Angles(math.rad(-120),math.rad(45),math.rad(5)) , nil, function(X) return math.sin(math.rad(X)) end, 0.375 * GunSetup.AnimSpeed)
		
				if (StoredAmmo.Value - (GunSetup.Ammo - Ammo)) < 0 then
				Ammo = Ammo + StoredAmmo.Value
				StoredAmmo.Value = 0
			elseif Ammo <= 0 then
				StoredAmmo.Value = StoredAmmo.Value - (GunSetup.Ammo - Ammo)
				Ammo = GunSetup.Ammo
				Chambered = false
			elseif Ammo > 0 and Chambered and GunSetup.Chamber then
				StoredAmmo.Value = StoredAmmo.Value - (GunSetup.Ammo - Ammo)
				Ammo = GunSetup.Ammo + 1
			elseif Ammo > 0 and Chambered and not GunSetup.Chamber then
				StoredAmmo.Value = StoredAmmo.Value - (GunSetup.Ammo - Ammo)
				Ammo = GunSetup.Ammo
			end
			
			wait(0.75 * GunSetup.AnimSpeed)

			tweenJoint(RAW,  CFrame.new(0.213, -0.265, -1.25) * CFrame.Angles(math.rad(-90), math.rad(7.5), math.rad(-50.5)) , nil, function(X) return math.sin(math.rad(X)) end, 0.325 * GunSetup.AnimSpeed)
			tweenJoint(LAW,  CFrame.new(1.25,0.55,-1.08) * CFrame.Angles(math.rad(-100),math.rad(25),math.rad(-41)) , nil, function(X) return math.sin(math.rad(X)) end, 0.375 * GunSetup.AnimSpeed)
					
	end
end

-----------------------ADS Function------------------------------










Mouse.Button2Down:connect(function()
	if Equipped then
		if not Aiming and not Reloading and not GLReloading and not Sprinting and not Safemode and not Checando then
			Aiming = true
--			Mouse.Icon = GunSetup.Cursor.Aiming
			if AimPartMode == 1 then
				tweenJoint(RAW,  RAW.C0 *  CFrame.new(-Tool.AimPart.CFrame:toObjectSpace(Character.Head.CFrame).p), nil, function(X) return math.sin(math.rad(X)) end, 0.25 * GunSetup.AnimSpeed)
				tweenJoint(LAW,  GunSetup.LeftAimPosition , nil, function(X) return math.sin(math.rad(X)) end, 0.25 * GunSetup.AnimSpeed)
				tweenFoV(GunSetup.FOV1, 40)
			end
			if AimPartMode == 2 then
				tweenJoint(RAW,  RAW.C0 *  CFrame.new(-Tool.AimPart2.CFrame:toObjectSpace(Character.Head.CFrame).p), nil, function(X) return math.sin(math.rad(X)) end, 0.25 * GunSetup.AnimSpeed)
				tweenJoint(LAW,  GunSetup.LeftAim2Position , nil, function(X) return math.sin(math.rad(X)) end, 0.25 * GunSetup.AnimSpeed)
				tweenFoV(GunSetup.FOV2, 40)
			end
				
			game.Workspace.CurrentCamera.CameraSubject = game.Players.LocalPlayer.Character.Humanoid
		end
	end
end)

Mouse.Button2Up:connect(function()
	if Equipped then
		if Aiming then
			Aiming = false
--			Mouse.Icon = GunSetup.Cursor.Aiming
			if not Safemode then
			IdleOrSteadyAnim()
			tweenFoV(70, 40)
			end
		end
	end
end)


-----------------------shooting function-----------------

function Rand(Min, Max, Accuracy)
	local Inverse = 1 / (Accuracy or 1)
	return (math.random(Min * Inverse, Max * Inverse) / Inverse)
end

function GetHitSurfaceCFrame(HitPos,Obj)
	local SurfaceCF = {
		{"Back",Obj.CFrame * CFrame.new(0,0,Obj.Size.z)};
		{"Bottom",Obj.CFrame * CFrame.new(0,-Obj.Size.y,0)};
		{"Front",Obj.CFrame * CFrame.new(0,0,-Obj.Size.z)};
		{"Left",Obj.CFrame * CFrame.new(-Obj.Size.x,0,0)};
		{"Right",Obj.CFrame * CFrame.new(Obj.Size.x,0,0)};
		{"Top",Obj.CFrame * CFrame.new(0,Obj.Size.y,0)}
	}
	local ClosestDist = math.huge
	local ClosestSurface = nil
	for _,v in pairs(SurfaceCF) do
		local SurfaceDist = (HitPos - v[2].p).magnitude
		if SurfaceDist < ClosestDist then
			ClosestDist = SurfaceDist
			ClosestSurface = v
		end
	end
	return ClosestSurface[2]
end



local Bullet
local HitMark
local BulletModel = workspace:FindFirstChild("Ray_Ignore") or Instance.new("Model", workspace)
BulletModel.Name = "Ray_Ignore"
spawn(function()
	while true do
		BulletModel.Parent = game.Workspace
		wait(1 / 20)
	end
end)

local Ray_Ignore = {Character, BulletModel, Camera}

function CreateBullet()
	
local Origin = Tool.FirePart.Position
local Direction = Tool.FirePart.CFrame.lookVector
local BulletCF = CFrame.new(Origin, Origin + Direction)	
	
	Bullet = Instance.new("Part")
	game.Debris:AddItem(Bullet, 3)
	Bullet.Name = "Bullet"
	Bullet.Shape = Enum.PartType.Ball
	Bullet.Size = Vector3.new(0.2, 0.2, 0.2)
	Bullet.TopSurface = "Smooth"
	Bullet.BottomSurface = "Smooth"
	Bullet.BrickColor = BrickColor.new("Bright yellow")
	Bullet.Material = "Neon"
	Bullet.Transparency = 0
	Bullet.CanCollide = false
	Bullet.CFrame = Tool.FirePart.CFrame + (Tool.FirePart.CFrame.p - Tool.FirePart.CFrame.p)
	Bullet.CFrame = CFrame.new(Tool.FirePart.CFrame.p, Tool.FirePart.CFrame.p + Tool.FirePart.CFrame.lookVector)
	local BM = Instance.new("SpecialMesh", Bullet)
	BM.MeshType = "Brick"
	BM.Scale = Vector3.new(0.2,0.2,25)
	local BulletMass = Bullet.Size.X * Bullet.Size.Y * Bullet.Size.Z
	local BF = Instance.new("BodyForce")
		BF.force = Vector3.new(0, BulletMass * (65 - GunSetup.BDrop), 0)
		BF.Parent = Bullet
		Bullet.Velocity = Direction * 1000
		Bullet.CFrame = BulletCF + Direction

if GunSetup.BSpeed >= 343 then
	local BulletWhizz = Instance.new("Sound")
	BulletWhizz.Parent = Bullet
	BulletWhizz.Pitch = 1
	BulletWhizz.Looped = true
	BulletWhizz.EmitterSize = 25
	BulletWhizz.MaxDistance = 500
	BulletWhizz.SoundId = "rbxassetid://151284431"
	BulletWhizz:Play()
end
	
	return Bullet

end

function CreateBulletImpact(HitPos, HitObj, HumanoidFound)
	local SurfaceCF = GetHitSurfaceCFrame(HitPos, HitObj)
	local SurfaceDir = CFrame.new(HitObj.CFrame.p, SurfaceCF.p)
	local SurfaceDist = SurfaceDir.lookVector * (HitObj.CFrame.p - SurfaceCF.p).magnitude / 2
	local SurfaceOffset = HitPos - SurfaceCF.p + SurfaceDist
	local SurfaceCFrame = SurfaceDir + SurfaceDist + SurfaceOffset
	
	HitMark = Instance.new("Part")
	HitMark.BrickColor = BrickColor.new("Black")
	HitMark.Transparency = 1
	HitMark.Anchored = true
	HitMark.CanCollide = false
	HitMark.FormFactor = "Custom"
	HitMark.Size = Vector3.new(math.random(1,1.5), math.random(1,1.5), 0.2)
	HitMark.TopSurface = 0
	HitMark.BottomSurface = 0
	local Mesh = Instance.new("BlockMesh")
	Mesh.Offset = Vector3.new(0, 0, -0.05)
	Mesh.Scale = Vector3.new(-0.25, -0.25, 0)
	Mesh.Parent = HitMark

	local mat = HitObj.Material

	if mat == Enum.Material.Wood or mat == Enum.Material.WoodPlanks then
		local BulletWhizz = Instance.new("Sound")
	BulletWhizz.Parent = HitMark
	BulletWhizz.Pitch = BulletWhizz.Pitch * math.random(34, 46)/40
	BulletWhizz.SoundId = "rbxassetid://142082171"
	BulletWhizz:Play()
	
	if game.ReplicatedStorage:FindFirstChild("Dust" or "Smoke") then
	local D1 = game.ReplicatedStorage.Dust:clone()
	D1.Parent = HitMark
	D1.Enabled = true
	end

	
	local Decal = Instance.new("Decal")
	Decal.Face = Enum.NormalId.Front
	Decal.Texture = "http://www.roblox.com/asset/?id=64291961"
	Decal.Parent = HitMark
	HitMark.Parent = BulletModel
	HitMark.CFrame = SurfaceCFrame
		local Particles = Instance.new("ParticleEmitter")
		Particles.Color = ColorSequence.new(Color3.new(255, 255, 255))
		Particles.LightEmission = 0
		Particles.Size = NumberSequence.new(0.25)
		Particles.Texture = "http://www.roblox.com/asset/?id=434255560"
		Particles.Transparency = NumberSequence.new(
			{
				NumberSequenceKeypoint.new(0, 0.25, 0.25);
				NumberSequenceKeypoint.new(1, 1);
			}
		)
		Particles.Acceleration = Vector3.new(0, -196.2, 0)
		Particles.Lifetime = NumberRange.new(0.25 - 0.05, 0.25 + 0.15)
		Particles.Rate = 500
		Particles.RotSpeed = NumberRange.new(360)
		Particles.Speed = NumberRange.new(25 - 0, 25 + 0)
		Particles.VelocitySpread = 45
		Particles.Parent = HitMark
		Particles.EmissionDirection = "Top"
		game.Debris:AddItem(Particles, 0.2)
	game.Debris:AddItem(HitMark, 0.95)

	elseif mat == Enum.Material.Plastic and HitObj.Name == "Head" or HitObj.Name == "Torso" or HitObj.Name == "Right Arm" or HitObj.Name == "Left Arm" or HitObj.Name == "Right Leg" or HitObj.Name == "Left Leg" then
	
	local BulletWhizz = Instance.new("Sound")
	BulletWhizz.Parent = HitMark
	BulletWhizz.Pitch = BulletWhizz.Pitch * math.random(34, 46)/40
	BulletWhizz.SoundId = "rbxassetid://330595293"
	BulletWhizz:Play()

		local Decal = Instance.new("Decal")
	Decal.Face = Enum.NormalId.Front
	Decal.Texture = "http://www.roblox.com/asset/?id=112969718"
	Decal.Parent = HitMark
	HitMark.Parent = BulletModel
	HitMark.CFrame = SurfaceCFrame
		local Particles = Instance.new("ParticleEmitter")
		Particles.Color = ColorSequence.new(Color3.new(25, 0, 0))
		Particles.LightEmission = 0
		Particles.Size = NumberSequence.new(.5)
		Particles.Texture = "http://www.roblox.com/asset/?id=176677966"
		Particles.Transparency = NumberSequence.new(
			{
				NumberSequenceKeypoint.new(0, 0, 0);
				NumberSequenceKeypoint.new(1, 1);
			}
		)
		Particles.Acceleration = Vector3.new(0, 0, 0)
		Particles.Lifetime = NumberRange.new(0.1 - 0.05, 0.1 + 0.05)
		Particles.Rate = 500
		Particles.RotSpeed = NumberRange.new(1000)
		Particles.Speed = NumberRange.new(0 - 0, 0 + 0)
		Particles.VelocitySpread = 0
		Particles.Parent = HitMark
		Particles.EmissionDirection = "Top"
		game.Debris:AddItem(Particles, 0.2)
	game.Debris:AddItem(HitMark, 0.95)


	elseif mat == Enum.Material.Concrete or mat == Enum.Material.Slate or mat == Enum.Material.Cobblestone or mat == Enum.Material.Brick or mat == Enum.Material.Granite or mat == Enum.Material.Granite or mat == Enum.Material.Plastic or mat == Enum.Material.SmoothPlastic then
		local BulletWhizz = Instance.new("Sound")
	BulletWhizz.Parent = HitMark
	BulletWhizz.Pitch = BulletWhizz.Pitch * math.random(34, 46)/40
	BulletWhizz.SoundId = "rbxassetid://142082166"
	BulletWhizz:Play()
	
	if game.ReplicatedStorage:FindFirstChild("Dust" or "Smoke") then
	local D1 = game.ReplicatedStorage.Dust:clone()
	D1.Parent = HitMark
	D1.Enabled = true
	local D2 = game.ReplicatedStorage.Smoke:clone()
	D2.Parent = HitMark
	D2.Enabled = true
	end
	
		local Decal = Instance.new("Decal")
	Decal.Face = Enum.NormalId.Front
	Decal.Texture = "http://www.roblox.com/asset/?id=64291961"
	Decal.Parent = HitMark
	HitMark.Parent = BulletModel
	HitMark.CFrame = SurfaceCFrame
		local Particles = Instance.new("ParticleEmitter")
		Particles.Color = ColorSequence.new(Color3.new(50, 50, 50))
		Particles.LightEmission = 0
		Particles.Size = NumberSequence.new(0.25)
		Particles.Texture = "rbxasset://textures/particles/smoke_main.dds"
		Particles.Transparency = NumberSequence.new(
			{
				NumberSequenceKeypoint.new(0, 0.25, 0.25);
				NumberSequenceKeypoint.new(1, 1);
			}
		)
		Particles.Acceleration = Vector3.new(0, -196.2, 0)
		Particles.Lifetime = NumberRange.new(0.1 - 0.05, 0.1 + 0.05)
		Particles.Rate = 500
		Particles.RotSpeed = NumberRange.new(360)
		Particles.Speed = NumberRange.new(25 - 5, 25 + 5)
		Particles.VelocitySpread = 45
		Particles.Parent = HitMark
		Particles.EmissionDirection = "Top"
		game.Debris:AddItem(Particles, 0.2)
	game.Debris:AddItem(HitMark, 0.95)

	elseif	mat == Enum.Material.Grass or mat == Enum.Material.Sand then
		local BulletWhizz = Instance.new("Sound")
	BulletWhizz.Parent = HitMark
	BulletWhizz.Pitch = BulletWhizz.Pitch * math.random(34, 46)/40
	BulletWhizz.SoundId = "rbxassetid://133758545"
	BulletWhizz:Play()

	if game.ReplicatedStorage:FindFirstChild("Dust" or "Smoke") then
	local D1 = game.ReplicatedStorage.Dust:clone()
	D1.Parent = HitMark
	D1.Enabled = true
	local D2 = game.ReplicatedStorage.Smoke:clone()
	D2.Parent = HitMark
	D2.Enabled = true
	end
	
	if game.ReplicatedStorage:FindFirstChild("Dust" or "Smoke") then
	local D1 = game.ReplicatedStorage.Dust:clone()
	D1.Parent = HitMark
	D1.Enabled = true
	local D2 = game.ReplicatedStorage.Smoke:clone()
	D2.Parent = HitMark
	D2.Enabled = true
	end
	
		local Decal = Instance.new("Decal")
	Decal.Face = Enum.NormalId.Front
	Decal.Texture = "http://www.roblox.com/asset/?id=64291961"
	Decal.Parent = HitMark
	HitMark.Parent = BulletModel
	HitMark.CFrame = SurfaceCFrame
		local Particles = Instance.new("ParticleEmitter")
		Particles.Color = ColorSequence.new(Color3.new(50, 50, 50))
		Particles.LightEmission = 0
		Particles.Size = NumberSequence.new(0.25)
		Particles.Texture = "rbxasset://textures/particles/smoke_main.dds"
		Particles.Transparency = NumberSequence.new(
			{
				NumberSequenceKeypoint.new(0, 0.25, 0.25);
				NumberSequenceKeypoint.new(1, 1);
			}
		)
		Particles.Acceleration = Vector3.new(0, -196.2, 0)
		Particles.Lifetime = NumberRange.new(0.1 - 0.05, 0.1 + 0.05)
		Particles.Rate = 500
		Particles.RotSpeed = NumberRange.new(360)
		Particles.Speed = NumberRange.new(25 - 5, 25 + 5)
		Particles.VelocitySpread = 45
		Particles.Parent = HitMark
		Particles.EmissionDirection = "Top"
		game.Debris:AddItem(Particles, 0.2)
	game.Debris:AddItem(HitMark, 0.95)

	elseif mat == Enum.Material.CorrodedMetal or mat == Enum.Material.Metal or mat == Enum.Material.DiamondPlate then
		local BulletWhizz = Instance.new("Sound")
	BulletWhizz.Parent = HitMark
	BulletWhizz.Pitch = BulletWhizz.Pitch * math.random(34, 46)/40
	BulletWhizz.SoundId = "rbxassetid://142082170"
	BulletWhizz:Play()
	
	local Decal = Instance.new("Decal")
	Decal.Face = Enum.NormalId.Front
	Decal.Texture = "http://www.roblox.com/asset/?id=64291961"
	Decal.Parent = HitMark
	HitMark.Parent = BulletModel
	HitMark.CFrame = SurfaceCFrame
		local Particles = Instance.new("ParticleEmitter")
		Particles.Color = ColorSequence.new(Color3.new(255, 200, 0))
		Particles.LightEmission = 1
		Particles.Size = NumberSequence.new(0.075)
		Particles.Texture = "http://www.roblox.com/asset/?id=416917683"
		Particles.Transparency = NumberSequence.new(
			{
				NumberSequenceKeypoint.new(0, 0.25, 0.25);
				NumberSequenceKeypoint.new(1, 1);
			}
		)
		Particles.Acceleration = Vector3.new(0, -196.2, 0)
		Particles.Lifetime = NumberRange.new(0.1 - 0.05, 0.1 + 0.05)
		Particles.Rate = 500
		Particles.RotSpeed = NumberRange.new(360)
		Particles.Speed = NumberRange.new(25 - 5, 25 + 5)
		Particles.VelocitySpread = 45
		Particles.Parent = HitMark
		Particles.EmissionDirection = "Top"
		game.Debris:AddItem(Particles, 0.2)
	game.Debris:AddItem(HitMark, 0.95)


	else
		local BulletWhizz = Instance.new("Sound")
	BulletWhizz.Parent = HitMark
	BulletWhizz.Pitch = BulletWhizz.Pitch * math.random(34, 46)/40
	BulletWhizz.SoundId = "rbxassetid://142082166"
	BulletWhizz:Play()
	end



	end
	
	


		--rocket.Touched:connect(function(hit)

function EjectShells()
	shell = Shell:clone()
		shell.CFrame =  Tool.Chamber.CFrame * CFrame.fromEulerAnglesXYZ(2.5,1,1.25)
		shell.Velocity = Tool.Chamber.CFrame.lookVector * 20 + Vector3.new(0,10,0)
		shell.RotVelocity = Vector3.new(-10,40,30)
		shell.Parent = BulletModel
		game:GetService("Debris"):addItem(shell,0.125)
		print("Ejecting Shell")

	end
local connection

function M203()
	if GunSetup.GrenadeLauncher == true then
		Tool.Handle.M203:Play()
		local M203 = game.ReplicatedStorage.M203["M203"]:clone()
		M203.Parent = game.Workspace
		M203.CFrame = Tool.FirePart2.CFrame*CFrame.new(.15,-0.7,-5.5)
		
		if GunSetup.M203Ammo == 1 then
		M203.Velocity = Tool.FirePart2.CFrame.lookVector*(500-196.2)
		end
		if GunSetup.M203Ammo == 2 then
		M203.Velocity = Tool.FirePart2.CFrame.lookVector*(575-196.2)
		end		
		
		if GunSetup.M203Ammo == 1 then
		local Explosion =Instance.new("Explosion")
			Explosion.BlastRadius=15
			Explosion.BlastPressure=0
			damage = math.random(80,120)
	 		M203.Touched:connect(function(Hit)
			Explosion.Hit:connect(Damage)
			Explosion.Position= M203.Position
	
			Explosion.Parent=game.Workspace
			M203:remove()
			end)
		end
		if GunSetup.M203Ammo == 2 then
		local Smoke = M203.Smoke
	 	M203.Touched:connect(function(Hit)
			
			Smoke.Enabled = true
			M203.Velocity = Camera.CoordinateFrame.lookVector*0
			wait(9.5)
			Smoke.Enabled = false
			wait(1.5)
			M203:remove()
			end)
		end
	end
end

function Raycasting()
	local Hit,Pos
	local Position0 = Bullet.Position;
	local Position1 = Bullet.Position;
	local Distance = 0
	while true do
		RS.RenderStepped:wait()
		if Distance > 1500 then
			Bullet:Destroy()
			break
		end
		Position1 = Bullet.Position;
		Distance = Distance + (Position1 - Position0).magnitude
		Hit, Pos = workspace:FindPartOnRayWithIgnoreList(Ray.new(Position0,(Position1 - Position0)), Ray_Ignore);

		if Hit then
			Bullet:Destroy()
	
			local hitHumanoid = ( Hit.Parent:IsA( "Accessory" ) and Hit.Parent.Parent:FindFirstChild( "Humanoid" ) or Hit.Parent:FindFirstChild( "Humanoid" ) );
			local c = Instance.new("ObjectValue");
			c.Name = "creator";
			c.Value = Player;
			game.Debris:AddItem(c, 3);
			c.Parent = hitHumanoid;
			local hitPlyr = ( hitHumanoid and game.Players:GetPlayerFromCharacter( hitHumanoid.Parent ) );
				if not hitHumanoid then
					CreateBulletImpact(Pos,Hit,false)
					if game.ReplicatedStorage:FindFirstChild("Smoke") then
						local D2 = game.ReplicatedStorage.Smoke:clone()
						D2.Parent = HitMark
						D2.Enabled = true
					end
				elseif hitHumanoid then
					if game.ReplicatedStorage:FindFirstChild("Blood") then
						local D2 = game.ReplicatedStorage.Blood:clone()
						D2.Parent = HitMark
						D2.Enabled = true
					end
					CreateBulletImpact(Pos,Hit,true)
				end
				
				if hitPlyr then
					local isEnemy;
					if GunSetup.ATK then
						isEnemy = ( hitPlyr.TeamColor ~= Player.TeamColor or hitPlyr.Neutral );
					elseif not GunSetup.ATK then
						isEnemy = (hitPlyr.TeamColor == Player.TeamColor or hitPlyr.TeamColor ~= Player.TeamColor or hitPlyr.Neutral );
					end
					if isEnemy and Hit.Name == "Head" then
						hitHumanoid:TakeDamage( GunSetup.HeadDamage );
					elseif isEnemy and Hit.Name ~= "Head" then
						hitHumanoid:TakeDamage( GunSetup.Damage);
					elseif isEnemy and Hit.Name == "Chest" then
						hitHumanoid:TakeDamage( GunSetup.Damage);
					elseif isEnemy and Hit:IsA("Accessory") or Hit:IsA("Hat") and Hit.Parent.Parent:FindFirstChild("Humanoid") then
						Hit.Parent.Parent:FindFirstChild("Humanoid"):TakeDamage(GunSetup.HeadDamage);
					end
					
					elseif hitHumanoid and Hit.Name == "Head" then
						hitHumanoid:TakeDamage( GunSetup.HeadDamage );
					elseif hitHumanoid and Hit.Name ~= "Head" then
						hitHumanoid:TakeDamage( GunSetup.Damage );
					elseif hitHumanoid and Hit.Name == "Chest" then
						hitHumanoid:TakeDamage( GunSetup.VestDamage );
					elseif hitHumanoid and Hit:IsA("Accessory") or Hit:IsA("Hat") or Hit.Name == "Face" and Hit.Parent.Parent:FindFirstChild("Humanoid") then
						Hit.Parent.Parent:FindFirstChild("Humanoid"):TakeDamage( GunSetup.HeadDamage);	
					end
				print(Hit.Name)
				return Hit, Pos;
			end
		Position0 = Position1;
	end
end


function Damage(Targ)
 local humanoid=Targ.Parent:FindFirstChild("Humanoid")
	if Targ.Parent:FindFirstChild("Humanoid") then
--		for i,v in ipairs(humanoids) do
--			if v==targ.Parent.Humanoid then
--				return
--			end
--		end
--		table.insert(humanoids,targ.Parent.Humanoid)
	Targ.Parent.Humanoid:TakeDamage(damage)
end
end




function shoot()
	
		local move = (Tool.FirePart.CFrame * CFrame.Angles(math.rad(math.random(-GunSetup.BSpread, GunSetup.BSpread)/10), math.rad(math.random(-GunSetup.BSpread, GunSetup.BSpread)/10), math.rad(math.random(-GunSetup.BSpread, GunSetup.BSpread)/10))).lookVector * 450
		local from = Tool.FirePart.Position
		local ray = Ray.new(from,move-Vector3.new(0, GunSetup.BDrop*0.05, 0))
		local Hit,Pos = workspace:FindPartOnRayWithIgnoreList(ray, Ray_Ignore)	
		local HumanoidFound = false

		
		CreateBullet()


		local humanoid
			if Hit then
				CreateBulletImpact(Pos, Hit, HumanoidFound)	
				
			if Hit.Parent.Name == "Chest" then
				if Hit.Parent.Parent:FindFirstChild("Humanoid") then
				humanoid = Hit.Parent.Parent:FindFirstChild("Humanoid")
				local c = Instance.new("ObjectValue")
				c.Name = "creator"
				c.Value = Player
				game.Debris:AddItem(c, 3)
				c.Parent = humanoid	
				humanoid:TakeDamage(GunSetup.VestDamage)
				HumanoidFound = true

				end
				
			elseif Hit.Parent:IsA("Hat") or Hit.Parent:IsA("Accessory") then
				if Hit.Parent.Parent:FindFirstChild("Humanoid") then
				humanoid = Hit.Parent.Parent:FindFirstChild("Humanoid")
				local c = Instance.new("ObjectValue")
				c.Name = "creator"
				c.Value = Player
				game.Debris:AddItem(c, 3)
				c.Parent = humanoid	
				local d = math.random(GunSetup.HeadDamage[1], GunSetup.HeadDamage[2])
				humanoid:TakeDamage(d)
				HumanoidFound = true

				end
			elseif Hit.Parent.Name=="Face" then
				if Hit.Parent.Parent:FindFirstChild("Humanoid") then
				humanoid = Hit.Parent.Parent:FindFirstChild("Humanoid")
				local c = Instance.new("ObjectValue")
				c.Name = "creator"
				c.Value = Player
				game.Debris:AddItem(c, 3)
				c.Parent = humanoid	
				humanoid:TakeDamage(GunSetup.HelmetDamage)
				HumanoidFound = true

				end
			end
			if Hit.Parent:FindFirstChild("Humanoid") and Hit.Name == "Head" then
				humanoid = Hit.Parent:FindFirstChild("Humanoid")
				local c = Instance.new("ObjectValue")
				c.Name = "creator"
				c.Value = Player
				game.Debris:AddItem(c, 3)
				c.Parent = humanoid	
				local d = math.random(GunSetup.HeadDamage[1], GunSetup.HeadDamage[2])
				humanoid:TakeDamage(d)
				HumanoidFound = true

			elseif Hit.Parent:FindFirstChild("Humanoid") and Hit.Name == "Torso" then
				humanoid = Hit.Parent:FindFirstChild("Humanoid")
				local c = Instance.new("ObjectValue")
				c.Name = "creator"
				c.Value = Player
				game.Debris:AddItem(c, 3)
				c.Parent = humanoid	
				local d = math.random(GunSetup.TorsoDamage[1], GunSetup.TorsoDamage[2])
				humanoid:TakeDamage(d)
				HumanoidFound = true
				
			elseif Hit.Parent:FindFirstChild("Humanoid") and Hit.Name == "Right Arm" or Hit.Name == "Left Arm" or Hit.Name == "Right Leg" or Hit.Name == "Left Leg" then
				humanoid = Hit.Parent:FindFirstChild("Humanoid")
				local c = Instance.new("ObjectValue")
				c.Name = "creator"
				c.Value = Player
				game.Debris:AddItem(c, 3)
				c.Parent = humanoid	
				 local d = math.random(GunSetup.LimbsDamage[1], GunSetup.LimbsDamage[2])
				humanoid:TakeDamage(d)
				HumanoidFound = true

			end
			end
			
			Tool.FirePart.Fire:Play()
					RecoilG = math.rad(math.random(GunSetup.Recoil[1],GunSetup.Recoil[1])/10 * Rand(1, 1.5, 0.1))--(GunSettings.Recoil*math.random(1,4))
					Recoilup = RecoilG/2
					print(RecoilG)
					for i = Recoil, Recoil*Recoil do
						Recoilup = Recoilup * math.abs(Recoil) * math.random(-i,i)
					end

			for _, v in pairs(Tool.FirePart:GetChildren()) do
			if v.Name:sub(1, 7) == "FlashFX" or v.Name:sub(1, 7) == "Smoke" then
				v.Enabled = true
				end
			end

			delay(1 / 30, function()
			for _, v in pairs(Tool.FirePart:GetChildren()) do
			if v.Name:sub(1, 7) == "FlashFX" or v.Name:sub(1, 7) == "Smoke" then
				v.Enabled = false
				Recoilup = 0
			end
			end
			end)
			

					coroutine.resume(coroutine.create(function()
					local r  = math.abs(Recoilup)/3
					local r2  = math.abs(Recoilup)/12
					local r3 = math.abs(Recoilup)/14
					if _G.Crouched then
						r = r2
					elseif _G.Proned then
						r = r3
					end
					local ran = math.random(-1, 1)
					Camera.CoordinateFrame = CFrame.new(Camera.Focus.p) * (Camera.CoordinateFrame - Camera.CoordinateFrame.p) * CFrame.Angles(r,  0, 0) * CFrame.new(0, 0, (Camera.Focus.p - Camera.CoordinateFrame.p).magnitude)
					local c = -r/20
					local cx = -(r*ran)/20
					for i = 1, math.random(15, 25) do
						if EquipId == curId then
							Camera.CoordinateFrame = CFrame.new(Camera.Focus.p) * (Camera.CoordinateFrame - Camera.CoordinateFrame.p) * CFrame.Angles(c,  0, 0) * CFrame.new(0, 0, (Camera.Focus.p - Camera.CoordinateFrame.p).magnitude)
							wait()
							
						else
							break
						end
						
					end
				end))
					
		
		-- Bullet Creation

		EjectShells()
		AmmoGui.Frame.AText.Text = Ammo
		print(Ammo)

end




------------Some Random Functions----------------

local Btype = script.BType
Btype.Value = GunSetup.BType

function Checar()
	CheckAnim()
end

function Emperrar()
	if GunSetup.CanBreak == true then
	local Jam = math.random(200)
	print("Chance de emperrar: "..Jam)
	if Jam <= 2 then
		Emperrado = true
	end
end
end

------------Shooting Function--------------------


Mouse.Button1Down:connect(function()
	if Equipped then
	if Safemode or slideback then return end
	MouseHeld = true
	if GetAmmo() == 0 or MagOut and GunSetup.FireMode ~= "M203" then
		Tool.Handle.Click:Play()
		Chambered = false
	end
	
	if Emperrado or not Chambered and GunSetup.FireMode ~= "M203" then
		Tool.Handle.Click:Play()
		return
	end

	if not Shooting and not Reloading and not GLReloading or Sprinting and not Emperrado and not Checando then
	Shooting = true
	if GunSetup.FireMode == "Single" and GetAmmo() > 0 and not Checando then
		shoot()
		Emperrar()
		Ammo = Ammo - 1
		GetAmmo()
		wait(Firerate)
	elseif GunSetup.FireMode == "Automatic" then
		while MouseHeld and Equipped and Shooting and not Emperrado and GetAmmo() > 0 and not Checando do
			shoot()	
			Emperrar()
			Ammo = Ammo - 1
			GetAmmo()
			wait(Firerate)
		end
	elseif GunSetup.FireMode == "Burst" and GetAmmo() > 0 and not Checando  then
		for i = 1, GunSetup.BurstFire do
			if GetAmmo() < 1 then
				break
			end
			shoot()
			Emperrar()
			Ammo = Ammo - 1
			GetAmmo()
			wait(BURSTFirerate)
		end
	elseif GunSetup.FireMode == "M203" and GLAmmo.Value > 0 and GLChambered and not Checando then
		M203()
		GLChambered = false
		GLAmmo.Value = GLAmmo.Value - 1
		wait(GLFirerate)	
	end
	Shooting = false
	end
	end
end)


Mouse.Button1Up:connect(function()
	if Equipped then
	MouseHeld = false
	end
end)



----------------Mouse Function---------------------------

Mouse.KeyDown:connect(function(Key)
	if Equipped then
	if Key == "t" then
		if not Reloading and not GLReloading and not Aiming and not Checando then
		if Safemode then
			Safemode = false
			IdleOrSteadyAnim()
		elseif not Safemode then
			if MouseHeld then
				MouseHeld = false
			end
			Safemode = true
			SafetyAnim()
		end
	end
	end
	if Key:byte() == 48 then
		if MouseHeld then
			MouseHeld = false
		end
		if not Sprinting and not Reloading and not GLReloading and not Checando and not Aiming  and not _G.Crouched and not _G.Proned then
			Sprinting = true
			SprintAnim()
		end
	end
	if Key == "y" then
		if Tool:FindFirstChild('AimPart2') ~= nil then
		if EnableCycleSight then
		if AimPartMode == 1 then
			AimPartMode = 2
			if Aiming then
				tweenJoint(RAW,  RAW.C0 *  CFrame.new(-Tool.AimPart2.CFrame:toObjectSpace(Character.Head.CFrame).p), nil, function(X) return math.sin(math.rad(X)) end, 0.25)
				tweenJoint(LAW,  GunSetup.LeftAim2Position , nil, function(X) return math.sin(math.rad(X)) end, 0.25)
				tweenFoV(GunSetup.FOV2, 60)
			end
		elseif AimPartMode == 2 then
			AimPartMode = 1
			if Aiming then
				tweenJoint(RAW,  RAW.C0 *  CFrame.new(-Tool.AimPart.CFrame:toObjectSpace(Character.Head.CFrame).p), nil, function(X) return math.sin(math.rad(X)) end, 0.25)
				tweenJoint(LAW,  GunSetup.LeftAimPosition , nil, function(X) return math.sin(math.rad(X)) end, 0.25)
				tweenFoV(GunSetup.FOV1, 60)
			end
		end
		end
	end
	end
if Key == "f" then
		if EnableFireMode then
			if MouseHeld then
				MouseHeld = false
			end
			if GunSetup.FireMode == "Automatic" then
				if GunSetup.SwitchableModes.Burst then
					GunSetup.FireMode = "Burst"
					Tool.Handle.SafetyClick:Play()
				elseif GunSetup.SwitchableModes.Single then
					GunSetup.FireMode = "Single"
					Tool.Handle.SafetyClick:Play()
				end
			elseif GunSetup.FireMode == "Burst" then
				if GunSetup.SwitchableModes.Single then
					GunSetup.FireMode = "Single"
					Tool.Handle.SafetyClick:Play()
				elseif GunSetup.SwitchableModes.Automatic then
					GunSetup.FireMode = "Automatic"
					Tool.Handle.SafetyClick:Play()
				end
			elseif GunSetup.FireMode == "Single" then
				if GunSetup.SwitchableModes.Automatic then
					GunSetup.FireMode = "Automatic"
					Tool.Handle.SafetyClick:Play()
				elseif GunSetup.SwitchableModes.Burst then
					GunSetup.FireMode = "Burst"
					Tool.Handle.SafetyClick:Play()
				end
			end
--			if GunSetup.FireMode == "Automatic" then
--				GunSetup.FireMode = "Single"
--				Tool.Handle.SafetyClick:Play()
--			elseif GunSetup.FireMode == "Single" then
--				GunSetup.FireMode = "Burst"
--				Tool.Handle.SafetyClick:Play()
--			elseif GunSetup.FireMode == "Burst" then
--				GunSetup.FireMode = "Automatic"
--				Tool.Handle.SafetyClick:Play()
--			end
		end

	end
	if Key == "r" then
		if not Reloading and not Animando and not GLReloading  and StoredAmmo.Value > 0 and not Sprinting and not Aiming and Checando and not MagOut then
			if MouseHeld then
				MouseHeld = false
			end
			Reloading = true
			ReloadAnim()
			Reloading = false
			if Checando then
				CheckAnim()
			elseif Safemode then
				SafetyAnim()
			end
		end
		
	end


		if Key == "r" then
		if GunSetup.FastReload and not Animando and not Reloading and not GLReloading and StoredAmmo.Value > 0 and not Sprinting and not Aiming and not Checando and not MagOut then
			if MouseHeld then
				MouseHeld = false
			end
			Reloading = true
			FastReloadAnim()
			FastBolt()
			Reloading = false
			if Safemode then
				SafetyAnim()
			end
		end
		
	end


		if Key == "q" then
		if not Reloading and not GLReloading and not Sprinting and not Aiming and not Checando then
			if MouseHeld then
				MouseHeld = false
			end
			Checando = true
			CheckAnim()
			AmmoGui.Frame.Some.Visible = true
			AmmoGui.Frame.Btext.Visible = true
			AmmoGui.Frame.FText.Visible = true
			AmmoGui.Frame.SAText.Visible = true
		elseif not Reloading and not GLReloading  and not Sprinting and not Aiming and Checando then
			if Safemode then
			SafetyAnim()
			Checando = false
			AmmoGui.Frame.Some.Visible = false
			AmmoGui.Frame.Btext.Visible = false
			AmmoGui.Frame.FText.Visible = false
			AmmoGui.Frame.SAText.Visible = false
			else
			IdleOrSteadyAnim()
			Checando = false
			AmmoGui.Frame.Some.Visible = false
			AmmoGui.Frame.Btext.Visible = false
			AmmoGui.Frame.FText.Visible = false
			AmmoGui.Frame.SAText.Visible = false
			end
		
		end
		end
end

if Key == "e" then
		if not Animando and not Reloading and not GLReloading and not Sprinting and not Aiming and Checando and not MagOut then
			if MouseHeld then
				MouseHeld = false
			end
 	if not slideback then
			ChamberAnim()
			slideback = true
			Emperrado = false
		if Ammo > 0 and Chambered and not MagOut then
			EjectShells()
			Ammo = Ammo - 1
		print(Ammo)
		end
	elseif slideback then
		ChamberBKAnim()
		slideback = false
		Chambered = true
end
		end
		end


if Key == "g" then
		if GunSetup.GrenadeLauncher and not Checando then
			if MouseHeld then
				MouseHeld = false
			end
		if GunSetup.FireMode ~= "M203" then
		Tool.Handle.SafetyClick:Play()
		GunSetup.FireMode = "M203"
		else
		Tool.Handle.SafetyClick:Play()
		GunSetup.FireMode = GunSetup.BkFM	
end		
end
end


if Key == "g" then
		if GunSetup.GrenadeLauncher and not Animando and GLAmmo.Value > 0 and not Reloading and not GLReloading and not Sprinting and Checando and not MagOut then
			if MouseHeld then
				MouseHeld = false
			end
	GLReloading = true
	GLReloadAnim()
	GLReloading = false	
	GLChambered = true
end
end

if Key == "b" then
		if GunSetup.CanSeeMag and not Animando and not Reloading and not GLReloading and not Sprinting and not Aiming and Checando then
			if MouseHeld then
				MouseHeld = false
			end


	if not MagOut then
	MagOut = true
 	SeeMag()
	AmmoGui.Frame.Some2.Visible = true
	AmmoGui.Frame.AText.Visible = true
	else
	AmmoGui.Frame.Some2.Visible = false
	AmmoGui.Frame.AText.Visible = false
	UNSeeMag()	
	MagOut = false
end



end
end

end)


Mouse.KeyUp:connect(function(Key)
	if Equipped then
	if Key:byte() == 48 then
		if MouseHeld then
			MouseHeld = false
		end
		if Sprinting and not Aiming and not Reloading and not GLReloading and not _G.Crouched and not _G.Proned then
			if not Safemode then
			IdleOrSteadyAnim()
			end
			wait(0.25 * GunSetup.AnimSpeed)
			_G.Sprinting = false
			Humanoid.WalkSpeed = 16
			Sprinting = false
		end
	end
	end
end)

-----------------Unequiping------------

Character.Humanoid.Died:connect(function()
	Tool.Parent = Player.Backpack
	Equipped = false
	Torso:WaitForChild("Right Shoulder").Part1 = Character["Right Arm"]
	Torso:WaitForChild("Left Shoulder").Part1 = Character["Left Arm"]
	RAW:Destroy()
	LAW:Destroy()
	if Aiming then
		Aiming = false
	end
	if Reloading then
		Reloading = false
	end
	if GLReloading then
		GLReloading = false
	end
	if Sprinting then
		Sprinting = false
	end
end)

Tool.Unequipped:connect(function()
	Equipped = false
	uis.MouseIconEnabled = true
	if MouseHeld then
		MouseHeld = false
	end
	if GunSetup.FireMode == "M203" then
		AmmoGui.Frame.AText.Text = GLAmmo.Value
	end
	if GunSetup.FireMode ~= "M203" then
		AmmoGui.Frame.AText.Text = Ammo
	end
	Player.PlayerGui:WaitForChild("AmmoGui"):Destroy()
	if Aiming then
		Aiming = false
	end
	if Reloading then
		Reloading = false
			IdleOrSteadyAnim()
	end	
	tweenFoV(70, 10)
	_G.Sprinting = false
	Player.CameraMode="Classic"
	Torso:WaitForChild("Right Shoulder").Part1 = Character["Right Arm"]
	Torso:WaitForChild("Left Shoulder").Part1 = Character["Left Arm"]
	RAW:Destroy()
	LAW:Destroy()


end)

end))
NumberValue12.Name = "Ammo"
NumberValue12.Parent = LocalScript11
NumberValue12.Value = 50
StringValue13.Name = "BType"
StringValue13.Parent = LocalScript11
NumberValue14.Name = "StoredAmmo"
NumberValue14.Parent = LocalScript11
NumberValue14.Value = 10000000000
NumberValue15.Name = "MaxAmmo"
NumberValue15.Parent = LocalScript11
NumberValue15.Value = 1e+18
NumberValue16.Name = "GLAmmo"
NumberValue16.Parent = LocalScript11
NumberValue16.Value = 10
ScreenGui17.Name = "AmmoGui"
ScreenGui17.Parent = LocalScript11
Frame18.Parent = ScreenGui17
Frame18.Transparency = 1
Frame18.Size = UDim2.new(0.0812182724, 0, 0.300000012, 0)
Frame18.Position = UDim2.new(0.899999976, 0, 0.649999976, 0)
Frame18.BackgroundColor3 = Color3.new(0, 0, 0)
Frame18.BackgroundTransparency = 1
Frame19.Name = "nao"
Frame19.Parent = Frame18
Frame19.Size = UDim2.new(1, 0, 0.100000001, 0)
Frame19.Style = Enum.FrameStyle.RobloxRound
Frame19.BackgroundColor3 = Color3.new(0, 0, 0)
TextLabel20.Name = "NText"
TextLabel20.Parent = Frame18
TextLabel20.Transparency = 1
TextLabel20.Size = UDim2.new(1, 0, 0.100000001, 0)
TextLabel20.Text = "M16A4"
TextLabel20.BackgroundColor3 = Color3.new(0, 0, 0)
TextLabel20.BackgroundTransparency = 1
TextLabel20.BorderSizePixel = 0
TextLabel20.Font = Enum.Font.SourceSansBold
TextLabel20.FontSize = Enum.FontSize.Size18
TextLabel20.TextColor3 = Color3.new(1, 1, 1)
TextLabel20.TextStrokeTransparency = 0.85000002384186
TextLabel20.TextWrapped = true
Frame21.Name = "Some"
Frame21.Parent = Frame18
Frame21.Size = UDim2.new(1, 0, 0.600000024, 0)
Frame21.Style = Enum.FrameStyle.RobloxRound
Frame21.Position = UDim2.new(0, 0, 0.400000006, 0)
Frame21.Visible = false
Frame21.BackgroundColor3 = Color3.new(0, 0, 0)
TextLabel22.Name = "FText"
TextLabel22.Parent = Frame18
TextLabel22.Transparency = 1
TextLabel22.Size = UDim2.new(1, 0, 0.100000001, 0)
TextLabel22.Text = "Automatic"
TextLabel22.Position = UDim2.new(0, 0, 0.400000006, 0)
TextLabel22.Visible = false
TextLabel22.BackgroundColor3 = Color3.new(0, 0, 0)
TextLabel22.BackgroundTransparency = 1
TextLabel22.BorderSizePixel = 0
TextLabel22.Font = Enum.Font.SourceSansBold
TextLabel22.FontSize = Enum.FontSize.Size18
TextLabel22.TextColor3 = Color3.new(1, 1, 1)
TextLabel22.TextStrokeTransparency = 0.85000002384186
TextLabel22.TextWrapped = true
TextLabel23.Name = "SAText"
TextLabel23.Parent = Frame18
TextLabel23.Transparency = 1
TextLabel23.Size = UDim2.new(1, 0, 0.25, 0)
TextLabel23.Text = "30"
TextLabel23.Position = UDim2.new(0, 0, 0.550000012, 0)
TextLabel23.Visible = false
TextLabel23.BackgroundColor3 = Color3.new(0, 0, 0)
TextLabel23.BackgroundTransparency = 1
TextLabel23.BorderSizePixel = 0
TextLabel23.Font = Enum.Font.SourceSansBold
TextLabel23.FontSize = Enum.FontSize.Size24
TextLabel23.TextColor3 = Color3.new(1, 1, 1)
TextLabel23.TextScaled = true
TextLabel23.TextStrokeTransparency = 0.85000002384186
TextLabel23.TextWrapped = true
TextLabel24.Name = "Btext"
TextLabel24.Parent = Frame18
TextLabel24.Transparency = 1
TextLabel24.Size = UDim2.new(1, 0, 0.100000001, 0)
TextLabel24.Text = "5.56x45mm"
TextLabel24.Position = UDim2.new(0, 0, 0.850000024, 0)
TextLabel24.Visible = false
TextLabel24.BackgroundColor3 = Color3.new(0, 0, 0)
TextLabel24.BackgroundTransparency = 1
TextLabel24.BorderSizePixel = 0
TextLabel24.Font = Enum.Font.SourceSansBold
TextLabel24.FontSize = Enum.FontSize.Size18
TextLabel24.TextColor3 = Color3.new(1, 1, 1)
TextLabel24.TextStrokeTransparency = 0.85000002384186
TextLabel24.TextWrapped = true
Frame25.Name = "nao"
Frame25.Parent = Frame18
Frame25.Size = UDim2.new(1, 0, 0.100000001, 0)
Frame25.Style = Enum.FrameStyle.RobloxRound
Frame25.Position = UDim2.new(0, 0, 0.150000006, 0)
Frame25.BackgroundColor3 = Color3.new(0, 0, 0)
ImageLabel26.Name = "A"
ImageLabel26.Parent = Frame18
ImageLabel26.Size = UDim2.new(0.100000001, 0, 0.0500000007, 0)
ImageLabel26.Position = UDim2.new(0.100000001, 0, 0.180000007, 0)
ImageLabel26.BackgroundColor3 = Color3.new(0, 1, 0)
ImageLabel26.Image = "rbxassetid://133293265"
ImageLabel26.ImageTransparency = 1
ImageLabel27.Name = "B"
ImageLabel27.Parent = Frame18
ImageLabel27.Size = UDim2.new(0.100000001, 0, 0.0500000007, 0)
ImageLabel27.Position = UDim2.new(0.280000001, 0, 0.180000007, 0)
ImageLabel27.BackgroundColor3 = Color3.new(1, 1, 0)
ImageLabel27.Image = "rbxassetid://133293265"
ImageLabel27.ImageTransparency = 1
ImageLabel28.Name = "C"
ImageLabel28.Parent = Frame18
ImageLabel28.Size = UDim2.new(0.100000001, 0, 0.0500000007, 0)
ImageLabel28.Position = UDim2.new(0.460000008, 0, 0.180000007, 0)
ImageLabel28.BackgroundColor3 = Color3.new(1, 0, 0)
ImageLabel28.Image = "rbxassetid://133293265"
ImageLabel28.ImageTransparency = 1
ImageLabel29.Name = "D"
ImageLabel29.Parent = Frame18
ImageLabel29.Size = UDim2.new(0.100000001, 0, 0.0500000007, 0)
ImageLabel29.Position = UDim2.new(0.819999993, 0, 0.180000007, 0)
ImageLabel29.BackgroundColor3 = Color3.new(0, 1, 1)
ImageLabel29.Image = "rbxassetid://133293265"
ImageLabel29.ImageTransparency = 1
Frame30.Name = "Some2"
Frame30.Parent = Frame18
Frame30.Size = UDim2.new(1, 0, 0.100000001, 0)
Frame30.Style = Enum.FrameStyle.RobloxRound
Frame30.Position = UDim2.new(0, 0, 0.289999992, 0)
Frame30.Visible = false
Frame30.BackgroundColor3 = Color3.new(0, 0, 0)
TextLabel31.Name = "AText"
TextLabel31.Parent = Frame18
TextLabel31.Transparency = 1
TextLabel31.Size = UDim2.new(1, 0, 0.100000001, 0)
TextLabel31.Text = "30 Bullets"
TextLabel31.Position = UDim2.new(0, 0, 0.280000001, 0)
TextLabel31.Visible = false
TextLabel31.BackgroundColor3 = Color3.new(0, 0, 0)
TextLabel31.BackgroundTransparency = 1
TextLabel31.BorderSizePixel = 0
TextLabel31.Font = Enum.Font.SourceSansBold
TextLabel31.FontSize = Enum.FontSize.Size48
TextLabel31.TextColor3 = Color3.new(1, 1, 1)
TextLabel31.TextScaled = true
TextLabel31.TextStrokeTransparency = 0.85000002384186
TextLabel31.TextWrapped = true
ImageLabel32.Name = "E"
ImageLabel32.Parent = Frame18
ImageLabel32.Size = UDim2.new(0.100000001, 0, 0.0500000007, 0)
ImageLabel32.Position = UDim2.new(0.639999986, 0, 0.180000007, 0)
ImageLabel32.BackgroundColor3 = Color3.new(1, 1, 1)
ImageLabel32.Image = "rbxassetid://133293265"
ImageLabel32.ImageTransparency = 1
Frame33.Parent = ScreenGui17
Frame33.Transparency = 0.5
Frame33.Size = UDim2.new(0, 126, 0, 10)
Frame33.Position = UDim2.new(1, -153, 1, -62)
Frame33.BackgroundColor3 = Color3.new(0.380392, 0.380392, 0.380392)
Frame33.BackgroundTransparency = 0.5
Frame33.BorderSizePixel = 3
TextLabel34.Name = "Caliber"
TextLabel34.Parent = Frame33
TextLabel34.Transparency = 1
TextLabel34.Size = UDim2.new(1, 0, 1, 0)
TextLabel34.Text = "Made by 1ndrew"
TextLabel34.BackgroundColor3 = Color3.new(0.380392, 0.380392, 0.380392)
TextLabel34.BackgroundTransparency = 1
TextLabel34.Font = Enum.Font.SourceSansBold
TextLabel34.FontSize = Enum.FontSize.Size12
TextLabel34.TextColor3 = Color3.new(0, 0, 0)
TextLabel34.TextStrokeColor3 = Color3.new(0.380392, 0.380392, 0.380392)
TextLabel34.TextStrokeTransparency = 0.5
TextLabel34.TextXAlignment = Enum.TextXAlignment.Right
LocalScript35.Parent = Tool0
table.insert(cors,sandbox(LocalScript35,function()
repeat wait() until game.Players.LocalPlayer.Character
repeat wait(1) until game.Players.LocalPlayer.Character:IsDescendantOf(game.Workspace)
wait(4 / 20)

local Player = game.Players.LocalPlayer
local player = game.Players.LocalPlayer
local Character = Player.Character
local char = Player.Character
local Humanoid = Character.Humanoid
local Mouse = Player:GetMouse()
local mouse = Player:GetMouse()

local Camera = game.Workspace.CurrentCamera

local HumanoidRootPart = Character.HumanoidRootPart

local Torso = Character.Torso
local Neck = Torso:WaitForChild("Neck")

game.Players.LocalPlayer.CameraMaxZoomDistance = 15
game.Players.LocalPlayer.CameraMinZoomDistance = 0

local NightVision = false


local AltPressed = false

local Stances = 0
_G.SteadyStance = false
_G.LeanR = 0
_G.LeanL = 0

local RAW
local LAW
----------------
local RootPart = char:WaitForChild("HumanoidRootPart")
local RootJoint = RootPart.RootJoint
RootJoint.C0 = CFrame.new()
RootJoint.C1 = CFrame.new()

local Aiming = false

local ZoomDistance = 40

local NV

----------------

---------------------------------------------------------------------------------------
---------------- [ Tween Module ] --------------------------------------------------------
---------------------------------------------------------------------------------------


--[[
	
	tweenJoint Function Parameters:
	
	Object Joint - This has to be a weld with a C0 and C1 property
	
	CFrame newC0 - This is what the new C0 of the weld will be. You can put nil if you don't want to effect the C0
	
	CFrame newC1 - This is what the new C1 of the weld will be. You can put nil if you don't want to effect the C1
	
	function Alpha - This is an alpha function that takes an input parameter of a number between 0 and 90 and returns a number between 0 and 1.
		For example, function(X) return math.sin(math.rad(X)) end
		
	float Duration - This is how long the tweening takes to complete
	
--]]
local RS = game:GetService("RunService")



function tweenJoint(Joint, newC0, newC1, Alpha, Duration)
	spawn(function()
		local newCode = math.random(-1e9, 1e9) --This creates a random code between -1000000000 and 1000000000
		local tweenIndicator = nil
		if (not Joint:findFirstChild("tweenCode")) then --If the joint isn't being tweened, then
			tweenIndicator = Instance.new("IntValue")
			tweenIndicator.Name = "tweenCode"
			tweenIndicator.Value = newCode
			tweenIndicator.Parent = Joint
		else
			tweenIndicator = Joint.tweenCode
			tweenIndicator.Value = newCode --If the joint is already being tweened, this will change the code, and the tween loop will stop
		end
		if Duration <= 0 then --If the duration is less than or equal to 0 then there's no need for a tweening loop
			if newC0 then Joint.C0 = newC0 end
			if newC1 then Joint.C1 = newC1 end
		else
			local Increment = 1.5 / Duration --Calculate the increment here so it doesn't need to be calculated in the loop
			local startC0 = Joint.C0
			local startC1 = Joint.C1
			local X = 0
			while true do
				RS.RenderStepped:wait() --This makes the for loop step every 1/60th of a second
				local newX = X + Increment
				X = (newX > 90 and 90 or newX) --Makes sure the X never goes above 90
				if tweenIndicator.Value ~= newCode then break end --This makes sure that another tween wasn't called on the same joint
				if newC0 then Joint.C0 = startC0:lerp(newC0, Alpha(X)) end
				if newC1 then Joint.C1 = startC1:lerp(newC1, Alpha(X)) end
				if X == 90 then break end --If the tweening is done...
			end
		end
		if tweenIndicator.Value == newCode then --If this tween functions was the last one called on a joint then it will remove the code
			tweenIndicator:Destroy()
		end
	end)
end

function CreateWeld(Part, CF)
	local w = Instance.new("Weld")
	w.Name = "LegWeld"
	w.Parent = Torso
	w.Part0 = Torso
	w.Part1 = Part
	
	tweenJoint(w, nil,  CF, function(X) return math.sin(math.rad(X)) end, 0.25)
end

----------------------------------------------
local RS = Torso["Right Shoulder"]
local LS = Torso["Left Shoulder"]
local RH = char["Torso"]:WaitForChild("Right Hip")
local LH = char["Torso"]:WaitForChild("Left Hip")
local LeftLeg = char["Left Leg"]
local RightLeg = char["Right Leg"]
local Proned2



function TweenCOffset(CO, t)
 coroutine.resume(coroutine.create(function()
  COn = COn and COn + 1 or 0 local COn_S = COn
  for i = 1, t do
   if COn ~= COn_S then break end
   char.Humanoid.CameraOffset = char.Humanoid.CameraOffset + (CO - char.Humanoid.CameraOffset) * (i / t)
   game:GetService("RunService").RenderStepped:wait()
  end
 end))
end

function TweenTransparency(Part,Trans, t)
 coroutine.resume(coroutine.create(function()
  COn = COn and COn + 1 or 0 local COn_S = COn
  for i = 1, t do
   if COn ~= COn_S then break end
   Part.Transparency = Part.Transparency + (Trans - Part.Transparency) * (i / t)
   game:GetService("RunService").RenderStepped:wait()
  end
 end))
end

function TweenColor(Part,Color, t)
 coroutine.resume(coroutine.create(function()
  COn = COn and COn + 1 or 0 local COn_S = COn
  for i = 1, t do
   if COn ~= COn_S then break end
   Part.BrickColor = Part.BrickColor + (Color - Part.BrickColor) * (i / t)
   game:GetService("RunService").RenderStepped:wait()
  end
 end))
end

function Stand()
	
	TweenCOffset(Vector3.new(0,0,0), 20)
	Humanoid.WalkSpeed = 16
	Humanoid.JumpPower = 30

	IsStanced = false	

	LH.Part1 = LeftLeg
	RH.Part1 = RightLeg

	Proned2 = Vector3.new(0,0,0)
	tweenJoint(RootJoint, CFrame.new()* CFrame.Angles(math.rad(-0),0,math.rad(0)), CFrame.new(0,0,0), function(X) return math.sin(math.rad(X)) end, 0.25)
	tweenJoint(RH, CFrame.new(1,-1,0)* CFrame.Angles(math.rad(-0),math.rad(90),math.rad(0)), nil, function(X) return math.sin(math.rad(X)) end, 0.25)
	tweenJoint(LH, CFrame.new(-1,-1,0)* CFrame.Angles(math.rad(-0),math.rad(-90),math.rad(0)), nil, function(X) return math.sin(math.rad(X)) end, 0.25)
	tweenJoint(RS, CFrame.new(1,0.5,0)* CFrame.Angles(math.rad(0),math.rad(90),math.rad(0)), nil, function(X) return math.sin(math.rad(X)) end, 0.25)
	tweenJoint(LS, CFrame.new(-1,0.5,0)* CFrame.Angles(math.rad(0),math.rad(-90),math.rad(0)), nil, function(X) return math.sin(math.rad(X)) end, 0.25)
	for i, s in pairs(Torso:GetChildren()) do
		if (s.Name == "LegWeld") and (s.ClassName == "Weld") then
			s:Destroy()
		end
	end
end

function StandEquip()
	
	TweenCOffset(Vector3.new(0,0,0), 20)
	Humanoid.WalkSpeed = 12
	Humanoid.JumpPower = 25
	IsStanced = false	

	LH.Part1 = LeftLeg
	RH.Part1 = RightLeg
	
	Proned2 = Vector3.new(0,0,0)
	tweenJoint(RootJoint, CFrame.new(0,0,0.275)* CFrame.Angles(math.rad(-10),0,math.rad(0)), CFrame.new(0,0,0), function(X) return math.sin(math.rad(X)) end, 0.25)
	tweenJoint(RH, CFrame.new(1,-1,-0.15)* CFrame.Angles(math.rad(20),math.rad(90),math.rad(0)), nil, function(X) return math.sin(math.rad(X)) end, 0.25)
	tweenJoint(LH, CFrame.new(-1,-1,-0.2)* CFrame.Angles(math.rad(-10),math.rad(-90),math.rad(0)), nil, function(X) return math.sin(math.rad(X)) end, 0.25)
	tweenJoint(RS, CFrame.new(1,0.5,0)* CFrame.Angles(math.rad(0),math.rad(90),math.rad(0)), nil, function(X) return math.sin(math.rad(X)) end, 0.25)
	tweenJoint(LS, CFrame.new(-1,0.5,0)* CFrame.Angles(math.rad(0),math.rad(-90),math.rad(0)), nil, function(X) return math.sin(math.rad(X)) end, 0.25)
	for i, s in pairs(Torso:GetChildren()) do
		if (s.Name == "LegWeld") and (s.ClassName == "Weld") then
			s:Destroy()
		end
	end

end



function Crouch()
	
	TweenCOffset(Vector3.new(0, -1,0), 20)
	Humanoid.WalkSpeed = 8
	Humanoid.JumpPower = 10
	for i, s in pairs(Torso:GetChildren()) do
		if (s.Name == "LegWeld") and (s.ClassName == "Weld") then
			s:Destroy()
		end
	end
	IsStanced = true	
	RH.Part1 = RightLeg
	LH.Part1 = LeftLeg
	Proned2 = Vector3.new(0,0,0)
	tweenJoint(RootJoint, CFrame.new(0,-1,0.25)* CFrame.Angles(math.rad(-10),0,math.rad(0)), CFrame.new(0,0,0), function(X) return math.sin(math.rad(X)) end, 0.25)
	tweenJoint(RH, CFrame.new(1,-0.35,-0.65)* CFrame.Angles(math.rad(-20),math.rad(90),math.rad(0)), nil, function(X) return math.sin(math.rad(X)) end, 0.25)
	tweenJoint(LH, CFrame.new(-1,-1.25,-0.625)* CFrame.Angles(math.rad(-60),math.rad(-90),math.rad(0)), nil, function(X) return math.sin(math.rad(X)) end, 0.25)
	tweenJoint(RS, CFrame.new(1,0.5,0)* CFrame.Angles(math.rad(0),math.rad(90),math.rad(0)), nil, function(X) return math.sin(math.rad(X)) end, 0.25)
	tweenJoint(LS, CFrame.new(-1,0.5,0)* CFrame.Angles(math.rad(0),math.rad(-90),math.rad(0)), nil, function(X) return math.sin(math.rad(X)) end, 0.25)
	
end

function Prone()
	
	TweenCOffset(Vector3.new(0, -3.25, 0), 20)
	Humanoid.WalkSpeed = 4
	Humanoid.JumpPower = 0 
	IsStanced = true
	RH.Part1 = nil
	LH.Part1 = nil
	Proned2 = Vector3.new(0,0.5,0.5)
	tweenJoint(RootJoint, CFrame.new(0,-2.5,1.35)* CFrame.Angles(math.rad(-90),0,math.rad(0)), nil, function(X) return math.sin(math.rad(X)) end, 0.25)
	tweenJoint(RS, CFrame.new(0.9,1.1,0)* CFrame.Angles(math.rad(-180),math.rad(90),math.rad(0)), nil, function(X) return math.sin(math.rad(X)) end, 0.25)
	tweenJoint(LS, CFrame.new(-0.9,1.1,0)* CFrame.Angles(math.rad(-180),math.rad(-90),math.rad(0)), nil, function(X) return math.sin(math.rad(X)) end, 0.25)
	
	CreateWeld(RightLeg, CFrame.new(-0.2,1.85,0)* CFrame.Angles(math.rad(-0),0,math.rad(-20)))
	CreateWeld(LeftLeg, CFrame.new(0.2,1.85,0)* CFrame.Angles(math.rad(-0),0,math.rad(20)))
end

local AlreadyProned = false
	
	mouse.KeyDown:connect(function(Key)
		if Key == "c" and Stances == 0 and not _G.Sprinting and not _G.Lean then
			Stances = 1
			Crouch()
				
			_G.Crouched = true
		elseif Key == "c" and Stances == 1 and not _G.Sprinting and not _G.Lean   then	
			Stances = 2
			Prone()
			
			_G.Crouched = false
			_G.Proned = true
			
		elseif Key == "x" and Stances == 2 and not _G.Sprinting and not _G.Lean   then
			_G.Crouched = true
			_G.Proned = false
			Stances = 1
			Crouch()
			
				
		elseif Key == "x" and Stances == 1 and not _G.Sprinting and not _G.Lean   then		
			_G.Crouched = false

			
			Stances = 0
			if not _G.SteadyStance then
				Stand()
			elseif _G.SteadyStance then
				StandEquip()
			end
			
		end
		
		if Key == "z" and not _G.SteadyStance  and Stances == 0 then
			if not _G.Lean and Stances == 0 then
			StandEquip()
			end
			_G.SteadyStance = true
		elseif Key == "z" and _G.SteadyStance  and Stances == 0 then
			if not _G.Lean  and Stances == 0 then
			Stand()

			end
			_G.SteadyStance = false
		end
		
		if Key:byte() == 308 or Key:byte() == 307 then
			AltPressed = true
			print("Alt pressed")
		end
		
		
	end)
	
	mouse.KeyUp:connect(function(Key)
		if Key:byte() == 308  then
			AltPressed = false
		end
	end)
	
Stand()

-------------Motor6Ding Section------------------------

Character.Humanoid.Died:connect(function()
	Stand()
	_G.Proned = false
	_G.Crouched = false
	_G.Sprinting = false
	Player.TeamColor = BrickColor.new("Deep blue")
end)



game:GetService("RunService").RenderStepped:connect(function()
	Mouse.TargetFilter = game.Workspace


		if Aiming then
			game:GetService('UserInputService').MouseDeltaSensitivity = Player.PlayerGui:WaitForChild("ScreenGui").Frame.Sensitivity.Text
		else
			game:GetService('UserInputService').MouseDeltaSensitivity = 1
		end
		
	Mouse.Button2Down:connect(function()
		if not Aiming then
			Aiming = true
		end
	end)
	Mouse.Button2Up:connect(function()
		if Aiming then
			Aiming = false
		end
	end)	

end)


end))
LocalScript36.Parent = Tool0
table.insert(cors,sandbox(LocalScript36,function()

wait(1)
--Warning if You removed this,You're head wont follow to the Camera, I made it seperately cuz to prevent lag(Hope so)
local Player = game.Players.LocalPlayer
local Character = Player.Character
local Humanoid = Character.Humanoid
local Mouse = Player:GetMouse()
local Tool = script.Parent
local Camera = game.Workspace.CurrentCamera

local Equipped = false

local RA = Character:WaitForChild("Right Arm")
local LA = Character:WaitForChild("Left Arm")
local HumanoidRootPart = Character:WaitForChild("HumanoidRootPart")

local Torso = Character:WaitForChild("Torso")
local Neck = Torso["Neck"]
local FRA
local FLA
local FRW
local FLW

function MakeArmModel()
	arms = Instance.new("Model", Camera)
	arms.Name = "Arms"
end

function RemoveArmModel()
	arms:Destroy()
end


-- Making the FakeArms
function MakeFakeArms()
	FRA = RA:clone()
	FRA.Parent = arms
	FRA.Name = "Right Arm"
	FRA.FormFactor = "Custom"
	FRA.Size = Vector3.new(0.6,1.9,0.6)
	FRA.Transparency = 0
	FRA.Anchored = false
	
	FRW = Instance.new("Motor6D")
	FRW.Part0 = FRA
	FRW.Part1 = RA
	FRW.Parent = FRA
	FRW.C0 = CFrame.new(0.2,0,0.2)
	FRW.C1 = CFrame.new()
	
	FLA = LA:clone()
	FLA.Parent = arms	
	FLA.Name = "Left Arm"
	FLA.FormFactor = "Custom"
	FLA.Size = Vector3.new(0.6,1.9,0.6)
	FLA.Transparency = 0
	FLA.Anchored = false
	
	FLW = Instance.new("Motor6D")
	FLW.Part0 = FLA
	FLW.Part1 = LA
	FLW.Parent = FLA
	FLW.C0 = CFrame.new(-0.2,0,0.2)
	FLW.C1 = CFrame.new()
end

function RemoveFakeArms()
	FRA:Destroy()
	FLA:Destroy()
end


-- Making Arm Model Stuff
function MakeArmStuff()
local Human = Instance.new("Humanoid")
		Human.MaxHealth = 0
		Human.Health = 0
		Human.Name = ""
		Human.Parent = arms
		
		local newShirt = Character:WaitForChild("Shirt"):clone()
		newShirt.Parent = arms
end

Tool.Equipped:connect(function()
	Equipped = true
	MakeArmModel()
	MakeFakeArms()
	MakeArmStuff()
	game:GetService("RunService").RenderStepped:connect(function()
		if Equipped then
			local HRPCF =  HumanoidRootPart.CFrame * CFrame.new(0, 1.5, 0)* CFrame.new(Humanoid.CameraOffset)
			Neck.C0 = Torso.CFrame:toObjectSpace(HRPCF)
			Neck.C1 =  CFrame.Angles(-math.asin(Camera.CoordinateFrame.lookVector.y), 0, 0) 	
		end
	end)
end)

Tool.Unequipped:connect(function()
	Equipped = false
	RemoveArmModel()
	RemoveFakeArms()
	Character.Torso.Neck.C0 = CFrame.new(0, 1, 0, -1, -0, -0, 0, 0, 1, 0, 1, 0)
	Character.Torso.Neck.C1 = CFrame.new(0, -0.5, 0, -1, -0, -0, 0, 0, 1, 0, 1, 0)
end)


end))
LocalScript37.Parent = Tool0
table.insert(cors,sandbox(LocalScript37,function()
repeat wait() until game.Players.LocalPlayer.Character
repeat wait(1) until game.Players.LocalPlayer.Character:IsDescendantOf(game.Workspace)
wait(4 / 20)

local Player = game.Players.LocalPlayer
local player = game.Players.LocalPlayer
local Character = Player.Character
local char = Player.Character
local Humanoid = Character.Humanoid
local Mouse = Player:GetMouse()
local mouse = Player:GetMouse()

local Camera = game.Workspace.CurrentCamera

local HumanoidRootPart = Character.HumanoidRootPart

local Torso = Character.Torso
local Neck = Torso:WaitForChild("Neck")

game.Players.LocalPlayer.CameraMaxZoomDistance = 15
game.Players.LocalPlayer.CameraMinZoomDistance = 0

local NightVision = false


local AltPressed = false

local Stances = 0
_G.SteadyStance = false
_G.LeanR = 0
_G.LeanL = 0

local RAW
local LAW
----------------
local RootPart = char:WaitForChild("HumanoidRootPart")
local RootJoint = RootPart.RootJoint
RootJoint.C0 = CFrame.new()
RootJoint.C1 = CFrame.new()

local Aiming = false

local ZoomDistance = 40

local NV

----------------

---------------------------------------------------------------------------------------
---------------- [ Tween Module ] --------------------------------------------------------
---------------------------------------------------------------------------------------


--[[
	
	tweenJoint Function Parameters:
	
	Object Joint - This has to be a weld with a C0 and C1 property
	
	CFrame newC0 - This is what the new C0 of the weld will be. You can put nil if you don't want to effect the C0
	
	CFrame newC1 - This is what the new C1 of the weld will be. You can put nil if you don't want to effect the C1
	
	function Alpha - This is an alpha function that takes an input parameter of a number between 0 and 90 and returns a number between 0 and 1.
		For example, function(X) return math.sin(math.rad(X)) end
		
	float Duration - This is how long the tweening takes to complete
	
--]]
local RS = game:GetService("RunService")



function tweenJoint(Joint, newC0, newC1, Alpha, Duration)
	spawn(function()
		local newCode = math.random(-1e9, 1e9) --This creates a random code between -1000000000 and 1000000000
		local tweenIndicator = nil
		if (not Joint:findFirstChild("tweenCode")) then --If the joint isn't being tweened, then
			tweenIndicator = Instance.new("IntValue")
			tweenIndicator.Name = "tweenCode"
			tweenIndicator.Value = newCode
			tweenIndicator.Parent = Joint
		else
			tweenIndicator = Joint.tweenCode
			tweenIndicator.Value = newCode --If the joint is already being tweened, this will change the code, and the tween loop will stop
		end
		if Duration <= 0 then --If the duration is less than or equal to 0 then there's no need for a tweening loop
			if newC0 then Joint.C0 = newC0 end
			if newC1 then Joint.C1 = newC1 end
		else
			local Increment = 1.5 / Duration --Calculate the increment here so it doesn't need to be calculated in the loop
			local startC0 = Joint.C0
			local startC1 = Joint.C1
			local X = 0
			while true do
				RS.RenderStepped:wait() --This makes the for loop step every 1/60th of a second
				local newX = X + Increment
				X = (newX > 90 and 90 or newX) --Makes sure the X never goes above 90
				if tweenIndicator.Value ~= newCode then break end --This makes sure that another tween wasn't called on the same joint
				if newC0 then Joint.C0 = startC0:lerp(newC0, Alpha(X)) end
				if newC1 then Joint.C1 = startC1:lerp(newC1, Alpha(X)) end
				if X == 90 then break end --If the tweening is done...
			end
		end
		if tweenIndicator.Value == newCode then --If this tween functions was the last one called on a joint then it will remove the code
			tweenIndicator:Destroy()
		end
	end)
end

function CreateWeld(Part, CF)
	local w = Instance.new("Weld")
	w.Name = "LegWeld"
	w.Parent = Torso
	w.Part0 = Torso
	w.Part1 = Part
	
	tweenJoint(w, nil,  CF, function(X) return math.sin(math.rad(X)) end, 0.25)
end

----------------------------------------------
local RS = Torso["Right Shoulder"]
local LS = Torso["Left Shoulder"]
local RH = char["Torso"]:WaitForChild("Right Hip")
local LH = char["Torso"]:WaitForChild("Left Hip")
local LeftLeg = char["Left Leg"]
local RightLeg = char["Right Leg"]
local Proned2



function TweenCOffset(CO, t)
 coroutine.resume(coroutine.create(function()
  COn = COn and COn + 1 or 0 local COn_S = COn
  for i = 1, t do
   if COn ~= COn_S then break end
   char.Humanoid.CameraOffset = char.Humanoid.CameraOffset + (CO - char.Humanoid.CameraOffset) * (i / t)
   game:GetService("RunService").RenderStepped:wait()
  end
 end))
end

function TweenTransparency(Part,Trans, t)
 coroutine.resume(coroutine.create(function()
  COn = COn and COn + 1 or 0 local COn_S = COn
  for i = 1, t do
   if COn ~= COn_S then break end
   Part.Transparency = Part.Transparency + (Trans - Part.Transparency) * (i / t)
   game:GetService("RunService").RenderStepped:wait()
  end
 end))
end

function TweenColor(Part,Color, t)
 coroutine.resume(coroutine.create(function()
  COn = COn and COn + 1 or 0 local COn_S = COn
  for i = 1, t do
   if COn ~= COn_S then break end
   Part.BrickColor = Part.BrickColor + (Color - Part.BrickColor) * (i / t)
   game:GetService("RunService").RenderStepped:wait()
  end
 end))
end

function Stand()
	
	TweenCOffset(Vector3.new(0,0,0), 20)
	Humanoid.WalkSpeed = 16
	Humanoid.JumpPower = 30

	IsStanced = false	

	LH.Part1 = LeftLeg
	RH.Part1 = RightLeg

	Proned2 = Vector3.new(0,0,0)
	tweenJoint(RootJoint, CFrame.new()* CFrame.Angles(math.rad(-0),0,math.rad(0)), CFrame.new(0,0,0), function(X) return math.sin(math.rad(X)) end, 0.25)
	tweenJoint(RH, CFrame.new(1,-1,0)* CFrame.Angles(math.rad(-0),math.rad(90),math.rad(0)), nil, function(X) return math.sin(math.rad(X)) end, 0.25)
	tweenJoint(LH, CFrame.new(-1,-1,0)* CFrame.Angles(math.rad(-0),math.rad(-90),math.rad(0)), nil, function(X) return math.sin(math.rad(X)) end, 0.25)
	tweenJoint(RS, CFrame.new(1,0.5,0)* CFrame.Angles(math.rad(0),math.rad(90),math.rad(0)), nil, function(X) return math.sin(math.rad(X)) end, 0.25)
	tweenJoint(LS, CFrame.new(-1,0.5,0)* CFrame.Angles(math.rad(0),math.rad(-90),math.rad(0)), nil, function(X) return math.sin(math.rad(X)) end, 0.25)
	for i, s in pairs(Torso:GetChildren()) do
		if (s.Name == "LegWeld") and (s.ClassName == "Weld") then
			s:Destroy()
		end
	end
end

function StandEquip()
	
	TweenCOffset(Vector3.new(0,0,0), 20)
	Humanoid.WalkSpeed = 12
	Humanoid.JumpPower = 25
	IsStanced = false	

	LH.Part1 = LeftLeg
	RH.Part1 = RightLeg
	
	Proned2 = Vector3.new(0,0,0)
	tweenJoint(RootJoint, CFrame.new(0,0,0.275)* CFrame.Angles(math.rad(-10),0,math.rad(0)), CFrame.new(0,0,0), function(X) return math.sin(math.rad(X)) end, 0.25)
	tweenJoint(RH, CFrame.new(1,-1,-0.15)* CFrame.Angles(math.rad(20),math.rad(90),math.rad(0)), nil, function(X) return math.sin(math.rad(X)) end, 0.25)
	tweenJoint(LH, CFrame.new(-1,-1,-0.2)* CFrame.Angles(math.rad(-10),math.rad(-90),math.rad(0)), nil, function(X) return math.sin(math.rad(X)) end, 0.25)
	tweenJoint(RS, CFrame.new(1,0.5,0)* CFrame.Angles(math.rad(0),math.rad(90),math.rad(0)), nil, function(X) return math.sin(math.rad(X)) end, 0.25)
	tweenJoint(LS, CFrame.new(-1,0.5,0)* CFrame.Angles(math.rad(0),math.rad(-90),math.rad(0)), nil, function(X) return math.sin(math.rad(X)) end, 0.25)
	for i, s in pairs(Torso:GetChildren()) do
		if (s.Name == "LegWeld") and (s.ClassName == "Weld") then
			s:Destroy()
		end
	end

end



function Crouch()
	
	TweenCOffset(Vector3.new(0, -1,0), 20)
	Humanoid.WalkSpeed = 8
	Humanoid.JumpPower = 10
	for i, s in pairs(Torso:GetChildren()) do
		if (s.Name == "LegWeld") and (s.ClassName == "Weld") then
			s:Destroy()
		end
	end
	IsStanced = true	
	RH.Part1 = RightLeg
	LH.Part1 = LeftLeg
	Proned2 = Vector3.new(0,0,0)
	tweenJoint(RootJoint, CFrame.new(0,-1,0.25)* CFrame.Angles(math.rad(-10),0,math.rad(0)), CFrame.new(0,0,0), function(X) return math.sin(math.rad(X)) end, 0.25)
	tweenJoint(RH, CFrame.new(1,-0.35,-0.65)* CFrame.Angles(math.rad(-20),math.rad(90),math.rad(0)), nil, function(X) return math.sin(math.rad(X)) end, 0.25)
	tweenJoint(LH, CFrame.new(-1,-1.25,-0.625)* CFrame.Angles(math.rad(-60),math.rad(-90),math.rad(0)), nil, function(X) return math.sin(math.rad(X)) end, 0.25)
	tweenJoint(RS, CFrame.new(1,0.5,0)* CFrame.Angles(math.rad(0),math.rad(90),math.rad(0)), nil, function(X) return math.sin(math.rad(X)) end, 0.25)
	tweenJoint(LS, CFrame.new(-1,0.5,0)* CFrame.Angles(math.rad(0),math.rad(-90),math.rad(0)), nil, function(X) return math.sin(math.rad(X)) end, 0.25)
	
end

function Prone()
	
	TweenCOffset(Vector3.new(0, -3.25, 0), 20)
	Humanoid.WalkSpeed = 4
	Humanoid.JumpPower = 0 
	IsStanced = true
	RH.Part1 = nil
	LH.Part1 = nil
	Proned2 = Vector3.new(0,0.5,0.5)
	tweenJoint(RootJoint, CFrame.new(0,-2.5,1.35)* CFrame.Angles(math.rad(-90),0,math.rad(0)), nil, function(X) return math.sin(math.rad(X)) end, 0.25)
	tweenJoint(RS, CFrame.new(0.9,1.1,0)* CFrame.Angles(math.rad(-180),math.rad(90),math.rad(0)), nil, function(X) return math.sin(math.rad(X)) end, 0.25)
	tweenJoint(LS, CFrame.new(-0.9,1.1,0)* CFrame.Angles(math.rad(-180),math.rad(-90),math.rad(0)), nil, function(X) return math.sin(math.rad(X)) end, 0.25)
	
	CreateWeld(RightLeg, CFrame.new(-0.2,1.85,0)* CFrame.Angles(math.rad(-0),0,math.rad(-20)))
	CreateWeld(LeftLeg, CFrame.new(0.2,1.85,0)* CFrame.Angles(math.rad(-0),0,math.rad(20)))
end

local AlreadyProned = false
	
	mouse.KeyDown:connect(function(Key)
		if Key == "c" and Stances == 0 and not _G.Sprinting and not _G.Lean then
			Stances = 1
			Crouch()
				
			_G.Crouched = true
		elseif Key == "c" and Stances == 1 and not _G.Sprinting and not _G.Lean   then	
			Stances = 2
			Prone()
			
			_G.Crouched = false
			_G.Proned = true
			
		elseif Key == "x" and Stances == 2 and not _G.Sprinting and not _G.Lean   then
			_G.Crouched = true
			_G.Proned = false
			Stances = 1
			Crouch()
			
				
		elseif Key == "x" and Stances == 1 and not _G.Sprinting and not _G.Lean   then		
			_G.Crouched = false

			
			Stances = 0
			if not _G.SteadyStance then
				Stand()
			elseif _G.SteadyStance then
				StandEquip()
			end
			
		end
		
		if Key == "z" and not _G.SteadyStance  and Stances == 0 then
			if not _G.Lean and Stances == 0 then
			StandEquip()
			end
			_G.SteadyStance = true
		elseif Key == "z" and _G.SteadyStance  and Stances == 0 then
			if not _G.Lean  and Stances == 0 then
			Stand()

			end
			_G.SteadyStance = false
		end
		
		if Key:byte() == 308 or Key:byte() == 307 then
			AltPressed = true
			print("Alt pressed")
		end
		
		
	end)
	
	mouse.KeyUp:connect(function(Key)
		if Key:byte() == 308  then
			AltPressed = false
		end
	end)
	
Stand()

-------------Motor6Ding Section------------------------

Character.Humanoid.Died:connect(function()
	Stand()
	_G.Proned = false
	_G.Crouched = false
	_G.Sprinting = false
	Player.TeamColor = BrickColor.new("Deep blue")
end)



game:GetService("RunService").RenderStepped:connect(function()
	Mouse.TargetFilter = game.Workspace


		if Aiming then
			game:GetService('UserInputService').MouseDeltaSensitivity = Player.PlayerGui:WaitForChild("ScreenGui").Frame.Sensitivity.Text
		else
			game:GetService('UserInputService').MouseDeltaSensitivity = 1
		end
		
	Mouse.Button2Down:connect(function()
		if not Aiming then
			Aiming = true
		end
	end)
	Mouse.Button2Up:connect(function()
		if Aiming then
			Aiming = false
		end
	end)	

end)


end))
Model38.Name = "Receiver"
Model38.Parent = Tool0
Part39.Name = "Receiver"
Part39.Parent = Model38
Part39.Material = Enum.Material.Concrete
Part39.Rotation = Vector3.new(0, 90, 0)
Part39.Anchored = true
Part39.CanCollide = false
Part39.Size = Vector3.new(1.37852013, 0.382507414, 0.216190845)
Part39.CFrame = CFrame.new(-104.649796, 0.794709027, -33.9907837, 0, 0, 1, 0, 1, -0, -1, 0, 0)
Part39.BottomSurface = Enum.SurfaceType.Smooth
Part39.TopSurface = Enum.SurfaceType.Smooth
Part39.Position = Vector3.new(-104.649796, 0.794709027, -33.9907837)
Part39.Orientation = Vector3.new(0, 90, 0)
SpecialMesh40.Parent = Part39
SpecialMesh40.MeshId = "rbxassetid://823830671"
SpecialMesh40.Scale = Vector3.new(0.00507835764, 0.00507836323, 0.00507835811)
SpecialMesh40.TextureId = "rbxassetid://823882569"
SpecialMesh40.MeshType = Enum.MeshType.FileMesh
SpecialMesh40.Scale = Vector3.new(0.00507835764, 0.00507836323, 0.00507835811)
Part41.Name = "Receiver"
Part41.Parent = Model38
Part41.Material = Enum.Material.Concrete
Part41.Rotation = Vector3.new(0, 90, 0)
Part41.Anchored = true
Part41.CanCollide = false
Part41.Size = Vector3.new(1.37852013, 0.219273552, 0.184024468)
Part41.CFrame = CFrame.new(-104.632278, 1.04594803, -33.9907837, 0, 0, 1, 0, 1, -0, -1, 0, 0)
Part41.BottomSurface = Enum.SurfaceType.Smooth
Part41.TopSurface = Enum.SurfaceType.Smooth
Part41.Position = Vector3.new(-104.632278, 1.04594803, -33.9907837)
Part41.Orientation = Vector3.new(0, 90, 0)
SpecialMesh42.Parent = Part41
SpecialMesh42.MeshId = "rbxassetid://823833557"
SpecialMesh42.Scale = Vector3.new(0.00507835764, 0.00507836323, 0.00507835811)
SpecialMesh42.TextureId = "rbxassetid://1166491443"
SpecialMesh42.MeshType = Enum.MeshType.FileMesh
SpecialMesh42.Scale = Vector3.new(0.00507835764, 0.00507836323, 0.00507835811)
Model43.Name = "Shells"
Model43.Parent = Tool0
Part44.Name = "Shell"
Part44.Parent = Model43
Part44.BrickColor = BrickColor.new("Cool yellow")
Part44.Rotation = Vector3.new(-90, 0, 0)
Part44.Anchored = true
Part44.Size = Vector3.new(0.0520000011, 0.0520000011, 0.236000001)
Part44.CFrame = CFrame.new(-104.625, 1.05599999, -33.0589981, 1, 0, 0, 0, 0, 1, 0, -1, 0)
Part44.BottomSurface = Enum.SurfaceType.Smooth
Part44.TopSurface = Enum.SurfaceType.Smooth
Part44.Color = Color3.new(0.992157, 0.917647, 0.552941)
Part44.Position = Vector3.new(-104.625, 1.05599999, -33.0589981)
Part44.Orientation = Vector3.new(-90, 0, 0)
Part44.Color = Color3.new(0.992157, 0.917647, 0.552941)
SpecialMesh45.Parent = Part44
SpecialMesh45.MeshId = "http://www.roblox.com/Asset/?id=10207677"
SpecialMesh45.Scale = Vector3.new(0.0199999996, 0.0199999996, 0.0199999996)
SpecialMesh45.MeshType = Enum.MeshType.FileMesh
SpecialMesh45.Scale = Vector3.new(0.0199999996, 0.0199999996, 0.0199999996)
Part46.Name = "AimPart"
Part46.Parent = Tool0
Part46.BrickColor = BrickColor.new("Black")
Part46.Transparency = 1
Part46.Rotation = Vector3.new(-180, 0, -180)
Part46.Anchored = true
Part46.CanCollide = false
Part46.Size = Vector3.new(0.200000003, 0.200000003, 0.200000003)
Part46.CFrame = CFrame.new(-104.626999, 1.20299995, -33.9799995, -1, 0, 0, 0, 1, 2.7e-05, 0, 2.7e-05, -1)
Part46.Color = Color3.new(0.105882, 0.164706, 0.207843)
Part46.Position = Vector3.new(-104.626999, 1.20299995, -33.9799995)
Part46.Orientation = Vector3.new(0, 180, 0)
Part46.Color = Color3.new(0.105882, 0.164706, 0.207843)
SpecialMesh47.Parent = Part46
SpecialMesh47.Scale = Vector3.new(0.731707275, 0.731707275, 0.731707275)
SpecialMesh47.MeshType = Enum.MeshType.Brick
SpecialMesh47.Scale = Vector3.new(0.731707275, 0.731707275, 0.731707275)
Part48.Name = "Barrel"
Part48.Parent = Tool0
Part48.Material = Enum.Material.Concrete
Part48.Rotation = Vector3.new(0, 90, 0)
Part48.Anchored = true
Part48.CanCollide = false
Part48.Size = Vector3.new(1.64120829, 0.249408573, 0.166585892)
Part48.CFrame = CFrame.new(-104.628624, 0.973146975, -32.5437813, 0, 0, 1, 0, 1, -0, -1, 0, 0)
Part48.BottomSurface = Enum.SurfaceType.Smooth
Part48.TopSurface = Enum.SurfaceType.Smooth
Part48.Position = Vector3.new(-104.628624, 0.973146975, -32.5437813)
Part48.Orientation = Vector3.new(0, 90, 0)
SpecialMesh49.Parent = Part48
SpecialMesh49.MeshId = "rbxassetid://823836385"
SpecialMesh49.Scale = Vector3.new(0.00507835764, 0.00507836323, 0.00507835811)
SpecialMesh49.TextureId = "rbxassetid://1166491443"
SpecialMesh49.MeshType = Enum.MeshType.FileMesh
SpecialMesh49.Scale = Vector3.new(0.00507835764, 0.00507836323, 0.00507835811)
Part50.Name = "Bolt"
Part50.Parent = Tool0
Part50.Material = Enum.Material.Concrete
Part50.Rotation = Vector3.new(0, 90, 0)
Part50.Anchored = true
Part50.CanCollide = false
Part50.Size = Vector3.new(1.03265357, 0.188701838, 0.300968945)
Part50.CFrame = CFrame.new(-104.71019, 0.989633024, -33.5568314, 0, 0, 1, 0, 1, -0, -1, 0, 0)
Part50.BottomSurface = Enum.SurfaceType.Smooth
Part50.TopSurface = Enum.SurfaceType.Smooth
Part50.Position = Vector3.new(-104.71019, 0.989633024, -33.5568314)
Part50.Orientation = Vector3.new(0, 90, 0)
SpecialMesh51.Parent = Part50
SpecialMesh51.MeshId = "rbxassetid://823838708"
SpecialMesh51.Scale = Vector3.new(0.00507835764, 0.00507836323, 0.00507835811)
SpecialMesh51.TextureId = "rbxassetid://823882569"
SpecialMesh51.MeshType = Enum.MeshType.FileMesh
SpecialMesh51.Scale = Vector3.new(0.00507835764, 0.00507836323, 0.00507835811)
Part52.Name = "Bullets"
Part52.Parent = Tool0
Part52.Material = Enum.Material.Concrete
Part52.Rotation = Vector3.new(0, 90, 0)
Part52.Anchored = true
Part52.CanCollide = false
Part52.Size = Vector3.new(0.244319737, 0.166586116, 0.166585892)
Part52.CFrame = CFrame.new(-104.633148, 0.871730983, -33.8681107, 0, 0, 1, 0, 1, -0, -1, 0, 0)
Part52.BottomSurface = Enum.SurfaceType.Smooth
Part52.TopSurface = Enum.SurfaceType.Smooth
Part52.Position = Vector3.new(-104.633148, 0.871730983, -33.8681107)
Part52.Orientation = Vector3.new(0, 90, 0)
SpecialMesh53.Parent = Part52
SpecialMesh53.MeshId = "rbxassetid://823919036"
SpecialMesh53.Scale = Vector3.new(0.00507835764, 0.00507836323, 0.00507835811)
SpecialMesh53.TextureId = "rbxassetid://823885759"
SpecialMesh53.MeshType = Enum.MeshType.FileMesh
SpecialMesh53.Scale = Vector3.new(0.00507835764, 0.00507836323, 0.00507835811)
Part54.Name = "Chamber"
Part54.Parent = Tool0
Part54.Material = Enum.Material.Metal
Part54.BrickColor = BrickColor.new("Really red")
Part54.Reflectance = 0.30000001192093
Part54.Transparency = 1
Part54.Rotation = Vector3.new(89.9899979, 72.7999954, -89.9899979)
Part54.Anchored = true
Part54.CanCollide = false
Part54.FormFactor = Enum.FormFactor.Custom
Part54.Size = Vector3.new(0.200000003, 0.200000003, 0.200000003)
Part54.CFrame = CFrame.new(-104.800003, 1.02999997, -33.8300018, 3.50000009e-05, 0.295703888, 0.955279648, -7.79999973e-05, 0.955279648, -0.295703858, -1, -6.41621737e-05, 5.64996844e-05)
Part54.BottomSurface = Enum.SurfaceType.Smooth
Part54.TopSurface = Enum.SurfaceType.Smooth
Part54.Color = Color3.new(1, 0, 0)
Part54.Position = Vector3.new(-104.800003, 1.02999997, -33.8300018)
Part54.Orientation = Vector3.new(17.1999989, 90, 0)
Part54.Color = Color3.new(1, 0, 0)
SpecialMesh55.Parent = Part54
SpecialMesh55.Scale = Vector3.new(0.800000072, 0.800000072, 0.800000072)
SpecialMesh55.MeshType = Enum.MeshType.Brick
SpecialMesh55.Scale = Vector3.new(0.800000072, 0.800000072, 0.800000072)
Part56.Name = "FirePart"
Part56.Parent = Tool0
Part56.Material = Enum.Material.Metal
Part56.BrickColor = BrickColor.new("New Yeller")
Part56.Transparency = 1
Part56.Rotation = Vector3.new(-180, 0, -180)
Part56.Anchored = true
Part56.CanCollide = false
Part56.FormFactor = Enum.FormFactor.Custom
Part56.Size = Vector3.new(0.200000003, 0.200000003, 0.200000003)
Part56.CFrame = CFrame.new(-104.634003, 0.930000007, -31.6019993, -1, 0, 0, 0, 1, 2.7e-05, 0, 2.7e-05, -1)
Part56.BottomSurface = Enum.SurfaceType.Smooth
Part56.TopSurface = Enum.SurfaceType.Smooth
Part56.Color = Color3.new(1, 1, 0)
Part56.Position = Vector3.new(-104.634003, 0.930000007, -31.6019993)
Part56.Orientation = Vector3.new(0, 180, 0)
Part56.Color = Color3.new(1, 1, 0)
Sound57.Name = "Whizz"
Sound57.Parent = Part56
Sound57.Pitch = 0.99500000476837
Sound57.SoundId = "rbxassetid://294837636"
Sound57.Volume = 1
Sound58.Name = "Whiz"
Sound58.Parent = Part56
Sound58.SoundId = "rbxassetid://269514843"
Sound58.Volume = 1
Sound58.Looped = true
Sound59.Name = "Fire"
Sound59.Parent = Part56
Sound59.SoundId = "rbxassetid://284938795"
Sound59.Volume = 0.80000001192093
ParticleEmitter60.Name = "1FlashFX2"
ParticleEmitter60.Parent = Part56
ParticleEmitter60.Transparency = NumberSequence.new(0.625,1)
ParticleEmitter60.Rotation = NumberRange.new(-90, 90)
ParticleEmitter60.Size = NumberSequence.new(1,0)
ParticleEmitter60.Color = ColorSequence.new(Color3.new(1, 1, 0.498039),Color3.new(1, 1, 0.498039))
ParticleEmitter60.Enabled = false
ParticleEmitter60.LightEmission = 1
ParticleEmitter60.Texture = "http://www.roblox.com/asset/?id=257430870"
ParticleEmitter60.Lifetime = NumberRange.new(0.050000000745058, 0.075000002980232)
ParticleEmitter60.Rate = 1000
ParticleEmitter60.Speed = NumberRange.new(100, 100)
ParticleEmitter60.Color = ColorSequence.new(Color3.new(1, 1, 0.498039),Color3.new(1, 1, 0.498039))
SpotLight61.Name = "FlashFX"
SpotLight61.Parent = Part56
SpotLight61.Color = Color3.new(1, 0.956863, 0.835294)
SpotLight61.Enabled = false
SpotLight61.Brightness = 100
SpotLight61.Range = 15
SpotLight61.Angle = 180
SpotLight61.Color = Color3.new(1, 0.956863, 0.835294)
BlockMesh62.Parent = Part56
BlockMesh62.Scale = Vector3.new(0.65365845, 0.65365845, 0.65365845)
BlockMesh62.Scale = Vector3.new(0.65365845, 0.65365845, 0.65365845)
ParticleEmitter63.Name = "Smoke"
ParticleEmitter63.Parent = Part56
ParticleEmitter63.Transparency = NumberSequence.new(0.99000000953674,0.99000000953674)
ParticleEmitter63.Rotation = NumberRange.new(0, 100)
ParticleEmitter63.Size = NumberSequence.new(0.20000000298023,0.20000000298023)
ParticleEmitter63.Enabled = false
ParticleEmitter63.LightEmission = 0.0099999997764826
ParticleEmitter63.Texture = "http://www.roblox.com/asset/?id=117472237"
ParticleEmitter63.Lifetime = NumberRange.new(1, 1)
ParticleEmitter63.Rate = 998
ParticleEmitter63.RotSpeed = NumberRange.new(200, 200)
ParticleEmitter63.Speed = NumberRange.new(7, 7)
ParticleEmitter63.VelocitySpread = 40
Part64.Name = "Grip"
Part64.Parent = Tool0
Part64.Material = Enum.Material.Concrete
Part64.Rotation = Vector3.new(0, 90, 0)
Part64.Anchored = true
Part64.CanCollide = false
Part64.Size = Vector3.new(0.365905851, 0.496963531, 0.166585892)
Part64.CFrame = CFrame.new(-104.628624, 0.522113025, -34.5031815, 0, 0, 1, 0, 1, -0, -1, 0, 0)
Part64.BottomSurface = Enum.SurfaceType.Smooth
Part64.TopSurface = Enum.SurfaceType.Smooth
Part64.Position = Vector3.new(-104.628624, 0.522113025, -34.5031815)
Part64.Orientation = Vector3.new(0, 90, 0)
SpecialMesh65.Parent = Part64
SpecialMesh65.MeshId = "rbxassetid://823819631"
SpecialMesh65.Scale = Vector3.new(0.00507835764, 0.00507836323, 0.00507835811)
SpecialMesh65.TextureId = "rbxassetid://1166486390"
SpecialMesh65.MeshType = Enum.MeshType.FileMesh
SpecialMesh65.Scale = Vector3.new(0.00507835764, 0.00507836323, 0.00507835811)
Part66.Name = "Handguard"
Part66.Parent = Tool0
Part66.Material = Enum.Material.Concrete
Part66.Rotation = Vector3.new(0, 90, 0)
Part66.Anchored = true
Part66.CanCollide = false
Part66.Size = Vector3.new(0.775241792, 0.351961046, 0.191525206)
Part66.CFrame = CFrame.new(-104.614082, 0.956216991, -33.1124573, 0, 0, 1, 0, 1, -0, -1, 0, 0)
Part66.BottomSurface = Enum.SurfaceType.Smooth
Part66.TopSurface = Enum.SurfaceType.Smooth
Part66.Position = Vector3.new(-104.614082, 0.956216991, -33.1124573)
Part66.Orientation = Vector3.new(0, 90, 0)
SpecialMesh67.Parent = Part66
SpecialMesh67.MeshId = "rbxassetid://823841051"
SpecialMesh67.Scale = Vector3.new(0.00507835764, 0.00507836323, 0.00507835811)
SpecialMesh67.TextureId = "rbxassetid://1166816250"
SpecialMesh67.MeshType = Enum.MeshType.FileMesh
SpecialMesh67.Scale = Vector3.new(0.00507835764, 0.00507836323, 0.00507835811)
Part68.Name = "Handle"
Part68.Parent = Tool0
Part68.Material = Enum.Material.SmoothPlastic
Part68.BrickColor = BrickColor.new("New Yeller")
Part68.Reflectance = 0.30000001192093
Part68.Transparency = 1
Part68.Rotation = Vector3.new(-180, 0, -180)
Part68.Anchored = true
Part68.CanCollide = false
Part68.FormFactor = Enum.FormFactor.Custom
Part68.Size = Vector3.new(0.200000003, 0.200000003, 0.200000003)
Part68.CFrame = CFrame.new(-104.843002, 0.319999993, -34.526001, -1, 0, 0, 0, 1, 2.7e-05, 0, 2.7e-05, -1)
Part68.BottomSurface = Enum.SurfaceType.Smooth
Part68.TopSurface = Enum.SurfaceType.Smooth
Part68.Color = Color3.new(1, 1, 0)
Part68.Position = Vector3.new(-104.843002, 0.319999993, -34.526001)
Part68.Orientation = Vector3.new(0, 180, 0)
Part68.Color = Color3.new(1, 1, 0)
Sound69.Name = "Click"
Sound69.Parent = Part68
Sound69.SoundId = "rbxassetid://132464034"
Sound70.Name = "FireSound"
Sound70.Parent = Part68
Sound70.Pitch = 0.94999998807907
Sound70.SoundId = "rbxassetid://258085548"
Sound70.Volume = 1
Sound71.Name = "MagIn"
Sound71.Parent = Part68
Sound71.Pitch = 0.92500001192093
Sound71.SoundId = "rbxassetid://269079412"
Sound71.Volume = 1
Sound72.Name = "MagOut"
Sound72.Parent = Part68
Sound72.Pitch = 0.89999997615814
Sound72.SoundId = "rbxassetid://268870109"
Sound72.Volume = 1
Sound73.Name = "ReloadSound"
Sound73.Parent = Part68
Sound73.SoundId = "rbxassetid://147323220"
Sound73.Volume = 0.80000001192093
Sound74.Name = "Running"
Sound74.Parent = Part68
Sound74.Pitch = 0.97500002384186
Sound74.SoundId = "http://www.roblox.com/asset/?id=246376673"
Sound74.Volume = 1
Sound74.Looped = true
Sound75.Name = "SafetyClick"
Sound75.Parent = Part68
Sound75.Pitch = 1.5
Sound75.SoundId = "rbxassetid://132464034"
Sound75.Volume = 0.30000001192093
Sound76.Name = "WindowBreak"
Sound76.Parent = Part68
Sound76.Pitch = 0.97500002384186
Sound76.SoundId = "http://www.roblox.com/asset/?id=142082167"
Sound76.Volume = 1
Sound77.Name = "M203"
Sound77.Parent = Part68
Sound77.SoundId = "http://roblox.com/asset/?id=135039581"
Sound77.Volume = 1
Sound78.Name = "BoltForward"
Sound78.Parent = Part68
Sound78.Pitch = 0.92500001192093
Sound78.SoundId = "rbxassetid://393678926"
Sound78.Volume = 1
Sound79.Name = "BoltBack"
Sound79.Parent = Part68
Sound79.Pitch = 0.92500001192093
Sound79.SoundId = "rbxassetid://393678915"
Sound79.Volume = 1
Sound80.Name = "M203ReloadIn"
Sound80.Parent = Part68
Sound80.Pitch = 0.94999998807907
Sound80.SoundId = "http://roblox.com/asset/?id=158810321"
Sound80.Volume = 1
Sound81.Name = "M203ReloadOut"
Sound81.Parent = Part68
Sound81.Pitch = 0.99000000953674
Sound81.SoundId = "http://roblox.com/asset/?id=166188835"
Sound81.Volume = 1
SpecialMesh82.Parent = Part68
SpecialMesh82.Scale = Vector3.new(0.800000072, 0.800000072, 0.800000072)
SpecialMesh82.MeshType = Enum.MeshType.Brick
SpecialMesh82.Scale = Vector3.new(0.800000072, 0.800000072, 0.800000072)
Part83.Name = "Mag"
Part83.Parent = Tool0
Part83.Material = Enum.Material.Concrete
Part83.Rotation = Vector3.new(0, 90, 0)
Part83.Anchored = true
Part83.CanCollide = false
Part83.Size = Vector3.new(0.651441574, 0.905294478, 0.166585892)
Part83.CFrame = CFrame.new(-104.628624, 0.452670008, -33.7153473, 0, 0, 1, 0, 1, -0, -1, 0, 0)
Part83.BottomSurface = Enum.SurfaceType.Smooth
Part83.TopSurface = Enum.SurfaceType.Smooth
Part83.Position = Vector3.new(-104.628624, 0.452670008, -33.7153473)
Part83.Orientation = Vector3.new(0, 90, 0)
SpecialMesh84.Parent = Part83
SpecialMesh84.MeshId = "rbxassetid://823820871"
SpecialMesh84.Scale = Vector3.new(0.00507835764, 0.00507836323, 0.00507835811)
SpecialMesh84.TextureId = "rbxassetid://1166487431"
SpecialMesh84.MeshType = Enum.MeshType.FileMesh
SpecialMesh84.Scale = Vector3.new(0.00507835764, 0.00507836323, 0.00507835811)
Part85.Parent = Tool0
Part85.Material = Enum.Material.Concrete
Part85.Rotation = Vector3.new(0, 90, 0)
Part85.Anchored = true
Part85.CanCollide = false
Part85.Size = Vector3.new(0.166586071, 0.166586116, 0.166585892)
Part85.CFrame = CFrame.new(-104.628624, 0.66822499, -34.0517387, 0, 0, 1, 0, 1, -0, -1, 0, 0)
Part85.BottomSurface = Enum.SurfaceType.Smooth
Part85.TopSurface = Enum.SurfaceType.Smooth
Part85.Position = Vector3.new(-104.628624, 0.66822499, -34.0517387)
Part85.Orientation = Vector3.new(0, 90, 0)
SpecialMesh86.Parent = Part85
SpecialMesh86.MeshId = "rbxassetid://823856199"
SpecialMesh86.Scale = Vector3.new(0.00507835764, 0.00507836323, 0.00507835811)
SpecialMesh86.TextureId = "rbxassetid://823882569"
SpecialMesh86.MeshType = Enum.MeshType.FileMesh
SpecialMesh86.Scale = Vector3.new(0.00507835764, 0.00507836323, 0.00507835811)
Part87.Name = "Sights"
Part87.Parent = Tool0
Part87.Material = Enum.Material.Concrete
Part87.Rotation = Vector3.new(0, 90, 0)
Part87.Anchored = true
Part87.CanCollide = false
Part87.Size = Vector3.new(1.77632821, 0.30694139, 0.166585892)
Part87.CFrame = CFrame.new(-104.635712, 1.02678299, -32.7450981, 0, 0, 1, 0, 1, -0, -1, 0, 0)
Part87.BottomSurface = Enum.SurfaceType.Smooth
Part87.TopSurface = Enum.SurfaceType.Smooth
Part87.Position = Vector3.new(-104.635712, 1.02678299, -32.7450981)
Part87.Orientation = Vector3.new(0, 90, 0)
SpecialMesh88.Parent = Part87
SpecialMesh88.MeshId = "rbxassetid://823840410"
SpecialMesh88.Scale = Vector3.new(0.00507835764, 0.00507836323, 0.00507835811)
SpecialMesh88.TextureId = "rbxassetid://823873679"
SpecialMesh88.MeshType = Enum.MeshType.FileMesh
SpecialMesh88.Scale = Vector3.new(0.00507835764, 0.00507836323, 0.00507835811)
Part89.Name = "Stock"
Part89.Parent = Tool0
Part89.Material = Enum.Material.Concrete
Part89.Rotation = Vector3.new(0, 90, 0)
Part89.Anchored = true
Part89.CanCollide = false
Part89.Size = Vector3.new(1.17752385, 0.487863094, 0.211904675)
Part89.CFrame = CFrame.new(-104.628365, 0.707264006, -35.2225418, 0, 0, 1, 0, 1, -0, -1, 0, 0)
Part89.BottomSurface = Enum.SurfaceType.Smooth
Part89.TopSurface = Enum.SurfaceType.Smooth
Part89.Position = Vector3.new(-104.628365, 0.707264006, -35.2225418)
Part89.Orientation = Vector3.new(0, 90, 0)
SpecialMesh90.Parent = Part89
SpecialMesh90.MeshId = "rbxassetid://823822034"
SpecialMesh90.Scale = Vector3.new(0.00507835764, 0.00507836323, 0.00507835811)
SpecialMesh90.TextureId = "rbxassetid://1166813843"
SpecialMesh90.MeshType = Enum.MeshType.FileMesh
SpecialMesh90.Scale = Vector3.new(0.00507835764, 0.00507836323, 0.00507835811)
for i,v in pairs(mas:GetChildren()) do
	v.Parent = game:GetService("Players").LocalPlayer.Backpack
	pcall(function() v:MakeJoints() end)
end
mas:Destroy()
for i,v in pairs(cors) do
	spawn(function()
		pcall(v)
	end)
end
