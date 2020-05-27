# proyis
proyecto de curso

IMPORTANTE  luego de clonar el repositorio debemos darle permisos de ejecucion a los scripts de python 
            para esto nos ubicamos en el directorio robot_ws/src/robot_app y ejecutamos el comando
            
            chmod +x scripts/rotate.py
            
para crear los paquertes de robot y simulacion 
primero nos ubicamos en el directorio de robot_wr e ingresamos los comandos 

rosdep update
rosdep install --from-paths src --ignore-src -r -y
colcon build
colcon bundle

luego hacemos los mismo pero en el directrio simulation_wr
rosdep update
rosdep install --from-paths src --ignore-src -r -y
colcon build
colcon bundle


*los comandos colcon sirven para agrupar y compilar los codigos escrito(trabajo en ROS)
