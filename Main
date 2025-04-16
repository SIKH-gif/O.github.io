using UnityEngine;

public class PlayerController : MonoBehaviour
{
    public float speed = 10f;
    public float horizontalSpeed = 5f;

    private Vector3 movement;

    void Update()
    {
        // Forward movement
        movement.z = speed * Time.deltaTime;

        // Horizontal movement
        float horizontalInput = Input.GetAxis("Horizontal");
        movement.x = horizontalInput * horizontalSpeed * Time.deltaTime;

        // Apply movement
        transform.Translate(movement);
    }
}
