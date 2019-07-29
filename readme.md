<html>
  <head>
    <title>TattingCAD</title>
    <!-- Fabric.js library -->
    <script src="js/fabric.js"></script>
    <!-- jQuery -->
    <script src="js/jquery-3.4.1.js"></script>
    <!-- Material Design Lite for Tooltips -->
    <link rel="stylesheet" href="css/material.indigo-pink.min.css" />
    <script src="js/material.min.js"></script>
    <!-- Toolbars Library https://github.com/danielktaylor/gToolbars.js -->
    <link rel="stylesheet" type="text/css" href="css/gToolbars-0.2.0.css" />
    <script src="js/gToolbars-0.2.0.js"></script>
    <!-- FileSaver https://github.com/eligrey/FileSaver.js/ -->
    <script src="js/FileSaver.js"></script>
    <!-- Main app -->
    <link rel="stylesheet" href="css/tatting.css" />
    <script src="js/tatting.js"></script>
  </head>
  <body>
    <div id="container">
      <div class="gt-toolbar">
        <div id="toolbar-undo" class="gt-button"></div>
        <div class="mdl-tooltip mdl-tooltip--large gt-noselect" for="toolbar-undo">Annulla</div>
        <div class="gt-separator"></div>
        <div id="toolbar-file-open" class="gt-button"></div>
        <input type="file" id="file_open" name="file_open" accept=".tat">
        <div class="mdl-tooltip mdl-tooltip--large gt-noselect" for="toolbar-file-open">Apri file</div>
        <div id="toolbar-file-save" class="gt-button"></div>
        <div class="mdl-tooltip mdl-tooltip--large gt-noselect" for="toolbar-file-save">Salva</div>
        <div class="gt-separator"></div>
        <div id="toolbar-simple-node" class="gt-button"></div>
        <div class="mdl-tooltip mdl-tooltip--large gt-noselect" for="toolbar-simple-node">Nodo doppio</div>
        <div id="toolbar-picot" class="gt-button"></div>
        <div class="mdl-tooltip mdl-tooltip--large gt-noselect" for="toolbar-picot">Picot</div>
        <div id="toolbar-arc" class="gt-button"></div>
        <div class="mdl-tooltip mdl-tooltip--large gt-noselect" for="toolbar-arc">Arco</div>
        <div id="toolbar-text-box" class="gt-button"></div>
        <div class="mdl-tooltip mdl-tooltip--large gt-noselect" for="toolbar-text-box">Box di testo</div>
        <div class="gt-separator"></div>
        <div id="toolbar-clone" class="gt-button"></div>
        <div class="mdl-tooltip mdl-tooltip--large gt-noselect" for="toolbar-clone">Clona</div>
        <div id="toolbar-group" class="gt-button"></div>
        <div class="mdl-tooltip mdl-tooltip--large gt-noselect" for="toolbar-group">Raggruppa</div>
        <div id="toolbar-ungroup" class="gt-button"></div>
        <div class="mdl-tooltip mdl-tooltip--large gt-noselect" for="toolbar-ungroup">Separa</div>
        <div id="toolbar-colors" class="gt-button"></div>
        <div class="mdl-tooltip mdl-tooltip--large gt-noselect" for="toolbar-colors">Colore</div>
        <input class="colorPickerBtn" type="color" value="#FF0000" id="colorPicker" style="display:none">
        <div id="toolbar-delete" class="gt-button"></div>
        <div class="mdl-tooltip mdl-tooltip--large gt-noselect" for="toolbar-delete">Elimina</div>
        <div class="gt-separator"></div>
        <div id="toolbar-send-backward" class="gt-button"></div>
        <div class="mdl-tooltip mdl-tooltip--large gt-noselect" for="toolbar-send-backward">Porta indietro</div>
        <div id="toolbar-bring-forward" class="gt-button"></div>
        <div class="mdl-tooltip mdl-tooltip--large gt-noselect" for="toolbar-bring-forward">Porta avanti</div>
        <div class="gt-separator"></div>        
        <div id="toolbar-zoom-out" class="gt-button"></div>
        <div class="mdl-tooltip mdl-tooltip--large gt-noselect" for="toolbar-zoom-out">Zoom out</div>
        <div id="toolbar-zoom-in" class="gt-button"></div>
        <div class="mdl-tooltip mdl-tooltip--large gt-noselect" for="toolbar-zoom-in">Zoom in</div>
        <div id="toolbar-zoom-reset" class="gt-button"></div>
        <div class="mdl-tooltip mdl-tooltip--large gt-noselect" for="toolbar-zoom-reset">Zoom Reset</div>
        <div class="gt-separator"></div>
        <div id="toolbar-clear" class="gt-button"></div>
        <div class="mdl-tooltip mdl-tooltip--large gt-noselect" for="toolbar-clear">Cancella tutto</div>
      </div>
      <!-- /toolbar -->
      <br><br>
      <canvas id="canvas" width="1900" height="890"></canvas>
    </div>
    <!-- /container -->
  </body>
</html>