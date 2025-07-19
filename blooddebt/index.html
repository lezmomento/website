-- guns some guns will appear as unknown so add them urself
-- this is is not GUI based!! it is not an internal script!
-- this script tells you who is the murderer and the sherrif by outputting the answer in LUAVM
-- script is free to use however you like
-- made for external exploits 
-- discord: loleazymoment
local killerWeapons = {
    ["CharcoalSteel JS-22"] = true, ["Pretty Pink RR-LCP"] = true,
    ["JS2-BondsDerringy"] = true, ["GILDED"] = true, ["Kamatov"] = true,
    ["JS2-Derringy"] = true, ["JS-22"] = true, ["NGO"] = true,
    ["Throwing Dagger"] = true, ["SoundMaker"] = true, ["SoundMakerSlower"] = true,
    ["RR-LightCompactPistolS"] = true, ["J9-Mereta"] = true, ["RY's GG-17"] = true,
    ["RR-LCP"] = true, ["JS1 Competitor"] = true, ["AT's KAR15"] = true,
    ["VK's ANKM"] = true, ["Clothed Sawn-off"] = true, ["Sawn-off"] = true,
    ["Clothed Rosen-Obrez"] = true, ["Rosen-Obrez"] = true,
    ["GraySteel K1911"] = true, ["DarkSteel K1911"] = true,
    ["SilverSteel K1911"] = true, ["K1911"] = true, ["ZZ-90"] = true,
    ["SKORPION"] = true, ["Mares Leg"] = true, ["RR-LightCompactPistol"] = true,
    ["KamatovS"] = true, ["Throwing Tomahawk"] = true, ["Throwing Kunai"] = true,
    ["ChromeSlide Turqoise RR-LCP"] = true, ["JS-1 CYCLOPS"] = true,
    ["THUMPA"] = true, ["LUT-E 'KRUS'"] = true
}

local vigilanteWeapons = {
    ["Beagle"] = true, ["IZVEKH-412"] = true, ["SilverSteel RR-Snubby"] = true,
    ["RR-Snubby"] = true, ["ZKZ-Obrez"] = true, ["GG-17"] = true,
    ["J9-M"] = true, ["J9-Meretta"] = true, ["Pretty Pink GG-17"] = true,
    ["GG-17 TAN"] = true, ["GG-17 GILDED"] = true,
    ["RR-Snubby GILDED"] = true, ["HWISSH-226"] = true, ["ZKZ-Obrez10"] = true
}

-- Gun checker function
local function findGun(container)
    for _, item in ipairs(container:GetChildren()) do
        if item:FindFirstChild("GUNCHECK") then
            return item.Name
        end
    end
    return nil
end

-- logic lol
local playersFolder = game:FindFirstChild("Players")
local npcsFolder = workspace:FindFirstChild("NPCSfolder")

if not playersFolder then
    warn("[ERROR] 'Players' folder not found.")
    return
end

for _, player in ipairs(playersFolder:GetChildren()) do
    local name = player.Name
    local backpack = player:FindFirstChild("Backpack")
    local npcModel = nil
    local gunName = nil

    -- Look in Backpack first
    if backpack then
        gunName = findGun(backpack)
    end

    -- If not in Backpack, try to find their model under NPCSfolder
    if not gunName and npcsFolder then
        for _, npc in ipairs(npcsFolder:GetChildren()) do
            if npc.Name == name then
                npcModel = npc
                break
            end
        end

        if npcModel then
            gunName = findGun(npcModel)
        end
    end

    -- roles
    if gunName then
        local role = "[UNKNOWN GUN]"
        if killerWeapons[gunName] then
            role = "[KILLER]"
        elseif vigilanteWeapons[gunName] then
            role = "[SHERIFF]"
        end
        print("[RESULT]: " .. name .. " has a gun: " .. gunName .. " " .. role)
    else
        print("[RESULT]: " .. name .. " does NOT have a gun.")
    end
end
