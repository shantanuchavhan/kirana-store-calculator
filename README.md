# kirana-store-calculator
sum=0
list=[]
count=0
while True:
    try:
        count+=1
        
        userInput=input("enter the prise: \n")
       
        
        if (userInput!="q"):
            list.append(userInput)
            
            sum=sum+int(userInput)
            print(f"order otal so far:{sum}") 
        else:
            print("bbk store ")
            index=1
            for item in list:
                print(f"{index}:{item}")
                index+=1
            print(f"your bill total is {sum}.Thanks for shopping")
            break
    except Exception as  e:
        print("please enter again")


    
    

    
