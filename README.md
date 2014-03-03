nagios-plugins-elasticsearch                                                    
============================                                                    
                                                                                
Overview                                                                        
--------                                                                        
                                                                                
This project contains a set of nagios checks useful for monitoring Elasticsearch in the context of Logstash logs storage.
                                                                                
Usage                                                                           
-----                                                                         
                                                                                
Check if there are PostgreSQL events from a specific host during the last 60 seconds
                                                                                
    ./check_elasticsearch_events --second 60 --query "type:postgresql AND host:mypghost"
    

License
-------

Copyright (c) 2013 All rights reserved.

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.
    
    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.
    
    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.
