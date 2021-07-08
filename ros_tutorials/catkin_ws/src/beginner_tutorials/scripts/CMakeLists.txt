catkin_install_python(PROGRAMS scripts/talker.py scripts/listener.py
	  DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION}
	  )
