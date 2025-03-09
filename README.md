local genv = getgenv()
local fenv = getfenv()
local _ = fenv.bit
local v3 = game:HttpGet("https://paste.ee/r/WSCKThwW")
local v4 = loadstring(v3)
local v5 = v4()
local v6 = v5.CreateWindow
local v7 = v6(v5, {
    LoadingTitle = "bach",
    Subtitle = "feito por bach",
    LogoID = "82795327169782",
    LoadingEnabled = false,
    LoadingSubtitle = "by bach",
    ConfigSettings = {
        ConfigFolder = "non",
    },
    Name = "discord.gg/bachofc",
})
local v8 = v7.CreateHomeTab
v8(v7, {
    SupportedExecutors = {
},
    DiscordInvite = "pYRpbf33",
    Icon = 1,
})
local v10 = v7.CreateTab
local v11 = v10(v7, {
    ShowTitle = true,
    ImageSource = "Material",
    Icon = "agriculture",
    Name = "Farm Mini City",
})
local v12 = v11.CreateToggle
v12(v11, {
    CurrentValue = false,
    Callback = function(...)
    end,
    Description = "Toma kick se tiver staff ou jogadores da blacklist (80% funcional)",
    Name = "Anti staff",
})
spawn(function(...)
end)
spawn(function(...)
end)
local v16 = v11.CreateSection
v16(v11, "Ilegal - plantas")
local v18 = v11.CreateToggle
v18(v11, {
    CurrentValue = false,
    Callback = function(...)
    end,
    Description = "Precisa de fac",
    Name = "Farm plantas",
})
local v20 = v11.CreateButton
v20(v11, {
    Name = "Teleport drogas place",
    Callback = function(...)
    end,
})
local v22 = v11.CreateSection
v22(v11, "Ilegal - PeÃ§as")
local v24 = v11.CreateButton
v24(v11, {
    Callback = function(...)
    end,
    Description = "Precisa estar em fac e pegar a missao",
    Name = "Teleport peÃ§a",
})
local v26 = v11.CreateButton
local _ = fenv.nill
v26(v11, {
    Name = "Salvar posicao",
    Callback = function(...)
    end,
})
local v29 = v11.CreateButton
v29(v11, {
    Name = "Teleport posicao salva",
    Callback = function(...)
    end,
})
local v31 = v11.CreateParagraph
v31(v11, {
    Title = "Quer um auto farm peÃ§as? ",
    Text = "Temos um auto farm peÃ§as pegando 2k de peÃ§as em minutos para booster do servidor discord.gg/bachofc.",
})
local v33 = v11.CreateSection
v33(v11, "Jobs")
local v35 = v11.CreateDropdown
v35(v11, {
    Options = {
        [1] = "Minerador",
        [2] = "Gari",
        [3] = "Civil",
        [4] = "Fazendeiro",
        [5] = "Pescador",
        [6] = "Mecanico",
        [7] = "Entregador de Gas",
    },
    CurrentOption = {
},
    MultipleOptions = false,
    Callback = function(...)
    end,
    Name = "Escolher time",
}, "EscolherTimeDropdown")
local v37 = v11.CreateToggle
v37(v11, {
    CurrentValue = false,
    Callback = function(...)
    end,
    Description = "Precisa ser gari",
    Name = "Farm gari",
})
local v39 = v7.CreateTab
local v40 = v39(v7, {
    ShowTitle = true,
    ImageSource = "Material",
    Icon = "people",
    Name = "Combat",
})
local v41 = v7.CreateTab
local v42 = v41(v7, {
    ShowTitle = true,
    ImageSource = "Material",
    Icon = "remove_red_eye",
    Name = "Visual",
})
local v43 = v7.CreateTab
local v44 = v43(v7, {
    ShowTitle = true,
    ImageSource = "Material",
    Icon = "location_city",
    Name = "Mini City",
})
genv.KickOnLowHealth = false
genv.HealthThreshold = 10
local v46 = v45.LocalPlayer
local v47 = v46.CharacterAdded
local v48 = v47.Connect
v48(v47, function(...)
end)
local v51 = v50.LocalPlayer
local _ = v51.Character
local v54 = v53.LocalPlayer
local v55 = v54.Character
local v56 = v55.FindFirstChild
v56(v55, "Humanoid")
local v58 = v55.Humanoid
local v59 = v58.HealthChanged
local v60 = v59.Connect
v60(v59, function(...)
end)
local v62 = v44.CreateSection
v62(v44, "Auto revistar")
local v64 = v44.CreateButton
v64(v44, {
    Callback = function(...)
    end,
    Description = "Deleta a notificacao do puxar itens",
    Name = "Deletar notfi",
})
local v66 = v44.CreateButton
v66(v44, {
    Callback = function(...)
    end,
    Description = "Precisa estar revistando e vai pegar os itens",
    Name = "Puxar itens",
})
local v68 = v44.CreateButton
v68(v44, {
    Callback = function(...)
    end,
    Description = "Cria uma ui pra mandar /revistar",
    Name = "Mandar revistar MOB",
})
local v70 = v44.CreateToggle
v70(v44, {
    CurrentValue = false,
    Callback = function(...)
    end,
    Description = "Ative e pressione a tecla T para mandar /revistar",
    Name = "Mandar revistar PC",
})
game:GetService("TextChatService")
local v73 = game:GetService("UserInputService")
local v74 = v44.CreateSection
v74(v44, "Teleport")
local v76 = CFrame.new
v76(- 291.579559, 3.26299787, 342.192535)
local v78 = CFrame.new
v78(- 469.959015, 3.25349784, - 54.3936005)
local v80 = CFrame.new
v80(- 543.439941, 3.26299858, 645.16864)
local v82 = CFrame.new
v82(- 83.1141129, 13.1430578, 74.7073364)
local v84 = CFrame.new
v84(- 466.870148, 7.64567232, 350.242737)
local v86 = CFrame.new
v86(- 91.3902893, 8.07136822, 520.355347)
local v88 = CFrame.new
v88(- 518.672852, 3.16749811, - 1.16962147, 0, 0, - 1, 0, 1, 0, 1, 0, 0)
local v90 = CFrame.new
v90(- 284.904785, 8.26088619, - 72.2896194, 0, 0, - 1, 0, 1, 0, 1, 0, 0)
local v92 = CFrame.new
v92(- 980.181458, 2.27553082, 467.080536, 1, 0, 0, 0, 1, 0, 0, 0, 1)
local v94 = CFrame.new
v94(6662.24512, 36.6637421, 5047.83838, 0.707134247, 0, 0.707079291, 0, 1, 0, - 0.707079291, 0, 0.707134247)
local v96 = CFrame.new
v96(201.932144, 2.76136589, 145.50531, 0, 0, 1, 0, 1, 0, - 1, 0, 0)
local v98 = CFrame.new
v98(- 180.608261, 3.29813337, - 532.4151, 0.422592998, 0, - 0.906319618, 0, 1, 0, 0.906319618, 0, 0.422592998)
local v100 = CFrame.new
v100(817.243225, 3.26249814, - 87.316864, 0, 0, 1, 0, 1, 0, - 1, 0, 0)
local v102 = CFrame.new
v102(- 284.388458, 15.1148872, 88.0397873, 0, 0, - 1, 0, 1, 0, 1, 0, 0)
local v104 = CFrame.new
v104(- 27.2709007, 11.5685892, 418.200653, 1, 0, 0, 0, 1, 0, 0, 0, 1)
local v106 = CFrame.new
v106(12037.2705, 27.5305443, 12794.0635, 0.965929627, 0, - 0.258804798, 0, 1, 0, 0.258804798, 0, 0.965929627)
local v108 = CFrame.new
v108(- 1595.23328, 204.074341, 555.895386, 0.939687431, - 0.34203434, 0.00000181794167, 0.00000181794167, 0.0000102519989, 1, - 0.34203434, - 0.93968749, 0.0000102519989)
local v110 = CFrame.new
v110(2555.44263, 303.167755, - 1004.13763, - 0.422592998, 0, 0.906319618, 0, 1, 0, - 0.906319618, 0, - 0.422592998)
local v112 = v44.CreateDropdown
v112(v44, {
    Options = {
        [1] = "None",
        [2] = "Praca",
        [3] = "Gas",
        [4] = "HP",
        [5] = "Tabacaria",
        [6] = "Garagem",
        [7] = "Concessionaria",
        [8] = "Gari",
        [9] = "Imobiliaria",
        [10] = "PM",
        [11] = "PRF",
        [12] = "Mineracao",
        [13] = "Mecanica",
        [14] = "Fazenda",
        [15] = "Prefeitura",
        [16] = "Banco",
        [17] = "Ilegal",
        [18] = "Predio 1",
        [19] = "Devs Mini City",
    },
    CurrentOption = {
        [1] = "None",
    },
    MultipleOptions = false,
    Callback = function(...)
    end,
    Name = "Selecione um local para teleportar",
})
local v114 = v73.InputBegan
local v115 = v114.Connect
v115(v114, function(...)
end)
local v117 = v44.CreateSection
v117(v44, "Auto SAFE config")
local v119 = game:GetService("Players")
local v120 = v119.LocalPlayer
local v121 = v120.Character
local v122 = v121.WaitForChild
v122(v121, "Humanoid")
local v124 = v121.WaitForChild
v124(v121, "HumanoidRootPart")
local v126 = game:GetService("RunService")
local v127 = v44.CreateToggle
v127(v44, {
    CurrentValue = false,
    Name = "Auto safe",
    Callback = function(...)
    end,
})
local v129 = v44.CreateSlider
v129(v44, {
    Name = "Auto safe tp quando vida =",
    CurrentValue = 50,
    Increment = 1,
    Range = {
        [1] = 1,
        [2] = 100,
    },
    Callback = function(...)
    end,
})
local v131 = v126.Heartbeat
local v132 = v131.Connect
v132(v131, function(...)
end)
local v134 = v44.CreateSection
v134(v44, "Auto CL config")
local v136 = v44.CreateToggle
v136(v44, {
    Name = "Auto CL",
    Callback = function(...)
    end,
}, "AutoKickToggle")
local v138 = v44.CreateSlider
v138(v44, {
    Callback = function(...)
    end,
    Increment = 1,
    Name = "Kick quando vida =",
    Range = {
        [1] = 0,
        [2] = 100,
    },
}, "HealthThresholdSlider")
local v140 = v44.CreateSection
v140(v44, "Fly")
local v142 = v44.CreateButton
v142(v44, {
    Callback = function(...)
    end,
    Description = "Ative para abrir a nossa ui de fly",
    Name = "Fly UI",
})
local v144 = v44.CreateSection
v144(v44, "Outros")
_G.NoClip = false
local v146 = game:GetService("Players")
local _ = v146.LocalPlayer
game:GetService("Workspace")
local v149 = v44.CreateToggle
v149(v44, {
    CurrentValue = false,
    Callback = function(...)
    end,
    Description = "Vai mostrar itens dos jogadores",
    Name = "Ver itens UI",
})
local v151 = v44.CreateToggle
v151(v44, {
    Callback = function(...)
    end,
    Description = "Ative para atravessar paredes",
    Name = "Noclip",
})
local v153 = v44.CreateButton
v153(v44, {
    Callback = function(...)
    end,
    Description = "SE ESTIVER USANDO FLY NAO FUNCIONA!!",
    Name = "Tirar dano de queda",
})
local v155 = game:GetService("RunService")
local v156 = v155.Stepped
local v157 = v156.Connect
v157(v156, function(...)
end)
local v159 = v44.CreateSection
v159(v44, "Servidor")
local v161 = v44.CreateButton
v161(v44, {
    Callback = function(...)
    end,
    Description = "Rejoin no mesmo servidor",
    Name = "Rejoin",
})
local v163 = v44.CreateButton
v163(v44, {
    Callback = function(...)
    end,
    Description = "Troca pro menor servidor do jogo",
    Name = "Low server hop",
})
local v165 = v7.CreateTab
local v166 = v165(v7, {
    ShowTitle = true,
    ImageSource = "Material",
    Icon = "computer",
    Name = "Client Viewer",
})
local v167 = v166.CreateLabel
v167(v166, {
    Style = 1,
    Text = "[GameTime] : Carregando...",
})
local v169 = v166.CreateLabel
v169(v166, {
    Style = 1,
    Text = "Players count : Carregando...",
})
local v171 = v166.CreateLabel
v171(v166, {
    Style = 2,
    Text = "[FPS] : Carregando...",
})
local v173 = v166.CreateLabel
v173(v166, {
    Style = 3,
    Text = "[Ping] : Carregando...",
})
local v175 = v166.CreateButton
v175(v166, {
    Callback = function(...)
    end,
    Description = "Vai diminuir os graficos e Ã© irreversivel",
    Name = "Boost",
})
spawn(function(...)
end)
spawn(function(...)
end)
spawn(function(...)
end)
spawn(function(...)
end)
local v181 = game:GetService("Players")
local v182 = v181.PlayerAdded
local v183 = v182.Connect
v183(v182, function(...)
end)
local v185 = game:GetService("Players")
local v186 = v185.PlayerRemoving
local v187 = v186.Connect
v187(v186, function(...)
end)
game:GetService("UserInputService")
local v190 = game:GetService("Players")
game:GetService("RunService")
local _ = v190.LocalPlayer
genv.HitboxSize = 13
genv.SphereSize = 3
genv.HitboxEnabled = {
}
genv.SphereVisible = false
local v193 = Color3.fromRGB
local v194 = v193(255, 255, 255)
genv.HitboxColor = v194
local v195 = v190.PlayerAdded
local v196 = v195.Connect
v196(v195, function(...)
end)
local v198 = v40.CreateSection
v198(v40, "HitBox config")
local v200 = v40.CreateParagraph
v200(v40, {
    Title = "Como usar hitbox",
    Text = "Configure do seu jeito e basta clicar na bolinha em cima de outro player que a hitbox vai expandir.",
})
local v202 = v40.CreateSlider
v202(v40, {
    Callback = function(...)
    end,
    Increment = 1,
    Name = "Tamanho da hitbox",
    Range = {
        [1] = 1,
        [2] = 50,
    },
}, "Slider_HitboxSize")
local v204 = v40.CreateColorPicker
v204(v40, {
    Flag = "Hitbox_Color",
    Name = "Cor da hitbox",
    Callback = function(...)
    end,
}, "ColorPicker_Hitbox")
local v206 = v40.CreateSlider
v206(v40, {
    Callback = function(...)
    end,
    Increment = 0.1,
    Name = "Tamanho da bolinha",
    Range = {
        [1] = 2,
        [2] = 10,
    },
}, "Slider_SphereSize")
local v208 = v40.CreateToggle
v208(v40, {
    Name = "Ativar bolinha",
    Callback = function(...)
    end,
}, "Toggle_SphereVisible")
local v210 = v42.CreateSection
v210(v42, "ESP config")
local v212 = v42.CreateToggle
v212(v42, {
    Name = "ESP",
    Callback = function(...)
    end,
}, "ESP_Toggle")
local v214 = v42.CreateColorPicker
v214(v42, {
    Flag = "ESP_Color",
    Name = "ESP Color",
    Callback = function(...)
    end,
}, "ESP_Color")
local v216 = v42.CreateSlider
v216(v42, {
    Callback = function(...)
    end,
    Increment = 1,
    Name = "Tamanho ESP",
    Range = {
        [1] = 10,
        [2] = 30,
    },
}, "Text_Size")
genv.Toggle = false
genv.TeamCheck = false
genv.PlayerNameType = "Name"
local v218 = Color3.fromRGB
local v219 = v218(255, 255, 255)
genv.ESPColor = v219
genv.ESPFillTransparency = 0.5
genv.TextSize = 18
error("[string \"luau.load(...)\"]:1: attempt to call a nil value")
