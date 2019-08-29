# supportops_requests

This is a new landing page for people to raise requests for HMH Tier 3 Support Ops.

This page is hosted on the following EC2 instance using nginx: 10.34.39.211

## Editing
The essentials for this page is located at /home/ec2-user/supportops_requests/html on the instance.
If you are making changes to the code make sure to update the html folder on the instance and push the code to this repo.

After changes are made on the instance run the following command: /etc/init.d/nginx restart

nginx information such as ports etc are located at: /etc/nginx/nginx.conf
