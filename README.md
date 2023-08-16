# jquery-zoomslider

ZoomSlider creates slideshows with a zoom effect using background-image and CSS3.
- - -

 *  zoomSlider - v0.1
 *  Title: ZoomSlider creates slideshows with a zoom effect using background-image and CSS3.
 *  Author: Amit Arya <https://github.com/aryaitandmedia/jquery-zoomslider>
 *  Website: aryaitandmedia.com
 *  Email: amit@aryaitandmedia.com
 *  Description: This program has been customized and reproduced with a feature to load slider captions as well
 *  Credit: Ming Yeung <https://github.com/mingyeungs/jquery-zoomslider>
 *  Under MIT License
 
Dependencies: 
	
- jQuery: 1.10.2+
- Modernizr: 2.6.2+ <small>(for css3 transform support detection. May implement custom script to remove this dependency in future)</small>

To initialize the zoom slider, add the attribute **data-zs-src** to a DOM element and the slider will auto-initialize.

	<div data-zs-src='["img1.jpg", "img2.jpg", "img3.jpg"]'>
    	<p>Sample inner content</p>
	</div>
	
All configurable properties:

<table>
	<thead>
		<tr>
			<th>Data attribute</th>
			<th>Default value</th>
			<th>Possible values</th>
		</tr>
	</thead>
	<tbody><tr>
		<td>data-zs-src</td>
		<td>null</td>
		<td>[]</td>
	</tr>
	<tr>
		<td>data-zs-speed</td>
		<td>8000</td>
		<td>Number (milliseconds)</td>
	</tr>
	<tr>
		<td>data-zs-switchSpeed</td>
		<td>800</td>
		<td>Number (milliseconds)</td>
	</tr>
	<tr>
		<td>data-zs-interval</td>
		<td>4500</td>
		<td>Number (milliseconds)</td>
	</tr>
	<tr>
		<td>data-zs-autoplay</td>
		<td>true</td>
		<td>true / false</td>
	</tr>
  <tr>
		<td>data-zs-titles</td>
		<td>null</td>
		<td>[]</td>
	</tr>
	<tr>
		<td>data-zs-bullets</td>
		<td>true</td>
		<td>true / false</td>
	</tr>
	<tr>
		<td>data-zs-overlay</td>
		<td>'plain'</td>
		<td>false, 'plain', 'dots'</td>
	</tr>
</tbody></table>
