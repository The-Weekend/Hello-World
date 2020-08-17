# Hello-World
learning GitHub
My name is Amritansh and i am learning how to GitHub for my team


badwtgs_10 <- dataprepare(  
  park_id <- '10',  
  eventcode <- '410',  
  supertag <- '430, 448, 645, 669, 672, 684, 687, 747, 801, 633, 609',  
  start_time_CT <- '01/01/2019',  
  end_time_CT <- '12/31/2019',  
  study_period_minute <- 10,  
  datatype_id <- 1,  
  timestep_id <- 3,  
  good_turbine <- 0)

write.csv(badwtgs_10, 'badwtgs_10min.csv')
