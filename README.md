# Unity-Script
 
{Version 1:                                               (Version 1 makes sound when u click on an object)

using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class SoundOnTouch : MonoBehaviour
{
    

    void OnMouseDown()
    {
        GetComponent<AudioSource>().Play();
    }
}

End of version 1
                                                         
{Version 2:                                               (Version 2 only makes sound when you hold an object)



using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class SoundOnTouch : MonoBehaviour
{
    

    void OnMouseDown()
    {
        GetComponent<AudioSource>().Play();
    }
    
    void OnMouseUp()
    {
        GetComponent<AudioSource>().Stop();
    }

}

End of version 2
