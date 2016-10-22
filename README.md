# Penn New Student Orientation Python SDK [Depreciated as of August 2016]

A quick ical parser to be used for NSO 2016 in place of an RSS Feed to list event times, locations, descriptions, etc.

## License

This is published under the MIT license. See [LICENSE](LICENSE).

Setup
-----
* Install [redis](http://redis.io/)
* Create new virtualenv
* Install requirments using 'pip install -r requirements.txt'
* Run the NSO API server using 'python runserver.py'

## Usage

<span name="dates"></span>
### View All Dates
<table>
<tr>
<td>URL</td>
<td><code>http://api.pennlabs.org/nso</code></td>
</tr>
<tr>
<td>Response Formats</td>
<td>JSON</td>
</tr>
</table>

<span name="events"></span>
### View All Events on Specific Date
<table>
<tr>
<td>URL</td>
<td><code>http://api.pennlabs.org/nso/events?q={date}</code></td>
</tr>
<tr>
<td>Parameters</td>
<td>
<table>
	<tr>
	<td>Name</td>
	<td>Default</td>
	<td>Description</td>
	<td>Example Values</td>
	</tr>
	<tr>
	<td>q</td>
	<td><strong>Required</strong></td>
	<td>The date of interest</td>
	<td>08-23-2016, 09-04-2016</td>
	</tr>
</table>
</td>
</tr>
</table>
