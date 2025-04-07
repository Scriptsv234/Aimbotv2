loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Aimbot-Universal-For-Mobile-and-PC-29153"))()
getgenv().Dino = {
    Enabled = true,
    Keybind = Enum.KeyCode.Q,
    Prediction = {
        X = 0.138778,
        Y = 0.138,
    },
    Hitpart = "HumanoidRootPart",
    Checks = {
        Knocked = false,
        Notify = false,
    },
}

loadstring(game:HttpGet("https://raw.githubusercontent.com/CookieScript/dino/refs/heads/main/Main/Loader.lua"))();
