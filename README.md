# jQuery Paginator 3000

## Usage

HTML:

    <div class="paginator" id="paginator1"></div>
    
JavaScript:

    $('paginator1').paginator();
    
## Settings

<table class="options">
    <thead>
        <tr>
            <th>Property</th>
            <th>Type</th>
            <th>Default</th>
            <th>Description</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>pagesTotal</td>
            <td>int</td>
            <td>1</td>
            <td>Total pages count</td>
        </tr>
        <tr>
            <td>pagesSpan</td>
            <td>int</td>
            <td>10</td>
            <td>Length span of pages</td>
        </tr>
        <tr>
            <td>pageCurrent</td>
            <td>int</td>
            <td>50</td>
            <td>Сurrent page number</td>
        </tr>
        <tr>
            <td>baseUrl</td>
            <td>string</td>
            <td>index.html?page=%number%</td>
            <td>URL pattern</td>
        </tr>
        <tr>
            <td>buildCounter</td>
            <td>function</td>
            <td></td>
            <td>Function for calculating page numbers</td>
        </tr>
        <tr>
            <td>clickHandler</td>
            <td>function</td>
            <td></td>
            <td>The callback function is called when was clicked page link</td>
        </tr>
        <tr>
            <td>returnOrder</td>
            <td>bool</td>
            <td>false</td>
            <td>Flag display pages in reverse order</td>
        </tr>
        <tr>
            <td>lang</td>
            <td>object</td>
            <td></td>
            <td>Object of localization</td>
        </tr>
    </tbody>
</table>
