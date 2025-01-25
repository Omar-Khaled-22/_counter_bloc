# counterapp

1-Set up a new Flutter project and add the flutter_bloc package to pubspec.yaml

2-create the counter cubit

3- Add cubit to your app

4-Access State
{Use context.read<CounterCubit>() to call the increment abd decrement methods
Use BlocBuilder to rebuild the UI when the state changes}

5-Update a Text widget to display the current counter value using BlocBuilder

6- Show a dialog when the counter reaches a negative value using BlocListener

7- make counter app with BlocConsumer to display the counter and
show a message whenever the counter reaches 10 or -10.
