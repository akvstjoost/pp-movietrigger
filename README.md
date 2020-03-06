# pp-movietrigger
This pi presents project starts or stops a movie with a switch connecting to ground on GPIO 11

get the raspbian image with pi presents installed from https://thomasrutgers.stackstorage.com/s/LA2Sbgaqi2mLlYl (the password is the name of the schools workshop/lab, t.....b)

put the movietrigger folder in the ```/home/pi/pp_profiles/``` folder

edit movie location in file ```mediashow.json``` (or use the ppwebeditor)

start it with: ```pp -f -p movietrigger```
(```pp``` is an alias for ```python /home/pi/pypresents.py```)

end with: ctrl-break
