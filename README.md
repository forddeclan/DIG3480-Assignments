using System.Collections;
using System.Collections.Generic;
using UnityEngine;
using UnityEngine.UI;

public class TextController : MonoBehaviour
{
    public Text NewText;
    // Start is called before the first frame update
    void Start()
    {
        
    }

    // Update is called once per frame
    void Update()
    {
        if(Input.GetKeyDown("space"))
        {
            NewText.text = "Hello my name is Declan Ford!"; 
        }

        if (Input.GetKey("escape"))
        {
            Application.Quit();
        }
    }
}

