from almalinux:8
arg username
run adduser $username
user $username
arg trainer
arg course
run echo "trainer is $trainer and the course is $course"
env trainer = $trainer \
    course = $course
cmd ["sleep" , "100"]