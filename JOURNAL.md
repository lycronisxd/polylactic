<h1>polylactic journalling.</h1>
<h3>entry 1, 27/07/26: 16:32 - 16:47</h3>
very short entry, since all i wanted to do to start off the build was outline some basic specifications that i want to include in my 3d printer.<br \>
i will paste the entire speclist here, but it is in the repo if you would like to look at it some more.<br \>
<img width="842" height="543" alt="image" src="https://github.com/user-attachments/assets/bf705d27-33dd-4826-848a-2c9749da247b" /><br \>
<br \>
<b>
entry time: 15 minutes<br \>
total time: 15 minutes
</b>
<hr>
<h3>entry 2, 27/07/26: 16:55 - 20:15</h3>
this entire entry consisted of 3d modelling. im tired.<br \>
i started off by importing some basic parts that i asm going to use for the printer, 2020 and 2040 aluminium extrusion, mgn12h rails etc etc.<br \>
i then resized everything to my liking and started designing the movement of each axis.<br \>
i started with the y-axis, because it is the easiest with just 1 linear rail on a piece of 2040 extrusion.<br \>
i then moved on to the z-axis and it was torture!<br \>
im proposing to use lead screws for the z-axis, but because im using linear rails, i had to make a custom collar type-thing that wraps around the extrusion and fits a t8 brass nut.<br \>
finally, i started to add the motor models into the design for clearance sake - but im halfway through as of writing this and will continue another time.<br \>
so here's the current model -<br \>
<img width="512" height="606" alt="image" src="https://github.com/user-attachments/assets/eefc9d63-c62e-430e-9990-e2c801e500ff" /><br \>
<br \>
<b>
entry time: 3 hours 20 minutes<br \>
total time: 3 hours 35 minutes
</b>
<hr>
<h3>entry 3, 29/07/26: 10:55 - 11:02, 11:28 - 13:45</h3>
okay so turns out all that time spent was lowkey useless because now i want to switch up my design to a corexy design thats direct drive and not bowden<br \>
so firstly, i updated the speclist.md to fit my new specs.<br \>
then - i deleted my entire onshape assembly and resized some parts i already had in my document to suit the new design.<br \>
i spent all the rest of the time designing and modelling the z-axis system for the printer.<br \>
<img width="729" height="759" alt="image" src="https://github.com/user-attachments/assets/82bac9ba-41ca-48af-9402-4bdd1969e1b4" /><br \>
its a 3 point z-axis system, meaning i need 3 motors to control the z-axis so the bed doesnt tilt in any weird ways<br \>
im planning to add a 5:1 gear reduction so the z moves more precisely<br \>
will also add motor mounts etc. in my next entry - just needed to model for clearance sake!<br \>
<br \>
<b>
entry time: 2 hours 54 minutes<br \>
total time: 6 hours 29 minutes
</b>
<hr>
<h3>entry 4, 31/07/26: 14:43 - 16:49</h3>
third z-axis redesign!!!!!!!!!<br \>
i swear it should not be this hard.<br \>
i re-designed all the rail and idler mounts and made them a lower profile.<br \>
i added the 5:1 reduction for the z-axis for torque reasons and am finally ready to attach all the motors to the bottom in the next entry.<br \>
<img width="636" height="690" alt="image" src="https://github.com/user-attachments/assets/f7674f5b-1d5b-492e-8c02-e411095222aa" /><br \>
too much time spent thinking so thats all for today :(<br \>
<br \>
<b>
entry time: 2 hours 6 minutes<br \>
total time: 8 hours 35 minutes
</b>
<hr>
<h3>entry 5, 03/08/26: 12:05 - 14:28</h3>
sooooo i redesigned some more :)<br \>
this is the final one i swear - using lead screws and linear rails instead of belt driving the z-axis so it doesnt fall when powers off.<br \>
i then redesigned the bed holder into a H instead of a T so i can use t-nuts in the aluminium extrusions for the bed<br \>
<br \>
and then for the actual work apart from redesign and optimization! (theres not much)<br \>
i added the y-axis linear rails and made motor mounts so that i can route corexy belts when needed<br \>
and then i added the x-axis crossbar and a linear rail on the top!<br \>
<br \>
next im going to finish off the x and y axis and then start on the toolhead mounts after!<br \>
this is the current state of the printer.<br \>
<br \>
<img width="561" height="619" alt="image" src="https://github.com/user-attachments/assets/080b3160-9fca-4a0e-a3a5-be495083d0f6" /><br \>
<br \>
<b>
entry time: 2 hours 23 minutes<br \>
total time: 10 hours 58 minutes
</b>
<hr>
<h3>entry 6, 04/08/26: 09:52 - 11:48</h3>
okay, a lot of progress today with the corexy gantry!!<br \>
i actually properly made a mount for the x axis rails that i can mount gt2 idler pulleys on<br \>
<img width="620" height="438" alt="image" src="https://github.com/user-attachments/assets/30ca61d8-f8ce-460c-87e3-9d226dc6384d" /><br \>
and made some gt2 idler corner mounts too (tried to make them reversable so i dont need to make loads of different models when printing)<br \>
<img width="776" height="555" alt="image" src="https://github.com/user-attachments/assets/f52f541c-6f5e-4f9b-8a9a-a3578bed83bc" /><br \>
<img width="666" height="400" alt="image" src="https://github.com/user-attachments/assets/5629119c-61a2-465e-95c1-15fbf904412e" /><br \>
then mated all the pulleys to the mounts (hoping to use m5 screws to bolt them down)<br \>
and finally modelled a belt that works on the y axis (not x axis yet because i havent modelled the carriage)<br \>
<img width="753" height="457" alt="image" src="https://github.com/user-attachments/assets/a8654a85-6965-4a11-90c6-5c6f9fd19f7a" /><br \>
and this is the current model!<br \>
<img width="603" height="592" alt="image" src="https://github.com/user-attachments/assets/5e70efcb-edf5-4b0e-85bf-64b9d0df1167" /><br \>
<br \>
<b>
entry time: 1 hour 56 minutes<br \>
total time: 12 hours 54 minutes
</b>
<hr>
<h3>entry 7, 04/08/26: 15:32 - 16:37</h3>
not much to say in this session other than i modelled the x-axis carriage and amended the belt for aesthetic reasons<br \>
<img width="779" height="534" alt="image" src="https://github.com/user-attachments/assets/de89d695-56e1-498d-a1a2-21e91de07beb" /><br \>
<img width="539" height="581" alt="image" src="https://github.com/user-attachments/assets/8384f68b-0c14-4cb5-8cf6-9fd85361a06c" /><br \>
so this is the final corexy belt path<br \>
<img width="684" height="687" alt="image" src="https://github.com/user-attachments/assets/7ddf66cc-1d5c-4539-9564-3957dc2f09f1" /><br \>
and this is what the printer looks like now<br \>
<img width="541" height="648" alt="image" src="https://github.com/user-attachments/assets/23cb3779-6b75-41f5-b4df-6162a8abf9ea" /><br \>
next up is to model the mount for the toolhead and filament drive,<br \>
and then also model the mounts for the aluminium extrusion so it will actually stay together<br \>
and then FINALLY model and feet to elevate the printer and mount the electronics to the printer.<br \>
<br \>
<b>
entry time: 1 hour 5 minutes<br \>
total time: 13 hours 59 minutes
</b>
<hr>
