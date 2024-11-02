local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("JU HUB | 1.0", "DarkTheme")
local Tab = Window:NewTab("AutoFarm")
local Section = Tab:NewSection("AutoFarm")
Section:NewToggle("fram Wood", "", function(state)
_G.autofarm = state

while _G.autofarm do wait()
pcall(function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1310.61572, 18.0391312, -1718.38159, -0.447192252, 8.70090346e-08, 0.89443785, -2.39332887e-09, 1, -9.84744943e-08, -0.89443785, -4.61777141e-08, -0.447192252)
    for i,v in pairs(game.Workspace.Farm.Wood:GetDescendants()) do
    if v.Name == "TouchInterest" then
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame
        wait(.1)
    end
    end
end)

end
end)

Section:NewToggle("fram Pork", "", function(state)
_G.autofarm = state

while _G.autofarm do wait()
pcall(function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-538.915894, 13.9583454, 2335.96924, 0.925712407, 3.55705119e-08, -0.378228158, -7.2071856e-08, 1, -8.23505601e-08, 0.378228158, 1.03492539e-07, 0.925712407)
    for i,v in pairs(game.Workspace.Farm.Pork:GetDescendants()) do
    if v.Name == "TouchInterest" then
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame
        wait(.1)
    end
    end
end)

end
end)

Section:NewToggle("fram Rock", "", function(state)
_G.autofarm = state

while _G.autofarm do wait()
pcall(function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-316.492859, -67.8217468, -2028.47546, 0.966099441, 4.67094008e-09, -0.258170217, -3.51835094e-09, 1, 4.92645214e-09, 0.258170217, -3.85110921e-09, 0.966099441)
    for i,v in pairs(game.Workspace.Farm.Rock:GetDescendants()) do
    if v.Name == "TouchInterest" then
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame
        wait(.1)
    end
    end
end)

end
end)

Section:NewToggle("fram Plant", "", function(state)
_G.autofarm = state

while _G.autofarm do wait()
pcall(function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(2199.05981, 16.2435379, -3326.05444, 0.998570502, 3.79036136e-09, -0.0534502007, -3.05782555e-09, 1, 1.37867948e-08, 0.0534502007, -1.36036453e-08, 0.998570502)
    for i,v in pairs(game.Workspace.Farm.Plant:GetDescendants()) do
    if v.Name == "TouchInterest" then
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame
        wait(.1)
    end
    end
end)

end
end)

Section:NewToggle("fram Corn", "", function(state)
_G.autofarm = state

while _G.autofarm do wait()
pcall(function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-171.547043, 48.5520935, 447.17688, -0.584445894, 4.76066866e-08, -0.811432719, 1.10644893e-09, 1, 5.78729775e-08, 0.811432719, 3.2925815e-08, -0.584445894)
    for i,v in pairs(game.Workspace.Farm.Corn:GetDescendants()) do
    if v.Name == "TouchInterest" then
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame
        wait(.1)
    end
    end
end)

end
end)

Section:NewToggle("fram Banana", "", function(state)
_G.autofarm = state

while _G.autofarm do wait()
pcall(function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(67.1075668, 18.4468536, -272.878082, -0.891458333, 3.7502299e-09, 0.453102678, 1.36071767e-08, 1, 1.84947062e-08, -0.453102678, 2.26527082e-08, -0.891458333)
    for i,v in pairs(game.Workspace.Farm.Banana:GetDescendants()) do
    if v.Name == "TouchInterest" then
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame
        wait(.1)
    end
    end
end)

end
end)

local Tab = Window:NewTab("Tp")
local Section = Tab:NewSection("Tp Farm")
Section:NewButton("Wood", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1310.61572, 18.0391312, -1718.38159, -0.447192252, 8.70090346e-08, 0.89443785, -2.39332887e-09, 1, -9.84744943e-08, -0.89443785, -4.61777141e-08, -0.447192252)
end)
Section:NewButton("Pork", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-538.915894, 13.9583454, 2335.96924, 0.925712407, 3.55705119e-08, -0.378228158, -7.2071856e-08, 1, -8.23505601e-08, 0.378228158, 1.03492539e-07, 0.925712407)
end)
Section:NewButton("Rock", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-316.492859, -67.8217468, -2028.47546, 0.966099441, 4.67094008e-09, -0.258170217, -3.51835094e-09, 1, 4.92645214e-09, 0.258170217, -3.85110921e-09, 0.966099441)
end)
Section:NewButton("Plant", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-316.492859, -67.8217468, -2028.47546, 0.966099441, 4.67094008e-09, -0.258170217, -3.51835094e-09, 1, 4.92645214e-09, 0.258170217, -3.85110921e-09, 0.966099441)
end)
Section:NewButton("Corn", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(2199.05981, 16.2435379, -3326.05444, 0.998570502, 3.79036136e-09, -0.0534502007, -3.05782555e-09, 1, 1.37867948e-08, 0.0534502007, -1.36036453e-08, 0.998570502)
end)
Section:NewButton("Banana", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(67.1075668, 18.4468536, -272.878082, -0.891458333, 3.7502299e-09, 0.453102678, 1.36071767e-08, 1, 1.84947062e-08, -0.453102678, 2.26527082e-08, -0.891458333)
end)
local Section = Tab:NewSection("Tp")
Section:NewButton("สภา", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1464.83838, 55.6054382, 828.143005, 0.123219244, 5.23793275e-08, 0.992379487, -5.56022961e-09, 1, -5.20911634e-08, -0.992379487, 9.00775787e-10, 0.123219244)
end)
Section:NewButton("ตํารวจ", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3687.34644, 14.27174, 3619.75391, 0.0894601196, -5.73128434e-09, 0.995990396, -5.78499515e-09, 1, 6.27396668e-09, -0.995990396, -6.32306962e-09, 0.0894601196)
end)
Section:NewButton("ร้านค้า", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3002.34497, 14.3816833, 1925.05872, 0.999999821, 3.88486789e-08, -0.000590398966, -3.8818456e-08, 1, 5.11995246e-08, 0.000590398966, -5.1176599e-08, 0.999999821)
end)
Section:NewButton("ปั้มนํ้ามัน 1", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3716.26562, 14.7984238, 2891.52588, 0.696943641, 1.31163098e-08, -0.717125893, 3.59137857e-08, 1, 5.31931654e-08, 0.717125893, -6.28273469e-08, 0.696943641)
end)
Section:NewButton("เรเบล", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(2501.14307, 15.1122379, 555.308167, -0.519874394, -9.84422428e-08, 0.854242682, -7.94727342e-08, 1, 6.68737314e-08, -0.854242682, -3.31230616e-08, -0.519874394)
end)
Section:NewButton("โรงพยาบาล", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3424.07275, 14.244236, 2596.35742, 0.95701617, 3.54125831e-08, 0.290034503, -2.19252403e-08, 1, -4.97519181e-08, -0.290034503, 4.12543137e-08, 0.95701617)
end)
Section:NewButton("แปรรูปหิน", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1896.18726, 13.1281643, 3201.65015, 0.966443598, -1.41463534e-08, 0.256879002, 3.9046629e-08, 1, -9.18331651e-08, -0.256879002, 9.87818325e-08, 0.966443598)
end)
Section:NewButton("ตลาดโลก", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(2845.45142, 14.2436848, 2079.27222, -0.388715088, 1.28141585e-06, -0.921357989, -1.4877221e-06, 1, 2.01845091e-06, 0.921357989, 2.15532691e-06, -0.388715088)
end)
Section:NewButton("ร้านขายรถ", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3031.60376, 14.2829304, 2884.8916, -0.647440672, -4.2225075e-08, -0.762115836, -7.45602406e-08, 1, 7.93613619e-09, 0.762115836, 6.1961714e-08, -0.647440672)
end)
Section:NewButton("ปั้มนํ้ามัน 4", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(293.110352, 14.1683521, -554.815552, 0.261437625, 3.62182604e-08, 0.965220392, 4.86328444e-09, 1, -3.88405681e-08, -0.965220392, 1.48485269e-08, 0.261437625)
end)
Section:NewButton("ปั้มนํ้ามัน 2", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-266.731415, 14.9860458, 3485.51465, -0.00118964224, -6.67604567e-08, -0.999999285, -5.34426814e-09, 1, -6.67541471e-08, 0.999999285, 5.26485078e-09, -0.00118964224)
end)
Section:NewButton("อู่ช่าง", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(2879.12012, 14.4760342, 2771.61133, -0.494345367, -3.71931961e-08, 0.869265616, -1.08556595e-08, 1, 3.6613379e-08, -0.869265616, 8.6632026e-09, -0.494345367)
end)
Section:NewButton("ปั้มนํ้ามัน 3", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1025.63696, 15.8193264, 1475.87134, 0.996082783, -9.14768372e-10, 0.0884257406, 5.54683299e-10, 1, 4.09674694e-09, -0.0884257406, -4.03165057e-09, 0.996082783)
end)

local Tab = Window:NewTab("Tp Black_Jobs")
local Section = Tab:NewSection("Tp Cement")
Section:NewButton("Cement 1", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3495.99414, 77.2299347, 2934.33594, -0.452851057, -8.97525894e-08, 0.891586185, -2.05007229e-08, 1, 9.02535504e-08, -0.891586185, 2.25932535e-08, -0.452851057)
end)
Section:NewButton("Cement 2", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3243.1123, 17.4799843, 2980.90454, 0.173435032, -1.82180937e-08, -0.98484534, 2.21042349e-08, 1, -1.46057904e-08, 0.98484534, -1.92360972e-08, 0.173435032)
end)
Section:NewButton("Cement 3", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3887.19189, 49.9490967, 3367.62817, -0.605714977, -4.62784939e-08, -0.795681655, 5.59857192e-08, 1, -1.00781364e-07, 0.795681655, -1.05591596e-07, -0.605714977)
end)
Section:NewButton("Cement 4", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(2859.61084, 17.2979889, 2443.59106, -0.0175855868, 3.63704835e-08, -0.999845386, 7.47965423e-09, 1, 3.6244554e-08, 0.999845386, -6.84111567e-09, -0.0175855868)
end)
local Section = Tab:NewSection("Tp Wire")
Section:NewButton("Wire 1", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3734.97949, 14.3816814, 2654.95483, 0.409280628, -5.27198418e-09, -0.912408531, -2.39213732e-10, 1, -5.88540061e-09, 0.912408531, 2.62704125e-09, 0.409280628)
end)
Section:NewButton("Wire 2", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(2620.24512, 14.3816891, 2479.66821, 0.621054471, -7.94673394e-09, 0.783767402, 1.45210608e-08, 1, -1.36728739e-09, -0.783767402, 1.22302941e-08, 0.621054471)
end)
Section:NewButton("Wire 3", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1911.3573, 14.5676041, 2506.57104, -0.168154433, -2.94396276e-08, 0.985760689, -1.25464965e-07, 1, 8.46264125e-09, -0.985760689, -1.22255386e-07, -0.168154433)
end)
Section:NewButton("Wire 4", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3167.71436, 14.5636768, 2767.69946, 0.253667325, -2.73629635e-08, -0.967291534, 5.92657834e-08, 1, -1.27460753e-08, 0.967291534, -5.4094027e-08, 0.253667325)
end)
Section:NewButton("Wire 5", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3736.69214, 14.3816814, 3681.44556, -0.999635398, -3.41276518e-09, 0.0270002559, -3.39440498e-09, 1, 7.25832283e-10, -0.0270002559, 6.33917807e-10, -0.999635398)
end)

local Tab = Window:NewTab("Highlight")
local Section = Tab:NewSection("All Highlight Black_Jobs")
Section:NewButton("All Highlight", "", function()
    for i,v in pairs(game.Workspace.Black_Jobs:GetDescendants()) do
        if v:IsA("Model") then  
            local A = Instance.new("Highlight")
            A.Parent = v
        end
    end
end)
local Section = Tab:NewSection("Highlight Cement")
Section:NewButton("Highlight Cement", "", function()
    for i,v in pairs(game.Workspace.Black_Jobs.Cement:GetDescendants()) do
        if v:IsA("Model") then  
            local A = Instance.new("Highlight")
            A.Parent = v
        end
    end
end)
local Section = Tab:NewSection("Highlight Electrical cabinet")
Section:NewButton("Highlight Electrical cabinet", "", function()
    for i,v in pairs(game.Workspace["Electrical cabinet"]:GetDescendants()) do
        if v:IsA("Model") then  
            local A = Instance.new("Highlight")
            A.Parent = v
        end
    end
end)
local Section = Tab:NewSection("Highlight Wire")
Section:NewButton("Highlight Wire", "", function()
    for i,v in pairs(game.Workspace.Black_Jobs.Wire:GetDescendants()) do
        if v:IsA("Model") then  
            local A = Instance.new("Highlight")
            A.Parent = v
        end
    end
end)

local Section = Tab:NewSection("Close Highlight")
Section:NewButton("Close Highlight", "", function()
    for i,v in pairs(game.Workspace:GetDescendants()) do
        if v:IsA("Highlight") then  
           v:Destroy()
        end
    end
end)


local Tab = Window:NewTab("Player")
local Section = Tab:NewSection("Select Player!")
Plr = {}
for i,v in pairs(game:GetService("Players"):GetChildren()) do
    table.insert(Plr,v.Name) 
end
local drop = Section:NewDropdown("Select Player!", "Click To Select", Plr, function(t)
   PlayerTP = t
end)
Section:NewButton("Click To TP", "", function()
    game.Workspcae.Character:FindFirstChild(game.Players.LocalPlayer.Name).HumanoidRootPart.CFrame = game.Workspace.Character:FindFirstChild(PlayerTP).HumanoidRootPart.CFrame
end)
Section:NewToggle("Auto Tp", "", function(t)
_G.TPPlayer = t
while _G.TPPlayer do wait()
    game.Workspcae.Character:FindFirstChild(game.Players.LocalPlayer.Name).HumanoidRootPart.CFrame = game.Workspace.Character:FindFirstChild(PlayerTP).HumanoidRootPart.CFrame
end
end)

Section:NewButton("Refresh Dropdown","Refresh Dropdown", function()
  drop:Refresh(Plr)
end)

local Tab = Window:NewTab("Key")
local Section = Tab:NewSection("Key")
Section:NewKeybind("KeybindText", "KeybindInfo", Enum.KeyCode.F, function()
	Library:ToggleUI()
end)
