# Update-a-File-using-Python
As part of my role, I am required to regularly update a file that identifies the employees who can access restricted content. The contents of the file are based on who is working with personal patient records. Employees are restricted access based on their IP address. There is an allow list for IP addresses permitted to sign into the restricted subnetwork. There's also a remove list that identifies which employees you must remove from this allow list.

My task is to create an algorithm that uses Python code to check whether the allow list contains any IP addresses identified on the remove list. If so, the algorithm should remove those IP addresses from the file containing the allow list.
