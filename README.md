# Simple readme - how to run experiments.

open a blank python project and copy paste the files in the repository there (this is an ad hoc repository with the purpose of only making the code available!)

the python version required is 3.8

go to main.py

near the bottom of the file, under the "if __name__ == '__main__':" line, there are number of parameters that you can change
the parameters are listed here with an example of values to use.

number_of_agents_list = [7,8]

number_of_faulty_list = [5]

agent_fault_probabilities_list = [0.9]

number_of_runs_list = [50]

number_of_instances_list = 30


for the above examples, the output will consist of 60 instances, with each of them showcasing 5 faulty agents, fault probability of 0.9, and spectrum with 50 lines. for 30 of the instances there will be a total of 7 agents, and for the other 30 - 8 agents.
