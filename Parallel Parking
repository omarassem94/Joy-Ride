car_parameters = {"throttle": 0, "steer": 0, "brake": 0}

def control(pos_x, pos_y, time, velocity):
    """ Controls the simulated car"""
    global car_parameters
    
    if(pos_y > 38):
        car_parameters["throttle"] = -0.1
        car_parameters["steer"] = 25
    
    elif(pos_y > 36): 
        car_parameters["throttle"] = -0.1 

    elif(pos_y > 33): 
        car_parameters["throttle"] = -0.1 
        car_parameters["steer"] = -25
 
    else: 
        car_parameters["brake"] = 1 
        
        
        
       
    
    return car_parameters
    
