# repo1
A completely easy way of programming
#hactoberfest2022
#hactoberfest

def pallindrome(n):
    low=0 
    high  = len(n)-1
    # for i in range (len(n)):
    while(low < high):

        if n[low] != n[high] :
            print ('NO')
            break
        low = low+1
        high = high -1
    else:
        print('yes')









n = input('enter a name')
(pallindrome(n))
