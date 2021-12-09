# Tahoma-TSA-1
Test repository

Movement inside update():

       if (Input.GetKeyDown("space"))
        {
            GetComponent<Rigidbody>().velocity = new Vector3(0, 3, 0);
        }

       if (Input.GetKey("w"))
        {
            GetComponent<Rigidbody>().velocity = new Vector3(0, 0, 3);
        }
        
       if (Input.GetKey("s"))
        {
            GetComponent<Rigidbody>().velocity = new Vector3(0, 0, -3);
        }
        
       if (Input.GetKey("a"))
        {
            GetComponent<Rigidbody>().velocity = new Vector3(-3, 0, 0);
        }
        
       if (Input.GetKey("d"))
        {
            GetComponent<Rigidbody>().velocity = new Vector3(3, 0, 0);
        }
