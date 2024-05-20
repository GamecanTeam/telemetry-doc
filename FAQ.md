# FAQ

**Q: How does your plugin compare to other telemetry plugins in terms of visualization and data accuracy?**

*A: Our plugin balances performance, clarity, and customization, providing valuable game data insights without affecting gameplay smoothness. It handles high-performance data for millions of events (tested with around 4 million), offers precise 3D shape visualizations, and ensures accurate data representation. Advanced filtering capabilities help focus on specific data points and avoid information overload.*

**Q: Does this plugin work in the editor (PIE) and in packaged builds (for network data collection)?**

*A:  Our plugin offers functionalities for both the editor and packaged builds, The editor module visualizes collected data, allowing you to analyze it in real-time during development, and The runtime module seamlessly integrates into your packaged game and collects data. (Current functionality focuses on local data collection, but future updates may introduce cloud data streaming capabilities.)*

**Q: Can the plugin use custom data sources?**

*A: The plugin offers some flexibility for integrating custom data sources. However, it's important to understand that the plugin itself doesn't directly support custom data sources. This involves writing code to extract and format the data you want to record.*

**Q: Does it work well with large, open worlds using Unreal Engine's world partition system?**

*A: The plugin excels in large, open-world environments. Its ability to record millions of events without compromising performance makes it a perfect fit for open-world games.*

**Q: Does using the plugin impact game performance while recording data?**

*A: Our focus on performance optimization ensures minimal impact on gameplay while recording data. This has been thoroughly tested in our fast-paced game, Contenders: Arena, so you can be confident using the plugin in demanding scenarios.*

**Q: Can I access recorded data during gameplay (runtime) or is it only usable in the editor? How are visualizations displayed in packaged builds?**

*A: While runtime visualization within the game itself is not currently supported, the collected data can be loaded and analyzed using the editor tool. we're exploring adding this functionality in future updates. *

**Q: Is the plugin compatible with dedicated servers, particularly Linux builds?**

*A: Absolutely! The plugin has been thoroughly tested in a real-world scenario, Our development team utilizes Linux-based dedicated servers for our own game, Contenders: Arena. We've successfully leveraged the plugin to record valuable server-side data.*

**Q: Which Unreal Engine versions does this plugin support?**

*A: While we strive to offer broad compatibility, our current plugin version officially supports Unreal Engine versions 5.3 and above.*
