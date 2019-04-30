# testproject-sg
git clone https://github.com/ivngithub/testproject-sg.git  
cd testproject-sg  
pip install sg-0.1.tar.gz  
  
import sg  
r = sg.get_log.logic_processing('maillog') #'maillog' is log file  
r = sg.get_log.show_results(r)  
print(r)  
