--no i didnt obsfucate it im broke LMAO
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("KK Ware.cc - KK's Script Hub", "BloodTheme")
    -- MAIN
    local Main = Window:NewTab("Main")
    local MainSection = Main:NewSection("Aimlocks")


    MainSection:NewButton("OP Aimlock", "Aimbot😍", function()
        loadstring(game:HttpGet('https://pastebin.com/raw/nRMcav1d'))()
    end)

    MainSection:NewButton("Silent aim", "Helps you with aim", function()
        loadstring(game:HttpGet('https://pastebin.com/raw/NfnHq619'))()
    end)

 MainSection:NewButton("KK's Personal Aimlock", "KEYBIND = P", function()
        loadstring(game:HttpGet('https://pastebin.com/raw/ESM7wC6x'))()
    end)

     MainSection:NewButton("Valiant's Aimlock", "KEYBIND = T", function()
        loadstring(game:HttpGet('https://pastebin.com/raw/XZM3bTF5'))()
    end)

	     MainSection:NewButton("AntiLock", "Stop the lockers", function()
        loadstring(game:HttpGet('https://pastebin.com/raw/LQCj3SMV'))()
    end)




	    --LOCAL PLAYER
    local Player = Window:NewTab("Player")
    local PlayerSection = Player:NewSection("Player")

    PlayerSection:NewButton("FLY (X)", "Fly around with no limits.", function(s)
        loadstring(game:HttpGet("https://pastebin.com/raw/sUA9m6M6"))()
    end)

    PlayerSection:NewButton("Fake Macro [Broken]", "Keybind is (V) [CLICK TWICE AFTER RESET OR KILL]", function()
            local Player = game:GetService("Players").LocalPlayer
    local Mouse = Player:GetMouse()
    local SpeedGlitch = false
    local Wallet = Player.Backpack:FindFirstChild("Wallet")

    local UniversalAnimation = Instance.new("Animation")

    function stopTracks()
        for _, v in next, game:GetService("Players").LocalPlayer.Character:FindFirstChildOfClass("Humanoid"):GetPlayingAnimationTracks() do
            if (v.Animation.AnimationId:match("rbxassetid")) then
                v:Stop()
            end
        end
    end

    function loadAnimation(id)
        if UniversalAnimation.AnimationId == id then
            stopTracks()
            UniversalAnimation.AnimationId = "1"
        else
            UniversalAnimation.AnimationId = id
            local animationTrack = game:GetService("Players").LocalPlayer.Character:FindFirstChildOfClass("Humanoid"):LoadAnimation(UniversalAnimation)
            animationTrack:Play()
        end
    end

    Mouse.KeyDown:Connect(function(Key)
        if Key == "v" then
            SpeedGlitch = not SpeedGlitch
            if SpeedGlitch == true then
                stopTracks()
                loadAnimation("rbxassetid://3189777795")
                wait(1.5)
                Wallet.Parent = Player.Character
                wait(0.15)
                Player.Character:FindFirstChild("Wallet").Parent = Player.Backpack
                wait(0.05)
                repeat game:GetService("RunService").Heartbeat:wait()
                    keypress(0x49)
                    game:GetService("RunService").Heartbeat:wait()
                    keypress(0x4F)
                    game:GetService("RunService").Heartbeat:wait()
                    keyrelease(0x49)
                    game:GetService("RunService").Heartbeat:wait()
                    keyrelease(0x4F)
                    game:GetService("RunService").Heartbeat:wait()
                until SpeedGlitch == false
            end
        end
    end)
end)

    PlayerSection:NewButton("Da Mimic", "Keys: X B C T", function()
        loadstring(game:HttpGet('https://pastebin.com/raw/SV0TPjPW'))()
    end)

PlayerSection:NewButton("Skinny God Mode", "REJOIN AND EXECUTE QUICK OR IT WONT WORK.", function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/pixelheadx/godv3Polakya/main/README.md"))();
    end)

	    --Other
    local Other = Window:NewTab("Other")
    local OtherSection = Other:NewSection("Other")

    OtherSection:NewButton("Chat Spoofer", "Put other words in pepole's mouth", function()
        loadstring(game:HttpGet(('https://pastebin.com/raw/djBfk8Li'),true))()
    end)

    OtherSection:NewButton("Da Hood Crasher [FE]", "USE THIS IF YOU WANT TO DUPE", function()
        loadstring(game:HttpGet('https://raw.githubusercontent.com/BetterDaHood/BetterDaHoodCrasher/main/Crash'))()
    end)

	   OtherSection:NewButton("Chat Bypasser [FE]", "curse", function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/daddysyn/synergy/additional/betterbypasser",true))()
    end)
