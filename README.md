# pr6-Sepulveda-Gonzalez-Angel-Alejandro-3W-1215

# 6. Función para capturar un email y verificar si es válido (contiene "@")

def validar_email(email):

  # Verificamos si el email contiene una '@' para considerarlo válido
    
  if "@" in email:
        
  # Si tiene '@', el email es válido
    
  return "Email válido"
    
  else:
    
  # Si no tiene '@', el email es inválido
        
  return "Email no válido"

# Pedimos al usuario que introduzca su dirección de email

email_usuario = input("Introduce tu dirección de email: ")

# Verificamos si el email es válido y mostramos el resultado

print(validar_email(email_usuario))
![image](https://github.com/user-attachments/assets/a2868770-4349-4a6e-9713-0fa1c9596969)
![image](https://github.com/user-attachments/assets/e4af6c2d-3d86-4602-8507-0d1fcfffcb29)
