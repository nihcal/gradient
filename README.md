# gradient
<style>
position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  --gradient-color-1: red;
  --gradient-color-2: blue;
  --gradient-color-3: green;
</style>

<canvas id="gradient-canvas"></canvas>

<script>
    import { Gradient } from './gradient';
    
    const gradient = new Gradient();
    gradient.initGradient('#beep-gradient')
</script>
