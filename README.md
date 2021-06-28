Hackintosh for Acer A515-51G-85J9, made with [opencore](https://dortania.github.io) 0.7.1.


Supported versions:

MacOS Big Sur (11.x.x) is working almost bugless.

MacOS Monterey (12.x.x), has bugs: <s>USB-C isn't working</s> <- fixed, Bluetooth isn't working, it takes long to boot.


USB Tethering doesn't works well

Added tools to disable [CFG Lock](https://dortania.github.io/OpenCore-Post-Install/misc/msr-lock.html)

Added folder to fix crackling sound when using wired headphones (jack) -> open terminal, 
"""
cd jack fix 
sudo cp -R had-verb /usr/local/bin
./Jack\ fix
"""
Recommendation: settings -> users & groups -> login items -> press on the + at the bottom -> select "Jack fix" executable

credits: [SiddheshNan](https://github.com/SiddheshNan) for base EFI
