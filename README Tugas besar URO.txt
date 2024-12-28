Perkenalkan nama saya Marco Yeremia Simanjuntak dari Cakru-17, berikut merupakan deskripsi tugas saya:

deskripsi:
program robot beroda dua yang diprogram menggunakan ros humble pada Linux ubuntu  dan disimulasikan dengan gazebo. robot ini adalah sebuah balok berwarna orange dengan 2 roda berwarna abu-abu.
ia dapat bergerak seperti yang kita inginkan dengan menggunakan keyboard karena disini saya menggunakan teleopkey.

cara menjalankan:
1. buat dan setup workspace ros2
2. cd ke directory src dan ketikkan: git clone <bagian file yang saya serahkan>
3. cd ke directory workspace dan ketikkan: colcon build --symlink-install
4. di directory yang sama, ketikkan: source install/local_setup.bash
5. untuk menjalankan simulasi gazebo ketikkan: ros2 launch my_first_pkg gazebo.launch.py
6. untuk menjalankan control robot melalui keyboard ketikkan: ros2 run teleop_twist_keyboard teleop_twist_keyboard
7. mainkan robot sesuka hati