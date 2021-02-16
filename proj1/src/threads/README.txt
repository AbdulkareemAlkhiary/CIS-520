In order to incorporate the the alarm-mega a few adjustments needed to be made such as:
1. Copying alarm-multiple.ck to the same folder while renaming the file to alarm-mega.ck.
2. Adjust the function parameter inside alarm-mega.ck from 7 to 70.
3. Add the function definition to alarm-wait.c for alarm-mega with function parameter (5,70).
4. Include alarm-mega tests/threads_TESTS in Make.Tests.
5. Include alarm-mega in Rubric.alarm.
6. Add {"alarm-mega", test_alarm_mega}, to test struct in tests.c.
7. Add extern test_func test_alarm_mega; to tests.h.





