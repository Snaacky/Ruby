# Ruby
Auto bunny hopper for CS:GO.

## Get Started
1. Clone the repository
```
git clone https://github.com/Snaacky/Ruby.git
```

2. Install the prerequisites
```
pip install -r requirements.txt
```

3. Execute the script in a terminal with elevated privileges 
```
python ruby.py
```

## Warning
Ruby comes as is with no guarantees regarding its standing with VAC. This is a cheat and will get you banned if you attempt to use it on any cheat protected servers.

## Common Issues
* Issue: The token does not have the specified privilege.
    * Fix: The terminal or interpreter must be ran with administrator privileges.

* Issue: `AttributeError: 'NoneType' object has no attribute` or any other Python error.
    * Fix: Make sure you are running at least Python 3.5 (future versions may have breaking issues), have installed the correct versions of the required modules from requirements.txt, and have updated the offsets to the latest version of CS:GO.


## Requirements
* Windows (minimum Vista, recommended 7/8.1/10)
* [Python 3.5](https://www.python.org/downloads/)
* [Python for Windows Extensions](https://github.com/mhammond/pywin32)
* [Pymem](https://github.com/srounet/Pymem)
* [keyboard](https://github.com/boppreh/keyboard)
