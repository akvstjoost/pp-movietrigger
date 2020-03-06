# pp-movietriggger
This pi presents project starts or stops a movie with a switch connecting to ground on GPIO 11

get the image from https://thomasrutgers.stackstorage.com/s/LA2Sbgaqi2mLlYl (the password is the name of the schools workshop/lab, t.....b)

put the movietrigger folder in the ```/home/pi/pp_profiles/``` folder

edit movie location in file ```mediashow.json``` (or use the ppwebeditor)

start with: ```python /home/pi/pipresents.py -f -p movietrigger```
(or shorter, in the image you can use the pp alias: ```pp -f -p movietrigger```)

end with: ctrl-break
