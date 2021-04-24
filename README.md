# url-requested

A simple script that makes list of all the urls that a site request upon loading. The results are then saved to a txt file. 

## Installation


```bash
python -m pip install -r requirements.txt
```
## Usage

```python
python3 url.py example.com
```
A list of domains will be parsed and printed. Then the results are saved as a result$.txt file
## Examples

* Enter a domain with out http or www:

```python
python3 url.py


Enter a FULL domain to scan: reddit.com

Press the any key to see list of domains that were parsed and results will be saved to result$.txt 
 

['reddit.com',
 'www.reddit.com',
 'www.redditstatic.com',
 'preview.redd.it',
 'preview.redd.it',
 'preview.redd.it',
 'preview.redd.it',
 'external-preview.redd.it']

saved to result$.txt

 ```
## License
[MIT](https://choosealicense.com/licenses/mit/)
