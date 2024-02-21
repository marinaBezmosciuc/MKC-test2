# MKC-test2

LEts Update
'''JavaScript

  useEffect(() => {
    // Check local storage for dark mode preference
    const savedDarkMode = localStorage.getItem('DarkModeTheme');
    const isDarkMode = savedDarkMode === 'true';

    if (isDarkMode !== darkMode) {
      setDarkSidenav(dispatch, isDarkMode);
      setDarkMode(dispatch, isDarkMode);
    }
  }, []);
