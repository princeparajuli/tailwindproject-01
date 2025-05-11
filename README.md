# tailwindproject-01
here i have created tailwind clone
to make it run 
step-1
>terminal
>npm install tailwindcss @tailwindcss/cli
step-2
input.css
>@import "tailwindcss";
step-3
>terminal
>npx @tailwindcss/cli -i .templates/index/input.css -o ./output/output.css --watch
step-4
>crtl+c
go to package
>add=>"scripts":
{"tailwind:run":"npx @tailwindcss/cli -i .templates/index/input.css -o ./output/output.css --watch"
}
step-5
>go to terminal again
npm run tailwind:run
step-6
index.html
>on <head>
<link href="/output/output.css" rel="stylesheet">
</head>
