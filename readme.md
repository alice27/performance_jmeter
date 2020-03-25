###Test task Jmeter
- the test scenario is placed in the root;
- reports are in reports folder;
- random csv is placed in random folder;

for a proper work of a random csv it has to be placed to /random folder regarding jmeter executable;

the report will be saved to /reports folder after the execution;

**jmeter -n -t "path_to_the_test" -Jusers=users_amount -Jramp_up=ramp_up_time -Jduration=thread_duration** is to run jmeter in console mod in win

**./jmeter.sh -n -t "path_to_the_test" -Jusers=users_amount -Jramp_up=ramp_up_time -Jduration=thread_duration** is to run jmeter in console mod in linux

The commands have to be executed in /bin folder of jmeter installation;