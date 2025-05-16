local args = {
    [1] = "Jolgue_001",
    [2] = "Hi",
    [3] = "Currency",
    [4] = "23214a5287f14f9cbb314b16e249d55d",
    [5] = 1000000000000
}

game:GetService("ReplicatedStorage").Network:FindFirstChild("Mailbox: Send"):InvokeServer(unpack(args))
