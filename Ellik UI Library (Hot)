local ellik = loadstring(game:HttpGet('https://raw.githubusercontent.com/ZepsyyCodesLUA/Ellik/main/source.lua', true))()


local win = ellik:Create({
    Title = "Ellik UI lib"
})

local tab = win:NewTab({
    Title = "Tab Example"
})

tab:Button({
    Text = 'Hello',
    Callback = function()
        print'hello'
    end
})

tab:Toggle({
    Text = 'Toggle Example',
    Callback = function(args)
        print(args)
    end
})

tab:Dropdown({
    Title = 'Hello',
    List = {'ho', 'hi'},
    Callback = function(args)
        print(args)
    end
})

tab:TextBox({
    PlaceHolder = 'Epik Place Holder lmfao',
    Callback = function(args)
        print(args)
    end
})

tab:Slider({
    Text = 'Slider Example',
    Min = 16,
    Def = 50,
    --Def Is A Bit Laggy lol.
    Max = 100,
    Callback = function(args)
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = args
    end
})
tab:Bind({
    Text = 'Bind Example',
    Callback = function(args)
        print(args)
    end
})
