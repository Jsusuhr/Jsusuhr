print('welcome the scrip secret')

--secret scrip--

--base
function main()
local button=gg.choice({'kill','reset','Sair'})
if button == 1 then kill() end
if button == 2 then reset() end
if button == 3 then sair() end
end

--function--

function kill()
gg.searchNumber('6',gg.TYPE_DOUBLE)
gg.getResults('1000')
gg.editAll('7',gg.TYPE_DOUBLE)
end


function sair()
os.exit()
end

while(true) do while gg.isVisible(true)
do 
gg.setVisible(false)
 main() 
 end
 end

--fim
