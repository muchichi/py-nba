import pandas as pd
from nba_py import team

raptors_id = 1610612761

def nba_main():
    raptors = team.TeamPassTracking(raptors_id)
    rp = raptors.passes_made().head()
    print(rp)
    #Raptors last game passes
def nba_passes():
    raptors_last_game = team.TeamPassTracking(raptors_id,last_n_games=1)
    raptors_last_game.passes_made().head()
    
    #Last game team shot tracking
def nba_shots():
    raptors_shots = team.TeamShotTracking(raptors_id,last_n_games=1)
    raptors_shots.closest_defender_shooting()

if __name__ == '__main__': nba_main()