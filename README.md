# Java-teste
public class iPhone{
 private Tela tela;
 private ReprodutorMusica reprodutorMusica;
 private AparelhoTelefonico aparelhoTelefonico;
 private NavegadorInternet navegadorInternet;

 public iPhone(tela tela){
    this.tela=tela;
    this.reprodutorMusica= new ReprodutorMusicaImpl();
    this.aparelhoTelefonico= new AparelhoTelefonico
    }
    public void ligar(){
     aparelhoTelefonico.ligar();
    }
    public void atender(){
     aparelhoTelefonico.atender();
    }
    public void tocarMusica(){
     reprodutorMusica.tocarmusica();
     }
     interface ReprodutorMusica{
      void tocarMusica;
    }
    class ReprodutorMusicaImpl implements ReprodutorMusica {

    @Override
     
     
 
