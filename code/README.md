# Blackboard Administrator Panel Header Colorize

Here is the CSS style code. Copy and paste it into the Stylus import box.

'@-moz-document url("https://your.blackboard.instance/ultra/admin") {
.base-header {
    background-color: #66cd8d !important;
}

}

@-moz-document url("https://your.blackboard.instance/ultra/admin") {
.base-header {
    background-color: #000000 !important;        
}

h1.page-title {
    color: #fff !important;
}

a.admin-back-button {
    color: #fff !important;
}
}

@-moz-document url-prefix("https://your.blackboard.instance/ultra/admin") {
.base-header {
    background-color: #4f2682 !important;
}

h1.page-title {
    color: #fff !important;
}

a.admin-back-button {
    color: #fff !important;
}
}'