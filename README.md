-- Variável inicial para armazenar a velocidade
local velocidade = 16 -- Velocidade inicial (padrão para Roblox)

-- Função para aumentar a velocidade
local function aumentarVelocidade()
    while true do
        wait(1) -- Espera 1 segundo
        velocidade = velocidade + 1 -- Aumenta a velocidade em 1
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = velocidade
    end
end

-- Executa a função
aumentarVelocidade()
