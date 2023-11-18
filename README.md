# BasicProgramming
Fundamentos de programación

#Comando básicos de Git
1. **Configurar Git con tus credenciales:**
   ```bash
   git config --global user.name "edro720189"
   git config --global user.email "edwin.rodriguez22@itca.edu.sv"
   ```

2. **Clonar un Repositorio:**

   ```bash
   git clone https://github.com/edro720189/[repositorio].git
   ```

3. **Cambiar de Rama:**
   ```bash
   git checkout nombre-rama
   ```

4. **Crear una Nueva Rama y Cambiarse a Ella:**
   ```bash
   git checkout -b nueva-rama
   ```

5. **Añadir Cambios al Área de Staging:**
   ```bash
   git add .
   ```

   O para añadir archivos específicos:
   ```bash
   git add nombre-archivo
   ```

6. **Hacer un Commit:**
   ```bash
   git commit -m "Mensaje descriptivo"
   ```

7. **Empujar Cambios a GitHub:**
   ```bash
   git push origin nombre-rama
   ```

   O para la rama principal (main):
   ```bash
   git push origin main
   ```

8. **Actualizar el Repositorio Local con los Cambios Remotos:**
   ```bash
   git pull origin nombre-rama
   ```

   O para la rama principal (main):
   ```bash
   git pull origin main
   ```

9. **Ver el Estado de tus Archivos y Commits:**
   ```bash
   git status
   ```

10. **Ver el Historial de Commits:**
   ```bash
   git log
   ```

Estos son solo algunos comandos básicos. Dependiendo de tu flujo de trabajo y las tareas que estés realizando, es posible que utilices comandos adicionales. Estos comandos deberían proporcionarte una base sólida para comenzar a trabajar con Git y GitHub.