 using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class PlayerMovement : MonoBehaviour
{
    Rigidbody rb;
    
    // Start is called before the first frame update
    void Start()
    {
        
        Debug.Log("Hello!");
    }

   void update ()
{
// This code is our player jump mechanic
  if(Input.GetButtonDown("space"))
  {
    GetComponent<Rigidbody2D>().velocity= newVector3(0,7,0);
  }
// This is our players 
}
}
