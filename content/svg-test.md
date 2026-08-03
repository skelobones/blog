---
title: Monochrome SVG Test
tags:
publish: true
publishDate: 2026-08-03
aliases:
enableToc: false
---

I want to draw things for this website that are positive/negative. However, with dark mode, the contrast will be lost. I did some research on .svg's and styling (2 hours well spent) and found out how to! This example is a portion of a diagram syntax I'm making up. I want to be able to draw factory diagrams for Minecraft Create mod automation. I'll eventually write about that but for now I'm trying to get this to work.

Play with the **dark mode icon** at the top to see how (or if) the image changes color!

<svg version="1.2" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 256 256" width="256" height="256">
	<style>
		tspan { white-space:pre } 
		.s0 { fill: none;stroke: currentColor;stroke-miterlimit:10 } 
		.t1 { font-size: 8px;fill: currentColor;font-weight: 400;font-family: "OpenSansRoman-Regular", "Open Sans" } 
	</style>
	<g id="Layer 1">
		<path id="Shape 2" fill-rule="evenodd" class="s0" d="m9.05 219.4c1.13 0.82 7.01 0.3 7.58 0.31 8.15 0.15 8.52 0.21 17.57 0.29 23.57 0.21 47.14-0.15 70.72-0.15"/>
		<path id="Shape 3" fill-rule="evenodd" class="s0" d="m105.19 220.14c-1.29-0.59-1.84-4.18-2.3-5.47-0.94-2.69-1.85-5.96-1.23-8.84 0.45-2.04 4.2-7.49 6.97-5.19 2.51 2.08 0.74 6.87-0.52 9.03-1.74 2.98-2.93 6.01-3.18 9.45"/>
		<path id="Shape 4" fill-rule="evenodd" class="s0" d="m104.08 221.35c-0.33 1.26-0.39 2.65-0.59 3.95-0.42 2.79-2.04 12.34 4.57 10.36 1.42-0.43 1.46-3.19 1.46-4.32 0.02-4.97-5.4-10.14-5.44-9.99z"/>
		<path id="Shape 22" fill-rule="evenodd" class="s0" d="m116.26 217.09c0.01-1.22 0.39-2.37 0.74-3.54 3.88-12.76 12.58 3.31 20.48 3.19 3.41-0.05 6.77-1.18 9.42-3.33 1.57-1.28 1.79-3.27 3.92-3.49"/>
		<path id="Shape 23" fill-rule="evenodd" class="s0" d="m119.04 225.44c-2.71-3.22 5.14-4.21 6.37-4.01 5.07 0.81 21.16 12.6 20.87-0.24"/>
		<path id="Shape 24" fill-rule="evenodd" class="s0" d="m9.66 38.77c28.65 0 67.46 3.39 95.98 0.81"/>
		<path id="Shape 25" fill-rule="evenodd" class="s0" d="m103.44 35.7c-1.12-3.49-1.25-14.39 5.23-13.17 2.01 0.38 0.42 6.4-0.07 7.39-2.23 4.51-11.41 15.39-7.5 20.68 5.3 7.19 8.53-2.37 6.88-7.15-0.36-1.04-4.17-6.6-4.54-7.75z"/>
		<path id="Shape 26" fill-rule="evenodd" class="s0" d="m109.9 32.69c0.75-1.64 9.72-0.64 11.25 0.33 5.49 3.5 8.9 9.57 15.08 12.21 5.2 2.23 10.78 0.8 16.2 0.61"/>
		<path id="Shape 27" fill-rule="evenodd" class="s0" d="m110.23 44.87c1.64 1.52 7.59-0.54 9.19-1.33 4.29-2.12 6.84-6.67 10.91-8.74 5.36-2.71 11.61-1.1 17.23-0.81"/>
		<path id="Shape 28" fill-rule="evenodd" class="s0" d="m157.39 31.04c-0.65 0.47-0.45 2.37-0.46 2.93-0.07 3.35-0.02 6.7-0.02 10.04"/>
		<path id="Shape 29" fill-rule="evenodd" class="s0" d="m157.15 38.49c16.98 0 64.16 0 81.14 0"/>
		<path id="Shape 7" fill-rule="evenodd" class="s0" d="m158.24 208.52q0 10.55 0 21.1"/>
		<path id="Shape 8" fill-rule="evenodd" class="s0" d="m158.91 218.65c23.75 0 63.36-0.85 87.09-0.85"/>
		<path id="Shape 9" fill-rule="evenodd" class="s0" d="m10.78 156.3c8.38-1.37 36.99-0.78 45.39-0.81q25.12-0.11 50.23-0.46"/>
		<path id="Shape 10" fill-rule="evenodd" class="s0" d="m105.5 153.55c-2.44-3.38-4.99-6.79-4.63-11.2 0.35-4.3 5.2-4.7 7.65-2.22 4.78 4.84-5.16 16.93-6.22 22.5-0.63 3.26-0.93 8.74 3.6 8.5 6.82-0.36 2.42-12.07 1.22-15.19-0.28-0.73-1.21-4.51-1.94-4.79"/>
		<path id="Shape 11" fill-rule="evenodd" class="s0" d="m113.58 144.69q8.69 0 17.37 0c2.53 0 6.64 0.8 9.09-0.51"/>
		<path id="Shape 12" fill-rule="evenodd" class="s0" d="m113.45 155.09c9.25 0.49 18.5-0.3 27.74-0.3"/>
		<path id="Shape 13" fill-rule="evenodd" class="s0" d="m114.22 163.22c10.19 0 20.83 0.94 30.93-0.63"/>
		<path id="Shape 14" fill-rule="evenodd" class="s0" d="m156.91 144.05c0.06 7.35 1.15 14.64 1.15 21.99"/>
		<path id="Shape 15" fill-rule="evenodd" class="s0" d="m158.32 153.51c18.29 1.33 62.71 0.9 81.08 0.9"/>
		<path id="Shape 16" fill-rule="evenodd" class="s0" d="m9 96.62c22.84 0.09 41.21 0.44 64.05 0.52 10.58 0.03 21.67 0.91 32.21-0.25"/>
		<path id="Shape 17" fill-rule="evenodd" class="s0" d="m105.78 97.19c-0.18-2.7-8.81-16.72-1.2-17.6 4.65-0.54 5.44 3.59 3.61 6.84-2.09 3.72-12.12 18.06-5.61 22.1 5.77 3.58 4.04-11.76 3.66-13.4"/>
		<path id="Shape 18" fill-rule="evenodd" class="s0" d="m112.87 91.62q17.19 0 34.38 0"/>
		<path id="Shape 19" fill-rule="evenodd" class="s0" d="m114.08 100.09q16.1 0 32.2 0"/>
		<path id="Shape 20" fill-rule="evenodd" class="s0" d="m156.14 84.83c0.86 6.23 1.74 12.94 1.83 19.23"/>
		<path id="Shape 21" fill-rule="evenodd" class="s0" d="m157.97 94.67c21.96 0 17.82 0 39.98 0 4.62 0 29.93-0.1 40.81-0.46"/>
		<text id="Washing" style="transform: matrix(1.504,0,0,1.504,9.475,214.87)">
			<tspan x="0" y="0" class="t1">W</tspan><tspan  y="0" class="t1">a</tspan><tspan  y="0" class="t1">s</tspan><tspan  y="0" class="t1">h</tspan><tspan  y="0" class="t1">i</tspan><tspan  y="0" class="t1">n</tspan><tspan  y="0" class="t1">g</tspan><tspan  y="0" class="t1">
</tspan>
		</text>
		<text id="Blasting" style="transform: matrix(1.504,0,0,1.504,10.979,151.718)">
			<tspan x="0" y="0" class="t1">B</tspan><tspan  y="0" class="t1">l</tspan><tspan  y="0" class="t1">a</tspan><tspan  y="0" class="t1">s</tspan><tspan  y="0" class="t1">t</tspan><tspan  y="0" class="t1">i</tspan><tspan  y="0" class="t1">n</tspan><tspan  y="0" class="t1">g
</tspan>
		</text>
		<text id="Smoking" style="transform: matrix(1.504,0,0,1.504,9.475,93.076)">
			<tspan x="0" y="0" class="t1">S</tspan><tspan  y="0" class="t1">m</tspan><tspan  y="0" class="t1">o</tspan><tspan  y="0" class="t1">k</tspan><tspan  y="0" class="t1">i</tspan><tspan  y="0" class="t1">n</tspan><tspan  y="0" class="t1">g</tspan><tspan  y="0" class="t1">
</tspan>
		</text>
		<text id="Haunting" style="transform: matrix(1.504,0,0,1.504,10.979,34.435)">
			<tspan x="0" y="0" class="t1">H</tspan><tspan  y="0" class="t1">a</tspan><tspan  y="0" class="t1">u</tspan><tspan  y="0" class="t1">n</tspan><tspan  y="0" class="t1">t</tspan><tspan  y="0" class="t1">i</tspan><tspan  y="0" class="t1">n</tspan><tspan  y="0" class="t1">g
</tspan>
		</text>
	</g>
</svg>