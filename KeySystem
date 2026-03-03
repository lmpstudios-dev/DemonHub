local v1 = loadstring(game:HttpGet('https://pastebin.com/raw/sdSWYHcp'))()

loadstring(game:HttpGet('https://raw.githubusercontent.com/dawid-scripts/Fluent/master/Addons/SaveManager.lua'))()
loadstring(game:HttpGet('https://raw.githubusercontent.com/dawid-scripts/Fluent/master/Addons/InterfaceManager.lua'))()

local v2 = v1:CreateWindow({
    Title = '  DEMONHUB',
    SubTitle = '  By Ulisted ',
    Search = false,
    Icon = 'rbxassetid://75943667313282',
    TabWidth = 120,
    Size = UDim2.fromOffset(460, 320),
    Acrylic = true,
    Theme = 'Bloody',
    MinimizeKey = Enum.KeyCode.LeftControl,
    UserInfo = true,
    UserInfoTop = true,
    UserInfoTitle = game.Players.LocalPlayer.DisplayName,
    UserInfoSubtitle = 'User',
    UserInfoSubtitleColor = Color3.fromRGB(71, 123, 255),
})

v1:CreateMinimizer({
    Icon = 'rbxassetid://75943667313282',
    Size = UDim2.fromOffset(60, 60),
    Position = UDim2.new(0, 710, 0, 24),
    Acrylic = true,
    Corner = 10,
    Transparency = 1,
    Draggable = false,
    Visible = true,
})

local v3 = v2:AddTab({
    Title = 'KEY SYSTEM',
    Icon = 'rbxassetid://0000',
})
local u4 = 'DemonOnTop'
local u5 = 'DemonOnTop'
local _KeyInput = v3:AddInput('KeyInput', {
    Title = 'ENTER YOUR KEY',
    Placeholder = 'Enter your access key here...',
    Default = '',
    Numeric = false,
    Finished = false,
})

v3:AddButton({
    Title = 'CHECK KEY ',
    Description = 'Check your access key',
    Callback = function()
        if _KeyInput.Value ~= u4 then
            game.StarterGui:SetCore('SendNotification', {
                Title = 'INVALID KEY',
                Text = 'Invalid key, please try again!',
                Duration = 4,
            })
        else
            game.StarterGui:SetCore('SendNotification', {
                Title = ' VERIFIED',
                Text = 'Key verified successfully! Loading DemonHub...',
                Duration = 3,
            })
            task.wait(1)
            loadstring(game:HttpGet('https://pastebin.com/raw/0qtSAMMf'))()
        end
    end,
})
v3:AddButton({
    Title = ' GET KEY',
    Description = 'Copy key',
    Callback = function()
        setclipboard(u5)
        game.StarterGui:SetCore('SendNotification', {
            Title = ' COPIED',
            Text = 'key copied.',
            Duration = 3,
        })
    end,
})
