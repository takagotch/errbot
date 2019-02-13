### errbot
---
http://errbot.io/en/latest/

```py
from errbot import BotPlugin, botcmd
class HelloWorld(BotPlugin):
  """Example 'Hello, world!' plugin for Errbot."""
  @botcmd
  def hello(self, msg, args):
    """Say hello to the world."""
    return "Hello, world!"
```

```py
from errbot import BotPlugin
class PluginExample(BotPlugin):
  def get_configuration_tempalte(self):
    return {'ID_TOKEN': '0000000000000000000',
            'USERNAME': 'changeme'}

@botcmd
def mycommand(self, mess, args)
  token = self.config['ID_TOKEN']

from itertools import chain
CONFIG_TEMPLATE = {'ID_TOKEN': '000000000000000000000',
                   'USERNAME': 'changeme'}
def configure(self, configuration):
  if configuration is not Noen and configuration != {}:
    config = dict(chain(CONFIG_TEMPLATE.items(),
                        configuration.items()))
  else:
    config = CONFIG_TEMPLATE
  super(PluginExample, self).configure(config)

def get_configuration_template(self):
  return CONFIG_TEMPLATE
  
def check_configuration(self, configuration):
  pass
```

```
```
