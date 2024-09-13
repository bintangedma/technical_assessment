def max_skill_level(N, current_skill, opponents_skill, reward):
    # Combine skill levels and rewards into a list of tuples
    opponents = list(zip(opponents_skill, reward))
    print(opponents)
    # Sort opponents by their skill levels (Ai)
    opponents.sort(key=lambda x: x[0])
    print(opponents)
    
    
    # Iterate through the sorted opponents
    for skill, reward in opponents:
        # Check if Juned can defeat the current opponent
        if current_skill >= skill:
            # Increase Juned's skill by the reward
            current_skill += reward
        else:
            # If Juned can't defeat this opponent, break the loop
            break
    
    return current_skill

# Input
N, M = map(int, input().split())  # Read N and M
A = list(map(int, input().split()))  # Read Ai values
B = list(map(int, input().split()))  # Read Bi values
# N, M = [4,2]
# A = [8,9,3,2]
# B = [5,4,1,3]

if (N != len(A) or N != len(B))  : 
    print('The length of A or B is not in desirable length (N length).')
else :
    if (1 <=N and M <= 100) :
        inside_range = True
        for r_a in A : 
            if 1 <= r_a <= 1000 : 
                ...
            else : 
                inside_range = False 
        for r_b in B : 
            if 1 <= r_b <= 1000 : 
                ...
            else : 
                inside_range = False 
        if inside_range is True : 
            range_b = [d for d in B]
            print(max_skill_level(N, M, A, B))
            print(N, len(A))
        else : 
            print('length of A or B does not meet the criteria (1 <= Ai/Bi <= 1000)')
    else :
        print('N must be more or equal than 1 and M must be below or equal 100')
    

# Output the maximum skill level Juned can achieve
# print(max_skill_level(N, M, A, B))
