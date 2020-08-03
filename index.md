<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>Learning HTML</title>
    </head>
    <body>
        <h1>Hello World</h1>

        Hello again

        <h3>Next Title</h3>

        <p>This is a paragraph</p>

        <p>This is the next paragraph</p>

        <h1>Links</h1>

        <p>I want to have a link to facebook.com <a href="http://www.facebook.com">here</a>.</p>

        <p>This link opens google in a new tab <a href="http://www.google.com.au" target="_blank">here</a>.</p>

        <h1>Images</h1>

        This is an image:
        <br/>
        <img src="beard.png" width="150" />

        <br/>

        <h1>Lists</h1>

        My favourite foods:
        <ol>
            <li>Pizza</li>
            <li>Pizza</li>
            <li>Pizza</li>
        </ol>

        To Do List:
        <ul>
            <li>Task 1</li>
            <li>Task 2</li>
            <li>Task 3</li>
        </ul>

        <h1>Tables</h1>

        <table border="1">
            <thead>
                <tr>
                    <th>Month</th>
                    <th>Sales</th>
                    <th>Costs</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>January</td>
                    <td>10000000</td>
                    <td>0</td>
                </tr>
                <tr>
                    <td>Feburary</td>
                    <td>34445000000</td>
                    <td>1</td>
                </tr>
                <tr>
                    <td>March</td>
                    <td>600</td>
                    <td>2</td>
                </tr>
            </tbody>
        </table>

        <h1>Forms</h1>

        <form>
            <div>
                <input type="text" value="Name"/>
            </div>
            <div>
                <input type="text" placeholder="Username"/>
            </div>
            <div>
                <input type="text" placeholder="Password"/>
            </div>
            <div>
                <button submit="submit">Submit details</button>
            </div>
        </form>

        <h1>Other types of inputs</h1>

        <form>
            <div>
                <input type="number" value="5" min="1" max="10" />
            </div>
            <div>
                <input type="color" />
            </div>
            <div>
                <input type="date" />
            </div>
            <div>
                <input type="range" value="20" min="1" max="100" />
            </div>
            <div>
                <textarea rows="5" cols="40">Default Content</textarea>
            </div>
            <div>
                <select>
                    <option>Pizza 1</option>
                    <option>Pizza 2</option>
                    <option>Pizza 3</option>
                    <option>Pizza 4</option>
                    <option>Pizza 5</option>
                    <option selected="selected">Original</option>
                </select>
            </div>
            <div>
                <select multiple="multiple">
                    <option>Car 1</option>
                    <option>Car 2</option>
                    <option>Car 3</option>
                    <option>Car 4</option>
                    <option>Car 5</option>
                </select>
            </div>
        </form>
    </body>
</html>















