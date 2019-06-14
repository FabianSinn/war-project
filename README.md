# war-project
extract war information from wikidata or wikipedia infoboxes.
gather_infoboxes_new.py is the code file for extracting infoboxes from wikipedia.
get_combatant1a_info.py,get_participants1_info.py,get_participants2_info.py,get_participants3_info.py and get_participants4_info.py are the codes for extracting participants of each side from infoboxes.
info_participants_aggregate.py is the code file for aggregating all the participants informations into one dataset.
get_commander1_info.py,get_commander2_info.py,get_commander3_info.py,get_commander4_info.py are the codes for getting commanders of each side from infoboxes.
info_commanders_aggregate.py is the code file for aggregating all the commander informations into one dataset.
get_time.py, get_location.py and get_partof.py are the files to get time dataset, location dataset and partof dataset respectively. Note the dataset got from get_partof.py is not in the form which Arash suggested.
the refactoring_script.py is the file for getting the information of conflicts and revolutions in the human history from wikipedia, including the participants ,commanders, time partof and locations. So it can be seen as the collection of the older files. But this file can not be used to catch the infoboxes from wikipedia articles. If you want to do so, please use gather_infoboxes_new.py instead.
