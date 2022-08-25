# Symbol-Blaster
Game with modern user interface (UI) inspired by retro arcade cabinets. Written in C# using Windows Presentation Foundation (WPF). Prototyped in Adobe XD.

![Symbol Blaster - prototype](/media/symbol_blaster_prototype.gif "Symbol Blaster - prototype")

# Summary
Symbol Blaster features a Model-View-ViewModel (M-V-VM) architecture to implement the UI and game world. A MainViewModel governs the state and behavior of the UI, while a GameViewModel governs the state and behavior of the game. The eXtensible Application Markup Language (XAML) code that defines the "skeleton" of the UI incorporates the ViewModel logic through various data-bindings that enable the user to influence application state. Since the UI navigation topology is fixed at compile time, navigation is handled by a simple TabControl populated with TabItems that contain collapsible sections. Both the front-end XAML and the back-end ViewModel components are modular in order to foster development efficiency and easier maintenance. NUnit is the unit testing framework used to conduct automated testing of the application
![Symbol Blaster - overview](/media/symbol_blaster_overview.gif "Symbol Blaster - overview")

# Features
- Modern "flat" UI prototyped in Adobe XD and implemented in XAML
- User Experience (UX) features for streamlined usage:
  - informative tooltips
  - dynamically resizable text
  - game control mapping visualization
  - form submission management
  - fluid-resize of applicaton
- Rudimentary game mechanics
- Custom update loop rendering performed via a CompositionTarget.Rendering event handler
- Unit tested with NUnit

# Screenshots
![Symbol Blaster - artboards](/media/symbol_blaster_artboards.gif "Symbol Blaster - artboards")
![Symbol Blaster - color selector](/media/symbol_blaster_color_selector.gif "Symbol Blaster - color selector")
![Symbol Blaster - comparison](/media/symbol_blaster_comparison.gif "Symbol Blaster - comparison")
![Symbol Blaster - game objects](/media/symbol_blaster_game_objects.gif "Symbol Blaster - game objects")
![Symbol Blaster - presets](/media/symbol_blaster_presets.gif "Symbol Blaster - presets")
![Symbol Blaster - sprites](/media/symbol_blaster_sprites.gif "Symbol Blaster - sprites")
