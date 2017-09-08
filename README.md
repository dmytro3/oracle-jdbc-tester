# jdbc-tester

A simple command line application to test JDBC connection to Oracle Database.

## How to run

Clone this repository and then run:

```
mvn clean package
```
Or download the JAR file from [release](https://github.com/aimtiaz11/jdbc-tester/releases) page. 

Execute the JAR file with the following 3 parameters with schema name, password and JDBC connection details:

```
java -jar target/jdbc-tester-1.0.jar <schema_name> <schema_password> jdbc:oracle:thin:@//<host>:<port>/<SID>
```

## License

(The MIT License)

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.