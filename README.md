# MKC-test2

'''JavaScript

  useEffect(() => {
    // Check local storage for dark mode preference
    const savedDarkMode = localStorage.getItem('DarkModeTheme');
    const isDarkMode = savedDarkMode === 'true';

    if (isDarkMode !== darkMode) {
      setDarkSidenav(dispatch, isDarkMode);
      setDarkMode(dispatch, isDarkMode);
    }

    LEts Update

  }, []);
