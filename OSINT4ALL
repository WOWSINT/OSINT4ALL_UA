 while true do
local obloka = [[   ___  ____ ___ _   _ _____ _  _     _    _     _     
 / _ \/ ___|_ _| \ | |_   _| || |   / \  | |   | |    
| | | \___ \| ||  \| | | | | || |_ / _ \ | |   | |    
| |_| |___) | || |\  | | | |__   _/ ___ \| |___| |___ 
 \___/|____/___|_| \_| |_|    |_|/_/   \_\_____|_____|
                                            ]]
print(obloka)
io.write("1. пошук через шерлок\n2. пошук через дорки\n3. взнати коли був зроблений сайт\n4. перевірити чи активний сайт\n5. генератор досьє\n6. nmap ")
local test = io.read()
if tonumber(test) == 1 then
    io.write("Введіть імʼя до пошуку: ")
local sherlock = io.read()
    os.execute("sherlock " .. sherlock)
elseif tonumber(test) == 5 then
    io.write("ПІБ: ")
    io.read()
    io.write("номер: ")
    io.read()
    io.write("оператор: ")
    io.read()
    io.write("місто: ")
    io.read()
    io.write("email: ")
    io.read()
    io.write("соцмережі: ")
    io.read()
elseif tonumber(test) == 6 then
    io.write("Введіть IP для перевірки: ")
    local domain = io.read()
    os.execute("nmap -sV " .. domain)
elseif tonumber(test) == 4 then
    io.write("Введіть домен для перевірки: ")
    local domain = io.read()
    os.execute("ping -c 4 " .. domain)
elseif tonumber(test) == 3 then
    io.write("Введіть домен для перевірки: ")
    local domain = io.read()
    os.execute("whois " .. domain)
elseif tonumber(test) == 2 then
    print(obloka)
io.write("1. пошук за точним словом\n2. пошук по конкретному сайті ")
local toch = io.read()
if tonumber(toch) == 1 then
    print(obloka)
    io.write("Введіть слово для пошуку: ")
    local word = io.read()
    os.execute('firefox --search \'"' .. word .. '"\' &')
elseif tonumber(toch) == 2 then
    print(obloka)
    io.write("Виберіть сайт для пошуку \n1. olx.ua\n2. пошук по всім державним реєстрам\n3.по телеграм\n4. пошук по публічним карток компаній та підприємств\n5. пошук по YouControl\n6. пошук по державних закупівель ")
    local site = io.read()--дорк сайт
    if tonumber(site) == 1 then
        io.write("Введіть слово для пошуку:  ")
        local site1 = io.read()--слово
        os.execute('firefox --search \'site:olx.ua "' .. site1 .. '"\' &')
    elseif tonumber(site) == 2 then
        io.write("Введіть слово для пошуку:  ")
        local site2 = io.read()--слово
        os.execute('firefox --search \'site:*.gov.ua "' .. site2 .. '"\' &')
    elseif tonumber(site) == 3 then
        io.write("Введіть слово для пошуку: ")
        local site3 = io.read()--слово
        os.execute('firefox --search \'site:t.me "' .. site3 .. '"\' &')
    elseif tonumber(site) == 4 then
        io.write("Введіть слово для пошуку: ")
        local site4 = io.read()--слово
        os.execute('firefox --search \'site:opendatabot.ua "' .. site4 .. '"\' &')
    elseif tonumber(site) == 5 then
        io.write("Введіть слово для пошуку: ")
        local site5 = io.read()--слово
        os.execute('firefox --search \'site:youcontrol.com.ua "' .. site5 .. '"\' &')
    elseif tonumber(site) == 6 then
        io.write("Введіть слово для пошуку: ")
        local site6 = io.read()--слово
        os.execute('firefox --search \'site:clarity-project.info "' .. site6 .. '"\' &')

end
end
end
end
