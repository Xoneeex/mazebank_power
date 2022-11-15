    local success = exports['mazebank_power']:StartMazeBankPower()
    if success then
        ESX.ShowNotification('Udane')
    elseif not success then
        ESX.ShowNotification('Nie Udane')
    end