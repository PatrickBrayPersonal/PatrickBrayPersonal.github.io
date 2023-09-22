# Python Packages
## Sematic
Excellent package with great artifacting of the data at each step.
The type checking is frustrating at the moment. You can't pass lists, which is absurd.
Also the error messages are rather unhelpful.
## MLFlow
The logging interface is incredible and autolog changes the game even further.
Major accelerator on any ML Project without experiment tracking.
## Darts
Darts *timeseries* is the dataframe of ts analysis. Built in functionality here is a major timesaver.
## NetworkX
A must for graph analysis. Not necessarily performant so watch out for that. Built in graph algorithms as well.
## cProfile
Profiling your code in an output log file. Can be hard to read.
## Fire
CLI for the lazy. Just uses function arguments.
```
import fire
main(arg1, arg2):
	print("blah")

if __name__ == __main__:
	fire.Fire(main)
```

```
python main.py --arg1 a --arg2 b
```
## dotenv
loads your .env file to environment variables
