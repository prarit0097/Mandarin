import java.awt.Color;
import java.awt.Dialog;
import java.awt.Dimension;
import java.awt.EventQueue;
import java.sql.Connection;
import java.util.*;
import java.sql.DriverManager;
import java.sql.PreparedStatement;
import java.sql.ResultSet;
import java.sql.ResultSetMetaData;
import java.sql.SQLException;
import java.text.DateFormat;
import java.text.SimpleDateFormat;
import java.time.LocalDate;
import java.time.ZoneId;
import java.time.format.DateTimeFormatter;

import javax.swing.JFrame;
import javax.swing.JLabel;
import javax.swing.JMenuItem;
import javax.swing.JOptionPane;
import javax.swing.JPanel;
import javax.swing.JPopupMenu;
import javax.swing.JScrollPane;
import javax.swing.JSeparator;
import javax.swing.JTabbedPane;
import javax.swing.JTable;

import java.awt.Font;
import java.awt.HeadlessException;
import java.awt.Image;
import java.awt.Toolkit;
import java.awt.Window;

import javax.print.attribute.standard.MediaSize.Other;
import javax.swing.DefaultComboBoxModel;
import javax.swing.JButton;
import javax.swing.JComboBox;
import javax.swing.JComponent;
import javax.swing.JDialog;
import javax.swing.JFileChooser;
import javax.swing.JTextField;
import javax.swing.SwingConstants;
import javax.swing.UIManager;
import javax.swing.table.DefaultTableModel;
import javax.swing.table.TableModel;

import com.toedter.calendar.JDateChooser;
import com.toedter.calendar.demo.DateChooserPanel;

/*import javafx.scene.Group;
import javafx.scene.Scene;
import javafx.scene.image.ImageView;
import javafx.scene.image.WritableImage;*/
import net.proteanit.sql.DbUtils;

import java.awt.event.ActionListener;
import java.awt.event.ActionEvent;
import java.awt.event.MouseAdapter;
import java.awt.event.MouseEvent;
import java.awt.event.MouseListener;
import java.beans.Statement;
import java.io.FileNotFoundException;
import java.io.IOException;
import java.nio.file.Files;
import java.nio.file.LinkOption;
import java.nio.file.Path;
import java.nio.file.Paths;
import java.nio.file.StandardCopyOption;

import javax.swing.JTextArea;
import javax.swing.ScrollPaneConstants;
import java.awt.event.KeyAdapter;
import java.awt.event.KeyEvent;
import com.toedter.calendar.JCalendar;
import javax.swing.ImageIcon;
import javax.swing.JPasswordField;
import javax.swing.JToggleButton;
import javax.swing.JWindow;
import javax.swing.JCheckBox;
import javax.swing.Icon;
import java.awt.BorderLayout;

import java.awt.image.BufferedImage;
import java.awt.image.DataBufferByte;
import java.awt.image.WritableRaster;
import java.io.FileNotFoundException;
import java.io.IOException;
import java.sql.Connection;
import java.sql.PreparedStatement;

/*import javafx.application.Application;
import javafx.embed.swing.SwingFXUtils;
import javafx.scene.Group;
import javafx.scene.Scene;
import javafx.scene.image.ImageView;
import javafx.scene.image.WritableImage;
import javafx.stage.Stage;*/

import java.awt.EventQueue;
import java.awt.Image;
import java.awt.image.BufferedImage;
import java.awt.image.DataBufferByte;
import java.io.ByteArrayOutputStream;
import java.io.File;
import java.io.FileInputStream;
import java.io.IOException;
import javax.imageio.ImageIO;
import javax.swing.JFrame;
import javax.swing.text.Element;
import java.awt.image.BufferedImage;
import java.awt.image.DataBufferByte;
import java.awt.image.WritableRaster;

import java.io.FileNotFoundException;
import java.io.IOException;

/*import org.opencv.core.Core;
import org.opencv.core.CvType;
import org.opencv.core.Mat;
import org.opencv.core.Scalar;
*/
import java.awt.image.BufferedImage;
import java.awt.image.DataBufferByte;
import java.awt.image.WritableRaster;

import java.io.FileNotFoundException;
import java.io.IOException;

/*import javafx.application.Application;
import javafx.embed.swing.SwingFXUtils;
import javafx.scene.Scene;
import javafx.scene.image.WritableImage;
import javafx.stage.Stage;*/

/*
import org.opencv.core.Core;
import org.opencv.core.Mat;
//import org.opencv.imgcodecs.Imgcodecs;
//import org.opencv.videoio.VideoCapture;
import org.opencv.core.Core;
import org.opencv.core.Mat;
//import org.opencv.imgcodecs.Imgcodecs;
//import org.opencv.videoio.VideoCapture;
*/
import javax.swing.ImageIcon;
import javax.swing.JButton;
import java.awt.event.ActionListener;
import java.awt.event.ActionEvent;
import javax.swing.JLabel;
import javax.swing.JOptionPane;

public class Trailor {

	public static JFrame f1;
	static Connection conn = null;
	int i = 0, ix1 = 0, ix2 = 0, ix3 = 0, ix4 = 0, ix5 = 0;
	int i1 = 0, i2 = 0;
	int l0 = 0, l1 = 0, l2 = 0, l3 = 0, l4 = 0, l5 = 0, l6 = 0, hk1 = 0, hk2 = 0, hk3 = 0, hk4 = 0, hk5 = 0, hk6 = 0;
	static DefaultTableModel model1, model2, model3, model4, model5, model6;
	static int row1, row2, row3, row4, row5, row6;
	double m, m1, m2, m3, m4, m5, m6, m7, m8, m9, m10, m11;
	JTextField date001, date002, date003, date004, date005, date006, date007, date008, date009, date0010, date0011,
			date0012;
	JPopupMenu popupMenu, popupMenu_1, popupMenu_2;
	JMenuItem menuItemAdd, menuItemAdd_1, menuItemAdd__1;
	JMenuItem menuItemRemoveAll;

	double shirtPeace, shirtPrice, Total_shirt_price;
	double pentPeace, pentPrice, Total_pent_price;
	double coatPeace, coatPrice, Total_coat_price;
	double jacketPeace, jacketPrice, Total_jacket_price;
	double kurtaPeace, kurtaPrice, Total_kurta_price;
	double pjamaPeace, pjamaPrice, Total_pjama_price;
	Double Totalall;
	double Total1, Total2, Total3, Total4, Total5, Total6;

	public String cv1, cv2, cv3, cv4, cv5, cv6, cv7, cv8, cv9, cv10;
	public String id01, id02, id03, id04, id05, id06;

	public static JPanel panel0, panel9, panel10, panel11, panel2, panel12, panel13, panel14, panel15, panel16, panel18,
			panel19, panel17, panel20, panel4, panel1, panel6, panel7, panel5, panel8, panel, panel21, panel22, panel23,
			panel24, panel25, panel26, panel27;

	private JTextField t6;
	int i01, i02, i03, i04;
	public String ax1, ax2, a7;
	Double q0 = 0.0, q01 = 0.0;
	public String s1, s2, s3, s4, s5, s6, s7, s8, s9, s10, s11, s12, s13, s14, s15, s16, s17, s18, e1, e2, e3, e4, e5,
			d1, d2, d3, d4, d5, d6, d7, d8, e6;
	public String Shirt, pent, Coat, Jacket, Kurta, Pjama;
	public String sid, s_6 = "User", s_7 = "Admin", s_8;
	public String x6, x7, x8, x9;
	public int id1;
	public String r1, r2, r3, r4, r5, r6, r7, r8, r9, r10, r11, r12, r13, r14, r15, r16, r17, r18, r19, r20, r21, r22,
			r23, r24, r25, r26, r27, r28, r29, r30, r31, r32, r33, r34, r35, r36, r37, r38, r39, r40, r41, r42, r43,
			r44, r45, r46, r47, r48, r49;
	public String o1, o2, o3, o4, o5, o6;
	public String za1, za2, za3, za4, za5, za6, za7, za8, zb1, zb2, zb3;
	String address, contact, name1, id2, Employee_id;
	public String w1, w2, w3, w4, w5, w6, w7, w8, w9, w10, w11, w12;
	public String wt1, wt2, wt3, wt4, wt5, wt6, wt7, wt8, wtx3, wtx4, wtx5, wt9, wt10, wt11;
	JComboBox comboBox_01;
	String n = null, un = null, q = null, a = null, n1 = null, nn = null;
	private JTextField t1;
	private JTextField t2;
	private JTextField t3;
	private JTextField t5;
	private JTextField t_1;
	private JTextField t_2;
	private JTextField t_3;
	private JTextField t_5;
	JTextField pass1;
	JTextField pass;
	JTextField en, ec, ed;
	JLabel lblEmployeeAddress, lblEmployeeName, lblEmployeeContact, lblEmployeeid, lblpent, lblShirt;
	JTable table;
	JLabel lbllmbai1, lblseena, lblkemer1, lblteera, lblbaju, lblgla;
	JLabel lbllmbai2, lblkemer2, lblhip, lblmori, lblgoda, lblpett, lblgidri;
	JComboBox comboBox_001;
	public String qw1 = null, qw2 = null, qw3 = null, qw4 = null;
	public String emp;
	private JTextField textField_2;
	private JTextField textField_3;
	private JTextField textField_4;
	private JTextField a_2;
	private JTextField a_1;
	private JTextField a_3;
	private JTextField a_4;
	private JTextField a_5;
	private JTextField a_6;
	private JLabel lblNewLabel;
	private JTextField a_7;
	private JTextField b1;
	private JTextField b2;
	private JTextField b3;
	private JTextField b4;
	private JTextField b5;
	private JTextField b6;
	private JTextField b7;
	private JTextField t_01;
	private JButton btnSearch;
	private JTextField ef;
	private JTextField textField_002;
	private JTextField textField_003;
	private JTextField textField_004;
	private JTextField textField_005;
	private JTextField t_001;
	private JTextField textField_001;
	private JTextField t_0001;
	private JTable table_3;
	private JTextField g1;
	private JTextField g2;
	private JTextField g3;
	private JTextField g4;
	private JTextField g5;
	private JTextField g6;
	private JTextField g7;
	private JTextField g8;
	private JTextField h2;
	private JTextField h3;
	private JTextField h4;
	private JTextField h7;
	private JTextField h6;
	private JTextField h1;
	private JTextField h5;
	private JTextField t_02;
	private JComboBox comboBox_02;

	private JLabel lblStartingDate;
	private JLabel lblEndingDate;
	JDateChooser chooser, chooser1;
	String x3;
	String x4;
	String up, up_1;
	public static JTable table_5;
	public JTable table_6;
	public String q1, q2, q3, q4, q5, q6, q7, q8, q9, q10, q11, q12, q13, q14, q15, q16, q17, q18, q19, q20, q21, q22,
			q23, q24, q25, q26, q27, q28;
	public Double q29 = 0d, q30 = 0d;
	public String hh1, hh2, hh3, hh4;
	public String z1, z2, z3, z4, z5, z6, z7, z8, z9, z10, z11, z12, z13, z14, z15, z16, z17, z18, z19, z20, z21, z22,
			z23, z24;
	public String y1, y2, y3, y4, y5, y6, y7, y8, y9, y10, y11, y12, y13, y14, y15, y16, y17, y18, y19, y20, y21, y22,
			y23, y24;
	LocalDate d, dx1, dx2, dx3, dx4, dx5;
	private JTextField txf;
	LocalDate billDate;
	int j;
	String id_1;
	private JTextField textField;
	private JButton btnNewButton;
	private JLabel lblName;
	private JLabel lblUsername;
	private JLabel lblQuestion;
	private JLabel lblAnswer;
	private JLabel label_2;
	private JLabel label_3;
	private JLabel label_5;
	private JLabel label_6;
	private JTextField textField_5;
	private JTextField textField_6;
	private JTextField textField_7;
	private JTextField textField_8;
	private JTextField textField_9;
	private JTextField textField_10;
	private JTextField textField__10;
	private JTextField textField_12;
	private JScrollPane scrollPane_111;
	private JTable table_8;
	private JTextField textField_13;
	private JTextField textField_14;
	private JTextField textField_15;
	private JTextField textField_16;
	private JLabel label_10;
	private JLabel label_14;
	private JLabel label_15;
	private JTable table_9;
	private JScrollPane scrollPane_3;
	private JLabel lblEmployeeName_1;
	private JLabel lblTotal;
	private JTextField textField_17;
	private JTextField textField_18;
	private JLabel lblDayTotal;
	private JTextField textField_19;
	private JTextField textField_20;
	public String pa4, pa5;
	private JLabel label_20;
	public String aq, User, s_5;
	private JTextField textField_21;
	private JTextField textField_22;
	private JTextField textField_23;
	private JTable table_10;
	private JPasswordField t7;
	private JTextField textField_25;
	private JTable table_1;
	private JTable table_4;
	private JTable table_7;
	private JTextField d_1;
	private JTextField d_2;
	private JTextField d_3;
	private JTextField d_5;
	private JTextField d_4;
	private JTextField e_1;
	private JTextField e_2;
	private JTextField e_3;
	private JTextField e_7;
	private JTextField e_6;
	private JTextField e_5;
	private JTextField e_4;
	private JTextField f_1;
	private JTextField f_2;
	private JTextField f_3;
	private JTextField f_7;
	private JTextField f_6;
	private JTextField f_5;
	private JTextField f_4;
	private JTextField c1;
	private JTextField c2;
	private JTextField c3;
	private JTextField c7;
	private JTextField c6;
	private JTextField c5;
	private JTextField c4;
	private JTextField c8;
	private JTextField c9;
	private JTextField c10;
	private JTextField textField_29;
	private JTextField h16;
	private JTextField h15;
	private JTextField h14;
	private JTextField h13;
	private JTextField h12;
	private JTextField h11;
	private JTextField h10;
	private JTextField h9;
	private JTextField h8;
	private JTextField h17;
	private JTextField h22;
	private JTextField h29;
	private JTextField h30;
	private JTextField h23;
	private JTextField h18;
	private JTextField h19;
	private JTextField h20;
	private JTextField h21;
	private JTextField h28;
	private JTextField h27;
	private JTextField h26;
	private JTextField h25;
	private JTextField h24;
	private JTextField h31;
	private JTextField h32;
	private JTextField h33;
	private JTextField h34;
	private JTextField h35;
	public static JTable table_11;
	public static JTable table_12;
	public static JTable table_13;
	public static JTable table_14;
	public static JTable table_15;
	public static JTable table_16;
	public static JTable table_17;
	public static JTable table_18;
	public static JTable table_19;
	public static JTable table_20;
	public static JTable table_21;
	public static JTable table_22;
	public static JTable table_23;
	private JTable table_24;
	private JTable table_25;
	private JTable table_26;
	private JTable table_27;
	private JTable table_28;
	private JTable table_29;
	private JTable table_30;
	private JTable table_31;
	private JTable table_32;
	private JTable table_33;
	private JTextField a_8;
	private JTextField a_9;
	private JTextField c11;
	private JTextField c12;
	private JTextField e_8;
	private JTextField e_9;
	private JTextField g9;
	private JTextField textField_26;
	private JTextField textField_27;
	private JTextField textField_28;
	private JTextField textField_30;
	private JPasswordField passwordField;
	private JTextField textField_31;
	private JTextField textField_32;
	private JTextField textField_33;
	private JTextField textField_34;
	private JTextField textField_35;
	private JTextField textField_36;
	private JTextField textField_37;
	private JTextField textField_38;
	private JTextField textField_39;
	private JTextField textField_40;
	private JTextField textField_41;
	private JTextField textField_42;
	private JTextField textField_43;
	private JTextField textField_44;
	private JTextField textField_45;
	private JTextField textField_46;
	private JTextField textField_47;
	private JTextField textField_48;
	private JTable table_2;
	private JPasswordField passwordField_1;
	private JPasswordField passwordField_2;
	private JPasswordField passwordField_3;
	private JTable table_34;
	private JTable table_35;
	private JTable table_36;
	private JTable table_37;
	private JTable table_38;
	private JTable table_39;
	static String value = null;
	private JLabel lblNewLabel_1;

	public static DefaultTableModel buildTableModel(ResultSet rs) throws SQLException {

		ResultSetMetaData metaData = rs.getMetaData();
		// names of columns
		Vector<String> columnNames = new Vector<String>();
		int columnCount = metaData.getColumnCount();
		for (int column = 1; column <= columnCount; column++) {
			columnNames.add(metaData.getColumnName(column));
		}

		// data of the table
		Vector<Vector<Object>> data = new Vector<Vector<Object>>();
		while (rs.next()) {
			Vector<Object> vector = new Vector<Object>();
			for (int columnIndex = 1; columnIndex <= columnCount; columnIndex++) {
				vector.add(rs.getObject(columnIndex));
			}
			data.add(vector);
		}

		return new DefaultTableModel(data, columnNames);

	}

	public void Backupalert() {

		JFileChooser chooser = new JFileChooser();
		chooser.setCurrentDirectory(new java.io.File("C:\\"));
		chooser.setDialogTitle(" Select Backup Directory");
		chooser.setFileSelectionMode(JFileChooser.DIRECTORIES_ONLY);
		chooser.setAcceptAllFileFilterUsed(false);
		if (chooser.showSaveDialog(null) == JFileChooser.APPROVE_OPTION) {
			Path file = Paths.get(System.getProperty("user.dir") + "\\Trailor.sqlite");
			Path target = Paths.get(chooser.getSelectedFile() + "\\Trailor.sqlite");
			if (Files.exists(target, LinkOption.NOFOLLOW_LINKS)) {
				int i = JOptionPane.showConfirmDialog(null,
						"There is alerady have Backup at this location if you want overwrite the Backup,click yes,othervise change the directory...",
						"Select an option", JOptionPane.YES_NO_OPTION);
				if (i == 0) {

					try {
						Files.copy(file, target, StandardCopyOption.REPLACE_EXISTING);
					} catch (IOException e1) {
					}
					JOptionPane.showMessageDialog(null, "Backup sucessfully");
				} else {
				}
			} else {

				try {
					Files.copy(file, target, StandardCopyOption.COPY_ATTRIBUTES);
				} catch (IOException e1) {
				}
				JOptionPane.showMessageDialog(null, "Backup sucessfully");

			}
		}

	}

	public static void main(String[] args) {

		try {
			// here you can put the selected theme class name in JTattoo
			UIManager.setLookAndFeel("com.jtattoo.plaf.bernstein.BernsteinLookAndFeel");

		} catch (ClassNotFoundException ex) {
			java.util.logging.Logger.getLogger(Trailor.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
		} catch (InstantiationException ex) {
			java.util.logging.Logger.getLogger(Trailor.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
		} catch (IllegalAccessException ex) {
			java.util.logging.Logger.getLogger(Trailor.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
		} catch (javax.swing.UnsupportedLookAndFeelException ex) {
			java.util.logging.Logger.getLogger(Trailor.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
		} catch (Exception e) {
			e.printStackTrace();
		}

		EventQueue.invokeLater(new Runnable() {
			public void run() {
				try {
					Trailor window = new Trailor();
					window.f1.setVisible(true);
				} catch (Exception e) {
					e.printStackTrace();
				}
			}
		});
	}

	/**
	 * Create the application.
	 */
	public Trailor() {
		initialize();
	}

	/**
	 * Initialize the contents of the frame.
	 */
	private void initialize() {
		conn = Sqcon.dbConnector();
		f1 = new JFrame();
		Dimension screenSize = Toolkit.getDefaultToolkit().getScreenSize();
		f1.setExtendedState(JFrame.MAXIMIZED_BOTH);
		f1.setBounds(0, 0, screenSize.width, screenSize.height);
		f1.setMinimumSize(new Dimension(700, 700));
		f1.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
		Image Imgh = new ImageIcon(this.getClass().getResource("/icon001.png")).getImage();
		f1.setIconImage(Imgh);

		panel1 = new JPanel();
		panel1.setBackground(new Color(102, 0, 0));
		panel1.setBounds(0, 0, screenSize.width, screenSize.height);
		f1.getContentPane().add(panel1);
		panel1.setLayout(null);

		JLabel lblUsername_4 = new JLabel("Username");
		lblUsername_4.setForeground(Color.WHITE);
		lblUsername_4.setRequestFocusEnabled(false);
		lblUsername_4.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 36));
		lblUsername_4.setBounds(159, 225, 241, 50);
		panel1.add(lblUsername_4);

		JLabel label_2 = new JLabel("Password");
		label_2.setForeground(Color.WHITE);
		label_2.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 36));
		label_2.setBounds(172, 390, 228, 59);
		panel1.add(label_2);

		t6 = new JTextField();
		t6.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 21));
		t6.setColumns(10);
		t6.setBounds(134, 281, 299, 50);
		panel1.add(t6);

		ImageIcon log1 = new ImageIcon(this.getClass().getResource("/log in but..jpg"));
		JButton btnNewButton1 = new JButton(log1);
		btnNewButton1.setContentAreaFilled(false);
		btnNewButton1.setBorderPainted(false);
		btnNewButton1.setBackground(new Color(102, 0, 0));
		btnNewButton1.setForeground(Color.WHITE);
		btnNewButton1.setOpaque(false);
		btnNewButton1.addKeyListener(new KeyAdapter() {
			@Override
			public void keyPressed(KeyEvent e) {
				s1 = t6.getText();
				s2 = t7.getText();
				try {

					String query = "Select * from Trailor Where UserName =  '" + s1 + "'  ";
					PreparedStatement pst = conn.prepareStatement(query);
					ResultSet rs = pst.executeQuery();

					while (rs.next()) {
						s3 = rs.getString("Username");
						s4 = rs.getString("Password");
						s_5 = rs.getString("User");

					}

					pst.execute();
					rs.close();

				} catch (Exception e1) {
					JOptionPane.showMessageDialog(null, "Error = " + e1);
				}
				if ((s1.equals(s3) && s2.equals(s4)))

				{
					if (s_5.equals("admin"))

					{
						l0 = 1;
						l1 = 1;
						l2 = 1;
						l3 = 1;
						l4 = 1;
						l5 = 1;
						l6 = 1;

						panel9.setVisible(true);
						panel1.setVisible(false);
					} else {
						panel6.setVisible(true);
						panel1.setVisible(false);
					}
				}

				else {
					JOptionPane.showMessageDialog(null, "Username & Password doesn't exist");
				}

				t6.setText(null);
				t7.setText(null);

			}
		});

		btnNewButton1.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent arg0) {

				s1 = t6.getText();
				s2 = t7.getText();
				try {

					String query = "Select * from Trailor Where UserName =  '" + s1 + "'  ";
					PreparedStatement pst = conn.prepareStatement(query);
					ResultSet rs = pst.executeQuery();

					while (rs.next()) {
						s3 = rs.getString("Username");
						s4 = rs.getString("Password");
						s_5 = rs.getString("User");

					}

					pst.execute();
					rs.close();

				} catch (Exception e) {
					JOptionPane.showMessageDialog(null, "Error = " + e);
				}
				if ((s1.equals(s3) && s2.equals(s4)))

				{
					if (s_5.equals("admin"))

					{
						l0 = 1;
						l1 = 1;
						l2 = 1;
						l3 = 1;
						l4 = 1;
						l5 = 1;
						l6 = 1;

						panel9.setVisible(true);
						panel1.setVisible(false);
					} else {
						panel6.setVisible(true);
						panel1.setVisible(false);
					}
				}

				else {
					JOptionPane.showMessageDialog(null, "Username & Password doesn't exist");
				}

				t6.setText(null);
				t7.setText(null);

			}
		});

		btnNewButton1.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 21));
		btnNewButton1.setBounds(141, 612, 135, 50);
		panel1.add(btnNewButton1);

		ImageIcon forgot2 = new ImageIcon(this.getClass().getResource("/forget but..jpg"));
		JButton btnSignUp = new JButton(forgot2);
		btnSignUp.setContentAreaFilled(false);
		btnSignUp.setOpaque(false);
		btnSignUp.setForeground(Color.WHITE);
		btnSignUp.setBorderPainted(false);
		btnSignUp.setBackground(new Color(102, 0, 0));
		btnSignUp.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent arg0) {

				panel5.setVisible(true);
				panel1.setVisible(false);

			}
		});
		btnSignUp.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 30));
		btnSignUp.setBounds(298, 612, 135, 50);
		panel1.add(btnSignUp);

		t7 = new JPasswordField();
		t7.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 21));
		t7.setBounds(134, 452, 299, 50);
		panel1.add(t7);

		JToggleButton b_01 = new JToggleButton("s\r\nh\r\no\r\nw ");
		b_01.setBorderPainted(false);
		b_01.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent arg0) {

				if (b_01.isSelected()) {
					t7.setVisible(false);
					textField_25.setVisible(true);
					textField_25.setText(t7.getText());

				} else {
					t7.setVisible(true);
					textField_25.setVisible(false);
				}

			}
		});
		b_01.setBounds(422, 452, 75, 50);
		panel1.add(b_01);

		textField_25 = new JTextField();
		textField_25.setBounds(134, 452, 299, 50);

		panel1.add(textField_25);
		textField_25.setColumns(10);

		ImageIcon gifImage = new ImageIcon(this.getClass().getResource("/screen background.jpg"));
		JLabel lblNewLabel_16 = new JLabel(gifImage);
		lblNewLabel_16.setBounds(0, 0, screenSize.width, screenSize.height);
		panel1.add(lblNewLabel_16);
		textField_25.setVisible(false);

		panel2 = new JPanel();
		panel2.setBackground(new Color(102, 0, 0));
		panel2.setForeground(Color.BLACK);
		panel2.setBounds(0, 0, screenSize.width, screenSize.height);
		f1.getContentPane().add(panel2);
		panel2.setVisible(false);
		panel2.setLayout(null);

		JComboBox comboBox = new JComboBox();
		comboBox.setModel(new DefaultComboBoxModel(new String[] { "1=What is your Nickname ?",
				"2=What is your first school ?", "3=What is your Mother's name ?" }));
		comboBox.setBounds(401, 244, 276, 46);
		panel2.add(comboBox);

		JLabel lblNewLabel = new JLabel("Name");
		lblNewLabel.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 30));
		lblNewLabel.setBounds(43, 34, 186, 27);
		panel2.add(lblNewLabel);

		JLabel lblNewLabel_101 = new JLabel("UserName");
		lblNewLabel_101.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 30));
		lblNewLabel_101.setBounds(42, 114, 187, 27);
		panel2.add(lblNewLabel_101);

		JLabel lblNewLabel_02 = new JLabel("Password");
		lblNewLabel_02.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 30));
		lblNewLabel_02.setBounds(42, 179, 187, 27);
		panel2.add(lblNewLabel_02);

		JLabel lblNewLabel_03 = new JLabel("Question");
		lblNewLabel_03.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 30));
		lblNewLabel_03.setBounds(42, 244, 187, 27);
		panel2.add(lblNewLabel_03);

		JLabel lblNewLabel_04 = new JLabel("Answer");
		lblNewLabel_04.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 30));
		lblNewLabel_04.setBounds(42, 326, 187, 27);
		panel2.add(lblNewLabel_04);

		JLabel lblNewLabel_05 = new JLabel("->");
		lblNewLabel_05.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 51));
		lblNewLabel_05.setBounds(294, 34, 56, 46);
		panel2.add(lblNewLabel_05);

		JLabel lblNewLabel_06 = new JLabel("->");
		lblNewLabel_06.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 51));
		lblNewLabel_06.setBounds(304, 106, 56, 46);
		panel2.add(lblNewLabel_06);

		JLabel lblNewLabel_07 = new JLabel("->");
		lblNewLabel_07.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 51));
		lblNewLabel_07.setBounds(294, 179, 56, 46);
		panel2.add(lblNewLabel_07);

		JLabel lblNewLabel_08 = new JLabel("->");
		lblNewLabel_08.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 51));
		lblNewLabel_08.setBounds(294, 244, 56, 46);
		panel2.add(lblNewLabel_08);

		JLabel lblNewLabel_09 = new JLabel("->");
		lblNewLabel_09.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 51));
		lblNewLabel_09.setBounds(294, 326, 56, 46);
		panel2.add(lblNewLabel_09);

		t1 = new JTextField();
		t1.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 30));
		t1.setBounds(401, 34, 276, 46);
		panel2.add(t1);
		t1.setColumns(10);

		t2 = new JTextField();
		t2.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 30));
		t2.setBounds(401, 106, 276, 46);
		panel2.add(t2);
		t2.setColumns(10);

		t3 = new JTextField();
		t3.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 30));
		t3.setBounds(401, 175, 276, 46);
		panel2.add(t3);
		t3.setColumns(10);

		t5 = new JTextField();
		t5.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 30));
		t5.setBounds(401, 319, 276, 46);
		panel2.add(t5);
		t5.setColumns(10);

		JButton btnNewButton2 = new JButton("Sign up");
		btnNewButton2.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent arg0) {

				try {
					String query = "Insert into Trailor (Name,UserName,Password,Question,Answer) values(?,?,?,?,?)";
					PreparedStatement pst = conn.prepareStatement(query);
					pst.setString(1, t1.getText());
					pst.setString(2, t2.getText());
					pst.setString(3, t3.getText());
					pst.setString(4, comboBox.getSelectedItem().toString());
					pst.setString(5, t5.getText());

					pst.execute();
					JOptionPane.showMessageDialog(null, "Data Saved ! ");
					pst.close();

				} catch (Exception e1) {
					JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
				}

				panel1.setVisible(true);
				panel2.setVisible(false);
			}
		});
		btnNewButton2.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 30));
		btnNewButton2.setBounds(270, 462, 226, 109);
		panel2.add(btnNewButton2);

		panel11 = new JPanel();
		panel11.setBackground(new Color(102, 0, 0));
		panel11.setForeground(Color.BLACK);
		panel11.setBounds(0, 0, screenSize.width, screenSize.height);
		f1.getContentPane().add(panel11);
		panel11.setVisible(false);
		panel11.setLayout(null);

		ImageIcon gifImage5 = new ImageIcon(this.getClass().getResource("/back.jpg"));
		JButton btnBackToButton1 = new JButton(gifImage5);
		btnBackToButton1.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 36));
		btnBackToButton1.setBounds(12, 13, 120, 57);
		btnBackToButton1.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {

				if (hk2 > 0) {
					panel9.setVisible(true);
					panel11.setVisible(false);
				} else {
					panel6.setVisible(true);
					panel11.setVisible(false);
				}

			}

		});
		panel11.add(btnBackToButton1);

		t_02 = new JTextField();
		t_02.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 21));
		t_02.setBounds(298, 158, 198, 60);
		panel11.add(t_02);
		t_02.setColumns(10);

		ImageIcon gifImage3 = new ImageIcon(this.getClass().getResource("/search 3rd page.jpg"));
		JButton btnSearch_2 = new JButton(gifImage3);
		btnSearch_2.setOpaque(false);
		btnSearch_2.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent arg0) {

				d7 = comboBox_02.getSelectedItem().toString();
				d8 = t_02.getText();

				if (d7.equals("Customer_id")) {
					try {
						String query = "Select * from Customer Where Customerid =  '" + d8 + "'  ";
						PreparedStatement pst = conn.prepareStatement(query);
						ResultSet rs = pst.executeQuery();
						table_4.setModel(DbUtils.resultSetToTableModel(rs));

					} catch (Exception e) {
						e.printStackTrace();
					}
				} else if (d7.equals("Customer_Name")) {
					try {
						String query = "Select * from Customer Where CustomerName =  '" + d8 + "'  ";
						PreparedStatement pst = conn.prepareStatement(query);
						ResultSet rs = pst.executeQuery();
						table_4.setModel(DbUtils.resultSetToTableModel(rs));

					} catch (Exception e) {
						e.printStackTrace();
					}
				} else if (d7.equals("Customer_Contact")) {
					try {
						String query = "Select * from Customer Where CustomerContact =  '" + d8 + "'  ";
						PreparedStatement pst = conn.prepareStatement(query);
						ResultSet rs = pst.executeQuery();
						table_4.setModel(DbUtils.resultSetToTableModel(rs));

					} catch (Exception e) {
						e.printStackTrace();
					}
				} else if (d7.equals("Customer_Address")) {
					try {
						String query = "Select * from Customer Where CustomerAddress =  '" + d8 + "'  ";
						PreparedStatement pst = conn.prepareStatement(query);
						ResultSet rs = pst.executeQuery();
						table_4.setModel(DbUtils.resultSetToTableModel(rs));

					} catch (Exception e) {
						e.printStackTrace();
					}
				}

			}
		});
		btnSearch_2.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 33));
		btnSearch_2.setBounds(564, 158, 188, 60);
		panel11.add(btnSearch_2);
		try {

			conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
			String query = "select * from Customer ";
			PreparedStatement statment = conn.prepareStatement(query);
			ResultSet rs = statment.executeQuery();
			rs.close();
			statment.close();
		} catch (SQLException e) {

			e.printStackTrace();
		}

		comboBox_02 = new JComboBox();
		comboBox_02.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 21));
		comboBox_02.setModel(new DefaultComboBoxModel(
				new String[] { "Customer_id", "Customer_Name", "Customer_Contact", "Customer_Address" }));
		comboBox_02.setBounds(33, 158, 198, 60);
		panel11.add(comboBox_02);

		JScrollPane scrollPane_2 = new JScrollPane();
		scrollPane_2.setOpaque(false);
		scrollPane_2.setBounds(23, 243, 836, 623);
		panel11.add(scrollPane_2);

		table_4 = new JTable();
		try {

			conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
			String query = "select * from Customer ";
			PreparedStatement statment = conn.prepareStatement(query);
			ResultSet rs = statment.executeQuery();
			table_4.setModel(DbUtils.resultSetToTableModel(rs));
			rs.close();
			statment.close();
		} catch (SQLException e) {

			e.printStackTrace();
		}

		scrollPane_2.setViewportView(table_4);

		ImageIcon gifImage3_a_a_ = new ImageIcon(this.getClass().getResource("/4rth page.jpg"));
		JLabel lblNewLabel_oldcus = new JLabel(gifImage3_a_a_);
		lblNewLabel_oldcus.setBounds(0, 0, screenSize.width, screenSize.height);
		panel11.add(lblNewLabel_oldcus);

		panel12 = new JPanel();
		panel12.setBackground(new Color(102, 0, 0));
		panel12.setBounds(0, 0, screenSize.width, screenSize.height);
		f1.getContentPane().add(panel12);
		panel12.setVisible(false);
		panel12.setLayout(null);

		ImageIcon gifImage4 = new ImageIcon(this.getClass().getResource("/back.jpg"));
		JButton btnBackToButton2 = new JButton(gifImage4);
		btnBackToButton2.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 48));
		btnBackToButton2.setBounds(12, 13, 120, 57);
		btnBackToButton2.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {

				if (hk3 > 0) {
					panel9.setVisible(true);
					panel12.setVisible(false);
				} else {
					panel6.setVisible(true);
					panel12.setVisible(false);
				}

			}

		});
		panel12.add(btnBackToButton2);

		JScrollPane scrollPane_0020 = new JScrollPane();
		scrollPane_0020.setBounds(200, 75, 685, 300);
		panel12.add(scrollPane_0020);

		table_7 = new JTable();
		table_7.setAutoResizeMode(JTable.AUTO_RESIZE_OFF);
		try {

			conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
			String query = "select * from deliverd_shirt ";
			PreparedStatement statment = conn.prepareStatement(query);
			ResultSet rs = statment.executeQuery();
			table_7.setModel(DbUtils.resultSetToTableModel(rs));

			rs.close();
			statment.close();
		} catch (SQLException e) {

			JOptionPane.showMessageDialog(null, "My Error 2" + e);
		}
		scrollPane_0020.setViewportView(table_7);

		JScrollPane scrollPane_210 = new JScrollPane();
		scrollPane_210.setBounds(200, 388, 685, 300);
		panel12.add(scrollPane_210);

		table_24 = new JTable();
		table_24.setAutoResizeMode(JTable.AUTO_RESIZE_OFF);
		try {

			conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
			String query = "select * from deliverd_coat ";
			PreparedStatement statment = conn.prepareStatement(query);
			ResultSet rs = statment.executeQuery();
			table_24.setModel(DbUtils.resultSetToTableModel(rs));

			rs.close();
			statment.close();
		} catch (SQLException e) {

			JOptionPane.showMessageDialog(null, "My Error 2" + e);
		}
		scrollPane_210.setViewportView(table_24);

		JScrollPane scrollPane_510 = new JScrollPane();
		scrollPane_510.setBounds(200, 701, 685, 300);
		panel12.add(scrollPane_510);

		table_25 = new JTable();
		table_25.setAutoResizeMode(JTable.AUTO_RESIZE_OFF);
		try {

			conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
			String query = "select * from deliverd_kurta ";
			PreparedStatement statment = conn.prepareStatement(query);
			ResultSet rs = statment.executeQuery();
			table_25.setModel(DbUtils.resultSetToTableModel(rs));

			rs.close();
			statment.close();
		} catch (SQLException e) {

			JOptionPane.showMessageDialog(null, "My Error 2" + e);
		}
		scrollPane_510.setViewportView(table_25);

		JScrollPane scrollPane_810 = new JScrollPane();
		scrollPane_810.setBounds(993, 75, 685, 300);
		panel12.add(scrollPane_810);

		table_26 = new JTable();
		table_26.setAutoResizeMode(JTable.AUTO_RESIZE_OFF);
		try {

			conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
			String query = "select * from deliverd_pent ";
			PreparedStatement statment = conn.prepareStatement(query);
			ResultSet rs = statment.executeQuery();
			table_26.setModel(DbUtils.resultSetToTableModel(rs));

			rs.close();
			statment.close();
		} catch (SQLException e) {

			JOptionPane.showMessageDialog(null, "My Error 2" + e);
		}
		scrollPane_810.setViewportView(table_26);

		JScrollPane scrollPane_1010 = new JScrollPane();
		scrollPane_1010.setBounds(993, 388, 685, 300);
		panel12.add(scrollPane_1010);

		table_27 = new JTable();
		table_27.setAutoResizeMode(JTable.AUTO_RESIZE_OFF);
		try {

			conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
			String query = "select * from deliverd_jacket ";
			PreparedStatement statment = conn.prepareStatement(query);
			ResultSet rs = statment.executeQuery();
			table_27.setModel(DbUtils.resultSetToTableModel(rs));

			rs.close();
			statment.close();
		} catch (SQLException e) {

			JOptionPane.showMessageDialog(null, "My Error 2" + e);
		}
		scrollPane_1010.setViewportView(table_27);

		JScrollPane scrollPane_910 = new JScrollPane();
		scrollPane_910.setBounds(993, 701, 685, 300);
		panel12.add(scrollPane_910);

		table_28 = new JTable();
		table_28.setAutoResizeMode(JTable.AUTO_RESIZE_OFF);
		try {

			conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
			String query = "select * from deliverd_pjama ";
			PreparedStatement statment = conn.prepareStatement(query);
			ResultSet rs = statment.executeQuery();
			table_28.setModel(DbUtils.resultSetToTableModel(rs));

			rs.close();
			statment.close();
		} catch (SQLException e) {

			JOptionPane.showMessageDialog(null, "My Error 2" + e);
		}
		scrollPane_910.setViewportView(table_28);

		ImageIcon deliimage = new ImageIcon(this.getClass().getResource("/5th page.jpg"));
		JLabel lblNewLabel_deliverd = new JLabel(deliimage);
		lblNewLabel_deliverd.setBounds(0, 0, screenSize.width, screenSize.height);
		panel12.add(lblNewLabel_deliverd);

		panel4 = new JPanel();
		panel4.setBackground(new Color(102, 0, 0));
		panel4.setBounds(0, 0, screenSize.width, screenSize.height);
		f1.getContentPane().add(panel4);
		panel4.setVisible(false);
		panel4.setLayout(null);

		ImageIcon gifImage606 = new ImageIcon(this.getClass().getResource("/back.jpg"));
		JButton btnBackToButton3 = new JButton(gifImage606);
		btnBackToButton3.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 30));
		btnBackToButton3.setBounds(12, 13, 120, 57);
		btnBackToButton3.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {

				if (hk4 > 0) {
					panel9.setVisible(true);
					panel4.setVisible(false);
				} else {
					panel6.setVisible(true);
					panel4.setVisible(false);
				}

			}

		});
		panel4.add(btnBackToButton3);

		JScrollPane scrollPane010101 = new JScrollPane();
		scrollPane010101.setBounds(186, 89, 769, 303);
		panel4.add(scrollPane010101);

		table_34 = new JTable();
		table_34.setAutoResizeMode(JTable.AUTO_RESIZE_OFF);
		try {

			conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
			String query = "select * from Shirt ";
			PreparedStatement statment = conn.prepareStatement(query);
			ResultSet rs = statment.executeQuery();
			table_34.setModel(DbUtils.resultSetToTableModel(rs));

			rs.close();
			statment.close();
		} catch (SQLException e) {

			JOptionPane.showMessageDialog(null, "My Error 2" + e);
		}
		table_34.addMouseListener(new MouseAdapter() {
			@Override
			public void mouseClicked(MouseEvent e) {
				TableModel model1 = null;
				row1 = 0;
				String id01 = null;
				int dialogButton = JOptionPane.YES_NO_OPTION;
				int dialogResult = JOptionPane.showConfirmDialog(null,
						"Would You Like to Save your Previous Note First?", "Warning", dialogButton);

				if (dialogResult == JOptionPane.YES_OPTION) {
					model1 = table_34.getModel();
					row1 = table_34.getSelectedRow();
					id01 = model1.getValueAt(row1, 9).toString();
					try {
						String query = "Select * from Shirt where Customerid='" + id01 + "' ";
						PreparedStatement pst = conn.prepareStatement(query);
						ResultSet rs = pst.executeQuery();

						while (rs.next()) {
							z1 = rs.getString("lmbai");
							z2 = rs.getString("seena");
							z3 = rs.getString("kemer");
							z4 = rs.getString("pait");
							z5 = rs.getString("hip");
							z6 = rs.getString("teera");
							z7 = rs.getString("glaa");
							z8 = rs.getString("baju");
							z9 = rs.getString("bs");
							z10 = rs.getString("Customerid");
							z11 = rs.getString("CustomerName");
							z12 = rs.getString("CustomerContact");
							z13 = rs.getString("CustomerAddress");
							z14 = rs.getString("price");
							z15 = rs.getString("advance_payments");
							z16 = rs.getString("pending_payments");
							z17 = rs.getString("Starting_date");
							z18 = rs.getString("Ending_date");
							z19 = rs.getString("price1");
							z20 = rs.getString("quantity");
							z21 = rs.getString("extra");
						}
						rs.close();
						pst.close();
					} catch (Exception e1) {
						e1.printStackTrace();
					}

					String h[] = { z1, z2, z3, z4, z5, z6, z7, z8, z9, z10, z11, z12, z13, z14, z15, z16, z17, z18, z19,
							z20, z21 };

					date001 = new JTextField();
					date002 = new JTextField();
					JComponent[] inputs = new JComponent[] { new JLabel("Price"), date001, new JLabel("Quantity"),
							date002,

					};
					int result = JOptionPane.showConfirmDialog(null, inputs, null, JOptionPane.PLAIN_MESSAGE);
					if (result == JOptionPane.OK_OPTION) {

						m = Double.parseDouble(z14);// total price
						m1 = Double.parseDouble(z19); // per piece price
						m2 = Double.parseDouble(z20); // quantity
						m10 = Double.parseDouble(z16); // pending_payments

						if (date001.getText().isEmpty()) {
							m3 = Double.parseDouble(date002.getText().toString());
							m5 = m2 - m3; // new quantity
							if (m3 == m2) {

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into deliverd_shirt (lmbai,seena,kemer,pait,hip,teera,glaa,baju,bs,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, String.valueOf(0.0));
									pst.setString(16, String.valueOf(0.0));
									pst.setString(17, z17);
									pst.setString(18, z18);
									pst.setString(19, z19);
									pst.setString(20, String.valueOf(m2));
									pst.setString(21, z21);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									String query1 = " DELETE FROM Shirt where Customerid= '" + z10 + "' ";
									PreparedStatement pst2 = conn.prepareStatement(query1);
									pst2.execute();
									pst2.close();
								} catch (Exception e1) {
									e1.printStackTrace();
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into payment_shirt(lmbai,seena,kemer,pait,hip,teera,glaa,baju,bs,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, String.valueOf(0.0));
									pst.setString(16, String.valueOf(0.0));
									pst.setString(17, z17);
									pst.setString(18, z18);
									pst.setString(19, z19);
									pst.setString(20, String.valueOf(m2));
									pst.setString(21, z21);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

							} else if (m3 > 0 && m3 < m2) {
								m5 = m2 - m3;

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "UPDATE Shirt set lmbai = ?,seena = ?,kemer = ?,pait = ?,hip = ?,teera = ?,glaa = ?,baju = ?,bs = ?,Customerid = ?,CustomerName = ?,CustomerContact = ?,CustomerAddress = ?,price = ?,advance_payments = ?,pending_payments = ?,Starting_date = ?,Ending_date = ?,price1 = ?,quantity = ?,extra = ? where Customerid = '"
											+ z10 + "' AND CustomerName ='" + z11 + "' AND CustomerContact = '" + z12
											+ "' AND CustomerAddress = '" + z13 + "' ";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, String.valueOf(0.0));
									pst.setString(16, String.valueOf(0.0));
									pst.setString(17, z17);
									pst.setString(18, z18);
									pst.setString(19, z19);
									pst.setString(20, String.valueOf(m5));
									pst.setString(21, z21);

									pst.executeUpdate();
									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into deliverd_shirt(lmbai,seena,kemer,pait,hip,teera,glaa,baju,bs,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, String.valueOf(0.0));
									pst.setString(16, String.valueOf(0.0));
									pst.setString(17, z17);
									pst.setString(18, z18);
									pst.setString(19, z19);
									pst.setString(20, String.valueOf(m3));
									pst.setString(21, z21);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}
								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into payment_shirt(lmbai,seena,kemer,pait,hip,teera,glaa,baju,bs,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, String.valueOf(0.0));
									pst.setString(16, String.valueOf(0.0));
									pst.setString(17, z17);
									pst.setString(18, z18);
									pst.setString(19, z19);
									pst.setString(20, String.valueOf(m3));
									pst.setString(21, z21);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}
							} else {
								JOptionPane.showMessageDialog(null, "Error");
							}

						} else if (date002.getText().isEmpty()) {
							m1 = Double.parseDouble(date001.getText().toString());
							if (m10 == 0.0) {
								m11 = m;
							} else {
								m11 = m10;
							}

							if (m1 < m11) {
								m6 = m11 - m1;

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into payment_shirt(lmbai,seena,kemer,pait,hip,teera,glaa,baju,bs,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, String.valueOf(m1));
									pst.setString(16, String.valueOf(m6));
									pst.setString(17, z17);
									pst.setString(18, z18);
									pst.setString(19, z19);
									pst.setString(20, z20);
									pst.setString(21, z21);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "UPDATE Shirt set lmbai = ?,seena = ?,kemer = ?,pait = ?,hip = ?,teera = ?,glaa = ?,baju = ?,bs = ?,Customerid = ?,CustomerName = ?,CustomerContact = ?,CustomerAddress = ?,price = ?,advance_payments = ?,pending_payments = ?,Starting_date = ?,Ending_date = ?,price1 = ?,quantity = ?,extra = ? where Customerid = '"
											+ z10 + "' AND CustomerName ='" + z11 + "' AND CustomerContact = '" + z12
											+ "' AND CustomerAddress = '" + z13 + "' ";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, String.valueOf(m1));
									pst.setString(16, String.valueOf(m6));
									pst.setString(17, z17);
									pst.setString(18, z18);
									pst.setString(19, z19);
									pst.setString(20, z20);
									pst.setString(21, z21);

									pst.executeUpdate();
									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

							} else if (m1 == m11) {

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "UPDATE Shirt set lmbai = ?,seena = ?,kemer = ?,pait = ?,hip = ?,teera = ?,glaa = ?,baju = ?,bs = ?,Customerid = ?,CustomerName = ?,CustomerContact = ?,CustomerAddress = ?,price = ?,advance_payments = ?,pending_payments = ?,Starting_date = ?,Ending_date = ?,price1 = ?,quantity = ?,extra = ? where Customerid = '"
											+ z10 + "' AND CustomerName ='" + z11 + "' AND CustomerContact = '" + z12
											+ "' AND CustomerAddress = '" + z13 + "' ";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, String.valueOf(m1));
									pst.setString(16, String.valueOf(0));
									pst.setString(17, z17);
									pst.setString(18, z18);
									pst.setString(19, z19);
									pst.setString(20, z20);
									pst.setString(21, z21);

									pst.executeUpdate();
									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into payment_shirt(lmbai,seena,kemer,pait,hip,teera,glaa,baju,bs,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, String.valueOf(m1));
									pst.setString(16, String.valueOf(0));
									pst.setString(17, z17);
									pst.setString(18, z18);
									pst.setString(19, z19);
									pst.setString(20, z20);
									pst.setString(21, z21);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

							}

						} else if (!date001.getText().isEmpty() && !date002.getText().isEmpty()) {
							m3 = Double.parseDouble(date002.getText().toString());
							m1 = Double.parseDouble(date001.getText().toString());

							if (m10 == 0.0) {
								m11 = m;

							} else {
								m11 = m10;

							}

							if (m1 == m11 && m2 == m3) {

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into deliverd_shirt(lmbai,seena,kemer,pait,hip,teera,glaa,baju,bs,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, String.valueOf(m));
									pst.setString(16, String.valueOf(m11));
									pst.setString(17, z17);
									pst.setString(18, z18);
									pst.setString(19, z19);
									pst.setString(20, String.valueOf(m3));
									pst.setString(21, z21);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									String query1 = " DELETE FROM Shirt where Customerid= '" + z10 + "' ";
									PreparedStatement pst2 = conn.prepareStatement(query1);
									pst2.execute();
									pst2.close();
								} catch (Exception e1) {
									e1.printStackTrace();
								}

							}

							else if (m1 < m11 && m3 < m2) {
								try {
									m5 = m2 - m3;
									m6 = m11 - m1;

									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into payment_shirt(lmbai,seena,kemer,pait,hip,teera,glaa,baju,bs,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, String.valueOf(m1));
									pst.setString(16, String.valueOf(m6));
									pst.setString(17, z17);
									pst.setString(18, z18);
									pst.setString(19, z19);
									pst.setString(20, String.valueOf(m3));
									pst.setString(21, z21);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "UPDATE Shirt set  lmbai = ?,seena = ?,kemer = ?,pait = ?,hip = ?,teera = ?,glaa = ?,baju = ?,bs = ?,Customerid = ?,CustomerName = ?,CustomerContact = ?,CustomerAddress = ?,price = ?,advance_payments = ?,pending_payments = ?,Starting_date = ?,Ending_date = ?,price1 = ?,quantity = ?,extra = ? where Customerid = '"
											+ z10 + "' AND CustomerName ='" + z11 + "' AND CustomerContact = '" + z12
											+ "' AND CustomerAddress = '" + z13 + "' ";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, String.valueOf(m1));
									pst.setString(16, String.valueOf(m6));
									pst.setString(17, z17);
									pst.setString(18, z18);
									pst.setString(19, z19);
									pst.setString(20, String.valueOf(m5));
									pst.setString(21, z21);

									pst.executeUpdate();
									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into deliverd_shirt(lmbai,seena,kemer,pait,hip,teera,glaa,baju,bs,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, String.valueOf(m1));
									pst.setString(16, String.valueOf(m6));
									pst.setString(17, z17);
									pst.setString(18, z18);
									pst.setString(19, z19);
									pst.setString(20, String.valueOf(m3));
									pst.setString(21, z21);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}
							}

							else if (m1 == m11 && m3 < m2) {
								m5 = m2 - m3;

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "UPDATE Shirt set  lmbai = ?,seena = ?,kemer = ?,pait = ?,hip = ?,teera = ?,glaa = ?,baju = ?,bs = ?,Customerid = ?,CustomerName = ?,CustomerContact = ?,CustomerAddress = ?,price = ?,advance_payments = ?,pending_payments = ?,Starting_date = ?,Ending_date = ?,price1 = ?,quantity = ?,extra = ? where Customerid = '"
											+ z10 + "' AND CustomerName ='" + z11 + "' AND CustomerContact = '" + z12
											+ "' AND CustomerAddress = '" + z13 + "' ";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, String.valueOf(z14));
									pst.setString(16, String.valueOf(0));
									pst.setString(17, z17);
									pst.setString(18, z18);
									pst.setString(19, z19);
									pst.setString(20, String.valueOf(m5));
									pst.setString(21, z21);

									pst.executeUpdate();
									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into deliverd_shirt(lmbai,seena,kemer,pait,hip,teera,glaa,baju,bs,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, String.valueOf(z14));
									pst.setString(16, String.valueOf(0));
									pst.setString(17, z17);
									pst.setString(18, z18);
									pst.setString(19, z19);
									pst.setString(20, String.valueOf(m3));
									pst.setString(21, z21);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

							}

							else if (m1 < m11 && m3 == m2) {
								m6 = m11 - m1;

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into payment_shirt(lmbai,seena,kemer,pait,hip,teera,glaa,baju,bs,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, String.valueOf(m1));
									pst.setString(16, String.valueOf(m6));
									pst.setString(17, z17);
									pst.setString(18, z18);
									pst.setString(19, z19);
									pst.setString(20, String.valueOf(m3));
									pst.setString(21, z21);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into deliverd_shirt(lmbai,seena,kemer,pait,hip,teera,glaa,baju,bs,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, String.valueOf(m1));
									pst.setString(16, String.valueOf(m6));
									pst.setString(17, z17);
									pst.setString(18, z18);
									pst.setString(19, z19);
									pst.setString(20, String.valueOf(m3));
									pst.setString(21, z21);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									String query1 = " DELETE FROM Shirt where Customerid= '" + z10 + "' ";
									PreparedStatement pst2 = conn.prepareStatement(query1);
									pst2.execute();
									pst2.close();
								} catch (Exception e1) {
									e1.printStackTrace();
								}

							}

							else {
							}
						}

					}

				} else {
					System.out.println("User canceled / closed the dialog, result = ");
				}

			}

		});
		scrollPane010101.setViewportView(table_34);

		JScrollPane scrollPane020202 = new JScrollPane();

		scrollPane020202.setBounds(186, 405, 769, 303);
		panel4.add(scrollPane020202);

		table_38 = new JTable();
		table_38.setAutoResizeMode(JTable.AUTO_RESIZE_OFF);
		try {

			conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
			String query = "select * from Coat ";
			PreparedStatement statment = conn.prepareStatement(query);
			ResultSet rs = statment.executeQuery();
			table_38.setModel(DbUtils.resultSetToTableModel(rs));

			rs.close();
			statment.close();
		} catch (SQLException e) {

			JOptionPane.showMessageDialog(null, "My Error 2" + e);
		}

		table_38.addMouseListener(new MouseAdapter() {
			@Override
			public void mouseClicked(MouseEvent e) {

				int dialogButton = JOptionPane.YES_NO_OPTION;
				int dialogResult = JOptionPane.showConfirmDialog(null,
						"Would You Like to Save your Previous Note First?", "Warning", dialogButton);

				if (dialogResult == JOptionPane.YES_OPTION) {
					model2 = (DefaultTableModel) table_38.getModel();
					row2 = table_38.getSelectedRow();
					id02 = model2.getValueAt(row2, 12).toString();
					try {
						String query = "Select * from Coat where Customerid='" + id02 + "' ";
						PreparedStatement pst = conn.prepareStatement(query);
						ResultSet rs = pst.executeQuery();

						while (rs.next()) {

							z1 = rs.getString("lmbai");
							z2 = rs.getString("seena");
							z3 = rs.getString("kemer");
							z4 = rs.getString("pait");
							z5 = rs.getString("hip");
							z6 = rs.getString("teera");
							z7 = rs.getString("baju");
							z8 = rs.getString("dor");
							z9 = rs.getString("back");
							z10 = rs.getString("bs");
							z11 = rs.getString("bm");
							z12 = rs.getString("shoulder");
							z13 = rs.getString("Customerid");
							z14 = rs.getString("CustomerName");
							z15 = rs.getString("CustomerContact");
							z16 = rs.getString("CustomerAddress");
							z17 = rs.getString("price");
							z18 = rs.getString("advance_payments");
							z19 = rs.getString("pending_payments");
							z20 = rs.getString("Starting_date");
							z21 = rs.getString("Ending_date");
							z22 = rs.getString("price1");
							z23 = rs.getString("quantity");
							z24 = rs.getString("extra");

						}

						rs.close();
						pst.close();

					} catch (Exception e1) {
						e1.printStackTrace();
					}

					String h[] = { z1, z2, z3, z4, z5, z6, z7, z8, z9, z10, z11, z12, z13, z14, z15, z16, z17, z18, z19,
							z20, z21, z22, z23, z24 };

					date005 = new JTextField();
					date006 = new JTextField();
					JComponent[] inputs = new JComponent[] { new JLabel("Price"), date005, new JLabel("Quantity"),
							date006,

					};
					int result = JOptionPane.showConfirmDialog(null, inputs, null, JOptionPane.PLAIN_MESSAGE);
					if (result == JOptionPane.OK_OPTION) {

						m = Double.parseDouble(z17);// total price
						m1 = Double.parseDouble(z22); // per piece price
						m2 = Double.parseDouble(z23); // quantity
						m10 = Double.parseDouble(z19); // pending_payments

						if (date005.getText().isEmpty()) {
							m3 = Double.parseDouble(date006.getText().toString());
							m5 = m2 - m3; // new quantity
							if (m3 == m2) {

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into deliverd_coat (lmbai ,seena ,kemer ,pait ,hip ,teera ,baju ,dor ,back ,bs ,bm ,shoulder,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, String.valueOf(0.0));
									pst.setString(19, String.valueOf(0.0));
									pst.setString(20, z20);
									pst.setString(21, z21);
									pst.setString(22, z22);
									pst.setString(23, String.valueOf(m2));
									pst.setString(24, z24);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									String query1 = " DELETE FROM Coat where Customerid= '" + z13 + "' ";
									PreparedStatement pst2 = conn.prepareStatement(query1);
									pst2.execute();
									pst2.close();
								} catch (Exception e1) {
									e1.printStackTrace();
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into payment_coat(lmbai ,seena ,kemer ,pait ,hip ,teera ,baju ,dor ,back ,bs ,bm ,shoulder,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, String.valueOf(0.0));
									pst.setString(19, String.valueOf(0.0));
									pst.setString(20, z20);
									pst.setString(21, z21);
									pst.setString(22, z22);
									pst.setString(23, String.valueOf(m2));
									pst.setString(24, z24);
									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

							} else if (m3 > 0 && m3 < m2) {
								m5 = m2 - m3;

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "UPDATE Coat set lmbai =?,seena =?,kemer =?,pait =?,hip =?,teera =?,baju =?,dor =?,back =?,bs =?,bm =?,shoulder =?,Customerid =?,CustomerName =?,CustomerContact =?,CustomerAddress =?,price =?,advance_payments =?,pending_payments =?,Starting_date =?,Ending_date =?,price1 = ?,quantity = ?,extra = ? where Customerid = '"
											+ q25 + "' AND CustomerName ='" + q26 + "' AND CustomerContact = '" + q27
											+ "' AND CustomerAddress = '" + q28 + "' ";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, String.valueOf(0.0));
									pst.setString(19, String.valueOf(0.0));
									pst.setString(20, z20);
									pst.setString(21, z21);
									pst.setString(22, z22);
									pst.setString(23, String.valueOf(m5));
									pst.setString(24, z24);

									pst.executeUpdate();
									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into deliverd_coat(lmbai ,seena ,kemer ,pait ,hip ,teera ,baju ,dor ,back ,bs ,bm ,shoulder,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, String.valueOf(0.0));
									pst.setString(19, String.valueOf(0.0));
									pst.setString(20, z20);
									pst.setString(21, z21);
									pst.setString(22, z22);
									pst.setString(23, String.valueOf(m3));
									pst.setString(24, z24);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}
								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into payment_coat(lmbai ,seena ,kemer ,pait ,hip ,teera ,baju ,dor ,back ,bs ,bm ,shoulder,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, String.valueOf(0.0));
									pst.setString(19, String.valueOf(0.0));
									pst.setString(20, z20);
									pst.setString(21, z21);
									pst.setString(22, z22);
									pst.setString(23, String.valueOf(m3));
									pst.setString(24, z24);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}
							} else {
								JOptionPane.showMessageDialog(null, "Error");
							}

						} else if (date006.getText().isEmpty()) {
							m1 = Double.parseDouble(date005.getText().toString());
							if (m10 == 0.0) {
								m11 = m;
							} else {
								m11 = m10;
							}

							if (m1 < m11) {
								m6 = m11 - m1;

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into payment_coat(lmbai ,seena ,kemer ,pait ,hip ,teera ,baju ,dor ,back ,bs ,bm ,shoulder,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, String.valueOf(m1));
									pst.setString(19, String.valueOf(m6));
									pst.setString(20, z20);
									pst.setString(21, z21);
									pst.setString(22, z22);
									pst.setString(23, z23);
									pst.setString(24, z24);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "UPDATE Coat set lmbai =?,seena =?,kemer =?,pait =?,hip =?,teera =?,baju =?,dor =?,back =?,bs =?,bm =?,shoulder =?,Customerid =?,CustomerName =?,CustomerContact =?,CustomerAddress =?,price =?,advance_payments =?,pending_payments =?,Starting_date =?,Ending_date =?,price1 = ?,quantity = ?,extra = ? where Customerid = '"
											+ q25 + "' AND CustomerName ='" + q26 + "' AND CustomerContact = '" + q27
											+ "' AND CustomerAddress = '" + q28 + "' ";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, String.valueOf(m1));
									pst.setString(19, String.valueOf(m6));
									pst.setString(20, z20);
									pst.setString(21, z21);
									pst.setString(22, z22);
									pst.setString(23, z23);
									pst.setString(24, z24);

									pst.executeUpdate();
									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

							} else if (m1 == m11) {

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "UPDATE Coat set lmbai =?,seena =?,kemer =?,pait =?,hip =?,teera =?,baju =?,dor =?,back =?,bs =?,bm =?,shoulder =?,Customerid =?,CustomerName =?,CustomerContact =?,CustomerAddress =?,price =?,advance_payments =?,pending_payments =?,Starting_date =?,Ending_date =?,price1 = ?,quantity = ?,extra = ? where Customerid = '"
											+ q25 + "' AND CustomerName ='" + q26 + "' AND CustomerContact = '" + q27
											+ "' AND CustomerAddress = '" + q28 + "' ";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, String.valueOf(m1));
									pst.setString(19, String.valueOf(0));
									pst.setString(20, z20);
									pst.setString(21, z21);
									pst.setString(22, z22);
									pst.setString(23, z23);
									pst.setString(24, z24);
									pst.executeUpdate();
									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into payment_coat(lmbai ,seena ,kemer ,pait ,hip ,teera ,baju ,dor ,back ,bs ,bm ,shoulder,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, String.valueOf(m1));
									pst.setString(19, String.valueOf(0));
									pst.setString(20, z20);
									pst.setString(21, z21);
									pst.setString(22, z22);
									pst.setString(23, z23);
									pst.setString(24, z24);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

							}

						} else if (!date005.getText().isEmpty() && !date006.getText().isEmpty()) {
							m3 = Double.parseDouble(date006.getText().toString());
							m1 = Double.parseDouble(date005.getText().toString());

							if (m10 == 0.0) {
								m11 = m;

							} else {
								m11 = m10;

							}

							if (m1 == m11 && m2 == m3) {

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into deliverd_coat(lmbai ,seena ,kemer ,pait ,hip ,teera ,baju ,dor ,back ,bs ,bm ,shoulder,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, String.valueOf(m));
									pst.setString(19, String.valueOf(m11));
									pst.setString(20, z20);
									pst.setString(21, z21);
									pst.setString(22, z22);
									pst.setString(23, String.valueOf(m11));
									pst.setString(24, z24);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									String query1 = " DELETE FROM Coat where Customerid= '" + z13 + "' ";
									PreparedStatement pst2 = conn.prepareStatement(query1);
									pst2.execute();
									pst2.close();
								} catch (Exception e1) {
									e1.printStackTrace();
								}

							}

							else if (m1 < m11 && m3 < m2) {
								try {
									m5 = m2 - m3;
									m6 = m11 - m1;

									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into payment_coat(lmbai ,seena ,kemer ,pait ,hip ,teera ,baju ,dor ,back ,bs ,bm ,shoulder,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, String.valueOf(m1));
									pst.setString(19, String.valueOf(m6));
									pst.setString(20, z20);
									pst.setString(21, z21);
									pst.setString(22, z22);
									pst.setString(23, String.valueOf(m3));
									pst.setString(24, z24);
									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "UPDATE Coat set  lmbai =?,seena =?,kemer =?,pait =?,hip =?,teera =?,baju =?,dor =?,back =?,bs =?,bm =?,shoulder =?,Customerid =?,CustomerName =?,CustomerContact =?,CustomerAddress =?,price =?,advance_payments =?,pending_payments =?,Starting_date =?,Ending_date =?,price1 = ?,quantity = ?,extra = ? where Customerid = '"
											+ q25 + "' AND CustomerName ='" + q26 + "' AND CustomerContact = '" + q27
											+ "' AND CustomerAddress = '" + q28 + "' ";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, String.valueOf(m1));
									pst.setString(19, String.valueOf(m6));
									pst.setString(20, z20);
									pst.setString(21, z21);
									pst.setString(22, z22);
									pst.setString(23, String.valueOf(m5));
									pst.setString(24, z24);
									pst.executeUpdate();
									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into deliverd_coat(lmbai ,seena ,kemer ,pait ,hip ,teera ,baju ,dor ,back ,bs ,bm ,shoulder,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, String.valueOf(m1));
									pst.setString(19, String.valueOf(m6));
									pst.setString(20, z20);
									pst.setString(21, z21);
									pst.setString(22, z22);
									pst.setString(23, String.valueOf(m3));
									pst.setString(24, z24);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}
							}

							else if (m1 == m11 && m3 < m2) {
								m5 = m2 - m3;

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "UPDATE Coat set  lmbai =?,seena =?,kemer =?,pait =?,hip =?,teera =?,baju =?,dor =?,back =?,bs =?,bm =?,shoulder =?,Customerid =?,CustomerName =?,CustomerContact =?,CustomerAddress =?,price =?,advance_payments =?,pending_payments =?,Starting_date =?,Ending_date =?,price1 = ?,quantity = ?,extra = ? where Customerid = '"
											+ q25 + "' AND CustomerName ='" + q26 + "' AND CustomerContact = '" + q27
											+ "' AND CustomerAddress = '" + q28 + "' ";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, z18);
									pst.setString(19, String.valueOf(0));
									pst.setString(20, z20);
									pst.setString(21, z21);
									pst.setString(22, z22);
									pst.setString(23, String.valueOf(m5));
									pst.setString(24, z24);

									pst.executeUpdate();
									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into deliverd_coat(lmbai ,seena ,kemer ,pait ,hip ,teera ,baju ,dor ,back ,bs ,bm ,shoulder,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, z18);
									pst.setString(19, String.valueOf(0));
									pst.setString(20, z20);
									pst.setString(21, z21);
									pst.setString(22, z22);
									pst.setString(23, String.valueOf(m3));
									pst.setString(24, z24);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

							}

							else if (m1 < m11 && m3 == m2) {
								m6 = m11 - m1;

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into payment_coat(lmbai ,seena ,kemer ,pait ,hip ,teera ,baju ,dor ,back ,bs ,bm ,shoulder,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, String.valueOf(m1));
									pst.setString(19, String.valueOf(m6));
									pst.setString(20, z20);
									pst.setString(21, z21);
									pst.setString(22, z22);
									pst.setString(23, String.valueOf(m3));
									pst.setString(24, z24);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into deliverd_coat(lmbai ,seena ,kemer ,pait ,hip ,teera ,baju ,dor ,back ,bs ,bm ,shoulder,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, String.valueOf(m1));
									pst.setString(19, String.valueOf(m6));
									pst.setString(20, z20);
									pst.setString(21, z21);
									pst.setString(22, z22);
									pst.setString(23, String.valueOf(m3));
									pst.setString(24, z24);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									String query1 = " DELETE FROM Coat where Customerid= '" + z13 + "' ";
									PreparedStatement pst2 = conn.prepareStatement(query1);
									pst2.execute();
									pst2.close();
								} catch (Exception e1) {
									e1.printStackTrace();
								}

							}

							else {
							}
						}

					}

				} else {
					System.out.println("User canceled / closed the dialog, result = ");
				}

			}
		});
		scrollPane020202.setViewportView(table_38);

		JScrollPane scrollPane030303 = new JScrollPane();

		scrollPane030303.setBounds(186, 721, 769, 303);
		panel4.add(scrollPane030303);

		table_35 = new JTable();
		table_35.setAutoResizeMode(JTable.AUTO_RESIZE_OFF);
		try {

			conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
			String query = "select * from Kurta ";
			PreparedStatement statment = conn.prepareStatement(query);
			ResultSet rs = statment.executeQuery();
			table_35.setModel(DbUtils.resultSetToTableModel(rs));

			rs.close();
			statment.close();
		} catch (SQLException e) {

			JOptionPane.showMessageDialog(null, "My Error 2" + e);
		}
		table_35.addMouseListener(new MouseAdapter() {
			@Override
			public void mouseClicked(MouseEvent e) {

				int dialogButton = JOptionPane.YES_NO_OPTION;
				int dialogResult = JOptionPane.showConfirmDialog(null,
						"Would You Like to Save your Previous Note First?", "Warning", dialogButton);

				if (dialogResult == JOptionPane.YES_OPTION) {
					model3 = (DefaultTableModel) table_35.getModel();
					row3 = table_35.getSelectedRow();
					id03 = model3.getValueAt(row3, 9).toString();

					try {
						String query = "Select * from Kurta where Customerid='" + id03 + "' ";
						PreparedStatement pst = conn.prepareStatement(query);
						ResultSet rs = pst.executeQuery();

						while (rs.next()) {

							z1 = rs.getString("lmbai");
							z2 = rs.getString("seena");
							z3 = rs.getString("kemer");
							z4 = rs.getString("pait");
							z5 = rs.getString("hip");
							z6 = rs.getString("teera");
							z7 = rs.getString("glaa");
							z8 = rs.getString("baju");
							z9 = rs.getString("bs");
							z10 = rs.getString("Customerid");
							z11 = rs.getString("CustomerName");
							z12 = rs.getString("CustomerContact");
							z13 = rs.getString("CustomerAddress");
							z14 = rs.getString("price");
							z15 = rs.getString("advance_payments");
							z16 = rs.getString("pending_payments");
							z17 = rs.getString("Starting_date");
							z18 = rs.getString("Ending_date");
							z19 = rs.getString("price1");
							z20 = rs.getString("quantity");
							z21 = rs.getString("extra");

						}

						rs.close();
						pst.close();

					} catch (Exception e1) {
						e1.printStackTrace();
					}

					String h[] = { z1, z2, z3, z4, z5, z6, z7, z8, z9, z10, z11, z12, z13, z14, z15, z16, z17, z18, z19,
							z20, z21 };

					date003 = new JTextField();
					date004 = new JTextField();
					JComponent[] inputs = new JComponent[] { new JLabel("Price"), date003, new JLabel("Quantity"),
							date004,

					};
					int result = JOptionPane.showConfirmDialog(null, inputs, null, JOptionPane.PLAIN_MESSAGE);
					if (result == JOptionPane.OK_OPTION) {

						m = Double.parseDouble(z14);// total price
						m1 = Double.parseDouble(z19); // per piece price
						m2 = Double.parseDouble(z20); // quantity
						m10 = Double.parseDouble(z16); // pending_payments

						if (date003.getText().isEmpty()) {
							m3 = Double.parseDouble(date004.getText().toString());
							m5 = m2 - m3; // new quantity
							if (m3 == m2) {

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into deliverd_kurta (lmbai,seena,kemer,pait,hip,teera,glaa,baju,bs,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, String.valueOf(0.0));
									pst.setString(16, String.valueOf(0.0));
									pst.setString(17, z17);
									pst.setString(18, z18);
									pst.setString(19, z19);
									pst.setString(20, String.valueOf(m2));
									pst.setString(21, z21);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									String query1 = " DELETE FROM Kurta where Customerid= '" + z10 + "' ";
									PreparedStatement pst2 = conn.prepareStatement(query1);
									pst2.execute();
									pst2.close();
								} catch (Exception e1) {
									e1.printStackTrace();
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into payment_kurta(lmbai,seena,kemer,pait,hip,teera,glaa,baju,bs,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, String.valueOf(0.0));
									pst.setString(16, String.valueOf(0.0));
									pst.setString(17, z17);
									pst.setString(18, z18);
									pst.setString(19, z19);
									pst.setString(20, String.valueOf(m2));
									pst.setString(21, z21);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

							} else if (m3 > 0 && m3 < m2) {
								m5 = m2 - m3;

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "UPDATE Kurta set lmbai = ?,seena = ?,kemer = ?,pait = ?,hip = ?,teera = ?,glaa = ?,baju = ?,bs = ?,Customerid = ?,CustomerName = ?,CustomerContact = ?,CustomerAddress = ?,price = ?,advance_payments = ?,pending_payments = ?,Starting_date = ?,Ending_date = ?,price1 = ?,quantity = ?,extra = ? where Customerid = '"
											+ z10 + "' AND CustomerName ='" + z11 + "' AND CustomerContact = '" + z12
											+ "' AND CustomerAddress = '" + z13 + "' ";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, String.valueOf(0.0));
									pst.setString(16, String.valueOf(0.0));
									pst.setString(17, z17);
									pst.setString(18, z18);
									pst.setString(19, z19);
									pst.setString(20, String.valueOf(m5));
									pst.setString(21, z21);

									pst.executeUpdate();
									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into deliverd_kurta(lmbai,seena,kemer,pait,hip,teera,glaa,baju,bs,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, String.valueOf(0.0));
									pst.setString(16, String.valueOf(0.0));
									pst.setString(17, z17);
									pst.setString(18, z18);
									pst.setString(19, z19);
									pst.setString(20, String.valueOf(m3));
									pst.setString(21, z21);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}
								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into payment_kurta(lmbai,seena,kemer,pait,hip,teera,glaa,baju,bs,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, String.valueOf(0.0));
									pst.setString(16, String.valueOf(0.0));
									pst.setString(17, z17);
									pst.setString(18, z18);
									pst.setString(19, z19);
									pst.setString(20, String.valueOf(m3));
									pst.setString(21, z21);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}
							} else {
								JOptionPane.showMessageDialog(null, "Error");
							}

						} else if (date004.getText().isEmpty()) {
							m1 = Double.parseDouble(date003.getText().toString());
							if (m10 == 0.0) {
								m11 = m;
							} else {
								m11 = m10;
							}

							if (m1 < m11) {
								m6 = m11 - m1;

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into payment_kurta(lmbai,seena,kemer,pait,hip,teera,glaa,baju,bs,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, String.valueOf(m1));
									pst.setString(16, String.valueOf(m6));
									pst.setString(17, z17);
									pst.setString(18, z18);
									pst.setString(19, z19);
									pst.setString(20, z20);
									pst.setString(21, z21);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "UPDATE Kurta set lmbai = ?,seena = ?,kemer = ?,pait = ?,hip = ?,teera = ?,glaa = ?,baju = ?,bs = ?,Customerid = ?,CustomerName = ?,CustomerContact = ?,CustomerAddress = ?,price = ?,advance_payments = ?,pending_payments = ?,Starting_date = ?,Ending_date = ?,price1 = ?,quantity = ?,extra = ? where Customerid = '"
											+ z10 + "' AND CustomerName ='" + z11 + "' AND CustomerContact = '" + z12
											+ "' AND CustomerAddress = '" + z13 + "' ";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, String.valueOf(m1));
									pst.setString(16, String.valueOf(m6));
									pst.setString(17, z17);
									pst.setString(18, z18);
									pst.setString(19, z19);
									pst.setString(20, z20);
									pst.setString(21, z21);

									pst.executeUpdate();
									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

							} else if (m1 == m11) {

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "UPDATE Kurta set lmbai = ?,seena = ?,kemer = ?,pait = ?,hip = ?,teera = ?,glaa = ?,baju = ?,bs = ?,Customerid = ?,CustomerName = ?,CustomerContact = ?,CustomerAddress = ?,price = ?,advance_payments = ?,pending_payments = ?,Starting_date = ?,Ending_date = ?,price1 = ?,quantity = ?,extra = ? where Customerid = '"
											+ z10 + "' AND CustomerName ='" + z11 + "' AND CustomerContact = '" + z12
											+ "' AND CustomerAddress = '" + z13 + "' ";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, String.valueOf(m1));
									pst.setString(16, String.valueOf(0));
									pst.setString(17, z17);
									pst.setString(18, z18);
									pst.setString(19, z19);
									pst.setString(20, z20);
									pst.setString(21, z21);

									pst.executeUpdate();
									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into payment_kurta(lmbai,seena,kemer,pait,hip,teera,glaa,baju,bs,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, String.valueOf(m1));
									pst.setString(16, String.valueOf(0));
									pst.setString(17, z17);
									pst.setString(18, z18);
									pst.setString(19, z19);
									pst.setString(20, z20);
									pst.setString(21, z21);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

							}

						} else if (!date003.getText().isEmpty() && !date004.getText().isEmpty()) {
							m3 = Double.parseDouble(date004.getText().toString());
							m1 = Double.parseDouble(date003.getText().toString());

							if (m10 == 0.0) {
								m11 = m;

							} else {
								m11 = m10;

							}

							if (m1 == m11 && m2 == m3) {

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into deliverd_kurta(lmbai,seena,kemer,pait,hip,teera,glaa,baju,bs,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, String.valueOf(m));
									pst.setString(16, String.valueOf(m11));
									pst.setString(17, z17);
									pst.setString(18, z18);
									pst.setString(19, z19);
									pst.setString(20, String.valueOf(m3));
									pst.setString(21, z21);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									String query1 = " DELETE FROM Kurta where Customerid= '" + z10 + "' ";
									PreparedStatement pst2 = conn.prepareStatement(query1);
									pst2.execute();
									pst2.close();
								} catch (Exception e1) {
									e1.printStackTrace();
								}

							}

							else if (m1 < m11 && m3 < m2) {
								try {
									m5 = m2 - m3;
									m6 = m11 - m1;

									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into payment_kurta(lmbai,seena,kemer,pait,hip,teera,glaa,baju,bs,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, String.valueOf(m1));
									pst.setString(16, String.valueOf(m6));
									pst.setString(17, z17);
									pst.setString(18, z18);
									pst.setString(19, z19);
									pst.setString(20, String.valueOf(m3));
									pst.setString(21, z21);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "UPDATE Kurta set  lmbai = ?,seena = ?,kemer = ?,pait = ?,hip = ?,teera = ?,glaa = ?,baju = ?,bs = ?,Customerid = ?,CustomerName = ?,CustomerContact = ?,CustomerAddress = ?,price = ?,advance_payments = ?,pending_payments = ?,Starting_date = ?,Ending_date = ?,price1 = ?,quantity = ?,extra = ? where Customerid = '"
											+ z10 + "' AND CustomerName ='" + z11 + "' AND CustomerContact = '" + z12
											+ "' AND CustomerAddress = '" + z13 + "' ";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, String.valueOf(m1));
									pst.setString(16, String.valueOf(m6));
									pst.setString(17, z17);
									pst.setString(18, z18);
									pst.setString(19, z19);
									pst.setString(20, String.valueOf(m5));
									pst.setString(21, z21);

									pst.executeUpdate();
									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into deliverd_kurta(lmbai,seena,kemer,pait,hip,teera,glaa,baju,bs,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, String.valueOf(m1));
									pst.setString(16, String.valueOf(m6));
									pst.setString(17, z17);
									pst.setString(18, z18);
									pst.setString(19, z19);
									pst.setString(20, String.valueOf(m3));
									pst.setString(21, z21);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}
							}

							else if (m1 == m11 && m3 < m2) {
								m5 = m2 - m3;

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "UPDATE Kurta set  lmbai = ?,seena = ?,kemer = ?,pait = ?,hip = ?,teera = ?,glaa = ?,baju = ?,bs = ?,Customerid = ?,CustomerName = ?,CustomerContact = ?,CustomerAddress = ?,price = ?,advance_payments = ?,pending_payments = ?,Starting_date = ?,Ending_date = ?,price1 = ?,quantity = ?,extra = ? where Customerid = '"
											+ z10 + "' AND CustomerName ='" + z11 + "' AND CustomerContact = '" + z12
											+ "' AND CustomerAddress = '" + z13 + "' ";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, String.valueOf(z14));
									pst.setString(16, String.valueOf(0));
									pst.setString(17, z17);
									pst.setString(18, z18);
									pst.setString(19, z19);
									pst.setString(20, String.valueOf(m5));
									pst.setString(21, z21);

									pst.executeUpdate();
									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into deliverd_kurta(lmbai,seena,kemer,pait,hip,teera,glaa,baju,bs,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, String.valueOf(z14));
									pst.setString(16, String.valueOf(0));
									pst.setString(17, z17);
									pst.setString(18, z18);
									pst.setString(19, z19);
									pst.setString(20, String.valueOf(m3));
									pst.setString(21, z21);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

							}

							else if (m1 < m11 && m3 == m2) {
								m6 = m11 - m1;

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into payment_kurta(lmbai,seena,kemer,pait,hip,teera,glaa,baju,bs,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, String.valueOf(m1));
									pst.setString(16, String.valueOf(m6));
									pst.setString(17, z17);
									pst.setString(18, z18);
									pst.setString(19, z19);
									pst.setString(20, String.valueOf(m3));
									pst.setString(21, z21);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into deliverd_kurta(lmbai,seena,kemer,pait,hip,teera,glaa,baju,bs,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, String.valueOf(m1));
									pst.setString(16, String.valueOf(m6));
									pst.setString(17, z17);
									pst.setString(18, z18);
									pst.setString(19, z19);
									pst.setString(20, String.valueOf(m3));
									pst.setString(21, z21);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									String query1 = " DELETE FROM Kurta where Customerid= '" + z10 + "' ";
									PreparedStatement pst2 = conn.prepareStatement(query1);
									pst2.execute();
									pst2.close();
								} catch (Exception e1) {
									e1.printStackTrace();
								}

							}

							else {
							}
						}

					}

				} else {
					System.out.println("User canceled / closed the dialog, result = ");
				}

			}
		});
		scrollPane030303.setViewportView(table_35);

		JScrollPane scrollPane040404 = new JScrollPane();

		scrollPane040404.setBounds(967, 89, 759, 303);
		panel4.add(scrollPane040404);

		table_39 = new JTable();
		table_39.setAutoResizeMode(JTable.AUTO_RESIZE_OFF);
		try {

			conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
			String query = "select * from pent ";
			PreparedStatement statment = conn.prepareStatement(query);
			ResultSet rs = statment.executeQuery();
			table_39.setModel(DbUtils.resultSetToTableModel(rs));

			rs.close();
			statment.close();
		} catch (SQLException e) {

			JOptionPane.showMessageDialog(null, "My Error 2" + e);
		}
		table_39.addMouseListener(new MouseAdapter() {
			@Override
			public void mouseClicked(MouseEvent e) {

				int dialogButton = JOptionPane.YES_NO_OPTION;
				int dialogResult = JOptionPane.showConfirmDialog(null,
						"Would You Like to Save your Previous Note First?", "Warning", dialogButton);

				if (dialogResult == JOptionPane.YES_OPTION) {

					model4 = (DefaultTableModel) table_39.getModel();
					row4 = table_39.getSelectedRow();
					id04 = model4.getValueAt(row4, 7).toString();
					try {
						String query = "Select * from pent where Customerid='" + id04 + "' ";
						PreparedStatement pst = conn.prepareStatement(query);
						ResultSet rs = pst.executeQuery();

						while (rs.next()) {

							z1 = rs.getString("lmbai");
							z2 = rs.getString("kemer");
							z3 = rs.getString("hip");
							z4 = rs.getString("gidri");
							z5 = rs.getString("pinjni");
							z6 = rs.getString("mori");
							z7 = rs.getString("putt");
							z8 = rs.getString("Customerid");
							z9 = rs.getString("CustomerName");
							z10 = rs.getString("CustomerContact");
							z11 = rs.getString("CustomerAddress");
							z12 = rs.getString("price");
							z13 = rs.getString("advance_payments");
							z14 = rs.getString("pending_payments");
							z15 = rs.getString("Starting_date");
							z16 = rs.getString("Ending_date");
							z17 = rs.getString("price1");
							z18 = rs.getString("quantity");
							z19 = rs.getString("extra");

						}

						rs.close();
						pst.close();

					} catch (Exception e1) {
						e1.printStackTrace();
					}

					String h[] = { z1, z2, z3, z4, z5, z6, z7, z8, z9, z10, z11, z12, z13, z14, z15, z16, z17, z18,
							z19 };
					date007 = new JTextField();
					date008 = new JTextField();
					JComponent[] inputs = new JComponent[] { new JLabel("Price"), date007, new JLabel("Quantity"),
							date008,

					};
					int result = JOptionPane.showConfirmDialog(null, inputs, null, JOptionPane.PLAIN_MESSAGE);
					if (result == JOptionPane.OK_OPTION) {

						m = Double.parseDouble(z14);// total price
						m1 = Double.parseDouble(z19); // per piece price
						m2 = Double.parseDouble(z20); // quantity
						m10 = Double.parseDouble(z16); // pending_payments

						if (date007.getText().isEmpty()) {
							m3 = Double.parseDouble(date008.getText().toString());
							m5 = m2 - m3; // new quantity
							if (m3 == m2) {

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into deliverd_pent (lmbai,kemer,hip,gidri,pinjni,mori,putt,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, String.valueOf(0.0));
									pst.setString(14, String.valueOf(0.0));
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, String.valueOf(m2));
									pst.setString(19, z19);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									String query1 = " DELETE FROM pent where Customerid= '" + z8 + "' ";
									PreparedStatement pst2 = conn.prepareStatement(query1);
									pst2.execute();
									pst2.close();
								} catch (Exception e1) {
									e1.printStackTrace();
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into payment_pent(lmbai,kemer,hip,gidri,pinjni,mori,putt,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, String.valueOf(0.0));
									pst.setString(14, String.valueOf(0.0));
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, String.valueOf(m2));
									pst.setString(19, z19);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

							} else if (m3 > 0 && m3 < m2) {
								m5 = m2 - m3;

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "UPDATE pent set lmbai =?,kemer =?,hip =?,gidri =?,pinjni =?,mori =?,putt =?,Customerid =?,CustomerName =?,CustomerContact =?,CustomerAddress =?,price =?,advance_payments =?,pending_payments =?,Starting_date =?,Ending_date =?,price1 = ?,quantity = ?,extra = ? where Customerid = '"
											+ q25 + "' AND CustomerName ='" + q26 + "' AND CustomerContact = '" + q27
											+ "' AND CustomerAddress = '" + q28 + "' ";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, String.valueOf(0.0));
									pst.setString(14, String.valueOf(0.0));
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, String.valueOf(m5));
									pst.setString(19, z19);

									pst.executeUpdate();
									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into deliverd_pent(lmbai,kemer,hip,gidri,pinjni,mori,putt,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, String.valueOf(0.0));
									pst.setString(14, String.valueOf(0.0));
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, String.valueOf(m3));
									pst.setString(19, z19);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}
								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into payment_pent(lmbai,kemer,hip,gidri,pinjni,mori,putt,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, String.valueOf(0.0));
									pst.setString(14, String.valueOf(0.0));
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, String.valueOf(m3));
									pst.setString(19, z19);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}
							} else {
								JOptionPane.showMessageDialog(null, "Error");
							}

						} else if (date008.getText().isEmpty()) {
							m1 = Double.parseDouble(date007.getText().toString());
							if (m10 == 0.0) {
								m11 = m;
							} else {
								m11 = m10;
							}

							if (m1 < m11) {
								m6 = m11 - m1;

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into payment_pent(lmbai,kemer,hip,gidri,pinjni,mori,putt,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, String.valueOf(m1));
									pst.setString(14, String.valueOf(m6));
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, z18);
									pst.setString(19, z19);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "UPDATE pent set lmbai =?,kemer =?,hip =?,gidri =?,pinjni =?,mori =?,putt =?,Customerid =?,CustomerName =?,CustomerContact =?,CustomerAddress =?,price =?,advance_payments =?,pending_payments =?,Starting_date =?,Ending_date =?,price1 = ?,quantity = ?,extra = ? where Customerid = '"
											+ q25 + "' AND CustomerName ='" + q26 + "' AND CustomerContact = '" + q27
											+ "' AND CustomerAddress = '" + q28 + "' ";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, String.valueOf(m1));
									pst.setString(14, String.valueOf(m6));
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, z18);
									pst.setString(19, z19);

									pst.executeUpdate();
									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

							} else if (m1 == m11) {

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "UPDATE pent set lmbai =?,kemer =?,hip =?,gidri =?,pinjni =?,mori =?,putt =?,Customerid =?,CustomerName =?,CustomerContact =?,CustomerAddress =?,price =?,advance_payments =?,pending_payments =?,Starting_date =?,Ending_date =?,price1 = ?,quantity = ?,extra = ? where Customerid = '"
											+ q25 + "' AND CustomerName ='" + q26 + "' AND CustomerContact = '" + q27
											+ "' AND CustomerAddress = '" + q28 + "' ";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, String.valueOf(m1));
									pst.setString(14, String.valueOf(0));
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, z18);
									pst.setString(19, z19);

									pst.executeUpdate();
									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into payment_pent(lmbai,kemer,hip,gidri,pinjni,mori,putt,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, String.valueOf(m1));
									pst.setString(14, String.valueOf(0));
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, z18);
									pst.setString(19, z19);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

							}

						} else if (!date007.getText().isEmpty() && !date008.getText().isEmpty()) {
							m3 = Double.parseDouble(date007.getText().toString());
							m1 = Double.parseDouble(date008.getText().toString());

							if (m10 == 0.0) {
								m11 = m;

							} else {
								m11 = m10;

							}

							if (m1 == m11 && m2 == m3) {

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into deliverd_pent(lmbai,kemer,hip,gidri,pinjni,mori,putt,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, String.valueOf(m));
									pst.setString(14, String.valueOf(m11));
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, String.valueOf(m3));
									pst.setString(19, z19);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									String query1 = " DELETE FROM pent where Customerid= '" + z8 + "' ";
									PreparedStatement pst2 = conn.prepareStatement(query1);
									pst2.execute();
									pst2.close();
								} catch (Exception e1) {
									e1.printStackTrace();
								}

							}

							else if (m1 < m11 && m3 < m2) {
								try {
									m5 = m2 - m3;
									m6 = m11 - m1;

									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into payment_pent(lmbai,kemer,hip,gidri,pinjni,mori,putt,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, String.valueOf(m1));
									pst.setString(14, String.valueOf(m6));
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, String.valueOf(m3));
									pst.setString(19, z19);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "UPDATE pent set  lmbai =?,kemer =?,hip =?,gidri =?,pinjni =?,mori =?,putt =?,Customerid =?,CustomerName =?,CustomerContact =?,CustomerAddress =?,price =?,advance_payments =?,pending_payments =?,Starting_date =?,Ending_date =?,price1 = ?,quantity = ?,extra = ? where Customerid = '"
											+ q25 + "' AND CustomerName ='" + q26 + "' AND CustomerContact = '" + q27
											+ "' AND CustomerAddress = '" + q28 + "' ";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, String.valueOf(m1));
									pst.setString(14, String.valueOf(m6));
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, String.valueOf(m5));
									pst.setString(19, z19);

									pst.executeUpdate();
									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into deliverd_pent(lmbai,kemer,hip,gidri,pinjni,mori,putt,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, String.valueOf(m1));
									pst.setString(14, String.valueOf(m6));
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, String.valueOf(m3));
									pst.setString(19, z19);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}
							}

							else if (m1 == m11 && m3 < m2) {
								m5 = m2 - m3;

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "UPDATE pent set  lmbai =?,kemer =?,hip =?,gidri =?,pinjni =?,mori =?,putt =?,Customerid =?,CustomerName =?,CustomerContact =?,CustomerAddress =?,price =?,advance_payments =?,pending_payments =?,Starting_date =?,Ending_date =?,price1 = ?,quantity = ?,extra = ? where Customerid = '"
											+ q25 + "' AND CustomerName ='" + q26 + "' AND CustomerContact = '" + q27
											+ "' AND CustomerAddress = '" + q28 + "' ";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, String.valueOf(0));
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, String.valueOf(m5));
									pst.setString(19, z19);

									pst.executeUpdate();
									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into deliverd_pent(lmbai,kemer,hip,gidri,pinjni,mori,putt,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, String.valueOf(0));
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, String.valueOf(m3));
									pst.setString(19, z19);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

							}

							else if (m1 < m11 && m3 == m2) {
								m6 = m11 - m1;

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into payment_pent(lmbai,kemer,hip,gidri,pinjni,mori,putt,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, String.valueOf(m1));
									pst.setString(14, String.valueOf(m6));
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, String.valueOf(m3));
									pst.setString(19, z19);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into deliverd_pent(lmbai,kemer,hip,gidri,pinjni,mori,putt,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, String.valueOf(m1));
									pst.setString(14, String.valueOf(m6));
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, String.valueOf(m3));
									pst.setString(19, z19);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									String query1 = " DELETE FROM pent where Customerid= '" + z8 + "' ";
									PreparedStatement pst2 = conn.prepareStatement(query1);
									pst2.execute();
									pst2.close();
								} catch (Exception e1) {
									e1.printStackTrace();
								}

							}

							else {
							}
						}

					}

				} else {
					System.out.println("User canceled / closed the dialog, result = ");
				}

			}
		});
		scrollPane040404.setViewportView(table_39);

		JScrollPane scrollPane050505 = new JScrollPane();

		scrollPane050505.setBounds(967, 405, 759, 303);
		panel4.add(scrollPane050505);

		table_36 = new JTable();
		table_36.setAutoResizeMode(JTable.AUTO_RESIZE_OFF);
		try {

			conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
			String query = "select * from Jacket ";
			PreparedStatement statment = conn.prepareStatement(query);
			ResultSet rs = statment.executeQuery();
			table_36.setModel(DbUtils.resultSetToTableModel(rs));

			rs.close();
			statment.close();
		} catch (SQLException e) {

			JOptionPane.showMessageDialog(null, "My Error 2" + e);
		}
		table_36.addMouseListener(new MouseAdapter() {
			@Override
			public void mouseClicked(MouseEvent e) {

				int dialogButton = JOptionPane.YES_NO_OPTION;
				int dialogResult = JOptionPane.showConfirmDialog(null,
						"Would You Like to Save your Previous Note First?", "Warning", dialogButton);

				if (dialogResult == JOptionPane.YES_OPTION) {

					model5 = (DefaultTableModel) table_36.getModel();
					row5 = table_36.getSelectedRow();

					id05 = model5.getValueAt(row5, 5).toString();

					try {
						String query = "Select * from Jacket where Customerid='" + id05 + "' ";
						PreparedStatement pst = conn.prepareStatement(query);
						ResultSet rs = pst.executeQuery();

						while (rs.next()) {

							z1 = rs.getString("lmbai");
							z2 = rs.getString("seena");
							z3 = rs.getString("kemer");
							z4 = rs.getString("hip");
							z5 = rs.getString("teera");
							z6 = rs.getString("Customerid");
							z7 = rs.getString("CustomerName");
							z8 = rs.getString("CustomerContact");
							z9 = rs.getString("CustomerAddress");
							z10 = rs.getString("price");
							z11 = rs.getString("advance_payments");
							z12 = rs.getString("pending_payments");
							z13 = rs.getString("Starting_date");
							z14 = rs.getString("Ending_date");
							z15 = rs.getString("price1");
							z16 = rs.getString("quantity");
							z17 = rs.getString("extra");

						}

						rs.close();
						pst.close();

					} catch (Exception e1) {
						e1.printStackTrace();
					}

					String h[] = { z1, z2, z3, z4, z5, z6, z7, z8, z9, z10, z11, z12, z13, z14, z15, z16, z17 };
					date0011 = new JTextField();
					date0012 = new JTextField();
					JComponent[] inputs = new JComponent[] { new JLabel("Price"), date0011, new JLabel("Quantity"),
							date0012,

					};
					int result = JOptionPane.showConfirmDialog(null, inputs, null, JOptionPane.PLAIN_MESSAGE);
					if (result == JOptionPane.OK_OPTION) {

						m = Double.parseDouble(z14);// total price
						m1 = Double.parseDouble(z19); // per piece price
						m2 = Double.parseDouble(z20); // quantity
						m10 = Double.parseDouble(z16); // pending_payments

						if (date0011.getText().isEmpty()) {
							m3 = Double.parseDouble(date0012.getText().toString());
							m5 = m2 - m3; // new quantity
							if (m3 == m2) {

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into deliverd_jacket (lmbai,seena,kemer,hip,teera,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, String.valueOf(0.0));
									pst.setString(12, String.valueOf(0.0));
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, z15);
									pst.setString(16, String.valueOf(m2));
									pst.setString(17, z17);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									String query1 = " DELETE FROM Jacket where Customerid= '" + z6 + "' ";
									PreparedStatement pst2 = conn.prepareStatement(query1);
									pst2.execute();
									pst2.close();
								} catch (Exception e1) {
									e1.printStackTrace();
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into payment_jacket(lmbai,seena,kemer,hip,teera,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, String.valueOf(0.0));
									pst.setString(12, String.valueOf(0.0));
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, z15);
									pst.setString(16, String.valueOf(m2));
									pst.setString(17, z17);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

							} else if (m3 > 0 && m3 < m2) {
								m5 = m2 - m3;

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "UPDATE Jacket set lmbai =?,seena =?,kemer =?,hip =?,teera =?,Customerid =?,CustomerName =?,CustomerContact =?,CustomerAddress =?,price =?,advance_payments =?,pending_payments =?,Starting_date =?,Ending_date =?,price1 = ?,quantity = ?,extra = ?  where Customerid = '"
											+ q25 + "' AND CustomerName ='" + q26 + "' AND CustomerContact = '" + q27
											+ "' AND CustomerAddress = '" + q28 + "' ";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, String.valueOf(0.0));
									pst.setString(12, String.valueOf(0.0));
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, z15);
									pst.setString(16, String.valueOf(m5));
									pst.setString(17, z17);

									pst.executeUpdate();
									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into deliverd_jacket(lmbai,seena,kemer,hip,teera,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, String.valueOf(0.0));
									pst.setString(12, String.valueOf(0.0));
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, z15);
									pst.setString(16, String.valueOf(m3));
									pst.setString(17, z17);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}
								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into payment_jacket(lmbai,seena,kemer,hip,teera,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, String.valueOf(0.0));
									pst.setString(12, String.valueOf(0.0));
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, z15);
									pst.setString(16, String.valueOf(m3));
									pst.setString(17, z17);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}
							} else {
								JOptionPane.showMessageDialog(null, "Error");
							}

						} else if (date0012.getText().isEmpty()) {
							m1 = Double.parseDouble(date0011.getText().toString());
							if (m10 == 0.0) {
								m11 = m;
							} else {
								m11 = m10;
							}

							if (m1 < m11) {
								m6 = m11 - m1;

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into payment_jacket(lmbai,seena,kemer,hip,teera,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, String.valueOf(m1));
									pst.setString(12, String.valueOf(m6));
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "UPDATE Jacket set lmbai =?,seena =?,kemer =?,hip =?,teera =?,Customerid =?,CustomerName =?,CustomerContact =?,CustomerAddress =?,price =?,advance_payments =?,pending_payments =?,Starting_date =?,Ending_date =?,price1 = ?,quantity = ?,extra = ?  where Customerid = '"
											+ q25 + "' AND CustomerName ='" + q26 + "' AND CustomerContact = '" + q27
											+ "' AND CustomerAddress = '" + q28 + "' ";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, String.valueOf(m1));
									pst.setString(12, String.valueOf(m6));
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);

									pst.executeUpdate();
									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

							} else if (m1 == m11) {

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "UPDATE Jacket set lmbai =?,seena =?,kemer =?,hip =?,teera =?,Customerid =?,CustomerName =?,CustomerContact =?,CustomerAddress =?,price =?,advance_payments =?,pending_payments =?,Starting_date =?,Ending_date =?,price1 = ?,quantity = ?,extra = ?  where Customerid = '"
											+ q25 + "' AND CustomerName ='" + q26 + "' AND CustomerContact = '" + q27
											+ "' AND CustomerAddress = '" + q28 + "' ";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, String.valueOf(m1));
									pst.setString(12, String.valueOf(0));
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);

									pst.executeUpdate();
									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into payment_jacket(lmbai,seena,kemer,hip,teera,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, String.valueOf(m1));
									pst.setString(12, String.valueOf(0));
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

							}

						} else if (!date0011.getText().isEmpty() && !date0012.getText().isEmpty()) {
							m3 = Double.parseDouble(date0011.getText().toString());
							m1 = Double.parseDouble(date0012.getText().toString());

							if (m10 == 0.0) {
								m11 = m;

							} else {
								m11 = m10;

							}

							if (m1 == m11 && m2 == m3) {

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into deliverd_jacket(lmbai,seena,kemer,hip,teera,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, String.valueOf(m));
									pst.setString(12, String.valueOf(m11));
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, z15);
									pst.setString(16, String.valueOf(m3));
									pst.setString(17, z17);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									String query1 = " DELETE FROM Jacket where Customerid= '" + z6 + "' ";
									PreparedStatement pst2 = conn.prepareStatement(query1);
									pst2.execute();
									pst2.close();
								} catch (Exception e1) {
									e1.printStackTrace();
								}

							}

							else if (m1 < m11 && m3 < m2) {
								try {
									m5 = m2 - m3;
									m6 = m11 - m1;

									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into payment_jacket(lmbai,seena,kemer,hip,teera,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, String.valueOf(m1));
									pst.setString(12, String.valueOf(m6));
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, z15);
									pst.setString(16, String.valueOf(m3));
									pst.setString(17, z17);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "UPDATE Jacket set  lmbai =?,seena =?,kemer =?,hip =?,teera =?,Customerid =?,CustomerName =?,CustomerContact =?,CustomerAddress =?,price =?,advance_payments =?,pending_payments =?,Starting_date =?,Ending_date =?,price1 = ?,quantity = ?,extra = ?  where Customerid = '"
											+ q25 + "' AND CustomerName ='" + q26 + "' AND CustomerContact = '" + q27
											+ "' AND CustomerAddress = '" + q28 + "' ";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, String.valueOf(m1));
									pst.setString(12, String.valueOf(m6));
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, z15);
									pst.setString(16, String.valueOf(m5));
									pst.setString(17, z17);

									pst.executeUpdate();
									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into deliverd_jacket(lmbai,seena,kemer,hip,teera,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, String.valueOf(m1));
									pst.setString(12, String.valueOf(m6));
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, z15);
									pst.setString(16, String.valueOf(m3));
									pst.setString(17, z17);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}
							}

							else if (m1 == m11 && m3 < m2) {
								m5 = m2 - m3;

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "UPDATE Jacket set  lmbai =?,seena =?,kemer =?,hip =?,teera =?,Customerid =?,CustomerName =?,CustomerContact =?,CustomerAddress =?,price =?,advance_payments =?,pending_payments =?,Starting_date =?,Ending_date =?,price1 = ?,quantity = ?,extra = ?  where Customerid = '"
											+ q25 + "' AND CustomerName ='" + q26 + "' AND CustomerContact = '" + q27
											+ "' AND CustomerAddress = '" + q28 + "' ";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, String.valueOf(0.0));
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, z15);
									pst.setString(16, String.valueOf(m5));
									pst.setString(17, z17);

									pst.executeUpdate();
									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into deliverd_jacket(lmbai,seena,kemer,hip,teera,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, String.valueOf(0.0));
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, z15);
									pst.setString(16, String.valueOf(m3));
									pst.setString(17, z17);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

							}

							else if (m1 < m11 && m3 == m2) {
								m6 = m11 - m1;

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into payment_jacket(lmbai,seena,kemer,hip,teera,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, String.valueOf(m1));
									pst.setString(12, String.valueOf(m6));
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, z15);
									pst.setString(16, String.valueOf(m3));
									pst.setString(17, z17);
									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into deliverd_jacket(lmbai,seena,kemer,hip,teera,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, String.valueOf(m1));
									pst.setString(12, String.valueOf(m6));
									pst.setString(13, z13);
									pst.setString(14, z14);
									pst.setString(15, z15);
									pst.setString(16, String.valueOf(m3));
									pst.setString(17, z17);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									String query1 = " DELETE FROM Jacket where Customerid= '" + z6 + "' ";
									PreparedStatement pst2 = conn.prepareStatement(query1);
									pst2.execute();
									pst2.close();
								} catch (Exception e1) {
									e1.printStackTrace();
								}

							}

							else {
							}
						}

					}

				} else {
					System.out.println("User canceled / closed the dialog, result = ");
				}

			}
		});
		scrollPane050505.setViewportView(table_36);

		JScrollPane scrollPane060606 = new JScrollPane();

		scrollPane060606.setBounds(967, 721, 759, 303);
		panel4.add(scrollPane060606);

		table_37 = new JTable();
		table_37.setAutoResizeMode(JTable.AUTO_RESIZE_OFF);
		try {

			conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
			String query = "select * from Pjama ";
			PreparedStatement statment = conn.prepareStatement(query);
			ResultSet rs = statment.executeQuery();
			table_37.setModel(DbUtils.resultSetToTableModel(rs));

			rs.close();
			statment.close();
		} catch (SQLException e) {

			JOptionPane.showMessageDialog(null, "My Error 2" + e);
		}

		table_37.addMouseListener(new MouseAdapter() {
			@Override
			public void mouseClicked(MouseEvent e) {

				int dialogButton = JOptionPane.YES_NO_OPTION;
				int dialogResult = JOptionPane.showConfirmDialog(null,
						"Would You Like to Save your Previous Note First?", "Warning", dialogButton);

				if (dialogResult == JOptionPane.YES_OPTION) {

					model6 = (DefaultTableModel) table_37.getModel();
					row6 = table_37.getSelectedRow();
					id06 = model6.getValueAt(row6, 7).toString();

					try {
						String query = "Select * from Pjama where Customerid='" + id06 + "' ";
						PreparedStatement pst = conn.prepareStatement(query);
						ResultSet rs = pst.executeQuery();

						while (rs.next()) {

							z1 = rs.getString("lmbai");
							z2 = rs.getString("kemer");
							z3 = rs.getString("hip");
							z4 = rs.getString("gidri");
							z5 = rs.getString("pinjni");
							z6 = rs.getString("mori");
							z7 = rs.getString("putt");
							z8 = rs.getString("Customerid");
							z9 = rs.getString("CustomerName");
							z10 = rs.getString("CustomerContact");
							z11 = rs.getString("CustomerAddress");
							z12 = rs.getString("price");
							z13 = rs.getString("advance_payments");
							z14 = rs.getString("pending_payments");
							z15 = rs.getString("Starting_date");
							z16 = rs.getString("Ending_date");
							z17 = rs.getString("price1");
							z18 = rs.getString("quantity");
							z19 = rs.getString("extra");

						}

						rs.close();
						pst.close();

					} catch (Exception e1) {
						e1.printStackTrace();
					}

					String h[] = { z1, z2, z3, z4, z5, z6, z7, z8, z9, z10, z11, z12, z13, z14, z15, z16, z17, z18,
							z19 };
					date009 = new JTextField();
					date0010 = new JTextField();
					JComponent[] inputs = new JComponent[] { new JLabel("Price"), date009, new JLabel("Quantity"),
							date0010,

					};
					int result = JOptionPane.showConfirmDialog(null, inputs, null, JOptionPane.PLAIN_MESSAGE);
					if (result == JOptionPane.OK_OPTION) {

						m = Double.parseDouble(z14);// total price
						m1 = Double.parseDouble(z19); // per piece price
						m2 = Double.parseDouble(z20); // quantity
						m10 = Double.parseDouble(z16); // pending_payments

						if (date009.getText().isEmpty()) {
							m3 = Double.parseDouble(date0010.getText().toString());
							m5 = m2 - m3; // new quantity
							if (m3 == m2) {

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into deliverd_pjama (lmbai,kemer,hip,gidri,pinjni,mori,putt,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, String.valueOf(0.0));
									pst.setString(14, String.valueOf(0.0));
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, String.valueOf(m2));
									pst.setString(19, z19);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									String query1 = " DELETE FROM Pjama where Customerid= '" + z8 + "' ";
									PreparedStatement pst2 = conn.prepareStatement(query1);
									pst2.execute();
									pst2.close();
								} catch (Exception e1) {
									e1.printStackTrace();
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into payment_pjama(lmbai,kemer,hip,gidri,pinjni,mori,putt,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, String.valueOf(0.0));
									pst.setString(14, String.valueOf(0.0));
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, String.valueOf(m2));
									pst.setString(19, z19);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

							} else if (m3 > 0 && m3 < m2) {
								m5 = m2 - m3;

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "UPDATE Pjama set lmbai =?,kemer =?,hip =?,gidri =?,pinjni =?,mori =?,putt =?,Customerid =?,CustomerName =?,CustomerContact =?,CustomerAddress =?,price =?,advance_payments =?,pending_payments =?,Starting_date =?,Ending_date =?,price1 = ?,quantity = ?,extra = ? where Customerid = '"
											+ q25 + "' AND CustomerName ='" + q26 + "' AND CustomerContact = '" + q27
											+ "' AND CustomerAddress = '" + q28 + "' ";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, String.valueOf(0.0));
									pst.setString(14, String.valueOf(0.0));
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, String.valueOf(m5));
									pst.setString(19, z19);

									pst.executeUpdate();
									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into deliverd_pjama(lmbai,kemer,hip,gidri,pinjni,mori,putt,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, String.valueOf(0.0));
									pst.setString(14, String.valueOf(0.0));
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, String.valueOf(m3));
									pst.setString(19, z19);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}
								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into payment_pjama(lmbai,kemer,hip,gidri,pinjni,mori,putt,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, String.valueOf(0.0));
									pst.setString(14, String.valueOf(0.0));
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, String.valueOf(m3));
									pst.setString(19, z19);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}
							} else {
								JOptionPane.showMessageDialog(null, "Error");
							}

						} else if (date009.getText().isEmpty()) {
							m1 = Double.parseDouble(date0010.getText().toString());
							if (m10 == 0.0) {
								m11 = m;
							} else {
								m11 = m10;
							}

							if (m1 < m11) {
								m6 = m11 - m1;

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into payment_pjama(lmbai,kemer,hip,gidri,pinjni,mori,putt,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, String.valueOf(m1));
									pst.setString(14, String.valueOf(m6));
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, z18);
									pst.setString(19, z19);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "UPDATE Pjama set lmbai =?,kemer =?,hip =?,gidri =?,pinjni =?,mori =?,putt =?,Customerid =?,CustomerName =?,CustomerContact =?,CustomerAddress =?,price =?,advance_payments =?,pending_payments =?,Starting_date =?,Ending_date =?,price1 = ?,quantity = ?,extra = ? where Customerid = '"
											+ q25 + "' AND CustomerName ='" + q26 + "' AND CustomerContact = '" + q27
											+ "' AND CustomerAddress = '" + q28 + "' ";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, String.valueOf(m1));
									pst.setString(14, String.valueOf(m6));
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, z18);
									pst.setString(19, z19);

									pst.executeUpdate();
									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

							} else if (m1 == m11) {

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "UPDATE Pjama set lmbai =?,kemer =?,hip =?,gidri =?,pinjni =?,mori =?,putt =?,Customerid =?,CustomerName =?,CustomerContact =?,CustomerAddress =?,price =?,advance_payments =?,pending_payments =?,Starting_date =?,Ending_date =?,price1 = ?,quantity = ?,extra = ? where Customerid = '"
											+ q25 + "' AND CustomerName ='" + q26 + "' AND CustomerContact = '" + q27
											+ "' AND CustomerAddress = '" + q28 + "' ";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, String.valueOf(m1));
									pst.setString(14, String.valueOf(0));
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, z18);
									pst.setString(19, z19);

									pst.executeUpdate();
									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into payment_pjama(lmbai,kemer,hip,gidri,pinjni,mori,putt,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, String.valueOf(m1));
									pst.setString(14, String.valueOf(0));
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, z18);
									pst.setString(19, z19);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

							}

						} else if (!date009.getText().isEmpty() && !date0010.getText().isEmpty()) {
							m3 = Double.parseDouble(date009.getText().toString());
							m1 = Double.parseDouble(date0010.getText().toString());

							if (m10 == 0.0) {
								m11 = m;

							} else {
								m11 = m10;

							}

							if (m1 == m11 && m2 == m3) {

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into deliverd_pjama(lmbai,kemer,hip,gidri,pinjni,mori,putt,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, String.valueOf(m));
									pst.setString(14, String.valueOf(m11));
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, String.valueOf(m3));
									pst.setString(19, z19);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									String query1 = " DELETE FROM Pjama where Customerid= '" + z8 + "' ";
									PreparedStatement pst2 = conn.prepareStatement(query1);
									pst2.execute();
									pst2.close();
								} catch (Exception e1) {
									e1.printStackTrace();
								}

							}

							else if (m1 < m11 && m3 < m2) {
								try {
									m5 = m2 - m3;
									m6 = m11 - m1;

									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into payment_pjama(lmbai,kemer,hip,gidri,pinjni,mori,putt,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, String.valueOf(m1));
									pst.setString(14, String.valueOf(m6));
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, String.valueOf(m3));
									pst.setString(19, z19);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "UPDATE Pjama set  lmbai =?,kemer =?,hip =?,gidri =?,pinjni =?,mori =?,putt =?,Customerid =?,CustomerName =?,CustomerContact =?,CustomerAddress =?,price =?,advance_payments =?,pending_payments =?,Starting_date =?,Ending_date =?,price1 = ?,quantity = ?,extra = ? where Customerid = '"
											+ q25 + "' AND CustomerName ='" + q26 + "' AND CustomerContact = '" + q27
											+ "' AND CustomerAddress = '" + q28 + "' ";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, String.valueOf(m1));
									pst.setString(14, String.valueOf(m6));
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, String.valueOf(m5));
									pst.setString(19, z19);

									pst.executeUpdate();
									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into deliverd_pjama(lmbai,kemer,hip,gidri,pinjni,mori,putt,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, String.valueOf(m1));
									pst.setString(14, String.valueOf(m6));
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, String.valueOf(m3));
									pst.setString(19, z19);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}
							}

							else if (m1 == m11 && m3 < m2) {
								m5 = m2 - m3;

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "UPDATE Pjama set  lmbai =?,kemer =?,hip =?,gidri =?,pinjni =?,mori =?,putt =?,Customerid =?,CustomerName =?,CustomerContact =?,CustomerAddress =?,price =?,advance_payments =?,pending_payments =?,Starting_date =?,Ending_date =?,price1 = ?,quantity = ?,extra = ? where Customerid = '"
											+ q25 + "' AND CustomerName ='" + q26 + "' AND CustomerContact = '" + q27
											+ "' AND CustomerAddress = '" + q28 + "' ";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, String.valueOf(0));
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, String.valueOf(m5));
									pst.setString(19, z19);

									pst.executeUpdate();
									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into deliverd_pjama(lmbai,kemer,hip,gidri,pinjni,mori,putt,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, z13);
									pst.setString(14, String.valueOf(0));
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, String.valueOf(m3));
									pst.setString(19, z19);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

							}

							else if (m1 < m11 && m3 == m2) {
								m6 = m11 - m1;

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into payment_pjama(lmbai,kemer,hip,gidri,pinjni,mori,putt,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, String.valueOf(m1));
									pst.setString(14, String.valueOf(m6));
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, String.valueOf(m3));
									pst.setString(19, z19);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
									String query = "Insert into deliverd_pjama(lmbai,kemer,hip,gidri,pinjni,mori,putt,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
									PreparedStatement pst = conn.prepareStatement(query);

									pst.setString(1, z1);
									pst.setString(2, z2);
									pst.setString(3, z3);
									pst.setString(4, z4);
									pst.setString(5, z5);
									pst.setString(6, z6);
									pst.setString(7, z7);
									pst.setString(8, z8);
									pst.setString(9, z9);
									pst.setString(10, z10);
									pst.setString(11, z11);
									pst.setString(12, z12);
									pst.setString(13, String.valueOf(m1));
									pst.setString(14, String.valueOf(m6));
									pst.setString(15, z15);
									pst.setString(16, z16);
									pst.setString(17, z17);
									pst.setString(18, String.valueOf(m3));
									pst.setString(19, z19);

									pst.execute();

									pst.close();

								} catch (Exception e1) {
									JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
								}

								try {
									String query1 = " DELETE FROM Pjama where Customerid= '" + z8 + "' ";
									PreparedStatement pst2 = conn.prepareStatement(query1);
									pst2.execute();
									pst2.close();
								} catch (Exception e1) {
									e1.printStackTrace();
								}

							}

							else {
							}
						}

					}

				} else {
					System.out.println("User canceled / closed the dialog, result = ");
				}
			}
		});
		scrollPane060606.setViewportView(table_37);

		ImageIcon gifImageaswx17 = new ImageIcon(this.getClass().getResource("/5th page.jpg"));
		JLabel lblNewLabellmk_1 = new JLabel(gifImageaswx17);
		lblNewLabellmk_1.setBounds(0, 0, screenSize.width, screenSize.height);
		panel4.add(lblNewLabellmk_1);

		panel14 = new JPanel();
		panel14.setBackground(Color.WHITE);
		panel14.setBounds(0, 0, screenSize.width, screenSize.height);
		f1.getContentPane().add(panel14);
		panel14.setVisible(false);
		panel14.setLayout(null);

		ImageIcon gifImage7 = new ImageIcon(this.getClass().getResource("/back.jpg"));
		JButton btnBackToButton4 = new JButton(gifImage7);
		btnBackToButton4.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 42));
		btnBackToButton4.setBounds(12, 13, 120, 57);
		btnBackToButton4.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {

				panel9.setVisible(true);
				panel14.setVisible(false);

			}

		});
		panel14.add(btnBackToButton4);

		JLabel lblNewLabel_8 = new JLabel("Employee_id");
		lblNewLabel_8.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 30));
		lblNewLabel_8.setBounds(119, 133, 222, 42);
		panel14.add(lblNewLabel_8);

		JLabel lblEmployeeName_1 = new JLabel("Employee Name");
		lblEmployeeName_1.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 30));
		lblEmployeeName_1.setBounds(119, 205, 247, 42);
		panel14.add(lblEmployeeName_1);

		JLabel lblNewLabel_01 = new JLabel("Employee Contact");
		lblNewLabel_01.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 30));
		lblNewLabel_01.setBounds(119, 300, 278, 42);
		panel14.add(lblNewLabel_01);

		JLabel lblNewLabel_2 = new JLabel("Employee Address");
		lblNewLabel_2.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 30));
		lblNewLabel_2.setBounds(119, 388, 278, 42);
		panel14.add(lblNewLabel_2);

		JLabel lblNewLabel_3 = new JLabel("Employee Sallery");
		lblNewLabel_3.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 30));
		lblNewLabel_3.setBounds(119, 476, 253, 42);
		panel14.add(lblNewLabel_3);

		textField_001 = new JTextField();
		textField_001.setBounds(409, 140, 200, 42);
		panel14.add(textField_001);
		textField_001.setColumns(10);

		try {

			String query = "Select * from Employee";
			PreparedStatement pst = conn.prepareStatement(query);
			ResultSet rs = pst.executeQuery();
			while (rs.next()) {
				id1 = rs.getInt("Employee_id");

			}
			sid = String.valueOf((id1 + 1));

			pst.close();
			rs.close();

		} catch (Exception e) {
			JOptionPane.showMessageDialog(null, "In line 2470" + e);
		}
		textField_001.setText(sid);

		textField_002 = new JTextField();
		textField_002.setBounds(409, 212, 200, 42);
		panel14.add(textField_002);
		textField_002.setColumns(10);

		textField_003 = new JTextField();
		textField_003.setBounds(409, 300, 200, 42);
		panel14.add(textField_003);
		textField_003.setColumns(10);

		textField_004 = new JTextField();
		textField_004.setBounds(409, 388, 200, 42);
		panel14.add(textField_004);
		textField_004.setColumns(10);

		textField_005 = new JTextField();
		textField_005.setBounds(409, 476, 200, 42);
		panel14.add(textField_005);
		textField_005.setColumns(10);

		ImageIcon savImage3 = new ImageIcon(this.getClass().getResource("/save.jpg"));
		JButton btnSave10 = new JButton(savImage3);
		btnSave10.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 60));
		btnSave10.setBounds(175, 621, 183, 70);
		panel14.add(btnSave10);
		btnSave10.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent arg0) {

				try {
					String query = "Insert into Employee (Employee_id,Employee_Name,Employee_Contact,Employee_Address,Employee_Sallery) values(?,?,?,?,?)";
					PreparedStatement pst = conn.prepareStatement(query);
					pst.setString(1, textField_001.getText());
					pst.setString(2, textField_002.getText());
					pst.setString(3, textField_003.getText());
					pst.setString(4, textField_004.getText());
					pst.setString(5, textField_005.getText());

					up = textField_001.getText();

					pst.execute();

					pst.close();

				} catch (Exception e1) {
					JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
				}

				try {

					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
					String query = "select * from Employee ";
					PreparedStatement statment = conn.prepareStatement(query);
					ResultSet rs = statment.executeQuery();
					table_2.setModel(DbUtils.resultSetToTableModel(rs));
					rs.close();
					statment.close();
				} catch (SQLException e) {

					e.printStackTrace();
				}

				textField_001.setText(null);
				textField_002.setText(null);
				textField_003.setText(null);
				textField_004.setText(null);
				textField_005.setText(null);

			}
		});

		JSeparator separator1 = new JSeparator();
		separator1.setOrientation(SwingConstants.VERTICAL);
		separator1.setBounds(815, 0, 8, 1033);
		panel14.add(separator1);

		try {

			conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
			String query = "select * from Employee ";
			PreparedStatement statment = conn.prepareStatement(query);
			ResultSet rs = statment.executeQuery();
			rs.close();
			statment.close();
		} catch (SQLException e) {

			e.printStackTrace();
		}

		t_001 = new JTextField();
		t_001.setBounds(920, 247, 177, 51);
		panel14.add(t_001);
		t_001.setColumns(10);

		JComboBox comboBox_0001 = new JComboBox();
		comboBox_0001.setForeground(Color.WHITE);
		comboBox_0001.setBackground(Color.BLACK);
		comboBox_0001.setModel(new DefaultComboBoxModel(
				new String[] { "Employee_id", "Employee_Name", "Employee_Contact", "Employee_Address" }));
		comboBox_0001.setBounds(920, 169, 166, 51);
		panel14.add(comboBox_0001);

		JButton btnSearch_1 = new JButton("Search");
		btnSearch_1.setForeground(Color.WHITE);
		btnSearch_1.setBackground(new Color(153, 0, 0));
		btnSearch_1.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent arg0) {

				// d3=comboBox_0001.getSelectedItem().toString();
				d4 = t_001.getText();

				if (d3.equals("Employee_id")) {
					try {
						String query = "Select * from Employee Where Employee_id =  '" + d4 + "'  ";
						PreparedStatement pst = conn.prepareStatement(query);
						ResultSet rs = pst.executeQuery();
						table_2.setModel(DbUtils.resultSetToTableModel(rs));

					} catch (Exception e) {
						e.printStackTrace();
					}
				} else if (d3.equals("Employee_Name")) {
					try {
						String query = "Select * from Employee Where Employee_Name =  '" + d4 + "'  ";
						PreparedStatement pst = conn.prepareStatement(query);
						ResultSet rs = pst.executeQuery();
						table_2.setModel(DbUtils.resultSetToTableModel(rs));

					} catch (Exception e) {
						e.printStackTrace();
					}
				} else if (d3.equals("Employee_Contact")) {
					try {
						String query = "Select * from Employee Where Employee_Contact =  '" + d4 + "'  ";
						PreparedStatement pst = conn.prepareStatement(query);
						ResultSet rs = pst.executeQuery();
						table_2.setModel(DbUtils.resultSetToTableModel(rs));

					} catch (Exception e) {
						e.printStackTrace();
					}
				} else if (d3.equals("Employee_Address")) {
					try {
						String query = "Select * from Employee Where Employee_Address =  '" + d4 + "'  ";
						PreparedStatement pst = conn.prepareStatement(query);
						ResultSet rs = pst.executeQuery();
						table_2.setModel(DbUtils.resultSetToTableModel(rs));

					} catch (Exception e) {
						e.printStackTrace();
					}
				}

			}
		});
		btnSearch_1.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 30));
		btnSearch_1.setBounds(1189, 169, 166, 51);
		panel14.add(btnSearch_1);

		JPopupMenu popupMenu_2 = new JPopupMenu();
		JMenuItem menuItemAdd__1 = new JMenuItem("Edit");
		menuItemAdd__1.addActionListener(new ActionListener() {

			@Override
			public void actionPerformed(ActionEvent arg0) {
				DefaultTableModel model = (DefaultTableModel) table_2.getModel();
				int row = table_2.getSelectedRow();
				textField_001.setText((String) model.getValueAt(row, 0));
				textField_002.setText((String) model.getValueAt(row, 1));
				textField_003.setText((String) model.getValueAt(row, 2));
				textField_004.setText((String) model.getValueAt(row, 3));
				textField_005.setText((String) model.getValueAt(row, 4));

			}

		});
		popupMenu_2.add(menuItemAdd__1);

		menuItemRemoveAll = new JMenuItem("Delete");
		menuItemRemoveAll.addActionListener(new ActionListener() {

			@Override
			public void actionPerformed(ActionEvent arg0) {

				DefaultTableModel model = (DefaultTableModel) table_2.getModel();
				int row = table_2.getSelectedRow();
				id_1 = model.getValueAt(row, 0).toString();
				try {
					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
					String query1 = " DELETE FROM Employee where Employee_id= '" + id_1 + "' ";
					PreparedStatement pst2 = conn.prepareStatement(query1);
					pst2.execute();
					pst2.close();
				} catch (Exception e1) {
					e1.printStackTrace();
				}

				try {

					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
					String query = "select * from Employee ";
					PreparedStatement statment = conn.prepareStatement(query);
					ResultSet rs = statment.executeQuery();
					table_2.setModel(DbUtils.resultSetToTableModel(rs));
					rs.close();
					statment.close();
				} catch (SQLException e) {

					e.printStackTrace();
				}

			}
		});

		popupMenu_2.add(menuItemRemoveAll);

		JScrollPane scrollPane_01 = new JScrollPane();
		scrollPane_01.setBounds(910, 341, 836, 623);
		panel14.add(scrollPane_01);
		table_2 = new JTable();
		table_2.addMouseListener(new MouseAdapter() {
			@Override
			public void mouseClicked(MouseEvent e) {

				table_2.setComponentPopupMenu(popupMenu_2);

			}
		});
		try {

			conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
			String query = "select * from Employee ";
			PreparedStatement statment = conn.prepareStatement(query);
			ResultSet rs = statment.executeQuery();
			table_2.setModel(DbUtils.resultSetToTableModel(rs));
			rs.close();
			statment.close();
		} catch (SQLException e) {
			e.printStackTrace();
		}

		scrollPane_01.setViewportView(table_2);

		ImageIcon naImage3 = new ImageIcon(this.getClass().getResource("/employee img.jpg"));

		JButton btnRefresh_2 = new JButton("Refresh");
		btnRefresh_2.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent arg0) {

				try {

					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
					String query = "select * from Employee ";
					PreparedStatement statment = conn.prepareStatement(query);
					ResultSet rs = statment.executeQuery();
					table_2.setModel(DbUtils.resultSetToTableModel(rs));
					rs.close();
					statment.close();
				} catch (SQLException e) {
					e.printStackTrace();
				}

			}
		});
		btnRefresh_2.setForeground(Color.WHITE);
		btnRefresh_2.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 30));
		btnRefresh_2.setBackground(new Color(153, 0, 0));
		btnRefresh_2.setBounds(1189, 247, 166, 51);
		panel14.add(btnRefresh_2);

		JButton btnUpdate_2 = new JButton((Icon) null);
		btnUpdate_2.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {

				DefaultTableModel model = (DefaultTableModel) table_2.getModel();
				int nn = table_2.getSelectedRow();
				String hk1 = model.getValueAt(nn, 0).toString();

				try {
					String query = "UPDATE Employee SET Employee_id = ?,Employee_Name = ?,Employee_Contact = ?,Employee_Address = ?,Employee_Sallery = ? Where Employee_id =  '"
							+ hk1 + "' ";
					PreparedStatement pst = conn.prepareStatement(query);

					pst.setString(1, textField_001.getText());
					pst.setString(2, textField_002.getText());
					pst.setString(3, textField_003.getText());
					pst.setString(4, textField_004.getText());
					pst.setString(5, textField_005.getText());
					pst.executeUpdate();
					JOptionPane.showMessageDialog(null, "Data Updated !");
					pst.close();

				} catch (Exception e1) {
					JOptionPane.showMessageDialog(null, e1);
				}

				try {

					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
					String query = "select * from Employee ";
					PreparedStatement statment = conn.prepareStatement(query);
					ResultSet rs = statment.executeQuery();
					table_2.setModel(DbUtils.resultSetToTableModel(rs));
					rs.close();
					statment.close();
				} catch (SQLException e1) {

					e1.printStackTrace();
				}

			}
		});
		btnUpdate_2.setForeground(Color.WHITE);
		btnUpdate_2.setText("Update");
		btnUpdate_2.setBackground(new Color(102, 51, 0));
		btnUpdate_2.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 39));
		btnUpdate_2.setBounds(395, 621, 183, 70);
		panel14.add(btnUpdate_2);
		JLabel lblNewLabel_employee = new JLabel(naImage3);

		lblNewLabel_employee.setBounds(0, 0, screenSize.width, screenSize.height);
		panel14.add(lblNewLabel_employee);

		panel15 = new JPanel();
		panel15.setBackground(new Color(102, 0, 0));
		panel15.setBounds(0, 0, screenSize.width, screenSize.height);
		f1.getContentPane().add(panel15);
		panel15.setVisible(false);
		panel15.setLayout(null);

		ImageIcon gifImage8 = new ImageIcon(this.getClass().getResource("/back.jpg"));
		JButton btnBackToButton5 = new JButton(gifImage8);
		btnBackToButton5.setBounds(12, 13, 120, 57);
		btnBackToButton5.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {

				panel15.setVisible(false);
				panel9.setVisible(true);
			}

		});
		panel15.add(btnBackToButton5);

		JLabel lblNewLabel__0 = new JLabel("UserName");
		lblNewLabel__0.setForeground(Color.WHITE);
		lblNewLabel__0.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 45));
		lblNewLabel__0.setBounds(149, 58, 206, 72);
		panel15.add(lblNewLabel__0);

		JLabel lblPassword = new JLabel("Password");
		lblPassword.setForeground(Color.WHITE);
		lblPassword.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 45));
		lblPassword.setBounds(149, 202, 206, 72);
		panel15.add(lblPassword);

		textField = new JTextField();
		textField.setFont(new Font("Times New Roman", Font.PLAIN, 21));
		textField.setBounds(458, 71, 211, 48);
		panel15.add(textField);
		textField.setColumns(10);

		ImageIcon btnSignin_0301_11 = new ImageIcon(this.getClass().getResource("/log in but..jpg"));
		JButton btnSignin = new JButton(btnSignin_0301_11);
		btnSignin.setForeground(new Color(102, 51, 51));

		btnSignin.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent arg0) {

				w1 = textField.getText();
				w2 = passwordField_3.getText();
				wtx5 = "admin";

				try {

					String query = "Select * from Trailor Where UserName =  '" + w1 + "'  ";
					PreparedStatement pst = conn.prepareStatement(query);
					ResultSet rs = pst.executeQuery();

					while (rs.next()) {
						w3 = rs.getString("Username");
						w4 = rs.getString("Password");
						wt11 = rs.getString("User");
					}

					if (w1.equals(w3) && w2.equals(w4))

					{
						if (wtx5.equalsIgnoreCase(wt11)) {
							panel23.setVisible(true);
							panel15.setVisible(false);
						}

						else {
							JOptionPane.showMessageDialog(null, "Username & Password doesn't exist");
						}

					}

					else {
						JOptionPane.showMessageDialog(null, "Username & Password doesn't exist");
					}

					pst.execute();
					rs.close();
				} catch (Exception e) {
					JOptionPane.showMessageDialog(null, "Error = " + e);
				}

			}
		});

		btnSignin.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 33));
		btnSignin.setBounds(312, 375, 133, 42);
		panel15.add(btnSignin);

		panel20 = new JPanel();
		panel20.setBackground(new Color(102, 0, 0));
		panel20.setBounds(0, 0, screenSize.width, screenSize.height);
		f1.getContentPane().add(panel20);
		panel20.setVisible(false);
		panel20.setLayout(null);

		ImageIcon gifImage9 = new ImageIcon(this.getClass().getResource("/back.jpg"));
		btnNewButton = new JButton(gifImage9);
		btnNewButton.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {
			}
		});
		btnNewButton.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 24));
		btnNewButton.setBounds(12, 13, 120, 57);
		panel20.add(btnNewButton);

		lblName = new JLabel("Name");
		lblName.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 30));
		lblName.setBounds(148, 59, 116, 38);
		panel20.add(lblName);

		lblUsername = new JLabel("UserName");
		lblUsername.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 30));
		lblUsername.setBounds(148, 138, 141, 38);
		panel20.add(lblUsername);

		lblQuestion = new JLabel("Question");
		lblQuestion.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 30));
		lblQuestion.setBounds(148, 224, 116, 38);
		panel20.add(lblQuestion);

		lblAnswer = new JLabel("Answer");
		lblAnswer.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 30));
		lblAnswer.setBounds(148, 305, 116, 38);
		panel20.add(lblAnswer);

		label_2 = new JLabel("->");
		label_2.setFont(new Font("Tahoma", Font.BOLD | Font.ITALIC, 30));
		label_2.setBounds(327, 59, 48, 46);
		panel20.add(label_2);

		label_3 = new JLabel("->");
		label_3.setFont(new Font("Tahoma", Font.BOLD | Font.ITALIC, 30));
		label_3.setBounds(327, 138, 48, 46);
		panel20.add(label_3);

		label_5 = new JLabel("->");
		label_5.setFont(new Font("Tahoma", Font.BOLD | Font.ITALIC, 30));
		label_5.setBounds(327, 224, 48, 46);
		panel20.add(label_5);

		label_6 = new JLabel("->");
		label_6.setFont(new Font("Tahoma", Font.BOLD | Font.ITALIC, 30));
		label_6.setBounds(327, 305, 48, 46);
		panel20.add(label_6);

		textField_5 = new JTextField();
		textField_5.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 21));
		textField_5.setBounds(416, 55, 188, 50);
		panel20.add(textField_5);
		textField_5.setColumns(10);

		textField_6 = new JTextField();
		textField_6.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 21));
		textField_6.setColumns(10);
		textField_6.setBounds(416, 135, 188, 50);
		panel20.add(textField_6);

		textField_7 = new JTextField();
		textField_7.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 21));
		textField_7.setColumns(10);
		textField_7.setBounds(416, 305, 188, 50);
		panel20.add(textField_7);

		JComboBox comboBox__01 = new JComboBox();
		comboBox__01.setModel(new DefaultComboBoxModel(new String[] { "1=What is your Nickname ?",
				"2=What is your first school ?", "3=What is your Mother's name ?" }));
		comboBox__01.setBounds(416, 225, 188, 46);
		panel20.add(comboBox__01);

		JButton btnProceed = new JButton("Proceed");
		btnProceed.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 45));
		btnProceed.setBounds(218, 464, 219, 58);
		btnProceed.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {

				w5 = textField_2.getText();
				w6 = textField_3.getText();
				w7 = comboBox.getSelectedItem().toString();
				w8 = textField_4.getText();

				qw1 = w5;
				qw2 = w6;
				qw3 = w7;
				qw4 = w8;

				panel22.setVisible(true);
				panel20.setVisible(false);
			}

		});
		panel20.add(btnProceed);

		ImageIcon gifImagebackg = new ImageIcon(this.getClass().getResource("/background without img.jpg"));
		JLabel lblNewLabelproceed = new JLabel(gifImagebackg);
		lblNewLabelproceed.setBounds(0, 0, screenSize.width, screenSize.height);
		panel20.add(lblNewLabelproceed);

		JButton btnBackToButton0002 = new JButton("Back to button 1");
		btnBackToButton0002.setBounds(59, 98, 327, 150);
		btnBackToButton0002.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {

				panel20.setVisible(false);
				panel4.setVisible(true);
			}

		});

		panel21 = new JPanel();
		panel21.setBackground(new Color(102, 0, 0));
		panel21.setBounds(0, 0, screenSize.width, screenSize.height);
		f1.getContentPane().add(panel21);
		panel21.setVisible(false);
		panel21.setLayout(null);

		JComboBox comboBoxx = new JComboBox();
		comboBoxx.setModel(new DefaultComboBoxModel(new String[] { "1=What is your Nickname ?",
				"2=What is your first school ?", "3=What is your Mother's name ?" }));
		comboBoxx.setBounds(401, 244, 276, 46);
		panel21.add(comboBoxx);

		JLabel lblNewLabeel = new JLabel("Name");
		lblNewLabeel.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 30));
		lblNewLabeel.setBounds(43, 34, 186, 27);
		panel21.add(lblNewLabeel);

		JLabel llblNewLabel_101 = new JLabel("UserName");
		llblNewLabel_101.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 30));
		llblNewLabel_101.setBounds(42, 114, 187, 27);
		panel21.add(llblNewLabel_101);

		JLabel llblNewLabel_02 = new JLabel("Password");
		llblNewLabel_02.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 30));
		llblNewLabel_02.setBounds(42, 179, 187, 27);
		panel21.add(llblNewLabel_02);

		JLabel llblNewLabel_03 = new JLabel("Question");
		llblNewLabel_03.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 30));
		llblNewLabel_03.setBounds(42, 244, 187, 27);
		panel21.add(llblNewLabel_03);

		JLabel llblNewLabel_04 = new JLabel("Answer");
		llblNewLabel_04.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 30));
		llblNewLabel_04.setBounds(42, 326, 187, 27);
		panel21.add(llblNewLabel_04);

		JLabel llblNewLabel_05 = new JLabel("->");
		llblNewLabel_05.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 51));
		llblNewLabel_05.setBounds(294, 34, 56, 46);
		panel21.add(llblNewLabel_05);

		JLabel llblNewLabel_06 = new JLabel("->");
		llblNewLabel_06.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 51));
		llblNewLabel_06.setBounds(304, 106, 56, 46);
		panel21.add(llblNewLabel_06);

		JLabel llblNewLabel_07 = new JLabel("->");
		llblNewLabel_07.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 51));
		llblNewLabel_07.setBounds(294, 179, 56, 46);
		panel21.add(llblNewLabel_07);

		JLabel llblNewLabel_08 = new JLabel("->");
		llblNewLabel_08.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 51));
		llblNewLabel_08.setBounds(294, 244, 56, 46);
		panel21.add(llblNewLabel_08);

		JLabel llblNewLabel_09 = new JLabel("->");
		llblNewLabel_09.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 51));
		llblNewLabel_09.setBounds(294, 326, 56, 46);
		panel21.add(llblNewLabel_09);

		t_1 = new JTextField();
		t_1.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 30));
		t_1.setBounds(401, 34, 276, 46);
		panel21.add(t_1);
		t_1.setColumns(10);

		t_2 = new JTextField();
		t_2.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 30));
		t_2.setBounds(401, 106, 276, 46);
		panel21.add(t_2);
		t_2.setColumns(10);

		t_3 = new JTextField();
		t_3.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 30));
		t_3.setBounds(401, 175, 276, 46);
		panel21.add(t_3);
		t_3.setColumns(10);

		t_5 = new JTextField();
		t_5.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 30));
		t_5.setBounds(401, 319, 276, 46);
		panel21.add(t_5);
		t_5.setColumns(10);

		JButton btnNewButton__2 = new JButton("Sign up");
		btnNewButton__2.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent arg0) {

				try {
					String query = "Insert into Trailor (Name,UserName,Password,Question,Answer,User) values(?,?,?,?,?,?)";
					PreparedStatement pst = conn.prepareStatement(query);
					pst.setString(1, t_1.getText());
					pst.setString(2, t_2.getText());
					pst.setString(3, t_3.getText());
					pst.setString(4, comboBoxx.getSelectedItem().toString());
					pst.setString(5, t_5.getText());
					pst.setString(6, "admin");

					pst.execute();
					JOptionPane.showMessageDialog(null, "Data Saved ! ");
					pst.close();

				} catch (Exception e1) {
					JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
				}

				panel15.setVisible(true);
				panel21.setVisible(false);
			}
		});
		btnNewButton__2.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 30));
		btnNewButton__2.setBounds(270, 462, 226, 109);
		panel21.add(btnNewButton__2);

		passwordField_3 = new JPasswordField();
		passwordField_3.setBounds(458, 202, 211, 48);
		panel15.add(passwordField_3);

		ImageIcon gifImageeee3 = new ImageIcon(this.getClass().getResource("/admin back.jpg"));
		JLabel lblNewLabeladmin = new JLabel(gifImageeee3);
		lblNewLabeladmin.setBounds(0, 0, screenSize.width, screenSize.height);
		panel15.add(lblNewLabeladmin);

		panel16 = new JPanel();
		panel16.setBackground(new Color(102, 0, 0));
		panel16.setBounds(0, 0, screenSize.width, screenSize.height);
		f1.getContentPane().add(panel16);
		panel16.setVisible(false);
		panel16.setLayout(null);

		JButton btnBackToButton6 = new JButton("Back");
		btnBackToButton6.setBounds(12, 13, 120, 57);
		btnBackToButton6.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {

				panel7.setVisible(false);
				panel9.setVisible(true);
			}

		});
		panel16.add(btnBackToButton6);

		panel17 = new JPanel();
		panel17.setBackground(new Color(102, 0, 0));
		panel17.setBounds(0, 0, screenSize.width, screenSize.height);
		f1.getContentPane().add(panel17);
		panel17.setVisible(false);
		panel17.setLayout(null);

		ImageIcon gifImage10 = new ImageIcon(this.getClass().getResource("/back.jpg"));
		JButton btnBackToButton7 = new JButton(gifImage10);
		btnBackToButton7.setFont(new Font("Sitka Text", Font.BOLD | Font.ITALIC, 48));
		btnBackToButton7.setBounds(12, 13, 120, 57);
		btnBackToButton7.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {

				if (hk5 > 0) {
					panel9.setVisible(true);
					panel17.setVisible(false);
				} else {
					panel6.setVisible(true);
					panel17.setVisible(false);
				}
			}

		});
		panel17.add(btnBackToButton7);

		t_0001 = new JTextField();
		t_0001.setBounds(210, 606, 97, 57);
		panel17.add(t_0001);
		t_0001.setColumns(10);

		ImageIcon gifImage3bb = new ImageIcon(this.getClass().getResource("/search 3rd page.jpg"));
		JButton btnNewButton_01 = new JButton(gifImage3bb);
		btnNewButton_01.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent arg0) {

				d5 = comboBox_001.getSelectedItem().toString();
				d6 = t_0001.getText();

				if (d5.equals("Customer_id")) {
					try {
						String query = "Select * from Customer Where Customerid =  '" + d6 + "'  ";
						PreparedStatement pst = conn.prepareStatement(query);
						ResultSet rs = pst.executeQuery();
						table_3.setModel(DbUtils.resultSetToTableModel(rs));

					} catch (Exception e) {
						e.printStackTrace();
					}
				} else if (d5.equals("Customer_Name")) {
					try {
						String query = "Select * from Customer Where CustomerName =  '" + d6 + "'  ";
						PreparedStatement pst = conn.prepareStatement(query);
						ResultSet rs = pst.executeQuery();
						table_3.setModel(DbUtils.resultSetToTableModel(rs));

					} catch (Exception e) {
						e.printStackTrace();
					}
				} else if (d5.equals("Customer_Contact")) {
					try {
						String query = "Select * from Customer Where CustomerContact =  '" + d6 + "'  ";
						PreparedStatement pst = conn.prepareStatement(query);
						ResultSet rs = pst.executeQuery();
						table_3.setModel(DbUtils.resultSetToTableModel(rs));

					} catch (Exception e) {
						e.printStackTrace();
					}
				} else if (d5.equals("Customer_Address")) {
					try {
						String query = "Select * from Customer Where CustomerAddress =  '" + d6 + "'  ";
						PreparedStatement pst = conn.prepareStatement(query);
						ResultSet rs = pst.executeQuery();
						table_3.setModel(DbUtils.resultSetToTableModel(rs));

					} catch (Exception e) {
						e.printStackTrace();
					}
				}

			}
		});
		btnNewButton_01.setBounds(113, 698, 149, 57);
		panel17.add(btnNewButton_01);

		try {

			conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
			String query = "select * from Customer ";
			PreparedStatement statment = conn.prepareStatement(query);
			ResultSet rs = statment.executeQuery();
			rs.close();
			statment.close();
		} catch (SQLException e) {

			e.printStackTrace();
		}

		JScrollPane scrollPane_011 = new JScrollPane();
		scrollPane_011.setBounds(12, 128, 295, 465);
		panel17.add(scrollPane_011);

		table_3 = new JTable();
		table_3.setAutoResizeMode(JTable.AUTO_RESIZE_OFF);
		try {

			conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
			String query = "select * from Customer ";
			PreparedStatement statment = conn.prepareStatement(query);
			ResultSet rs = statment.executeQuery();
			table_3.setModel(DbUtils.resultSetToTableModel(rs));
			rs.close();
			statment.close();
		} catch (SQLException e) {

			e.printStackTrace();
		}

		table_3.addMouseListener(new MouseAdapter() {
			@Override
			public void mouseClicked(MouseEvent arg0) {

				DefaultTableModel model = (DefaultTableModel) table_3.getModel();
				int row = table_3.getSelectedRow();

				id2 = model.getValueAt(row, 0).toString();
				name1 = model.getValueAt(row, 1).toString();
				contact = model.getValueAt(row, 2).toString();
				address = model.getValueAt(row, 3).toString();

				try {
					String query = "Select * from  Shirt where Customerid = '" + id2 + "' AND CustomerName = '" + name1
							+ "' ";
					PreparedStatement statment = conn.prepareStatement(query);
					ResultSet rs = statment.executeQuery();
					while (rs.next()) {
						g1.setText(rs.getString("lmbai"));
						g2.setText(rs.getString("seena"));
						g3.setText(rs.getString("kemer"));
						g4.setText(rs.getString("pait"));
						g5.setText(rs.getString("hip"));
						g6.setText(rs.getString("teera"));
						g7.setText(rs.getString("glaa"));
						g8.setText(rs.getString("baju"));
						g9.setText(rs.getString("bs"));

					}

					rs.close();
					statment.close();

				} catch (Exception e1) {
					JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
				}

				try {
					String query = "Select * from pent where Customerid = '" + id2 + "' AND CustomerName = '" + name1
							+ "'   ";
					PreparedStatement pst = conn.prepareStatement(query);
					ResultSet rs = pst.executeQuery();

					while (rs.next()) {

						h1.setText(rs.getString("lmbai"));
						h2.setText(rs.getString("kemer"));
						h3.setText(rs.getString("hip"));
						h4.setText(rs.getString("gidri"));
						h5.setText(rs.getString("pinjni"));
						h6.setText(rs.getString("mori"));
						h7.setText(rs.getString("putt"));
					}

					rs.close();
					pst.close();

				} catch (Exception e) {
					e.printStackTrace();
				}

				try {
					String query = "Select * from Coat where Customerid = '" + id2 + "' AND CustomerName = '" + name1
							+ "'   ";
					PreparedStatement pst = conn.prepareStatement(query);
					ResultSet rs = pst.executeQuery();

					while (rs.next()) {

						h8.setText(rs.getString("lmbai"));
						h9.setText(rs.getString("seena"));
						h10.setText(rs.getString("kemer"));
						h11.setText(rs.getString("pait"));
						h12.setText(rs.getString("hip"));
						h13.setText(rs.getString("teera"));
						h14.setText(rs.getString("baju"));
						h15.setText(rs.getString("dor"));
						h16.setText(rs.getString("back"));
						textField_29.setText(rs.getString("bs"));
						textField_26.setText(rs.getString("bm"));
						textField_27.setText(rs.getString("shoulder"));

					}

					rs.close();
					pst.close();

				} catch (Exception e) {
					e.printStackTrace();
				}

				try {
					String query = "Select * from Jacket where Customerid = '" + id2 + "' AND CustomerName = '" + name1
							+ "'   ";
					PreparedStatement pst = conn.prepareStatement(query);
					ResultSet rs = pst.executeQuery();

					while (rs.next()) {

						h17.setText(rs.getString("lmbai"));
						h18.setText(rs.getString("seena"));
						h19.setText(rs.getString("kemer"));
						h20.setText(rs.getString("hip"));
						h21.setText(rs.getString("teera"));

					}

					rs.close();
					pst.close();

				} catch (Exception e) {
					e.printStackTrace();
				}

				try {
					String query = "Select * from Kurta where Customerid = '" + id2 + "' AND CustomerName = '" + name1
							+ "'   ";
					PreparedStatement pst = conn.prepareStatement(query);
					ResultSet rs = pst.executeQuery();

					while (rs.next()) {

						h22.setText(rs.getString("lmbai"));
						h23.setText(rs.getString("seena"));
						h24.setText(rs.getString("kemer"));
						h25.setText(rs.getString("pait"));
						h26.setText(rs.getString("hip"));
						h27.setText(rs.getString("teera"));
						h28.setText(rs.getString("glaa"));
						textField_30.setText(rs.getString("baju"));
						textField_28.setText(rs.getString("bs"));

					}

					rs.close();
					pst.close();

				} catch (Exception e) {
					e.printStackTrace();
				}

				try {
					String query = "Select * from Pjama where Customerid = '" + id2 + "' AND CustomerName = '" + name1
							+ "'   ";
					PreparedStatement pst = conn.prepareStatement(query);
					ResultSet rs = pst.executeQuery();

					while (rs.next()) {

						h29.setText(rs.getString("lmbai"));
						h30.setText(rs.getString("kemer"));
						h31.setText(rs.getString("hip"));
						h32.setText(rs.getString("gidri"));
						h33.setText(rs.getString("pinjni"));
						h34.setText(rs.getString("mori"));
						h35.setText(rs.getString("putt"));

					}

					rs.close();
					pst.close();

				} catch (Exception e) {
					e.printStackTrace();
				}

			}
		});
		scrollPane_011.setViewportView(table_3);

		comboBox_001 = new JComboBox();
		comboBox_001.setModel(new DefaultComboBoxModel(
				new String[] { "Customer_id", "Customer_Name", "Customer_Contact", "Customer_Address" }));
		comboBox_001.setBounds(12, 606, 188, 56);
		panel17.add(comboBox_001);

		chooser = new JDateChooser();
		chooser.setDateFormatString("yyyy-MM-dd");
		chooser.setBounds(334, 399, 170, 56);
		panel17.add(chooser);

		chooser1 = new JDateChooser();
		chooser1.setDateFormatString("yyyy-MM-dd");
		chooser1.setBounds(334, 231, 188, 56);
		panel17.add(chooser1);

		JLabel lblNewLabel__011 = new JLabel("kemer");
		lblNewLabel__011.setOpaque(true);
		lblNewLabel__011.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 30));
		lblNewLabel__011.setBounds(817, 44, 97, 42);
		panel17.add(lblNewLabel__011);

		JLabel lblNewLabel__022 = new JLabel("seena");
		lblNewLabel__022.setOpaque(true);
		lblNewLabel__022.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 30));
		lblNewLabel__022.setBounds(719, 44, 86, 42);
		panel17.add(lblNewLabel__022);

		JLabel lblNewLabel__033 = new JLabel("pait");
		lblNewLabel__033.setOpaque(true);
		lblNewLabel__033.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 30));
		lblNewLabel__033.setBounds(926, 44, 66, 42);
		panel17.add(lblNewLabel__033);

		JLabel lblNewLabel_044 = new JLabel("hip");
		lblNewLabel_044.setOpaque(true);
		lblNewLabel_044.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 30));
		lblNewLabel_044.setBounds(1004, 44, 54, 42);
		panel17.add(lblNewLabel_044);

		JLabel lblNewLabel_055 = new JLabel("teera");
		lblNewLabel_055.setOpaque(true);
		lblNewLabel_055.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 30));
		lblNewLabel_055.setBounds(1070, 44, 74, 42);
		panel17.add(lblNewLabel_055);

		JLabel lblNewLabel_066 = new JLabel("glaa");
		lblNewLabel_066.setOpaque(true);
		lblNewLabel_066.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 30));
		lblNewLabel_066.setBounds(1175, 44, 66, 42);
		panel17.add(lblNewLabel_066);

		JLabel lblNewLabel_077 = new JLabel("baju");
		lblNewLabel_077.setOpaque(true);
		lblNewLabel_077.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 30));
		lblNewLabel_077.setBounds(1253, 46, 73, 42);
		panel17.add(lblNewLabel_077);

		g1 = new JTextField();
		g1.setBounds(621, 115, 86, 42);
		panel17.add(g1);
		g1.setColumns(10);

		g2 = new JTextField();
		g2.setBounds(719, 115, 86, 42);
		panel17.add(g2);
		g2.setColumns(10);

		g3 = new JTextField();
		g3.setBounds(817, 115, 97, 42);
		panel17.add(g3);
		g3.setColumns(10);

		g4 = new JTextField();
		g4.setBounds(926, 115, 66, 42);
		panel17.add(g4);
		g4.setColumns(10);

		g5 = new JTextField();
		g5.setBounds(1004, 115, 54, 42);
		panel17.add(g5);
		g5.setColumns(10);

		g6 = new JTextField();
		g6.setBounds(1070, 115, 74, 42);
		panel17.add(g6);
		g6.setColumns(10);

		g7 = new JTextField();
		g7.setBounds(1175, 115, 66, 42);
		panel17.add(g7);
		g7.setColumns(10);

		g8 = new JTextField();
		g8.setBounds(1253, 115, 73, 42);
		panel17.add(g8);
		g8.setColumns(10);

		g9 = new JTextField();
		g9.setColumns(10);
		g9.setBounds(1338, 115, 74, 42);
		panel17.add(g9);

		h1 = new JTextField();
		h1.setBounds(621, 286, 86, 42);
		panel17.add(h1);
		h1.setColumns(10);

		h2 = new JTextField();
		h2.setBounds(719, 286, 97, 42);
		panel17.add(h2);
		h2.setColumns(10);

		h3 = new JTextField();
		h3.setBounds(828, 286, 54, 42);
		panel17.add(h3);
		h3.setColumns(10);

		h4 = new JTextField();
		h4.setBounds(894, 286, 74, 42);
		panel17.add(h4);
		h4.setColumns(10);

		h5 = new JTextField();
		h5.setBounds(991, 286, 86, 42);
		panel17.add(h5);
		h5.setColumns(10);

		h6 = new JTextField();
		h6.setBounds(1089, 286, 74, 42);
		panel17.add(h6);
		h6.setColumns(10);

		h7 = new JTextField();
		h7.setBounds(1175, 286, 74, 42);
		panel17.add(h7);
		h7.setColumns(10);

		h8 = new JTextField();
		h8.setColumns(10);
		h8.setBounds(608, 431, 54, 42);
		panel17.add(h8);

		h9 = new JTextField();
		h9.setColumns(10);
		h9.setBounds(674, 431, 66, 42);
		panel17.add(h9);

		h10 = new JTextField();
		h10.setColumns(10);
		h10.setBounds(752, 431, 60, 42);
		panel17.add(h10);

		h11 = new JTextField();
		h11.setColumns(10);
		h11.setBounds(817, 431, 45, 42);
		panel17.add(h11);

		h12 = new JTextField();
		h12.setColumns(10);
		h12.setBounds(874, 431, 45, 42);
		panel17.add(h12);

		h13 = new JTextField();
		h13.setColumns(10);
		h13.setBounds(926, 431, 60, 42);
		panel17.add(h13);

		h14 = new JTextField();
		h14.setColumns(10);
		h14.setBounds(991, 431, 45, 42);
		panel17.add(h14);

		h15 = new JTextField();
		h15.setColumns(10);
		h15.setBounds(1048, 431, 52, 42);
		panel17.add(h15);

		h16 = new JTextField();
		h16.setColumns(10);
		h16.setBounds(1112, 431, 45, 42);
		panel17.add(h16);

		textField_29 = new JTextField();
		textField_29.setColumns(10);
		textField_29.setBounds(1175, 431, 37, 42);
		panel17.add(textField_29);

		textField_26 = new JTextField();
		textField_26.setColumns(10);
		textField_26.setBounds(1224, 431, 45, 42);
		panel17.add(textField_26);

		textField_27 = new JTextField();
		textField_27.setColumns(10);
		textField_27.setBounds(1284, 431, 86, 42);
		panel17.add(textField_27);

		h17 = new JTextField();
		h17.setColumns(10);
		h17.setBounds(603, 593, 85, 42);
		panel17.add(h17);

		h18 = new JTextField();
		h18.setColumns(10);
		h18.setBounds(705, 593, 85, 42);
		panel17.add(h18);

		h19 = new JTextField();
		h19.setColumns(10);
		h19.setBounds(810, 593, 85, 42);
		panel17.add(h19);

		h20 = new JTextField();
		h20.setColumns(10);
		h20.setBounds(917, 593, 85, 42);
		panel17.add(h20);

		h21 = new JTextField();
		h21.setColumns(10);
		h21.setBounds(1015, 593, 85, 42);
		panel17.add(h21);

		h22 = new JTextField();
		h22.setColumns(10);
		h22.setBounds(603, 721, 85, 42);
		panel17.add(h22);

		h23 = new JTextField();
		h23.setColumns(10);
		h23.setBounds(705, 721, 85, 42);
		panel17.add(h23);

		h24 = new JTextField();
		h24.setColumns(10);
		h24.setBounds(810, 725, 85, 42);
		panel17.add(h24);

		h25 = new JTextField();
		h25.setColumns(10);
		h25.setBounds(917, 725, 74, 42);
		panel17.add(h25);

		h26 = new JTextField();
		h26.setColumns(10);
		h26.setBounds(996, 721, 62, 42);
		panel17.add(h26);

		h27 = new JTextField();
		h27.setColumns(10);
		h27.setBounds(1070, 721, 85, 42);
		panel17.add(h27);

		h28 = new JTextField();
		h28.setColumns(10);
		h28.setBounds(1164, 721, 66, 42);
		panel17.add(h28);

		textField_30 = new JTextField();
		textField_30.setColumns(10);
		textField_30.setBounds(1239, 721, 74, 42);
		panel17.add(textField_30);

		textField_28 = new JTextField();
		textField_28.setColumns(10);
		textField_28.setBounds(1325, 721, 45, 42);
		panel17.add(textField_28);

		h29 = new JTextField();
		h29.setColumns(10);
		h29.setBounds(603, 864, 85, 42);
		panel17.add(h29);

		h30 = new JTextField();
		h30.setColumns(10);
		h30.setBounds(705, 864, 85, 42);
		panel17.add(h30);

		h31 = new JTextField();
		h31.setColumns(10);
		h31.setBounds(810, 864, 54, 42);
		panel17.add(h31);

		h32 = new JTextField();
		h32.setColumns(10);
		h32.setBounds(876, 864, 74, 42);
		panel17.add(h32);

		h33 = new JTextField();
		h33.setColumns(10);
		h33.setBounds(969, 864, 85, 42);
		panel17.add(h33);

		h34 = new JTextField();
		h34.setColumns(10);
		h34.setBounds(1067, 864, 74, 42);
		panel17.add(h34);

		h35 = new JTextField();
		h35.setColumns(10);
		h35.setBounds(1164, 864, 66, 42);
		panel17.add(h35);

		JLabel lblNewLabel_088 = new JLabel("lmbai");
		lblNewLabel_088.setOpaque(true);
		lblNewLabel_088.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 30));
		lblNewLabel_088.setBounds(621, 212, 86, 42);
		panel17.add(lblNewLabel_088);

		JLabel lblNewLabel_9 = new JLabel("kemer");
		lblNewLabel_9.setOpaque(true);
		lblNewLabel_9.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 30));
		lblNewLabel_9.setBounds(719, 212, 97, 42);
		panel17.add(lblNewLabel_9);

		JLabel lblNewLabel_10 = new JLabel("hip");
		lblNewLabel_10.setOpaque(true);
		lblNewLabel_10.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 30));
		lblNewLabel_10.setBounds(828, 212, 54, 42);
		panel17.add(lblNewLabel_10);

		JLabel lblNewLabel_11 = new JLabel("pinjni");
		lblNewLabel_11.setOpaque(true);
		lblNewLabel_11.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 30));
		lblNewLabel_11.setBounds(991, 212, 86, 42);
		panel17.add(lblNewLabel_11);

		JLabel lblNewLabel_12 = new JLabel("gidri");
		lblNewLabel_12.setOpaque(true);
		lblNewLabel_12.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 30));
		lblNewLabel_12.setBounds(894, 212, 74, 42);
		panel17.add(lblNewLabel_12);

		JLabel lblNewLabel_13 = new JLabel("mori");
		lblNewLabel_13.setOpaque(true);
		lblNewLabel_13.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 30));
		lblNewLabel_13.setBounds(1089, 212, 74, 42);
		panel17.add(lblNewLabel_13);

		JLabel lblNewLabel_14 = new JLabel("putt");
		lblNewLabel_14.setOpaque(true);
		lblNewLabel_14.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 30));
		lblNewLabel_14.setBounds(1175, 212, 74, 42);
		panel17.add(lblNewLabel_14);

		lblStartingDate = new JLabel("Starting date");
		lblStartingDate.setOpaque(true);
		lblStartingDate.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 30));
		lblStartingDate.setBounds(334, 162, 188, 56);
		panel17.add(lblStartingDate);

		lblEndingDate = new JLabel("Ending date");
		lblEndingDate.setOpaque(true);
		lblEndingDate.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 30));
		lblEndingDate.setBounds(334, 330, 170, 56);
		panel17.add(lblEndingDate);

		txf = new JTextField();
		txf.setBounds(390, 98, 54, 39);
		panel17.add(txf);
		txf.setColumns(10);

		try {

			String query = "Select * from Customer";
			PreparedStatement pst = conn.prepareStatement(query);
			ResultSet rs = pst.executeQuery();
			while (rs.next()) {
				id1 = rs.getInt("Customerid");

			}
			sid = String.valueOf((id1 + 1));

			pst.close();
			rs.close();

		} catch (Exception e) {
			JOptionPane.showMessageDialog(null, "In line 3828" + e);
		}
		txf.setText(sid);

		JLabel lblId = new JLabel("id");
		lblId.setOpaque(true);
		lblId.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 30));
		lblId.setBounds(390, 46, 54, 39);
		panel17.add(lblId);

		JLabel lblProduct = new JLabel("lmbai");
		lblProduct.setOpaque(true);
		lblProduct.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 30));
		lblProduct.setBounds(621, 44, 86, 42);
		panel17.add(lblProduct);

		textField_12 = new JTextField();
		textField_12.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 27));
		textField_12.setBounds(358, 577, 129, 66);
		panel17.add(textField_12);
		textField_12.setColumns(10);

		JLabel lblPrice = new JLabel("Total");
		lblPrice.setOpaque(true);
		lblPrice.setFont(new Font("Tahoma", Font.BOLD | Font.ITALIC, 27));
		lblPrice.setBounds(370, 498, 86, 66);
		panel17.add(lblPrice);

		JLabel labell = new JLabel("lmbai");
		labell.setOpaque(true);
		labell.setForeground(Color.BLACK);
		labell.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		labell.setBounds(608, 376, 60, 42);
		panel17.add(labell);

		JLabel labell_1 = new JLabel("seena");
		labell_1.setOpaque(true);
		labell_1.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		labell_1.setBounds(674, 376, 56, 42);
		panel17.add(labell_1);

		JLabel label_21 = new JLabel("kemer");
		label_21.setOpaque(true);
		label_21.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		label_21.setAutoscrolls(true);
		label_21.setBounds(742, 376, 66, 42);
		panel17.add(label_21);

		JLabel lblPait = new JLabel("pait");
		lblPait.setOpaque(true);
		lblPait.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		lblPait.setBounds(817, 376, 45, 42);
		panel17.add(lblPait);

		JLabel lblHip_2 = new JLabel("hip");
		lblHip_2.setOpaque(true);
		lblHip_2.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		lblHip_2.setBounds(876, 376, 45, 42);
		panel17.add(lblHip_2);

		JLabel lblTeera_1 = new JLabel("teera");
		lblTeera_1.setOpaque(true);
		lblTeera_1.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		lblTeera_1.setBounds(926, 376, 60, 42);
		panel17.add(lblTeera_1);

		JLabel lblBaju_5 = new JLabel("baju");
		lblBaju_5.setOpaque(true);
		lblBaju_5.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		lblBaju_5.setBounds(991, 376, 45, 42);
		panel17.add(lblBaju_5);

		JLabel lblDor_1 = new JLabel("dor");
		lblDor_1.setOpaque(true);
		lblDor_1.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		lblDor_1.setBounds(1048, 376, 45, 42);
		panel17.add(lblDor_1);

		JLabel lblBack_1 = new JLabel("back");
		lblBack_1.setOpaque(true);
		lblBack_1.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		lblBack_1.setBounds(1107, 376, 54, 42);
		panel17.add(lblBack_1);

		JLabel label_30 = new JLabel("b.s");
		label_30.setOpaque(true);
		label_30.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		label_30.setBounds(1175, 376, 37, 42);
		panel17.add(label_30);

		JLabel label_31 = new JLabel("lmbai");
		label_31.setOpaque(true);
		label_31.setForeground(Color.BLACK);
		label_31.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		label_31.setBounds(603, 534, 90, 42);
		panel17.add(label_31);

		JLabel lblTeera_2 = new JLabel("teera");
		lblTeera_2.setOpaque(true);
		lblTeera_2.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		lblTeera_2.setBounds(1014, 538, 90, 42);
		panel17.add(lblTeera_2);

		JLabel label_45 = new JLabel("hip");
		label_45.setOpaque(true);
		label_45.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		label_45.setBounds(912, 538, 90, 42);
		panel17.add(label_45);

		JLabel label_46 = new JLabel("kemer");
		label_46.setOpaque(true);
		label_46.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		label_46.setAutoscrolls(true);
		label_46.setBounds(810, 538, 90, 42);
		panel17.add(label_46);

		JLabel label_47 = new JLabel("seena");
		label_47.setOpaque(true);
		label_47.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		label_47.setBounds(705, 534, 90, 42);
		panel17.add(label_47);

		JCheckBox cb1 = new JCheckBox("SHIRT");
		cb1.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 17));
		cb1.setBounds(528, 44, 90, 113);
		panel17.add(cb1);

		JCheckBox cb2 = new JCheckBox("Pant");
		cb2.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 17));
		cb2.setBounds(528, 212, 90, 116);
		panel17.add(cb2);

		JCheckBox cb3 = new JCheckBox("COAT");
		cb3.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 17));
		cb3.setBounds(512, 376, 90, 97);
		panel17.add(cb3);

		JCheckBox cb4 = new JCheckBox("JACKET");
		cb4.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 17));
		cb4.setBounds(495, 534, 96, 97);
		panel17.add(cb4);

		JCheckBox cb5 = new JCheckBox("KURTA");
		cb5.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 17));
		cb5.setBounds(501, 666, 90, 97);
		panel17.add(cb5);

		JCheckBox cb6 = new JCheckBox("PJAMA");
		cb6.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 17));
		cb6.setBounds(501, 809, 90, 97);
		panel17.add(cb6);

		try {
			String query = "Select * from Customer";
			PreparedStatement pst1 = conn.prepareStatement(query);
			ResultSet rs1 = pst1.executeQuery();

			while (rs1.next()) {
				q25 = rs1.getString("Customerid");
				q26 = rs1.getString("CustomerName");
				q27 = rs1.getString("CustomerContact");
				q28 = rs1.getString("CustomerAddress");

			}
			rs1.close();
			pst1.close();
		} catch (Exception e) {
			e.printStackTrace();
		}

		ImageIcon gifImage3aa = new ImageIcon(this.getClass().getResource("/save.jpg"));
		JButton save_023_1 = new JButton(gifImage3aa);
		save_023_1.addKeyListener(new KeyAdapter() {
			@Override
			public void keyPressed(KeyEvent e) {

				SimpleDateFormat sdf = new SimpleDateFormat("yyyy-MM-dd");
				x3 = sdf.format(chooser.getDate());
				x4 = sdf.format(chooser1.getDate());

				String rzz = textField_12.getText();

				SimpleDateFormat sdf2 = new SimpleDateFormat("yyyy-MM-dd");
				za4 = sdf2.format(chooser1.getDate());

				SimpleDateFormat sdf3 = new SimpleDateFormat("yyyy-MM-dd");
				za5 = sdf3.format(chooser.getDate());

				try {
					if (cb1.isSelected()) {
						o1 = "Shirt";

						try {

							conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
							String query = "Update " + o1
									+ " set lmbai = ?,seena = ?,kemer = ?,pait = ?,hip = ?,teera = ?,glaa = ?,baju = ?,bs = ?,Customerid = ?,CustomerName = ?,CustomerContact = ?,CustomerAddress = ?,price = ?,advance_payments = ?,pending_payments = ?,Starting_date = ?,Ending_date = ?,price1 = ?,quantity = ?,extra = ? where Customerid = '"
									+ q25 + "' AND CustomerName ='" + q26 + "' AND CustomerContact = '" + q27
									+ "' AND CustomerAddress = '" + q28 + "' ";

							PreparedStatement statment = conn.prepareStatement(query);
							statment.setString(1, g1.getText());
							statment.setString(2, g2.getText());
							statment.setString(3, g3.getText());
							statment.setString(4, g4.getText());
							statment.setString(5, g5.getText());
							statment.setString(6, g6.getText());
							statment.setString(7, g7.getText());
							statment.setString(8, g8.getText());
							statment.setString(9, g9.getText());
							statment.setString(10, q25);
							statment.setString(11, q26);
							statment.setString(12, q27);
							statment.setString(13, q28);
							statment.setDouble(14, Double.parseDouble(textField_12.getText()));
							statment.setDouble(15, q29);// advance
							statment.setDouble(16, q30);// panding
							statment.setString(17, za4);
							statment.setString(18, za5);
							statment.setString(19, textField_33.getText());
							statment.setString(20, textField_32.getText());
							statment.setString(21, textField_31.getText());

							statment.executeUpdate();
							statment.close();

						}

						catch (SQLException e1) {

							JOptionPane.showMessageDialog(null, " shirt" + e1);
						}
					}
				} catch (Exception e1) {
					e1.printStackTrace();
				}

				try {
					if (cb2.isSelected()) {
						o2 = "pent";

						try {

							conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
							String query = "Update " + o2
									+ " set lmbai =?,kemer =?,hip =?,gidri =?,pinjni =?,mori =?,putt =?,Customerid =?,CustomerName =?,CustomerContact =?,CustomerAddress =?,price =?,advance_payments =?,pending_payments =?,Starting_date =?,Ending_date =?,price1 = ?,quantity = ?,extra = ? where Customerid = '"
									+ q25 + "' AND CustomerName ='" + q26 + "' AND CustomerContact = '" + q27
									+ "' AND CustomerAddress = '" + q28 + "' ";

							PreparedStatement statment = conn.prepareStatement(query);
							statment.setString(1, h1.getText());
							statment.setString(2, h2.getText());
							statment.setString(3, h3.getText());
							statment.setString(4, h4.getText());
							statment.setString(5, h5.getText());
							statment.setString(6, h6.getText());
							statment.setString(7, h7.getText());
							statment.setString(8, q25);
							statment.setString(9, q26);
							statment.setString(10, q27);
							statment.setString(11, q28);
							statment.setString(12, textField_12.getText());
							statment.setDouble(13, q29);
							statment.setDouble(14, q30);
							statment.setString(15, za4);
							statment.setString(16, za5);
							statment.setString(17, textField_34.getText());
							statment.setString(18, textField_35.getText());
							statment.setString(19, textField_36.getText());

							statment.executeUpdate();
							statment.close();
						}

						catch (SQLException e1) {
							JOptionPane.showMessageDialog(null, "pent :" + e1);
						}
					}
				} catch (Exception e2) {
					e2.printStackTrace();
				}

				try {
					if (cb3.isSelected()) {
						o3 = "Coat";

						try {

							conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
							String query = "Update " + o3
									+ " set lmbai =?,seena =?,kemer =?,pait =?,hip =?,teera =?,baju =?,dor =?,back =?,bs =?,bm =?,shoulder =?,Customerid =?,CustomerName =?,CustomerContact =?,CustomerAddress =?,price =?,advance_payments =?,pending_payments =?,Starting_date =?,Ending_date =?,price1 = ?,quantity = ?,extra = ? where Customerid = '"
									+ q25 + "' AND CustomerName ='" + q26 + "' AND CustomerContact = '" + q27
									+ "' AND CustomerAddress = '" + q28 + "' ";

							PreparedStatement statment = conn.prepareStatement(query);
							statment.setString(1, h8.getText());
							statment.setString(2, h9.getText());
							statment.setString(3, h10.getText());
							statment.setString(4, h11.getText());
							statment.setString(5, h12.getText());
							statment.setString(6, h13.getText());
							statment.setString(7, h14.getText());
							statment.setString(8, h15.getText());
							statment.setString(9, h16.getText());
							statment.setString(10, textField_29.getText());
							statment.setString(11, textField_26.getText());
							statment.setString(12, textField_27.getText());
							statment.setString(13, q25);
							statment.setString(14, q26);
							statment.setString(15, q27);
							statment.setString(16, q28);
							statment.setString(17, textField_12.getText());
							statment.setDouble(18, q29);
							statment.setDouble(19, q30);
							statment.setString(20, za4);
							statment.setString(21, za5);
							statment.setString(22, textField_37.getText());
							statment.setString(23, textField_38.getText());
							statment.setString(24, textField_39.getText());

							statment.executeUpdate();
							statment.close();

						}

						catch (SQLException e1) {

							JOptionPane.showMessageDialog(null, "coat" + e1);
						}
					}
				} catch (Exception e3) {
					e3.printStackTrace();
				}

				try {
					if (cb4.isSelected()) {
						o4 = "Jacket";

						try {

							conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
							String query = "Update " + o4
									+ " set lmbai =?,seena =?,kemer =?,hip =?,teera =?,Customerid =?,CustomerName =?,CustomerContact =?,CustomerAddress =?,price =?,advance_payments =?,pending_payments =?,Starting_date =?,Ending_date =?,price1 = ?,quantity = ?,extra = ?  where Customerid = '"
									+ q25 + "' AND CustomerName ='" + q26 + "' AND CustomerContact = '" + q27
									+ "' AND CustomerAddress = '" + q28 + "' ";

							PreparedStatement statment = conn.prepareStatement(query);
							statment.setString(1, h17.getText());
							statment.setString(2, h18.getText());
							statment.setString(3, h19.getText());
							statment.setString(4, h20.getText());
							statment.setString(5, h21.getText());
							statment.setString(6, q25);
							statment.setString(7, q26);
							statment.setString(8, q27);
							statment.setString(9, q28);
							statment.setString(10, textField_12.getText());
							statment.setDouble(11, q29);
							statment.setDouble(12, q30);
							statment.setString(13, za4);
							statment.setString(14, za5);
							statment.setString(15, textField_46.getText());
							statment.setString(16, textField_47.getText());
							statment.setString(17, textField_48.getText());

							statment.executeUpdate();
							statment.close();
						}

						catch (SQLException e1) {
							JOptionPane.showMessageDialog(null, "jacket" + e1);
						}

					} else {

					}
				} catch (Exception e4) {
					e4.printStackTrace();
				}

				try {
					if (cb5.isSelected()) {
						o5 = "Kurta";

						try {

							conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
							String query = "Update " + o5
									+ " set lmbai = ?,seena = ?,kemer = ?,pait = ?,hip = ?,teera = ?,glaa = ?,baju = ?,bs = ?,Customerid = ?,CustomerName = ?,CustomerContact = ?,CustomerAddress = ?,price = ?,advance_payments = ?,pending_payments = ?,Starting_date = ?,Ending_date = ?,price1 = ?,quantity = ?,extra = ? where Customerid = '"
									+ q25 + "' AND CustomerName ='" + q26 + "' AND CustomerContact = '" + q27
									+ "' AND CustomerAddress = '" + q28 + "' ";

							PreparedStatement statment = conn.prepareStatement(query);
							statment.setString(1, h22.getText());
							statment.setString(2, h23.getText());
							statment.setString(3, h24.getText());
							statment.setString(4, h25.getText());
							statment.setString(5, h26.getText());
							statment.setString(6, h27.getText());
							statment.setString(7, h28.getText());
							statment.setString(8, textField_30.getText());
							statment.setString(9, textField_28.getText());
							statment.setString(10, q25);
							statment.setString(11, q26);
							statment.setString(12, q27);
							statment.setString(13, q28);
							statment.setString(14, textField_12.getText());
							statment.setDouble(15, q29);
							statment.setDouble(16, q30);
							statment.setString(17, za4);
							statment.setString(18, za5);
							statment.setString(19, textField_40.getText());
							statment.setString(20, textField_41.getText());
							statment.setString(21, textField_42.getText());

							statment.executeUpdate();
							statment.close();
						}

						catch (SQLException e1) {

							e1.printStackTrace();
						}

					}
				} catch (Exception e5) {
					e5.printStackTrace();
				}

				try {
					if (cb6.isSelected()) {
						o6 = "Pjama";

						try {

							conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
							String query = "Update " + o6
									+ " set lmbai =?,kemer =?,hip =?,gidri =?,pinjni =?,mori =?,putt =?,Customerid =?,CustomerName =?,CustomerContact =?,CustomerAddress =?,price =?,advance_payments =?,pending_payments =?,Starting_date =?,Ending_date =?,price1 = ?,quantity = ?,extra = ? where Customerid = '"
									+ q25 + "' AND CustomerName ='" + q26 + "' AND CustomerContact = '" + q27
									+ "' AND CustomerAddress = '" + q28 + "' ";

							PreparedStatement statment = conn.prepareStatement(query);
							statment.setString(1, h29.getText());
							statment.setString(2, h30.getText());
							statment.setString(3, h31.getText());
							statment.setString(4, h32.getText());
							statment.setString(5, h33.getText());
							statment.setString(6, h34.getText());
							statment.setString(7, h35.getText());
							statment.setString(8, q25);
							statment.setString(9, q26);
							statment.setString(10, q27);
							statment.setString(11, q28);
							statment.setString(12, textField_12.getText());
							statment.setDouble(13, q29);
							statment.setDouble(14, q30);
							statment.setString(15, za4);
							statment.setString(16, za5);
							statment.setString(17, textField_45.getText());
							statment.setString(18, textField_44.getText());
							statment.setString(19, textField_43.getText());

							statment.executeUpdate();
							statment.close();
						}

						catch (SQLException e1) {
							JOptionPane.showMessageDialog(null, "Pjama");
						}

					}
				} catch (Exception e6) {
					e6.printStackTrace();
				}

				try {

					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
					String query = "select * from Shirt ";
					PreparedStatement statment = conn.prepareStatement(query);
					ResultSet rs = statment.executeQuery();
					table_5.setModel(DbUtils.resultSetToTableModel(rs));

					rs.close();
					statment.close();
				} catch (SQLException e1) {

					JOptionPane.showMessageDialog(null, "My Error 2" + e1);
				}

				try {

					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
					String query = "select * from pent ";
					PreparedStatement statment = conn.prepareStatement(query);
					ResultSet rs = statment.executeQuery();
					table_21.setModel(DbUtils.resultSetToTableModel(rs));

					rs.close();
					statment.close();
				} catch (SQLException e1) {

					JOptionPane.showMessageDialog(null, "My Error 2" + e1);
				}

				try {

					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
					String query = "select * from Coat ";
					PreparedStatement statment = conn.prepareStatement(query);
					ResultSet rs = statment.executeQuery();
					table_11.setModel(DbUtils.resultSetToTableModel(rs));

					rs.close();
					statment.close();
				} catch (SQLException e1) {

					JOptionPane.showMessageDialog(null, "My Error 2" + e1);
				}

				try {

					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
					String query = "select * from Jacket ";
					PreparedStatement statment = conn.prepareStatement(query);
					ResultSet rs = statment.executeQuery();
					table_22.setModel(DbUtils.resultSetToTableModel(rs));

					rs.close();
					statment.close();
				} catch (SQLException e1) {

					JOptionPane.showMessageDialog(null, "My Error 2" + e1);
				}

				try {

					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
					String query = "select * from Kurta ";
					PreparedStatement statment = conn.prepareStatement(query);
					ResultSet rs = statment.executeQuery();
					table_12.setModel(DbUtils.resultSetToTableModel(rs));

					rs.close();
					statment.close();
				} catch (SQLException e1) {

					JOptionPane.showMessageDialog(null, "My Error 2" + e1);
				}

				try {

					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
					String query = "select * from Pjama ";
					PreparedStatement statment = conn.prepareStatement(query);
					ResultSet rs = statment.executeQuery();
					table_23.setModel(DbUtils.resultSetToTableModel(rs));

					rs.close();
					statment.close();
				} catch (SQLException e1) {

					JOptionPane.showMessageDialog(null, "My Error 2" + e1);
				}

				f1.dispose();
				Trailor.main(null);
			}

		});

		save_023_1.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent arg0) {

				SimpleDateFormat sdf = new SimpleDateFormat("yyyy-MM-dd");
				x3 = sdf.format(chooser.getDate());
				x4 = sdf.format(chooser1.getDate());

				String rzz = textField_12.getText();

				SimpleDateFormat sdf2 = new SimpleDateFormat("yyyy-MM-dd");
				za4 = sdf2.format(chooser1.getDate());

				SimpleDateFormat sdf3 = new SimpleDateFormat("yyyy-MM-dd");
				za5 = sdf3.format(chooser.getDate());

				try {
					if (cb1.isSelected()) {
						o1 = "Shirt";

						try {

							conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
							String query = "Update " + o1
									+ " set lmbai = ?,seena = ?,kemer = ?,pait = ?,hip = ?,teera = ?,glaa = ?,baju = ?,bs = ?,Customerid = ?,CustomerName = ?,CustomerContact = ?,CustomerAddress = ?,price = ?,advance_payments = ?,pending_payments = ?,Starting_date = ?,Ending_date = ?,price1 = ?,quantity = ?,extra = ? where Customerid = '"
									+ id2 + "' AND CustomerName ='" + name1 + "' AND CustomerContact = '" + contact
									+ "' AND CustomerAddress = '" + address + "' ";

							PreparedStatement statment = conn.prepareStatement(query);
							statment.setString(1, g1.getText());
							statment.setString(2, g2.getText());
							statment.setString(3, g3.getText());
							statment.setString(4, g4.getText());
							statment.setString(5, g5.getText());
							statment.setString(6, g6.getText());
							statment.setString(7, g7.getText());
							statment.setString(8, g8.getText());
							statment.setString(9, g9.getText());
							statment.setString(10, id2);
							statment.setString(11, name1);
							statment.setString(12, contact);
							statment.setString(13, address);
							statment.setDouble(14, Double.parseDouble(textField_12.getText()));
							statment.setDouble(15, q29);// advance
							statment.setDouble(16, q30);// panding
							statment.setString(17, za4);
							statment.setString(18, za5);
							statment.setString(19, textField_33.getText());
							statment.setString(20, textField_32.getText());
							statment.setString(21, textField_31.getText());

							statment.executeUpdate();
							statment.close();

						}

						catch (SQLException e1) {

							JOptionPane.showMessageDialog(null, " shirt" + e1);
						}

					} else {
					}
				} catch (Exception e1) {
					e1.printStackTrace();
				}

				try {
					if (cb2.isSelected()) {
						o2 = "pent";

						try {

							conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
							String query = "Update " + o2
									+ " set lmbai =?,kemer =?,hip =?,gidri =?,pinjni =?,mori =?,putt =?,Customerid =?,CustomerName =?,CustomerContact =?,CustomerAddress =?,price =?,advance_payments =?,pending_payments =?,Starting_date =?,Ending_date =?,price1 = ?,quantity = ?,extra = ? where Customerid = '"
									+ id2 + "' AND CustomerName ='" + name1 + "' AND CustomerContact = '" + contact
									+ "' AND CustomerAddress = '" + address + "' ";

							PreparedStatement statment = conn.prepareStatement(query);
							statment.setString(1, h1.getText());
							statment.setString(2, h2.getText());
							statment.setString(3, h3.getText());
							statment.setString(4, h4.getText());
							statment.setString(5, h5.getText());
							statment.setString(6, h6.getText());
							statment.setString(7, h7.getText());
							statment.setString(8, id2);
							statment.setString(9, name1);
							statment.setString(10, contact);
							statment.setString(11, address);
							statment.setString(12, textField_12.getText());
							statment.setDouble(13, q29);
							statment.setDouble(14, q30);
							statment.setString(15, za4);
							statment.setString(16, za5);
							statment.setString(17, textField_34.getText());
							statment.setString(18, textField_35.getText());
							statment.setString(19, textField_36.getText());

							statment.executeUpdate();
							statment.close();
						}

						catch (SQLException e1) {
							JOptionPane.showMessageDialog(null, "pent :" + e1);
						}
					} else {
					}
				} catch (Exception e2) {
					e2.printStackTrace();
				}

				try {
					if (cb3.isSelected()) {
						o3 = "Coat";

						try {

							conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
							String query = "Update " + o3
									+ " set lmbai =?,seena =?,kemer =?,pait =?,hip =?,teera =?,baju =?,dor =?,back =?,bs =?,bm =?,shoulder =?,Customerid =?,CustomerName =?,CustomerContact =?,CustomerAddress =?,price =?,advance_payments =?,pending_payments =?,Starting_date =?,Ending_date =?,price1 = ?,quantity = ?,extra = ? where Customerid = '"
									+ id2 + "' AND CustomerName ='" + name1 + "' AND CustomerContact = '" + contact
									+ "' AND CustomerAddress = '" + address + "' ";

							PreparedStatement statment = conn.prepareStatement(query);
							statment.setString(1, h8.getText());
							statment.setString(2, h9.getText());
							statment.setString(3, h10.getText());
							statment.setString(4, h11.getText());
							statment.setString(5, h12.getText());
							statment.setString(6, h13.getText());
							statment.setString(7, h14.getText());
							statment.setString(8, h15.getText());
							statment.setString(9, h16.getText());
							statment.setString(10, textField_29.getText());
							statment.setString(11, textField_26.getText());
							statment.setString(12, textField_27.getText());
							statment.setString(13, id2);
							statment.setString(14, name1);
							statment.setString(15, contact);
							statment.setString(16, address);
							statment.setString(17, textField_12.getText());
							statment.setDouble(18, q29);
							statment.setDouble(19, q30);
							statment.setString(20, za4);
							statment.setString(21, za5);
							statment.setString(22, textField_37.getText());
							statment.setString(23, textField_38.getText());
							statment.setString(24, textField_39.getText());

							statment.executeUpdate();
							statment.close();

						}

						catch (SQLException e1) {

							JOptionPane.showMessageDialog(null, "coat" + e1);
						}
					} else {
					}
				} catch (Exception e3) {
					e3.printStackTrace();
				}

				try {
					if (cb4.isSelected()) {
						o4 = "Jacket";

						try {

							conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
							String query = "Update " + o4
									+ " set lmbai =?,seena =?,kemer =?,hip =?,teera =?,Customerid =?,CustomerName =?,CustomerContact =?,CustomerAddress =?,price =?,advance_payments =?,pending_payments =?,Starting_date =?,Ending_date =?,price1 = ?,quantity = ?,extra = ?  where Customerid = '"
									+ id2 + "' AND CustomerName ='" + name1 + "' AND CustomerContact = '" + contact
									+ "' AND CustomerAddress = '" + address + "' ";

							PreparedStatement statment = conn.prepareStatement(query);
							statment.setString(1, h17.getText());
							statment.setString(2, h18.getText());
							statment.setString(3, h19.getText());
							statment.setString(4, h20.getText());
							statment.setString(5, h21.getText());
							statment.setString(6, id2);
							statment.setString(7, name1);
							statment.setString(8, contact);
							statment.setString(9, address);
							statment.setString(10, textField_12.getText());
							statment.setDouble(11, q29);
							statment.setDouble(12, q30);
							statment.setString(13, za4);
							statment.setString(14, za5);
							statment.setString(15, textField_46.getText());
							statment.setString(16, textField_47.getText());
							statment.setString(17, textField_48.getText());

							statment.executeUpdate();
							statment.close();
						}

						catch (SQLException e1) {
							JOptionPane.showMessageDialog(null, "jacket" + e1);
						}

					} else {
					}
				} catch (Exception e4) {
					e4.printStackTrace();
				}

				try {
					if (cb5.isSelected()) {
						o5 = "Kurta";

						try {

							conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
							String query = "Update " + o5
									+ " set lmbai = ?,seena = ?,kemer = ?,pait = ?,hip = ?,teera = ?,glaa = ?,baju = ?,bs = ?,Customerid = ?,CustomerName = ?,CustomerContact = ?,CustomerAddress = ?,price = ?,advance_payments = ?,pending_payments = ?,Starting_date = ?,Ending_date = ?,price1 = ?,quantity = ?,extra = ? where Customerid = '"
									+ id2 + "' AND CustomerName ='" + name1 + "' AND CustomerContact = '" + contact
									+ "' AND CustomerAddress = '" + address + "' ";

							PreparedStatement statment = conn.prepareStatement(query);
							statment.setString(1, h22.getText());
							statment.setString(2, h23.getText());
							statment.setString(3, h24.getText());
							statment.setString(4, h25.getText());
							statment.setString(5, h26.getText());
							statment.setString(6, h27.getText());
							statment.setString(7, h28.getText());
							statment.setString(8, textField_30.getText());
							statment.setString(9, textField_28.getText());
							statment.setString(10, id2);
							statment.setString(11, name1);
							statment.setString(12, contact);
							statment.setString(13, address);
							statment.setString(14, textField_12.getText());
							statment.setDouble(15, q29);
							statment.setDouble(16, q30);
							statment.setString(17, za4);
							statment.setString(18, za5);
							statment.setString(19, textField_40.getText());
							statment.setString(20, textField_41.getText());
							statment.setString(21, textField_42.getText());

							statment.executeUpdate();
							statment.close();
						}

						catch (SQLException e1) {

							e1.printStackTrace();
						}

					} else {
					}
				} catch (Exception e5) {
					e5.printStackTrace();
				}

				try {
					if (cb6.isSelected()) {
						o6 = "Pjama";

						try {

							conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
							String query = "Update " + o6
									+ " set lmbai =?,kemer =?,hip =?,gidri =?,pinjni =?,mori =?,putt =?,Customerid =?,CustomerName =?,CustomerContact =?,CustomerAddress =?,price =?,advance_payments =?,pending_payments =?,Starting_date =?,Ending_date =?,price1 = ?,quantity = ?,extra = ? where Customerid = '"
									+ id2 + "' AND CustomerName ='" + name1 + "' AND CustomerContact = '" + contact
									+ "' AND CustomerAddress = '" + address + "' ";

							PreparedStatement statment = conn.prepareStatement(query);
							statment.setString(1, h29.getText());
							statment.setString(2, h30.getText());
							statment.setString(3, h31.getText());
							statment.setString(4, h32.getText());
							statment.setString(5, h33.getText());
							statment.setString(6, h34.getText());
							statment.setString(7, h35.getText());
							statment.setString(8, id2);
							statment.setString(9, name1);
							statment.setString(10, contact);
							statment.setString(11, address);
							statment.setString(12, textField_12.getText());
							statment.setDouble(13, q29);
							statment.setDouble(14, q30);
							statment.setString(15, za4);
							statment.setString(16, za5);
							statment.setString(17, textField_45.getText());
							statment.setString(18, textField_44.getText());
							statment.setString(19, textField_43.getText());

							statment.executeUpdate();
							statment.close();
						}

						catch (SQLException e1) {
							JOptionPane.showMessageDialog(null, "Pjama");
						}

					} else {
					}
				} catch (Exception e6) {
					e6.printStackTrace();
				}

				try {

					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
					String query = "select * from Shirt ";
					PreparedStatement statment = conn.prepareStatement(query);
					ResultSet rs = statment.executeQuery();
					table_34.setModel(DbUtils.resultSetToTableModel(rs));

					rs.close();
					statment.close();
				} catch (SQLException e) {

					JOptionPane.showMessageDialog(null, "My Error 2" + e);
				}

				try {

					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
					String query = "select * from pent ";
					PreparedStatement statment = conn.prepareStatement(query);
					ResultSet rs = statment.executeQuery();
					table_39.setModel(DbUtils.resultSetToTableModel(rs));

					rs.close();
					statment.close();
				} catch (SQLException e) {

					JOptionPane.showMessageDialog(null, "My Error 2" + e);
				}

				try {

					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
					String query = "select * from Coat ";
					PreparedStatement statment = conn.prepareStatement(query);
					ResultSet rs = statment.executeQuery();
					table_38.setModel(DbUtils.resultSetToTableModel(rs));

					rs.close();
					statment.close();
				} catch (SQLException e) {

					JOptionPane.showMessageDialog(null, "My Error 2" + e);
				}

				try {

					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
					String query = "select * from Jacket ";
					PreparedStatement statment = conn.prepareStatement(query);
					ResultSet rs = statment.executeQuery();
					table_36.setModel(DbUtils.resultSetToTableModel(rs));

					rs.close();
					statment.close();
				} catch (SQLException e) {

					JOptionPane.showMessageDialog(null, "My Error 2" + e);
				}

				try {

					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
					String query = "select * from Kurta ";
					PreparedStatement statment = conn.prepareStatement(query);
					ResultSet rs = statment.executeQuery();
					table_35.setModel(DbUtils.resultSetToTableModel(rs));

					rs.close();
					statment.close();
				} catch (SQLException e) {

					JOptionPane.showMessageDialog(null, "My Error 2" + e);
				}

				try {

					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
					String query = "select * from Pjama ";
					PreparedStatement statment = conn.prepareStatement(query);
					ResultSet rs = statment.executeQuery();
					table_37.setModel(DbUtils.resultSetToTableModel(rs));
					rs.close();
					statment.close();
				} catch (SQLException e) {

					JOptionPane.showMessageDialog(null, "My Error 2" + e);
				}

				JOptionPane.showMessageDialog(null, "Data saved");

			}
		});

		save_023_1.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 60));
		save_023_1.setBounds(83, 786, 179, 65);
		panel17.add(save_023_1);

		JLabel lblBs_4 = new JLabel("bs");
		lblBs_4.setOpaque(true);
		lblBs_4.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 30));
		lblBs_4.setBounds(1338, 44, 74, 42);
		panel17.add(lblBs_4);

		JLabel lblShoulder = new JLabel("shoulder");
		lblShoulder.setOpaque(true);
		lblShoulder.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		lblShoulder.setBounds(1290, 376, 86, 42);
		panel17.add(lblShoulder);

		JLabel lblBm_1 = new JLabel("b.m");
		lblBm_1.setOpaque(true);
		lblBm_1.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		lblBm_1.setBounds(1224, 376, 54, 42);
		panel17.add(lblBm_1);

		JLabel labeel = new JLabel("lmbai");
		labeel.setOpaque(true);
		labeel.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 30));
		labeel.setBounds(603, 666, 85, 42);
		panel17.add(labeel);

		JLabel labeel_1 = new JLabel("seena");
		labeel_1.setOpaque(true);
		labeel_1.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 30));
		labeel_1.setBounds(705, 666, 86, 42);
		panel17.add(labeel_1);

		JLabel label_22 = new JLabel("kemer");
		label_22.setOpaque(true);
		label_22.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 30));
		label_22.setBounds(810, 666, 97, 42);
		panel17.add(label_22);

		JLabel label_23 = new JLabel("pait");
		label_23.setOpaque(true);
		label_23.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 30));
		label_23.setBounds(917, 670, 79, 42);
		panel17.add(label_23);

		JLabel label_24 = new JLabel("hip");
		label_24.setOpaque(true);
		label_24.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 30));
		label_24.setBounds(1004, 670, 54, 42);
		panel17.add(label_24);

		JLabel label_26 = new JLabel("teera");
		label_26.setOpaque(true);
		label_26.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 30));
		label_26.setBounds(1070, 670, 74, 42);
		panel17.add(label_26);

		JLabel label_27 = new JLabel("glaa");
		label_27.setOpaque(true);
		label_27.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 30));
		label_27.setBounds(1153, 666, 66, 42);
		panel17.add(label_27);

		JLabel label_29 = new JLabel("baju");
		label_29.setOpaque(true);
		label_29.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 30));
		label_29.setBounds(1222, 670, 66, 42);
		panel17.add(label_29);

		JLabel label_32 = new JLabel("bs");
		label_32.setOpaque(true);
		label_32.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 30));
		label_32.setBounds(1300, 666, 66, 42);
		panel17.add(label_32);

		JLabel label_33 = new JLabel("lmbai");
		label_33.setOpaque(true);
		label_33.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 30));
		label_33.setBounds(599, 809, 86, 42);
		panel17.add(label_33);

		JLabel label_34 = new JLabel("kemer");
		label_34.setOpaque(true);
		label_34.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 30));
		label_34.setBounds(697, 809, 97, 42);
		panel17.add(label_34);

		JLabel label_35 = new JLabel("hip");
		label_35.setOpaque(true);
		label_35.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 30));
		label_35.setBounds(806, 809, 54, 42);
		panel17.add(label_35);

		JLabel label_39 = new JLabel("gidri");
		label_39.setOpaque(true);
		label_39.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 30));
		label_39.setBounds(872, 809, 74, 42);
		panel17.add(label_39);

		JLabel label_40 = new JLabel("pinjni");
		label_40.setOpaque(true);
		label_40.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 30));
		label_40.setBounds(969, 809, 86, 42);
		panel17.add(label_40);

		JLabel label_41 = new JLabel("mori");
		label_41.setOpaque(true);
		label_41.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 30));
		panel17.add(label_41);

		JLabel label_42 = new JLabel("putt");
		label_42.setOpaque(true);
		label_42.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 30));
		label_42.setBounds(1153, 809, 74, 42);
		panel17.add(label_42);

		JButton btnPrint = new JButton("Print");
		btnPrint.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent arg0) {

				cv1 = id2;
				cv2 = name1;
				cv3 = contact;
				cv4 = address;
				String h[] = { cv1, cv2, cv3, cv4 };
				Demo.main(h);

			}
		});
		btnPrint.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 60));
		btnPrint.setBounds(294, 787, 179, 65);
		panel17.add(btnPrint);

		JLabel lblPrice_1 = new JLabel("price");
		lblPrice_1.setOpaque(true);
		lblPrice_1.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 30));
		lblPrice_1.setBounds(1424, 46, 74, 42);
		panel17.add(lblPrice_1);

		JLabel lblQuantity = new JLabel("quantity");
		lblQuantity.setOpaque(true);
		lblQuantity.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 30));
		lblQuantity.setBounds(1510, 44, 120, 42);
		panel17.add(lblQuantity);

		JLabel lblExtra = new JLabel("extra");
		lblExtra.setOpaque(true);
		lblExtra.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 30));
		lblExtra.setBounds(1642, 46, 74, 42);
		panel17.add(lblExtra);

		textField_31 = new JTextField();
		textField_31.setColumns(10);
		textField_31.setBounds(1642, 115, 251, 42);
		panel17.add(textField_31);

		textField_32 = new JTextField();
		textField_32.setColumns(10);
		textField_32.setBounds(1510, 115, 120, 42);
		panel17.add(textField_32);

		textField_33 = new JTextField();
		textField_33.setColumns(10);
		textField_33.setBounds(1424, 115, 74, 42);
		panel17.add(textField_33);

		textField_34 = new JTextField();
		textField_34.setColumns(10);
		textField_34.setBounds(1260, 283, 74, 42);
		panel17.add(textField_34);

		textField_35 = new JTextField();
		textField_35.setColumns(10);
		textField_35.setBounds(1346, 283, 120, 42);
		panel17.add(textField_35);

		textField_36 = new JTextField();
		textField_36.setColumns(10);
		textField_36.setBounds(1478, 283, 415, 42);
		panel17.add(textField_36);

		JLabel label_1 = new JLabel("extra");
		label_1.setOpaque(true);
		label_1.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 30));
		label_1.setBounds(1478, 214, 74, 42);
		panel17.add(label_1);

		JLabel label_25 = new JLabel("quantity");
		label_25.setOpaque(true);
		label_25.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 30));
		label_25.setBounds(1346, 212, 120, 42);
		panel17.add(label_25);

		JLabel label_43 = new JLabel("price");
		label_43.setOpaque(true);
		label_43.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 30));
		label_43.setBounds(1260, 214, 74, 42);
		panel17.add(label_43);

		textField_37 = new JTextField();
		textField_37.setColumns(10);
		textField_37.setBounds(1382, 431, 74, 42);
		panel17.add(textField_37);

		textField_38 = new JTextField();
		textField_38.setColumns(10);
		textField_38.setBounds(1478, 431, 120, 42);
		panel17.add(textField_38);

		textField_39 = new JTextField();
		textField_39.setColumns(10);
		textField_39.setBounds(1610, 431, 283, 42);
		panel17.add(textField_39);

		JLabel label_48 = new JLabel("extra");
		label_48.setOpaque(true);
		label_48.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 30));
		label_48.setBounds(1610, 376, 74, 42);
		panel17.add(label_48);

		JLabel label_49 = new JLabel("quantity");
		label_49.setOpaque(true);
		label_49.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 30));
		label_49.setBounds(1478, 376, 120, 42);
		panel17.add(label_49);

		JLabel label_50 = new JLabel("price");
		label_50.setOpaque(true);
		label_50.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 30));
		label_50.setBounds(1388, 376, 74, 42);
		panel17.add(label_50);

		textField_40 = new JTextField();
		textField_40.setColumns(10);
		textField_40.setBounds(1382, 721, 74, 42);
		panel17.add(textField_40);

		textField_41 = new JTextField();
		textField_41.setColumns(10);
		textField_41.setBounds(1468, 721, 120, 42);
		panel17.add(textField_41);

		textField_42 = new JTextField();
		textField_42.setColumns(10);
		textField_42.setBounds(1594, 721, 299, 42);
		panel17.add(textField_42);

		JLabel label_51 = new JLabel("extra");
		label_51.setOpaque(true);
		label_51.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 30));
		label_51.setBounds(1594, 666, 74, 42);
		panel17.add(label_51);

		JLabel label_52 = new JLabel("quantity");
		label_52.setOpaque(true);
		label_52.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 30));
		label_52.setBounds(1464, 666, 120, 42);
		panel17.add(label_52);

		JLabel label_53 = new JLabel("price");
		label_53.setOpaque(true);
		label_53.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 30));
		label_53.setBounds(1378, 666, 74, 42);
		panel17.add(label_53);

		JLabel label_54 = new JLabel("price");
		label_54.setOpaque(true);
		label_54.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 30));
		label_54.setBounds(1247, 809, 74, 42);
		panel17.add(label_54);

		JLabel label_55 = new JLabel("quantity");
		label_55.setOpaque(true);
		label_55.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 30));
		label_55.setBounds(1341, 809, 120, 42);
		panel17.add(label_55);

		JLabel label_56 = new JLabel("extra");
		label_56.setOpaque(true);
		label_56.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 30));
		label_56.setBounds(1473, 809, 74, 42);
		panel17.add(label_56);

		textField_43 = new JTextField();
		textField_43.setColumns(10);
		textField_43.setBounds(1473, 864, 420, 42);
		panel17.add(textField_43);

		textField_44 = new JTextField();
		textField_44.setColumns(10);
		textField_44.setBounds(1341, 864, 120, 42);
		panel17.add(textField_44);

		textField_45 = new JTextField();
		textField_45.setColumns(10);
		textField_45.setBounds(1255, 864, 74, 42);
		panel17.add(textField_45);

		JButton btnOk = new JButton("ok");
		btnOk.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent arg0) {

				if (cb1.isSelected()) {
					if (textField_32.getText().isEmpty() || textField_33.getText().isEmpty()) {
						JOptionPane.showMessageDialog(null, "plz insert all values");
					} else {
						shirtPeace = Double.parseDouble(textField_32.getText());
						shirtPrice = Double.parseDouble(textField_33.getText());
						Total_shirt_price = shirtPeace * shirtPrice;
					}
				}

				if (cb2.isSelected()) {
					if (textField_35.getText().isEmpty() || textField_34.getText().isEmpty()) {
						JOptionPane.showMessageDialog(null, "plz insert all values");
					}

					else {
						pentPeace = Double.parseDouble(textField_35.getText());
						pentPrice = Double.parseDouble(textField_34.getText());
						Total_pent_price = pentPeace * pentPrice;
					}
				}

				if (cb3.isSelected()) {
					if (textField_38.getText().isEmpty() || textField_37.getText().isEmpty()) {
						JOptionPane.showMessageDialog(null, "plz insert all values");
					}

					else {
						coatPeace = Double.parseDouble(textField_38.getText());
						coatPrice = Double.parseDouble(textField_37.getText());
						Total_coat_price = coatPeace * coatPrice;
					}
				}

				if (cb4.isSelected()) {
					if (textField_47.getText().isEmpty() || textField_46.getText().isEmpty()) {
						JOptionPane.showMessageDialog(null, "plz insert all values");
					}

					else {
						jacketPeace = Double.parseDouble(textField_47.getText());
						jacketPrice = Double.parseDouble(textField_46.getText());
						Total_jacket_price = jacketPeace * jacketPrice;
					}
				}

				if (cb5.isSelected()) {
					if (textField_41.getText().isEmpty() || textField_40.getText().isEmpty()) {
						JOptionPane.showMessageDialog(null, "plz insert all values");
					}

					else {
						kurtaPeace = Double.parseDouble(textField_41.getText());
						kurtaPrice = Double.parseDouble(textField_40.getText());
						Total_kurta_price = kurtaPeace * kurtaPrice;
					}
				}

				if (cb6.isSelected()) {
					if (textField_44.getText().isEmpty() || textField_45.getText().isEmpty()) {
						JOptionPane.showMessageDialog(null, "plz insert all values");
					}

					else {
						pjamaPeace = Double.parseDouble(textField_44.getText());
						pjamaPrice = Double.parseDouble(textField_45.getText());
						Total_pjama_price = pjamaPeace * pjamaPrice;
					}
				}

				Totalall = (Total_shirt_price + Total_pent_price + Total_coat_price + Total_jacket_price
						+ Total_kurta_price + Total_pjama_price);
				textField_12.setText(Totalall.toString());

				JOptionPane.showMessageDialog(null, "Please review order again otherwise click save button");

			}
		});
		btnOk.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 60));
		btnOk.setBounds(265, 698, 103, 65);
		panel17.add(btnOk);

		JLabel label_57 = new JLabel("price");
		label_57.setOpaque(true);
		label_57.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 30));
		label_57.setBounds(1112, 538, 74, 42);
		panel17.add(label_57);

		textField_46 = new JTextField();
		textField_46.setColumns(10);
		textField_46.setBounds(1120, 593, 74, 42);
		panel17.add(textField_46);

		textField_47 = new JTextField();
		textField_47.setColumns(10);
		textField_47.setBounds(1206, 593, 120, 42);
		panel17.add(textField_47);

		JLabel label_58 = new JLabel("quantity");
		label_58.setOpaque(true);
		label_58.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 30));
		label_58.setBounds(1206, 538, 120, 42);
		panel17.add(label_58);

		JLabel label_59 = new JLabel("extra");
		label_59.setOpaque(true);
		label_59.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 30));
		label_59.setBounds(1338, 538, 74, 42);
		panel17.add(label_59);

		textField_48 = new JTextField();
		textField_48.setColumns(10);
		textField_48.setBounds(1338, 593, 273, 42);
		panel17.add(textField_48);

		ImageIcon gifImage3e = new ImageIcon(this.getClass().getResource("/background without img.jpg"));

		ImageIcon gifImage3aaazazaz = new ImageIcon(this.getClass().getResource("/can..jpg"));
		JButton cancel = new JButton(gifImage3aaazazaz);
		cancel.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent arg0) {

				g1.setText(null);
				g2.setText(null);
				g3.setText(null);
				g4.setText(null);
				g5.setText(null);
				g6.setText(null);
				g7.setText(null);
				g8.setText(null);
				g9.setText(null);
				textField_33.setText(null);
				textField_32.setText(null);
				textField_31.setText(null);

				h1.setText(null);
				h2.setText(null);
				h3.setText(null);
				h4.setText(null);
				h5.setText(null);
				h6.setText(null);
				h7.setText(null);
				textField_34.setText(null);
				textField_35.setText(null);
				textField_36.setText(null);

				h8.setText(null);
				h9.setText(null);
				h10.setText(null);
				h11.setText(null);
				h12.setText(null);
				h13.setText(null);
				h14.setText(null);
				h15.setText(null);
				h16.setText(null);
				textField_29.setText(null);
				textField_26.setText(null);
				textField_27.setText(null);
				textField_37.setText(null);
				textField_38.setText(null);
				textField_39.setText(null);

				h17.setText(null);
				h18.setText(null);
				h19.setText(null);
				h20.setText(null);
				h21.setText(null);
				textField_46.setText(null);
				textField_47.setText(null);
				textField_48.setText(null);

				h22.setText(null);
				h23.setText(null);
				h24.setText(null);
				h25.setText(null);
				h26.setText(null);
				h27.setText(null);
				h28.setText(null);
				textField_30.setText(null);
				textField_28.setText(null);
				textField_40.setText(null);
				textField_41.setText(null);
				textField_42.setText(null);

				h29.setText(null);
				h30.setText(null);
				h31.setText(null);
				h32.setText(null);
				h33.setText(null);
				h34.setText(null);
				h35.setText(null);
				textField_45.setText(null);
				textField_44.setText(null);
				textField_43.setText(null);

				textField_12.setText(null);

			}
		});
		cancel.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 60));
		cancel.setBounds(83, 873, 179, 65);
		panel17.add(cancel);

		JButton btnRefresh = new JButton("Refresh");
		btnRefresh.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent arg0) {

				try {

					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
					String query = "select * from Customer ";
					PreparedStatement statment = conn.prepareStatement(query);
					ResultSet rs = statment.executeQuery();
					table_3.setModel(DbUtils.resultSetToTableModel(rs));
					rs.close();
					statment.close();
				} catch (SQLException e) {

					e.printStackTrace();
				}

			}
		});
		btnRefresh.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 15));
		btnRefresh.setBounds(12, 698, 97, 57);
		panel17.add(btnRefresh);

		JLabel lblMori_1 = new JLabel("mori");
		lblMori_1.setOpaque(true);
		lblMori_1.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 30));
		lblMori_1.setBounds(1067, 809, 74, 42);
		panel17.add(lblMori_1);
		JLabel lblNewLabel_neworder = new JLabel(gifImage3e);

		lblNewLabel_neworder.setBounds(0, 0, screenSize.width, screenSize.height);
		panel17.add(lblNewLabel_neworder);

		panel18 = new JPanel();
		panel18.setBackground(new Color(102, 0, 0));
		panel18.setBounds(0, 0, screenSize.width, screenSize.height);
		f1.getContentPane().add(panel18);
		panel18.setVisible(false);
		panel18.setLayout(null);

		try {

			conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
			String query = "select * from Employee ";
			PreparedStatement statment = conn.prepareStatement(query);
			ResultSet rs = statment.executeQuery();
			table_2.setModel(DbUtils.resultSetToTableModel(rs));
			rs.close();
			statment.close();
		} catch (SQLException e) {
			e.printStackTrace();
		}

		ImageIcon gifImage11 = new ImageIcon(this.getClass().getResource("/back.jpg"));
		JButton btnBackToButton8 = new JButton(gifImage11);
		btnBackToButton8.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 30));
		btnBackToButton8.setBounds(12, 13, 120, 57);
		btnBackToButton8.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {

				panel18.setVisible(false);
				panel9.setVisible(true);
			}

		});
		panel18.add(btnBackToButton8);

		JSeparator separatora = new JSeparator();
		separatora.setOrientation(SwingConstants.VERTICAL);
		separatora.setBounds(955, 0, 32, 1008);
		panel18.add(separatora);

		JScrollPane scrollPanea_2 = new JScrollPane();
		scrollPanea_2.setBounds(23, 448, 892, 428);
		panel18.add(scrollPanea_2);

		JPopupMenu popupMenu = new JPopupMenu();
		JMenuItem menuItemAdd = new JMenuItem("Edit");
		menuItemAdd.addActionListener(new ActionListener() {

			@Override
			public void actionPerformed(ActionEvent arg0) {
				DefaultTableModel model = (DefaultTableModel) table_8.getModel();
				int row = table_8.getSelectedRow();
				up = model.getValueAt(row, 0).toString();
				textField_13.setText((String) model.getValueAt(row, 2));
				textField_14.setText((String) model.getValueAt(row, 3));

			}

		});

		JMenuItem menuItemRemoveAll = new JMenuItem("Delete");
		menuItemRemoveAll.addActionListener(new ActionListener() {

			@Override
			public void actionPerformed(ActionEvent arg0) {

				DefaultTableModel model = (DefaultTableModel) table_8.getModel();
				int row = table_8.getSelectedRow();
        		id_1 = model.getValueAt(row, 0).toString();
				try {
					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
					String query1 = " DELETE FROM Employee_daily_expense where Employee_id= '" + id_1 + "' ";
					PreparedStatement pst2 = conn.prepareStatement(query1);
					pst2.execute();
					pst2.close();
				} catch (Exception e1) {
					e1.printStackTrace();
				}

				try {

					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
					String query = "select * from Employee_daily_expense ";
					PreparedStatement statment = conn.prepareStatement(query);
					ResultSet rs = statment.executeQuery();
					table_8.setModel(DbUtils.resultSetToTableModel(rs));

					rs.close();
					statment.close();
				} catch (SQLException e) {

					e.printStackTrace();
				}

			}
		});

		popupMenu.add(menuItemAdd);
		popupMenu.add(menuItemRemoveAll);

		table_8 = new JTable();
		table_8.addMouseListener(new MouseAdapter() {
			@Override
			public void mouseClicked(MouseEvent arg0) {

				DefaultTableModel model = (DefaultTableModel) table_8.getModel();
				int row = table_8.getSelectedRow();

				Employee_id = model.getValueAt(row, 0).toString();

				try {
					String query = "Select * from  Employee_daily_expense where Employee_id = '" + Employee_id + "' ";
					PreparedStatement statment = conn.prepareStatement(query);
					ResultSet rs = statment.executeQuery();
					while (rs.next()) {
						textField_13.setText(rs.getString("Rupees"));
						textField_14.setText(rs.getString("Reason"));

					}

					rs.close();
					statment.close();

				} catch (Exception e1) {
					JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
				}

			}
		});
		table_8.setComponentPopupMenu(popupMenu);
		try {

			conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
			String query = "select * from Employee_daily_expense ";
			PreparedStatement statment = conn.prepareStatement(query);
			ResultSet rs = statment.executeQuery();
			table_8.setModel(DbUtils.resultSetToTableModel(rs));

			rs.close();
			statment.close();
		} catch (SQLException e) {

			e.printStackTrace();
		}
		scrollPanea_2.setViewportView(table_8);

		try {
			String query = "Select * from Employee_daily_expense ORDER BY rowid DESC";
			PreparedStatement pst = conn.prepareStatement(query);
			ResultSet rs = pst.executeQuery();
			table_8.setModel(buildTableModel(rs));
			rs.close();
			pst.close();
		} catch (Exception ej) {
			JOptionPane.showMessageDialog(null, "In line 5309" + ej);
		}

		textField_13 = new JTextField();
		textField_13.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 21));
		textField_13.setBounds(158, 77, 197, 57);
		panel18.add(textField_13);
		textField_13.setColumns(10);

		textField_14 = new JTextField();
		textField_14.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 21));
		textField_14.setColumns(10);
		textField_14.setBounds(555, 77, 197, 57);
		panel18.add(textField_14);

		String h0[] = new String[5000];

		try {

			conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
			String query = "select * from Employee ";
			PreparedStatement statment = conn.prepareStatement(query);
			ResultSet rs = statment.executeQuery();
			table_2.setModel(DbUtils.resultSetToTableModel(rs));
			rs.close();
			statment.close();
		} catch (SQLException e) {
			e.printStackTrace();
		}

		try {

			String query = "Select Employee_Contact,Employee_Name from Employee";
			PreparedStatement pst = conn.prepareStatement(query);
			ResultSet rs = pst.executeQuery();
			int i = 0;
			while (rs.next()) {
				h0[i] = rs.getString("Employee_Contact") + "_" + rs.getString("Employee_Name");
				i++;
			}
			pst.close();
			rs.close();

		} catch (Exception e) {
			JOptionPane.showMessageDialog(null, "In line 5345" + e);
		}

		JComboBox comboBoxEmp = new JComboBox(h0);
		comboBoxEmp.setBounds(273, 178, 185, 57);
		panel18.add(comboBoxEmp);

		JDateChooser dateChooser = new JDateChooser();
		dateChooser.setBounds(626, 178, 197, 57);
		panel18.add(dateChooser);

		textField_19 = new JTextField();
		textField_19.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 21));
		textField_19.setColumns(10);
		textField_19.setBounds(414, 919, 143, 57);
		panel18.add(textField_19);

		d = LocalDate.now();

		JButton btnSave = new JButton("Save");
		btnSave.setForeground(Color.WHITE);
		btnSave.setBackground(new Color(153, 0, 0));
		btnSave.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent arg0) {
				i01 = 0;
				i02 = 0;

				SimpleDateFormat sdf1 = new SimpleDateFormat("yyyy-MM-dd");
				za5 = sdf1.format(dateChooser.getDate());

				String emp = comboBoxEmp.getSelectedItem().toString();
				int index = emp.indexOf("_");
				String empid = emp.substring(0, index);
				String empname = emp.substring(index + 1, emp.length());

				try {

					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
					String query = "Insert into Employee_daily_expense (Employee_id,Employee_Name,Rupees,Reason,Date) values(?,?,?,?,?)";

					PreparedStatement statment = conn.prepareStatement(query);
					statment.setString(1, empid);
					statment.setString(2, empname);
					statment.setString(3, textField_13.getText());
					statment.setString(4, textField_14.getText());
					statment.setString(5, za5);

					statment.execute();
					statment.close();
				}

				catch (SQLException e1) {

					e1.printStackTrace();
				}
				try {

					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
					String query = "select * from Employee_daily_expense ";
					PreparedStatement statment = conn.prepareStatement(query);
					ResultSet rs = statment.executeQuery();
					table_8.setModel(DbUtils.resultSetToTableModel(rs));

					rs.close();
					statment.close();
				} catch (SQLException e) {

					e.printStackTrace();
				}

				try {
					String query = "Select Rupees from Employee_daily_expense where Date='" + d + "' ";
					PreparedStatement pst = conn.prepareStatement(query);
					ResultSet rs = pst.executeQuery();
					while (rs.next()) {
						String fd = rs.getString("Rupees");
						i01 = Integer.parseInt(fd);
						i02 = i01 + i02;
					}

					pst.close();
					rs.close();

				} catch (Exception e) {
					JOptionPane.showMessageDialog(null, "In line 5445" + e);
				}

				textField_17.setText(String.valueOf(i02));

			}
		});

		btnSave.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 54));
		btnSave.setBounds(735, 264, 170, 57);
		panel18.add(btnSave);

		JLabel lblEmployee = new JLabel("Employee  Daily Expense");
		lblEmployee.setForeground(Color.WHITE);
		lblEmployee.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 45));
		lblEmployee.setBounds(252, 0, 488, 57);
		panel18.add(lblEmployee);

		JLabel lblShopDailyExpense = new JLabel("Shop Daily Expense");
		lblShopDailyExpense.setForeground(Color.WHITE);
		lblShopDailyExpense.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 45));
		lblShopDailyExpense.setBounds(1180, 0, 398, 57);
		panel18.add(lblShopDailyExpense);

		textField_15 = new JTextField();
		textField_15.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 21));
		textField_15.setColumns(10);
		textField_15.setBounds(1235, 70, 197, 57);
		panel18.add(textField_15);

		textField_16 = new JTextField();
		textField_16.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 21));
		textField_16.setColumns(10);
		textField_16.setBounds(1263, 168, 197, 57);
		panel18.add(textField_16);

		JDateChooser dateChooser_1 = new JDateChooser();
		dateChooser_1.setBounds(1674, 70, 197, 57);
		panel18.add(dateChooser_1);

		textField_20 = new JTextField();
		textField_20.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 21));
		textField_20.setColumns(10);
		textField_20.setBounds(1235, 919, 197, 57);
		panel18.add(textField_20);

		JButton button_9 = new JButton("Save");
		button_9.setBackground(new Color(153, 0, 0));
		button_9.setForeground(Color.WHITE);
		button_9.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent arg0) {

				i03 = 0;
				i04 = 0;

				SimpleDateFormat sdf1 = new SimpleDateFormat("yyyy-MM-dd");
				za4 = sdf1.format(dateChooser_1.getDate());

				try {

					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
					String query = "Insert into Shop_daily_expense (Rupees,Reason,Date) values(?,?,?)";
					PreparedStatement statment = conn.prepareStatement(query);
					statment.setString(1, textField_15.getText());
					statment.setString(2, textField_16.getText());
					statment.setString(3, za4);
					statment.execute();
					statment.close();
				}

				catch (SQLException e1) {

					e1.printStackTrace();
				}
				try {

					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
					String query = "select * from Shop_daily_expense ";
					PreparedStatement statment = conn.prepareStatement(query);
					ResultSet rs = statment.executeQuery();
					table_9.setModel(DbUtils.resultSetToTableModel(rs));
					rs.close();
					statment.close();
				} catch (SQLException e) {

					e.printStackTrace();
				}

				try {
					String query = "Select Rupees from Shop_daily_expense where Date='" + d + "' ";
					PreparedStatement pst = conn.prepareStatement(query);
					ResultSet rs = pst.executeQuery();
					while (rs.next()) {
						String fds = rs.getString("Rupees");
						i03 = Integer.parseInt(fds);
						i04 = i04 + i03;

					}

					pst.close();
					rs.close();

				} catch (Exception e) {
					JOptionPane.showMessageDialog(null, "5559" + e);
				}

				textField_18.setText(String.valueOf(i04));

			}
		});
		button_9.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 42));
		button_9.setBounds(1575, 248, 233, 77);
		panel18.add(button_9);

		JLabel lblRupees = new JLabel("Rupees");
		lblRupees.setForeground(Color.WHITE);
		lblRupees.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 30));
		lblRupees.setBounds(12, 70, 105, 67);
		panel18.add(lblRupees);

		JLabel lblDate = new JLabel("Date");
		lblDate.setForeground(Color.WHITE);
		lblDate.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 30));
		lblDate.setBounds(501, 168, 67, 67);
		panel18.add(lblDate);

		JLabel lblReason = new JLabel("Reason");
		lblReason.setForeground(Color.WHITE);
		lblReason.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 30));
		lblReason.setBounds(406, 70, 105, 67);
		panel18.add(lblReason);

		label_10 = new JLabel("Rupees");
		label_10.setForeground(Color.WHITE);
		label_10.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 30));
		label_10.setBounds(1073, 70, 105, 67);
		panel18.add(label_10);

		label_14 = new JLabel("Date");
		label_14.setForeground(Color.WHITE);
		label_14.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 30));
		label_14.setBounds(1562, 63, 67, 67);
		panel18.add(label_14);

		label_15 = new JLabel("Reason");
		label_15.setForeground(Color.WHITE);
		label_15.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 30));
		label_15.setBounds(1073, 168, 105, 67);
		panel18.add(label_15);

		scrollPane_3 = new JScrollPane();
		scrollPane_3.setBounds(1059, 448, 892, 428);
		panel18.add(scrollPane_3);
		try {

			conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
			String query = "select * from Shop_daily_expense ";
			PreparedStatement statment = conn.prepareStatement(query);
			ResultSet rs = statment.executeQuery();

			rs.close();
			statment.close();
		} catch (SQLException e) {

			e.printStackTrace();
		}

		lblEmployeeName_1 = new JLabel("Employee Name");
		lblEmployeeName_1.setForeground(Color.WHITE);
		lblEmployeeName_1.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 30));
		lblEmployeeName_1.setBounds(12, 168, 214, 67);
		panel18.add(lblEmployeeName_1);
		
				table_9 = new JTable();
				table_9.setBounds(0, 0, 890, 0);
				panel18.add(table_9);
			//	table_9.setModel(DbUtils.resultSetToTableModel(rs));

		lblTotal = new JLabel("Day Total");
		lblTotal.setForeground(Color.WHITE);
		lblTotal.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 30));
		lblTotal.setBounds(656, 912, 134, 67);
		panel18.add(lblTotal);

		textField_17 = new JTextField();
		textField_17.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 21));
		textField_17.setColumns(10);
		textField_17.setBounds(820, 919, 123, 57);
		panel18.add(textField_17);
		try {
			String query = "Select Rupees from Employee_daily_expense where Date= '" + d + "' ";
			PreparedStatement pst = conn.prepareStatement(query);
			ResultSet rs = pst.executeQuery();
			while (rs.next()) {
				String fd = rs.getString("Rupees");
				i01 = Integer.parseInt(fd);
				i02 = i01 + i02;
			}
			pst.close();
			rs.close();

		} catch (Exception e) {
			JOptionPane.showMessageDialog(null, "5665" + e);
		}

		textField_17.setText(String.valueOf(i02));

		textField_18 = new JTextField();
		textField_18.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 21));
		textField_18.setColumns(10);
		textField_18.setBounds(1688, 919, 197, 57);
		panel18.add(textField_18);

		try {
			String query = "Select Rupees from Shop_daily_expense where Date= '" + d + "' ";
			PreparedStatement pst = conn.prepareStatement(query);
			ResultSet rs = pst.executeQuery();
			while (rs.next()) {
				String t = rs.getString("Rupees");
				double o = Double.parseDouble(t);
				q01 = q01 + o;

			}

			pst.close();
			rs.close();

		} catch (Exception e) {
			JOptionPane.showMessageDialog(null, "5695" + e);
		}
		textField_18.setText(String.valueOf(q01));

		lblDayTotal = new JLabel("Day Total");
		lblDayTotal.setForeground(Color.WHITE);
		lblDayTotal.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 30));
		lblDayTotal.setBounds(1515, 912, 134, 67);
		panel18.add(lblDayTotal);

		JLabel lblMonthlyTotal = new JLabel("Selected Total");
		lblMonthlyTotal.setForeground(Color.WHITE);
		lblMonthlyTotal.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 30));
		lblMonthlyTotal.setBounds(229, 912, 173, 67);
		panel18.add(lblMonthlyTotal);

		JLabel lblSelectedTotal = new JLabel("Selected Total");
		lblSelectedTotal.setForeground(Color.WHITE);
		lblSelectedTotal.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 30));
		lblSelectedTotal.setBounds(1012, 912, 185, 67);
		panel18.add(lblSelectedTotal);

		JLabel lblSearch = new JLabel("Search Below :");
		lblSearch.setForeground(Color.WHITE);
		lblSearch.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 45));
		lblSearch.setBounds(12, 300, 322, 57);
		panel18.add(lblSearch);

		JDateChooser dateChooser_2 = new JDateChooser();
		dateChooser_2.setBounds(23, 370, 266, 57);
		panel18.add(dateChooser_2);

		JDateChooser dateChooser_3 = new JDateChooser();
		dateChooser_3.setBounds(330, 370, 266, 57);
		panel18.add(dateChooser_3);

		JButton btnNewButtoon_1 = new JButton("FIND");
		btnNewButtoon_1.setBackground(new Color(153, 0, 0));
		btnNewButtoon_1.setForeground(Color.WHITE);
		btnNewButtoon_1.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 42));
		btnNewButtoon_1.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent arg0) {
			}
		});
		btnNewButtoon_1.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent arg0) {

				SimpleDateFormat sdf = new SimpleDateFormat("yyyy-MM-dd");
				pa4 = sdf.format(dateChooser_2.getDate());
				pa5 = sdf.format(dateChooser_3.getDate());
				double totalbyMonth = 0.0;

				try {
					String query = "SELECT * FROM Employee_daily_expense WHERE Date >= '" + pa4 + "' AND date <= '"
							+ pa5 + "' ";
					PreparedStatement pst = conn.prepareStatement(query);
					ResultSet rs = pst.executeQuery();
					table_8.setModel(DbUtils.resultSetToTableModel(rs));
					rs.close();
					pst.close();
				} catch (Exception e) {
					JOptionPane.showMessageDialog(null, "5759" + e);
				}

				try {
					String query = "SELECT * FROM Employee_daily_expense WHERE Date >= '" + pa4 + "' AND date <= '"
							+ pa5 + "' ";
					PreparedStatement pst = conn.prepareStatement(query);
					ResultSet rs = pst.executeQuery();
					while (rs.next()) {
						totalbyMonth = totalbyMonth + rs.getDouble("Rupees");
					}
					rs.close();
					pst.close();
				} catch (Exception e) {
					JOptionPane.showMessageDialog(null, e);
				}
				textField_19.setText(String.valueOf(totalbyMonth));

			}
		});
		btnNewButtoon_1.setBounds(638, 370, 170, 57);
		panel18.add(btnNewButtoon_1);

		label_20 = new JLabel("Search Below :");
		label_20.setForeground(Color.WHITE);
		label_20.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 45));
		label_20.setBounds(967, 300, 322, 57);
		panel18.add(label_20);

		JDateChooser dateChooser_4 = new JDateChooser();
		dateChooser_4.setBounds(1007, 370, 266, 57);
		panel18.add(dateChooser_4);

		JDateChooser dateChooser_5 = new JDateChooser();
		dateChooser_5.setBounds(1342, 370, 266, 57);
		panel18.add(dateChooser_5);

		JButton button_10 = new JButton("FIND");
		button_10.setBackground(new Color(153, 0, 0));
		button_10.setForeground(Color.WHITE);
		button_10.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent arg0) {

				SimpleDateFormat sdf = new SimpleDateFormat("yyyy-MM-dd");
				pa4 = sdf.format(dateChooser_4.getDate());
				pa5 = sdf.format(dateChooser_5.getDate());
				double totalbyMonth = 0.0;

				try {
					String query = "SELECT * FROM Shop_daily_expense WHERE Date >= '" + pa4 + "' AND date <= '" + pa5
							+ "' ";
					PreparedStatement pst = conn.prepareStatement(query);
					ResultSet rs = pst.executeQuery();
					table_9.setModel(DbUtils.resultSetToTableModel(rs));
					rs.close();
					pst.close();
				} catch (Exception e) {
					JOptionPane.showMessageDialog(null, e);
				}

				try {
					String query = "SELECT * FROM Shop_daily_expense WHERE Date >= '" + pa4 + "' AND date <= '" + pa5
							+ "' ";
					PreparedStatement pst = conn.prepareStatement(query);
					ResultSet rs = pst.executeQuery();
					while (rs.next()) {
						totalbyMonth = totalbyMonth + rs.getDouble("Rupees");
					}
					rs.close();
					pst.close();
				} catch (Exception e) {
					JOptionPane.showMessageDialog(null, e);
				}
				textField_20.setText(String.valueOf(totalbyMonth));

			}
		});
		button_10.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 42));
		button_10.setBounds(1701, 370, 170, 57);
		panel18.add(button_10);

		JButton btnUpdate = new JButton("Update");
		btnUpdate.setBackground(new Color(153, 0, 0));
		btnUpdate.setForeground(Color.WHITE);
		btnUpdate.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent arg0) {

				try {
					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
					String query = "UPDATE Employee_daily_expense set Rupees =?   Where Employee_id =  '" + Employee_id
							+ "' ";
					PreparedStatement pst = conn.prepareStatement(query);

					pst.setString(1, textField_13.getText());
					pst.executeUpdate();

					JOptionPane.showMessageDialog(null, "Data Updated !");
					pst.close();

				} catch (Exception e1) {
					e1.printStackTrace();
				}

				try {

					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
					String query = "select * from Employee_daily_expense ";
					PreparedStatement statment = conn.prepareStatement(query);
					ResultSet rs = statment.executeQuery();
					table_8.setModel(DbUtils.resultSetToTableModel(rs));

					rs.close();
					statment.close();
				} catch (SQLException e) {

					e.printStackTrace();
				}

			}
		});
		btnUpdate.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 42));
		btnUpdate.setBounds(501, 264, 170, 57);
		panel18.add(btnUpdate);

		ImageIcon gifImage3cc = new ImageIcon(this.getClass().getResource("/background without img.jpg"));
		JLabel lblNewLabel_de = new JLabel(gifImage3cc);

		lblNewLabel_de.setBounds(0, 0, screenSize.width, screenSize.height);
		panel18.add(lblNewLabel_de);

		panel19 = new JPanel();
		panel19.setBackground(new Color(102, 0, 0));
		panel19.setBounds(0, 0, screenSize.width, screenSize.height);
		f1.getContentPane().add(panel19);
		panel19.setVisible(false);
		panel19.setLayout(null);

		scrollPane_111 = new JScrollPane();
		scrollPane_111.setBounds(250, 71, 620, 300);
		panel19.add(scrollPane_111);

		table = new JTable();
		table.setAutoResizeMode(JTable.AUTO_RESIZE_OFF);
		scrollPane_111.setViewportView(table);
		try {

			conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
			String query = "select * from payment_shirt ";
			PreparedStatement statment = conn.prepareStatement(query);
			ResultSet rs = statment.executeQuery();
			table.setModel(DbUtils.resultSetToTableModel(rs));
			rs.close();
			statment.close();
		} catch (SQLException e) {

			e.printStackTrace();
		}
		table.addMouseListener(new MouseAdapter() {
			@Override
			public void mouseClicked(MouseEvent arg0) {

				DefaultTableModel model = (DefaultTableModel) table.getModel();
				int row = table.getSelectedRow();

				String id1 = model.getValueAt(row, 9).toString();

				try {
					String query = "Select * from payment_shirt where Customerid='" + id1 + "' ";
					PreparedStatement pst = conn.prepareStatement(query);
					ResultSet rs = pst.executeQuery();

					while (rs.next()) {
						z1 = rs.getString("lmbai");
						z2 = rs.getString("seena");
						z3 = rs.getString("kemer");
						z4 = rs.getString("pait");
						z5 = rs.getString("hip");
						z6 = rs.getString("teera");
						z7 = rs.getString("glaa");
						z8 = rs.getString("baju");
						z9 = rs.getString("bs");
						z10 = rs.getString("Customerid");
						z11 = rs.getString("CustomerName");
						z12 = rs.getString("CustomerContact");
						z13 = rs.getString("CustomerAddress");
						z14 = rs.getString("price");
						z15 = rs.getString("advance_payments");
						z16 = rs.getString("pending_payments");
						z17 = rs.getString("Starting_date");
						z18 = rs.getString("Ending_date");
						z19 = rs.getString("price1");
						z20 = rs.getString("quantity");
						z21 = rs.getString("extra");

					}

					rs.close();
					pst.close();

				} catch (Exception e1) {
					e1.printStackTrace();
				}

				int dialogButton = JOptionPane.YES_NO_OPTION;
				JOptionPane.showConfirmDialog(null, "Would You Like to Save your Previous Note First?", "Warning",
						dialogButton);

				if (dialogButton == JOptionPane.YES_OPTION) {

					try {
						String query1 = " DELETE FROM payment_shirt where Customerid= '" + id1 + "' ";
						PreparedStatement pst2 = conn.prepareStatement(query1);
						pst2.execute();
						pst2.close();
					} catch (Exception e1) {
						e1.printStackTrace();
					}
				} else {

				}
			}

		});

		ImageIcon gifImage12 = new ImageIcon(this.getClass().getResource("/back.jpg"));
		JButton btnBackToButton9 = new JButton(gifImage12);
		btnBackToButton9.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 30));
		btnBackToButton9.setBounds(12, 13, 120, 57);
		btnBackToButton9.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {

				panel19.setVisible(false);
				panel9.setVisible(true);
			}

		});
		panel19.add(btnBackToButton9);

		JScrollPane scrollPane_777 = new JScrollPane();
		scrollPane_777.setBounds(250, 399, 620, 300);
		panel19.add(scrollPane_777);

		table_29 = new JTable();
		table_29.setAutoResizeMode(JTable.AUTO_RESIZE_OFF);
		try {

			conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
			String query = "select * from payment_coat ";
			PreparedStatement statment = conn.prepareStatement(query);
			ResultSet rs = statment.executeQuery();
			table_29.setModel(DbUtils.resultSetToTableModel(rs));
			rs.close();
			statment.close();
		} catch (SQLException e) {

			e.printStackTrace();
		}
		table_29.addMouseListener(new MouseAdapter() {
			@Override
			public void mouseClicked(MouseEvent arg0) {

				DefaultTableModel model = (DefaultTableModel) table_29.getModel();
				int row = table_29.getSelectedRow();

				String id1 = model.getValueAt(row, 12).toString();

				try {
					String query = "Select * from payment_coat where Customerid='" + id1 + "' ";
					PreparedStatement pst = conn.prepareStatement(query);
					ResultSet rs = pst.executeQuery();

					while (rs.next()) {

						z1 = rs.getString("lmbai");
						z2 = rs.getString("seena");
						z3 = rs.getString("kemer");
						z4 = rs.getString("pait");
						z5 = rs.getString("hip");
						z6 = rs.getString("teera");
						z7 = rs.getString("baju");
						z8 = rs.getString("dor");
						z9 = rs.getString("back");
						z10 = rs.getString("bs");
						z11 = rs.getString("bm");
						z12 = rs.getString("shoulder");
						z13 = rs.getString("Customerid");
						z14 = rs.getString("CustomerName");
						z15 = rs.getString("CustomerContact");
						z16 = rs.getString("CustomerAddress");
						z17 = rs.getString("price");
						z18 = rs.getString("advance_payments");
						z19 = rs.getString("pending_payments");
						z20 = rs.getString("Starting_date");
						z21 = rs.getString("Ending_date");
						z22 = rs.getString("price1");
						z23 = rs.getString("quantity");
						z24 = rs.getString("extra");

					}

					rs.close();
					pst.close();

				} catch (Exception e1) {
					e1.printStackTrace();
				}

				int dialogButton = JOptionPane.YES_NO_OPTION;
				JOptionPane.showConfirmDialog(null, "Would You Like to Save your Previous Note First?", "Warning",
						dialogButton);

				if (dialogButton == JOptionPane.YES_OPTION) {

					try {
						String query1 = " DELETE FROM payment_coat where Customerid= '" + id1 + "' ";
						PreparedStatement pst2 = conn.prepareStatement(query1);
						pst2.execute();
						pst2.close();
					} catch (Exception e1) {
						e1.printStackTrace();
					}
				} else {

				}
			}

		});

		scrollPane_777.setViewportView(table_29);

		JScrollPane scrollPane_555 = new JScrollPane();
		scrollPane_555.setBounds(250, 730, 620, 300);
		panel19.add(scrollPane_555);

		table_30 = new JTable();
		table_30.setAutoResizeMode(JTable.AUTO_RESIZE_OFF);
		try {

			conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
			String query = "select * from payment_kurta ";
			PreparedStatement statment = conn.prepareStatement(query);
			ResultSet rs = statment.executeQuery();
			table_30.setModel(DbUtils.resultSetToTableModel(rs));
			rs.close();
			statment.close();
		} catch (SQLException e) {

			e.printStackTrace();
		}
		table_30.addMouseListener(new MouseAdapter() {
			@Override
			public void mouseClicked(MouseEvent arg0) {

				DefaultTableModel model = (DefaultTableModel) table_30.getModel();
				int row = table_30.getSelectedRow();

				String id1 = model.getValueAt(row, 9).toString();

				try {
					String query = "Select * from payment_kurta where id='" + id1 + "' ";
					PreparedStatement pst = conn.prepareStatement(query);
					ResultSet rs = pst.executeQuery();

					while (rs.next()) {

						z1 = rs.getString("lmbai");
						z2 = rs.getString("seena");
						z3 = rs.getString("kemer");
						z4 = rs.getString("pait");
						z5 = rs.getString("hip");
						z6 = rs.getString("teera");
						z7 = rs.getString("glaa");
						z8 = rs.getString("baju");
						z9 = rs.getString("bs");
						z10 = rs.getString("Customerid");
						z11 = rs.getString("CustomerName");
						z12 = rs.getString("CustomerContact");
						z13 = rs.getString("CustomerAddress");
						z14 = rs.getString("price");
						z15 = rs.getString("advance_payments");
						z16 = rs.getString("pending_payments");
						z17 = rs.getString("Starting_date");
						z18 = rs.getString("Ending_date");
						z19 = rs.getString("price1");
						z20 = rs.getString("quantity");
						z21 = rs.getString("extra");

					}

					rs.close();
					pst.close();

				} catch (Exception e1) {
					e1.printStackTrace();
				}

				int dialogButton = JOptionPane.YES_NO_OPTION;
				JOptionPane.showConfirmDialog(null, "Would You Like to Save your Previous Note First?", "Warning",
						dialogButton);

				if (dialogButton == JOptionPane.YES_OPTION) {

					try {
						String query1 = " DELETE FROM payment_kurta where Customerid= '" + id1 + "' ";
						PreparedStatement pst2 = conn.prepareStatement(query1);
						pst2.execute();
						pst2.close();
					} catch (Exception e1) {
						e1.printStackTrace();
					}
				} else {

				}
			}

		});

		scrollPane_555.setViewportView(table_30);

		JScrollPane scrollPane_222 = new JScrollPane();
		scrollPane_222.setBounds(984, 71, 620, 300);
		panel19.add(scrollPane_222);

		table_31 = new JTable();
		table_31.setAutoResizeMode(JTable.AUTO_RESIZE_OFF);
		try {

			conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
			String query = "select * from payment_pent ";
			PreparedStatement statment = conn.prepareStatement(query);
			ResultSet rs = statment.executeQuery();
			table_31.setModel(DbUtils.resultSetToTableModel(rs));
			rs.close();
			statment.close();
		} catch (SQLException e) {

			e.printStackTrace();
		}
		table_31.addMouseListener(new MouseAdapter() {
			@Override
			public void mouseClicked(MouseEvent arg0) {

				DefaultTableModel model = (DefaultTableModel) table_31.getModel();
				int row = table_31.getSelectedRow();

				String id1 = model.getValueAt(row, 7).toString();

				try {
					String query = "Select * from payment_pent where Customerid='" + id1 + "' ";
					PreparedStatement pst = conn.prepareStatement(query);
					ResultSet rs = pst.executeQuery();

					while (rs.next()) {

						z1 = rs.getString("lmbai");
						z2 = rs.getString("kemer");
						z3 = rs.getString("hip");
						z4 = rs.getString("gidri");
						z5 = rs.getString("pinjni");
						z6 = rs.getString("mori");
						z7 = rs.getString("putt");
						z8 = rs.getString("Customerid");
						z9 = rs.getString("CustomerName");
						z10 = rs.getString("CustomerContact");
						z11 = rs.getString("CustomerAddress");
						z12 = rs.getString("price");
						z13 = rs.getString("advance_payments");
						z14 = rs.getString("pending_payments");
						z15 = rs.getString("Starting_date");
						z16 = rs.getString("Ending_date");
						z17 = rs.getString("price1");
						z18 = rs.getString("quantity");
						z19 = rs.getString("extra");

					}

					rs.close();
					pst.close();

				} catch (Exception e1) {
					e1.printStackTrace();
				}

				int dialogButton = JOptionPane.YES_NO_OPTION;
				JOptionPane.showConfirmDialog(null, "Would You Like to Save your Previous Note First?", "Warning",
						dialogButton);

				if (dialogButton == JOptionPane.YES_OPTION) {

					try {
						String query1 = " DELETE FROM payment_pent where Customerid= '" + id1 + "' ";
						PreparedStatement pst2 = conn.prepareStatement(query1);
						pst2.execute();
						pst2.close();
					} catch (Exception e1) {
						e1.printStackTrace();
					}
				} else {

				}
			}

		});

		scrollPane_222.setViewportView(table_31);

		JScrollPane scrollPane_333 = new JScrollPane();
		scrollPane_333.setBounds(984, 399, 620, 300);
		panel19.add(scrollPane_333);

		table_32 = new JTable();
		table_32.setAutoResizeMode(JTable.AUTO_RESIZE_OFF);
		try {

			conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
			String query = "select * from payment_jacket ";
			PreparedStatement statment = conn.prepareStatement(query);
			ResultSet rs = statment.executeQuery();
			table_32.setModel(DbUtils.resultSetToTableModel(rs));
			rs.close();
			statment.close();
		} catch (SQLException e) {

			e.printStackTrace();
		}
		table_32.addMouseListener(new MouseAdapter() {
			@Override
			public void mouseClicked(MouseEvent arg0) {

				DefaultTableModel model = (DefaultTableModel) table_32.getModel();
				int row = table_32.getSelectedRow();

				String id1 = model.getValueAt(row, 6).toString();

				try {
					String query = "Select * from payment_jacket where Customerid='" + id1 + "' ";
					PreparedStatement pst = conn.prepareStatement(query);
					ResultSet rs = pst.executeQuery();

					while (rs.next()) {

						z1 = rs.getString("lmbai");
						z2 = rs.getString("seena");
						z3 = rs.getString("kemer");
						z4 = rs.getString("hip");
						z5 = rs.getString("teera");
						z6 = rs.getString("Customerid");
						z7 = rs.getString("CustomerName");
						z8 = rs.getString("CustomerContact");
						z9 = rs.getString("CustomerAddress");
						z10 = rs.getString("price");
						z11 = rs.getString("advance_payments");
						z12 = rs.getString("pending_payments");
						z13 = rs.getString("Starting_date");
						z14 = rs.getString("Ending_date");
						z15 = rs.getString("price1");
						z16 = rs.getString("quantity");
						z17 = rs.getString("extra");

					}

					rs.close();
					pst.close();

				} catch (Exception e1) {
					e1.printStackTrace();
				}

				int dialogButton = JOptionPane.YES_NO_OPTION;
				JOptionPane.showConfirmDialog(null, "Would You Like to Save your Previous Note First?", "Warning",
						dialogButton);

				if (dialogButton == JOptionPane.YES_OPTION) {

					try {
						String query1 = " DELETE FROM payment_jacket where Customerid= '" + id1 + "' ";
						PreparedStatement pst2 = conn.prepareStatement(query1);
						pst2.execute();
						pst2.close();
					} catch (Exception e1) {
						e1.printStackTrace();
					}
				} else {

				}
			}

		});

		scrollPane_333.setViewportView(table_32);

		JScrollPane scrollPane_444 = new JScrollPane();
		scrollPane_444.setBounds(984, 730, 620, 300);
		panel19.add(scrollPane_444);

		table_33 = new JTable();
		table_33.setAutoResizeMode(JTable.AUTO_RESIZE_OFF);
		try {

			conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
			String query = "select * from payment_pjama ";
			PreparedStatement statment = conn.prepareStatement(query);
			ResultSet rs = statment.executeQuery();
			table_33.setModel(DbUtils.resultSetToTableModel(rs));
			rs.close();
			statment.close();
		} catch (SQLException e) {

			e.printStackTrace();
		}
		table_33.addMouseListener(new MouseAdapter() {
			@Override
			public void mouseClicked(MouseEvent arg0) {

				DefaultTableModel model = (DefaultTableModel) table_33.getModel();
				int row = table_33.getSelectedRow();

				String id1 = model.getValueAt(row, 7).toString();

				try {
					String query = "Select * from payment_pjama where id='" + id1 + "' ";
					PreparedStatement pst = conn.prepareStatement(query);
					ResultSet rs = pst.executeQuery();

					while (rs.next()) {

						z1 = rs.getString("lmbai");
						z2 = rs.getString("kemer");
						z3 = rs.getString("hip");
						z4 = rs.getString("gidri");
						z5 = rs.getString("pinjni");
						z6 = rs.getString("mori");
						z7 = rs.getString("putt");
						z8 = rs.getString("Customerid");
						z9 = rs.getString("CustomerName");
						z10 = rs.getString("CustomerContact");
						z11 = rs.getString("CustomerAddress");
						z12 = rs.getString("price");
						z13 = rs.getString("advance_payments");
						z14 = rs.getString("pending_payments");
						z15 = rs.getString("Starting_date");
						z16 = rs.getString("Ending_date");
						z17 = rs.getString("price1");
						z18 = rs.getString("quantity");
						z19 = rs.getString("extra");

					}

					rs.close();
					pst.close();

				} catch (Exception e1) {
					e1.printStackTrace();
				}

				int dialogButton = JOptionPane.YES_NO_OPTION;
				JOptionPane.showConfirmDialog(null, "Would You Like to Save your Previous Note First?", "Warning",
						dialogButton);

				if (dialogButton == JOptionPane.YES_OPTION) {

					try {
						String query1 = " DELETE FROM payment_pjama where Customerid= '" + id1 + "' ";
						PreparedStatement pst2 = conn.prepareStatement(query1);
						pst2.execute();
						pst2.close();
					} catch (Exception e1) {
						e1.printStackTrace();
					}
				} else {

				}
			}

		});

		scrollPane_444.setViewportView(table_33);

		ImageIcon workingmage = new ImageIcon(this.getClass().getResource("/5th page.jpg"));
		JLabel label = new JLabel(workingmage);
		label.setBounds(0, 0, screenSize.width, screenSize.height);
		panel19.add(label);

		try {
			String query = "Select * from Customer";
			PreparedStatement pst = conn.prepareStatement(query);
			ResultSet rs = pst.executeQuery();
			while (rs.next()) {
				id1 = rs.getInt("Customerid");

			}
			sid = String.valueOf((id1 + 1));

			pst.close();
			rs.close();

		} catch (Exception e) {
			JOptionPane.showMessageDialog(null, "Hello  In line 6548" + e);
		}

		JMenuItem item1 = new JMenuItem("Details");
		item1.addActionListener(new ActionListener() {

			@Override
			public void actionPerformed(ActionEvent e) {

			}
		});

		ImageIcon gifImage3ff = new ImageIcon(this.getClass().getResource("/save.jpg"));

		ImageIcon gifImage3gg = new ImageIcon(this.getClass().getResource("/can..jpg"));

		JPopupMenu popupMenu_1 = new JPopupMenu();
		menuItemRemoveAll = new JMenuItem("Delete");
		menuItemRemoveAll.addActionListener(new ActionListener() {

			@Override
			public void actionPerformed(ActionEvent arg0) {

				DefaultTableModel model = (DefaultTableModel) table_1.getModel();
				int row = table_1.getSelectedRow();
				id_1 = model.getValueAt(row, 0).toString();
				try {
					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
					String query1 = " DELETE FROM Customer where Customerid= '" + id_1 + "' ";
					PreparedStatement pst2 = conn.prepareStatement(query1);
					pst2.execute();
					pst2.close();
				} catch (Exception e1) {
					e1.printStackTrace();
				}

				try {
					String query1 = " DELETE FROM Shirt where Customerid= '" + id_1 + "' ";
					PreparedStatement pst2 = conn.prepareStatement(query1);
					pst2.execute();
					pst2.close();
				} catch (Exception e1) {
					e1.printStackTrace();
				}

				try {
					String query1 = " DELETE FROM Pent where Customerid= '" + id_1 + "' ";
					PreparedStatement pst2 = conn.prepareStatement(query1);
					pst2.execute();
					pst2.close();
				} catch (Exception e1) {
					e1.printStackTrace();
				}

				try {
					String query1 = " DELETE FROM Coat where Customerid= '" + id_1 + "' ";
					PreparedStatement pst2 = conn.prepareStatement(query1);
					pst2.execute();
					pst2.close();
				} catch (Exception e1) {
					e1.printStackTrace();
				}

				try {
					String query1 = " DELETE FROM Jacket where Customerid= '" + id_1 + "' ";
					PreparedStatement pst2 = conn.prepareStatement(query1);
					pst2.execute();
					pst2.close();
				} catch (Exception e1) {
					e1.printStackTrace();
				}

				try {
					String query1 = " DELETE FROM Kurta where Customerid= '" + id_1 + "' ";
					PreparedStatement pst2 = conn.prepareStatement(query1);
					pst2.execute();
					pst2.close();
				} catch (Exception e1) {
					e1.printStackTrace();
				}

				try {
					String query1 = " DELETE FROM Pjama where Customerid= '" + id_1 + "' ";
					PreparedStatement pst2 = conn.prepareStatement(query1);
					pst2.execute();
					pst2.close();
				} catch (Exception e1) {
					e1.printStackTrace();
				}

				JOptionPane.showMessageDialog(null, "Data Deleted");

				try {

					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
					String query = "select * from Customer ";
					PreparedStatement statment = conn.prepareStatement(query);
					ResultSet rs = statment.executeQuery();
					table_1.setModel(DbUtils.resultSetToTableModel(rs));
					rs.close();
					statment.close();
				} catch (SQLException e) {

					e.printStackTrace();
				}

			}
		});

		popupMenu_1.add(menuItemRemoveAll);

		JPopupMenu popupMenu__1 = new JPopupMenu();
		JMenuItem menuItemAdd_1 = new JMenuItem("Edit");
		menuItemAdd_1.addActionListener(new ActionListener() {

			@Override
			public void actionPerformed(ActionEvent arg0) {
				DefaultTableModel model = (DefaultTableModel) table_1.getModel();
				int row = table_1.getSelectedRow();
				en.setText((String) model.getValueAt(row, 0));
				ec.setText((String) model.getValueAt(row, 1));
				ed.setText((String) model.getValueAt(row, 2));
				ef.setText((String) model.getValueAt(row, 3));

			}

		});
		popupMenu_1.add(menuItemAdd_1);

		try {

			conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
			String query = "select * from Customer ";
			PreparedStatement statment = conn.prepareStatement(query);
			ResultSet rs = statment.executeQuery();
			rs.close();
			statment.close();
		} catch (SQLException e) {

			e.printStackTrace();
		}

		ImageIcon btnSearch1 = new ImageIcon(this.getClass().getResource("/search.jpg"));

		ImageIcon gifImage13 = new ImageIcon(this.getClass().getResource("/back.jpg"));

		ImageIcon gifImage2 = new ImageIcon(this.getClass().getResource("/3rd page.jpg"));

		panel10 = new JPanel();
		panel10.setBackground(new Color(102, 0, 0));
		panel10.setBounds(0, 0, screenSize.width, screenSize.height);
		f1.getContentPane().add(panel10);
		panel10.setVisible(false);
		panel10.setLayout(null);

		lblEmployeeid = new JLabel("Customer id");
		lblEmployeeid.setHorizontalAlignment(SwingConstants.CENTER);
		lblEmployeeid.setOpaque(true);
		lblEmployeeid.setForeground(new Color(0, 100, 0));
		lblEmployeeid.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 24));
		lblEmployeeid.setBounds(1578, 0, 188, 42);
		panel10.add(lblEmployeeid);

		lblEmployeeName = new JLabel("Customer Name");
		lblEmployeeName.setHorizontalAlignment(SwingConstants.CENTER);
		lblEmployeeName.setOpaque(true);
		lblEmployeeName.setForeground(new Color(0, 128, 0));
		lblEmployeeName.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 24));
		lblEmployeeName.setBounds(1578, 55, 188, 42);
		panel10.add(lblEmployeeName);

		lblEmployeeContact = new JLabel("Customer Contact");
		lblEmployeeContact.setHorizontalAlignment(SwingConstants.CENTER);
		lblEmployeeContact.setOpaque(true);
		lblEmployeeContact.setForeground(new Color(0, 128, 0));
		lblEmployeeContact.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 24));
		lblEmployeeContact.setBounds(1578, 104, 188, 42);
		panel10.add(lblEmployeeContact);

		lblEmployeeAddress = new JLabel("Customer Address");
		lblEmployeeAddress.setHorizontalAlignment(SwingConstants.CENTER);
		lblEmployeeAddress.setOpaque(true);
		lblEmployeeAddress.setForeground(new Color(0, 128, 0));
		lblEmployeeAddress.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 24));
		lblEmployeeAddress.setBounds(1578, 159, 188, 42);
		panel10.add(lblEmployeeAddress);

		lblShirt = new JLabel("Shirt");
		lblShirt.setHorizontalAlignment(SwingConstants.CENTER);
		lblShirt.setOpaque(true);
		lblShirt.setForeground(Color.RED);
		lblShirt.setFont(new Font("Snap ITC", Font.BOLD, 30));
		lblShirt.setBounds(601, 162, 102, 97);
		panel10.add(lblShirt);

		lbllmbai1 = new JLabel("lmbai");
		lbllmbai1.setHorizontalAlignment(SwingConstants.CENTER);
		lbllmbai1.setOpaque(true);
		lbllmbai1.setForeground(Color.BLACK);
		lbllmbai1.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 20));
		lbllmbai1.setBounds(758, 162, 70, 42);
		panel10.add(lbllmbai1);

		lblseena = new JLabel("seena");
		lblseena.setHorizontalAlignment(SwingConstants.CENTER);
		lblseena.setOpaque(true);
		lblseena.setForeground(Color.BLACK);
		lblseena.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 20));
		lblseena.setBounds(850, 159, 70, 42);
		panel10.add(lblseena);

		lblkemer1 = new JLabel("kemer");
		lblkemer1.setHorizontalAlignment(SwingConstants.CENTER);
		lblkemer1.setOpaque(true);
		lblkemer1.setForeground(Color.BLACK);
		lblkemer1.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 20));
		lblkemer1.setBounds(939, 159, 70, 42);
		panel10.add(lblkemer1);

		lblteera = new JLabel("pait");
		lblteera.setHorizontalAlignment(SwingConstants.CENTER);
		lblteera.setOpaque(true);
		lblteera.setForeground(Color.BLACK);
		lblteera.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 20));
		lblteera.setBounds(1021, 159, 70, 42);
		panel10.add(lblteera);

		lblbaju = new JLabel("hip");
		lblbaju.setHorizontalAlignment(SwingConstants.CENTER);
		lblbaju.setOpaque(true);
		lblbaju.setForeground(Color.BLACK);
		lblbaju.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 20));
		lblbaju.setBounds(1103, 159, 70, 42);
		panel10.add(lblbaju);

		lblgla = new JLabel("teera");
		lblgla.setHorizontalAlignment(SwingConstants.CENTER);
		lblgla.setOpaque(true);
		lblgla.setForeground(Color.BLACK);
		lblgla.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 20));
		lblgla.setBounds(1185, 159, 70, 42);
		panel10.add(lblgla);

		JSeparator separator011 = new JSeparator();
		separator011.setOrientation(SwingConstants.VERTICAL);
		separator011.setForeground(Color.BLUE);
		separator011.setBounds(565, 0, 14, 1018);
		panel10.add(separator011);

		en = new JTextField();
		en.setBounds(1778, 3, 116, 42);
		panel10.add(en);
		en.setColumns(10);
		en.setText(sid);

		ec = new JTextField();
		ec.setBounds(1778, 52, 116, 42);
		panel10.add(ec);
		ec.setColumns(10);

		ed = new JTextField();
		ed.setBounds(1778, 107, 116, 42);
		panel10.add(ed);
		ed.setColumns(10);

		ef = new JTextField();
		ef.setBounds(1778, 162, 116, 42);
		panel10.add(ef);
		ef.setColumns(10);

		a_1 = new JTextField();
		a_1.setBounds(758, 217, 70, 42);
		panel10.add(a_1);
		a_1.setColumns(10);

		a_2 = new JTextField();
		a_2.setBounds(850, 217, 70, 42);
		panel10.add(a_2);
		a_2.setColumns(10);

		a_3 = new JTextField();
		a_3.setBounds(939, 217, 70, 42);
		panel10.add(a_3);
		a_3.setColumns(10);

		a_4 = new JTextField();
		a_4.setBounds(1021, 217, 70, 42);
		panel10.add(a_4);
		a_4.setColumns(10);

		a_5 = new JTextField();
		a_5.setBounds(1103, 217, 70, 42);
		panel10.add(a_5);
		a_5.setColumns(10);

		a_6 = new JTextField();
		a_6.setBounds(1185, 217, 70, 42);
		panel10.add(a_6);
		a_6.setColumns(10);

		a_7 = new JTextField();
		a_7.setBounds(1267, 217, 70, 42);
		panel10.add(a_7);
		a_7.setColumns(10);

		a_8 = new JTextField();
		a_8.setColumns(10);
		a_8.setBounds(1349, 217, 70, 42);
		panel10.add(a_8);

		a_9 = new JTextField();
		a_9.setColumns(10);
		a_9.setBounds(1436, 217, 70, 42);
		panel10.add(a_9);

		b1 = new JTextField();
		b1.setBounds(738, 343, 85, 42);
		panel10.add(b1);
		b1.setColumns(10);

		b2 = new JTextField();
		b2.setBounds(840, 343, 85, 42);
		panel10.add(b2);
		b2.setColumns(10);

		b3 = new JTextField();
		b3.setBounds(945, 347, 85, 42);
		panel10.add(b3);
		b3.setColumns(10);

		b4 = new JTextField();
		b4.setBounds(1052, 347, 85, 42);
		panel10.add(b4);
		b4.setColumns(10);

		b5 = new JTextField();
		b5.setBounds(1150, 347, 85, 42);
		panel10.add(b5);
		b5.setColumns(10);

		b6 = new JTextField();
		b6.setBounds(1252, 347, 85, 42);
		panel10.add(b6);
		b6.setColumns(10);

		b7 = new JTextField();
		b7.setBounds(1349, 347, 85, 42);
		panel10.add(b7);
		b7.setColumns(10);

		c1 = new JTextField();
		c1.setColumns(10);
		c1.setBounds(743, 493, 85, 42);
		panel10.add(c1);

		c2 = new JTextField();
		c2.setColumns(10);
		c2.setBounds(845, 493, 85, 42);
		panel10.add(c2);

		c3 = new JTextField();
		c3.setColumns(10);
		c3.setBounds(950, 497, 85, 42);
		panel10.add(c3);

		c4 = new JTextField();
		c4.setColumns(10);
		c4.setBounds(1057, 497, 85, 42);
		panel10.add(c4);

		c5 = new JTextField();
		c5.setColumns(10);
		c5.setBounds(1155, 497, 85, 42);
		panel10.add(c5);

		c6 = new JTextField();
		c6.setColumns(10);
		c6.setBounds(1252, 497, 85, 42);
		panel10.add(c6);

		c7 = new JTextField();
		c7.setColumns(10);
		c7.setBounds(1354, 497, 70, 42);
		panel10.add(c7);

		c8 = new JTextField();
		c8.setColumns(10);
		c8.setBounds(1436, 497, 70, 42);
		panel10.add(c8);

		c9 = new JTextField();
		c9.setColumns(10);
		c9.setBounds(1518, 497, 70, 42);
		panel10.add(c9);

		c10 = new JTextField();
		c10.setColumns(10);
		c10.setBounds(1600, 497, 70, 42);
		panel10.add(c10);

		c11 = new JTextField();
		c11.setColumns(10);
		c11.setBounds(1682, 497, 70, 42);
		panel10.add(c11);

		c12 = new JTextField();
		c12.setColumns(10);
		c12.setBounds(1764, 497, 90, 42);
		panel10.add(c12);

		d_1 = new JTextField();
		d_1.setColumns(10);
		d_1.setBounds(738, 655, 85, 42);
		panel10.add(d_1);

		d_2 = new JTextField();
		d_2.setColumns(10);
		d_2.setBounds(840, 655, 85, 42);
		panel10.add(d_2);

		d_3 = new JTextField();
		d_3.setColumns(10);
		d_3.setBounds(945, 655, 85, 42);
		panel10.add(d_3);

		d_4 = new JTextField();
		d_4.setColumns(10);
		d_4.setBounds(1052, 655, 85, 42);
		panel10.add(d_4);

		d_5 = new JTextField();
		d_5.setColumns(10);
		d_5.setBounds(1150, 655, 85, 42);
		panel10.add(d_5);

		e_1 = new JTextField();
		e_1.setColumns(10);
		e_1.setBounds(758, 787, 70, 42);
		panel10.add(e_1);

		e_2 = new JTextField();
		e_2.setColumns(10);
		e_2.setBounds(850, 787, 70, 42);
		panel10.add(e_2);

		e_3 = new JTextField();
		e_3.setColumns(10);
		e_3.setBounds(939, 787, 70, 42);
		panel10.add(e_3);

		e_4 = new JTextField();
		e_4.setColumns(10);
		e_4.setBounds(1021, 787, 70, 42);
		panel10.add(e_4);

		e_5 = new JTextField();
		e_5.setColumns(10);
		e_5.setBounds(1103, 787, 70, 42);
		panel10.add(e_5);

		e_6 = new JTextField();
		e_6.setColumns(10);
		e_6.setBounds(1185, 787, 70, 42);
		panel10.add(e_6);

		e_7 = new JTextField();
		e_7.setColumns(10);
		e_7.setBounds(1267, 787, 70, 42);
		panel10.add(e_7);

		e_8 = new JTextField();
		e_8.setColumns(10);
		e_8.setBounds(1349, 787, 70, 42);
		panel10.add(e_8);

		e_9 = new JTextField();
		e_9.setColumns(10);
		e_9.setBounds(1436, 787, 70, 42);
		panel10.add(e_9);

		f_1 = new JTextField();
		f_1.setColumns(10);
		f_1.setBounds(738, 926, 90, 42);
		panel10.add(f_1);

		f_2 = new JTextField();
		f_2.setColumns(10);
		f_2.setBounds(840, 926, 90, 42);
		panel10.add(f_2);

		f_3 = new JTextField();
		f_3.setColumns(10);
		f_3.setBounds(945, 926, 90, 42);
		panel10.add(f_3);

		f_4 = new JTextField();
		f_4.setColumns(10);
		f_4.setBounds(1047, 926, 90, 42);
		panel10.add(f_4);

		f_5 = new JTextField();
		f_5.setColumns(10);
		f_5.setBounds(1150, 926, 90, 42);
		panel10.add(f_5);

		f_6 = new JTextField();
		f_6.setColumns(10);
		f_6.setBounds(1247, 926, 90, 42);
		panel10.add(f_6);

		f_7 = new JTextField();
		f_7.setColumns(10);
		f_7.setBounds(1349, 926, 70, 42);
		panel10.add(f_7);

		JLabel lblpent_1 = new JLabel("Pant");
		lblpent_1.setOpaque(true);
		lblpent_1.setForeground(Color.RED);
		lblpent_1.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 30));
		lblpent_1.setBounds(601, 292, 102, 97);
		panel10.add(lblpent_1);

		lblNewLabel_1 = new JLabel("lmbai");
		lblNewLabel_1.setOpaque(true);
		lblNewLabel_1.setForeground(Color.BLACK);
		lblNewLabel_1.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 20));
		lblNewLabel_1.setBounds(738, 288, 90, 42);
		panel10.add(lblNewLabel_1);

		JLabel lblsaamanaa = new JLabel("glaa");
		lblsaamanaa.setOpaque(true);
		lblsaamanaa.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 20));
		lblsaamanaa.setBounds(1267, 159, 70, 42);
		panel10.add(lblsaamanaa);

		JLabel lblNewLabel_002 = new JLabel("kemer");
		lblNewLabel_002.setOpaque(true);
		lblNewLabel_002.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 20));
		lblNewLabel_002.setBounds(840, 288, 90, 42);
		panel10.add(lblNewLabel_002);

		JLabel lblNewLabel_003 = new JLabel("hip");
		lblNewLabel_003.setOpaque(true);
		lblNewLabel_003.setAutoscrolls(true);
		lblNewLabel_003.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 20));
		lblNewLabel_003.setBounds(945, 292, 90, 42);
		panel10.add(lblNewLabel_003);

		JLabel lblNewLabel_004 = new JLabel("gidri");
		lblNewLabel_004.setOpaque(true);
		lblNewLabel_004.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 20));
		lblNewLabel_004.setBounds(1047, 292, 90, 42);
		panel10.add(lblNewLabel_004);

		JLabel lblNewLabel_005 = new JLabel("pinjni");
		lblNewLabel_005.setOpaque(true);
		lblNewLabel_005.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 20));
		lblNewLabel_005.setBounds(1149, 292, 90, 42);
		panel10.add(lblNewLabel_005);

		JLabel lblNewLabel_006 = new JLabel("mori");
		lblNewLabel_006.setOpaque(true);
		lblNewLabel_006.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 20));
		lblNewLabel_006.setBounds(1247, 292, 90, 42);
		panel10.add(lblNewLabel_006);

		JLabel lblNewLabel_007 = new JLabel("putt");
		lblNewLabel_007.setOpaque(true);
		lblNewLabel_007.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 20));
		lblNewLabel_007.setBounds(1349, 292, 70, 42);
		panel10.add(lblNewLabel_007);
		JButton btnSave01 = new JButton(gifImage3ff);

		btnSave01.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent arg0) {

				try {

					e1 = en.getText();
					e2 = ec.getText();
					e3 = ed.getText();
					e4 = ef.getText();
					e5 = e1.concat(e2);

					r1 = a_1.getText();
					r2 = a_2.getText();
					r3 = a_3.getText();
					r4 = a_4.getText();
					r5 = a_5.getText();
					r6 = a_6.getText();
					r7 = a_7.getText();
					r8 = a_8.getText();
					r9 = a_9.getText();
					r10 = b1.getText();
					r11 = b2.getText();
					r12 = b3.getText();
					r13 = b4.getText();
					r14 = b5.getText();
					r15 = b6.getText();
					r16 = b7.getText();
					r17 = c1.getText();
					r18 = c2.getText();
					r19 = c3.getText();
					r20 = c4.getText();
					r21 = c5.getText();
					r22 = c6.getText();
					r23 = c7.getText();
					r24 = c8.getText();
					r25 = c9.getText();
					r26 = c10.getText();
					r27 = c11.getText();
					r28 = c12.getText();
					r29 = d_1.getText();
					r30 = d_2.getText();
					r31 = d_3.getText();
					r32 = d_4.getText();
					r33 = d_5.getText();
					r34 = e_1.getText();
					r35 = e_2.getText();
					r36 = e_3.getText();
					r37 = e_4.getText();
					r38 = e_5.getText();
					r39 = e_6.getText();
					r40 = e_7.getText();
					r41 = e_8.getText();
					r42 = e_9.getText();
					r43 = f_1.getText();
					r44 = f_2.getText();
					r45 = f_3.getText();
					r46 = f_4.getText();
					r47 = f_5.getText();
					r48 = f_6.getText();
					r49 = f_7.getText();

				} catch (Exception e) {
					JOptionPane.showMessageDialog(null, "Table is not created !" + e);
				}

				try {
					String query = "Insert into Customer(Customerid,CustomerName,CustomerContact,CustomerAddress) values(?,?,?,?)";
					PreparedStatement pst = conn.prepareStatement(query);

					pst.setString(1, en.getText());
					pst.setString(2, ec.getText());
					pst.setString(3, ed.getText());
					pst.setString(4, ef.getText());

					pst.execute();

					pst.close();

				} catch (Exception e1) {
					JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
				}

				try {
					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");

					String query = "select * from Customer ";
					PreparedStatement statement = conn.prepareStatement(query);
					ResultSet rs = statement.executeQuery();

					rs.close();
					statement.close();
				} catch (SQLException e) {
					e.printStackTrace();
				}

				try {
					String query = "CREATE TABLE IF NOT EXISTS  Shirt (lmbai TEXT,seena TEXT,kemer TEXT,pait TEXT,hip TEXT,teera TEXT,glaa TEXT,baju TEXT,bs TEXT,Customerid INT,CustomerName TEXT,CustomerContact TEXT,CustomerAddress TEXT,price DOUBLE,advance_payments DOUBLE,pending_payments DOUBLE,Starting_date DATETIME,Ending_date DATETIME,price1 DOUBLE,quantity INTEGER,extra TEXT)";

					PreparedStatement pst = conn.prepareStatement(query);
					pst.executeUpdate();
				} catch (Exception e) {
					JOptionPane.showMessageDialog(null, "Table is not created !" + e);
				}

				try {
					String query = "CREATE TABLE IF NOT EXISTS  pent (lmbai TEXT,kemer TEXT,hip TEXT,gidri TEXT,pinjni TEXT,mori TEXT,putt TEXT,Customerid INT,CustomerName TEXT,CustomerContact TEXT,CustomerAddress TEXT,price DOUBLE,advance_payments DOUBLE,pending_payments DOUBLE,Starting_date DATETIME,Ending_date DATETIME,price1 DOUBLE,quantity INTEGER,extra TEXT)";

					PreparedStatement pst = conn.prepareStatement(query);
					pst.execute();

				} catch (Exception e) {
					JOptionPane.showMessageDialog(null, "Table is not created !" + e);
				}
				try {
					String query = "CREATE TABLE IF NOT EXISTS Coat (lmbai TEXT,seena TEXT,kemer TEXT,pait TEXT,hip TEXT,teera TEXT,baju TEXT,dor TEXT,back TEXT,bs TEXT,bm TEXT,shoulder TEXT,Customerid INT,CustomerName TEXT,CustomerContact TEXT,CustomerAddress TEXT,price DOUBLE,advance_payments DOUBLE,pending_payments DOUBLE,Starting_date DATETIME,Ending_date DATETIME,price1 DOUBLE,quantity INTEGER,extra TEXT)";

					PreparedStatement pst = conn.prepareStatement(query);
					pst.execute();

				} catch (Exception e) {
					JOptionPane.showMessageDialog(null, "Table is not created !" + e);
				}
				try {
					String query = "CREATE TABLE IF NOT EXISTS  Jacket (lmbai TEXT,seena TEXT,kemer TEXT,hip TEXT,teera TEXT,Customerid INT,CustomerName TEXT,CustomerContact TEXT,CustomerAddress TEXT,price DOUBLE,advance_payments DOUBLE,pending_payments DOUBLE,Starting_date DATETIME,Ending_date DATETIME,price1 DOUBLE,quantity INTGER,extra TEXT)";

					PreparedStatement pst = conn.prepareStatement(query);
					pst.execute();

				} catch (Exception e) {
					JOptionPane.showMessageDialog(null, "Table is not created !" + e);
				}
				try {
					String query = "CREATE TABLE IF NOT EXISTS  Kurta (lmbai TEXT,seena TEXT,kemer TEXT,pait TEXT,hip TEXT,teera TEXT,glaa TEXT,baju TEXT,bs TEXT,Customerid INT,CustomerName TEXT,CustomerContact TEXT,CustomerAddress TEXT,price DOUBLE,advance_payments DOUBLE,pending_payments DOUBLE,Starting_date DATETIME,Ending_date DATETIME,price1 DOUBLE,quantity INTEGER,extra TEXT)";

					PreparedStatement pst = conn.prepareStatement(query);
					pst.executeUpdate();

				} catch (Exception e) {
					JOptionPane.showMessageDialog(null, "Table is not created !" + e);
				}
				try {
					String query = "CREATE TABLE IF NOT EXISTS  Pjama (lmbai TEXT,kemer TEXT,hip TEXT,gidri TEXT,pinjni TEXT,mori TEXT,putt TEXT,Customerid INT,CustomerName TEXT,CustomerContact TEXT,CustomerAddress TEXT,price DOUBLE,advance_payments DOUBLE,pending_payments DOUBLE,Starting_date DATETIME,Ending_date DATETIME,price1 DOUBLE,quantity INTGER,extra TEXT)";

					PreparedStatement pst = conn.prepareStatement(query);
					pst.executeUpdate();

				} catch (Exception e) {

				}

				try {

					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
					String query = "select * from Customer ";
					PreparedStatement statment = conn.prepareStatement(query);
					ResultSet rs = statment.executeQuery();
					table_1.setModel(DbUtils.resultSetToTableModel(rs));
					rs.close();
					statment.close();
				} catch (SQLException e) {

					e.printStackTrace();
				}

				try {

					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
					String query = "select * from Customer ";
					PreparedStatement statment = conn.prepareStatement(query);
					ResultSet rs = statment.executeQuery();
					table_3.setModel(DbUtils.resultSetToTableModel(rs));
					rs.close();
					statment.close();
				} catch (SQLException e) {

					e.printStackTrace();
				}
				if (a_1.getText().isEmpty() && a_2.getText().isEmpty() && a_3.getText().isEmpty()
						&& a_4.getText().isEmpty() && a_5.getText().isEmpty() && a_6.getText().isEmpty()
						&& a_7.getText().isEmpty() && a_8.getText().isEmpty() && a_9.getText().isEmpty()) {

				} else {
					try {
						String query = "Insert into Shirt (lmbai,seena,kemer,pait,hip,teera,glaa,baju,bs,Customerid,CustomerName,CustomerContact,CustomerAddress) values(?,?,?,?,?,?,?,?,?,?,?,?,?)";
						PreparedStatement pst = conn.prepareStatement(query);

						pst.setString(1, a_1.getText());
						pst.setString(2, a_2.getText());
						pst.setString(3, a_3.getText());
						pst.setString(4, a_4.getText());
						pst.setString(5, a_5.getText());
						pst.setString(6, a_6.getText());
						pst.setString(7, a_7.getText());
						pst.setString(8, a_8.getText());
						pst.setString(9, a_9.getText());
						pst.setString(10, en.getText());
						pst.setString(11, ec.getText());
						pst.setString(12, ed.getText());
						pst.setString(13, ef.getText());

						pst.execute();
						pst.close();

					} catch (Exception e) {
						e.printStackTrace();
					}
				}

				if (b1.getText().isEmpty() && b2.getText().isEmpty() && b3.getText().isEmpty() && b4.getText().isEmpty()
						&& b5.getText().isEmpty() && b6.getText().isEmpty() && b7.getText().isEmpty()) {
				} else {
					try {
						String query = "Insert into pent(lmbai,kemer,hip,gidri,pinjni,mori,putt,Customerid,CustomerName,CustomerContact,CustomerAddress) values(?,?,?,?,?,?,?,?,?,?,?)";
						PreparedStatement pst = conn.prepareStatement(query);

						pst.setString(1, b1.getText());
						pst.setString(2, b2.getText());
						pst.setString(3, b3.getText());
						pst.setString(4, b4.getText());
						pst.setString(5, b5.getText());
						pst.setString(6, b6.getText());
						pst.setString(7, b7.getText());
						pst.setString(8, en.getText());
						pst.setString(9, ec.getText());
						pst.setString(10, ed.getText());
						pst.setString(11, ef.getText());

						pst.execute();
						pst.close();

					} catch (Exception e) {
						e.printStackTrace();
					}
				}

				if (c1.getText().isEmpty() && c2.getText().isEmpty() && c3.getText().isEmpty() && c4.getText().isEmpty()
						&& c5.getText().isEmpty() && c6.getText().isEmpty() && c7.getText().isEmpty()
						&& c8.getText().isEmpty() && c9.getText().isEmpty()) {
				} else {
					try {
						String query = "Insert into Coat(lmbai,seena,kemer,pait,hip,teera,baju,dor,back,bs,bm,shoulder,Customerid,CustomerName,CustomerContact,CustomerAddress) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
						PreparedStatement pst = conn.prepareStatement(query);

						pst.setString(1, c1.getText());
						pst.setString(2, c2.getText());
						pst.setString(3, c3.getText());
						pst.setString(4, c4.getText());
						pst.setString(5, c5.getText());
						pst.setString(6, c6.getText());
						pst.setString(7, c7.getText());
						pst.setString(8, c8.getText());
						pst.setString(9, c9.getText());
						pst.setString(10, c7.getText());
						pst.setString(11, c8.getText());
						pst.setString(12, c9.getText());
						pst.setString(13, en.getText());
						pst.setString(14, ec.getText());
						pst.setString(15, ed.getText());
						pst.setString(16, ef.getText());

						pst.execute();
						pst.close();

					} catch (Exception e) {
						e.printStackTrace();
					}
				}

				if (d_1.getText().isEmpty() && d_2.getText().isEmpty() && d_3.getText().isEmpty()
						&& d_4.getText().isEmpty() && d_5.getText().isEmpty()) {
				} else {
					try {
						String query = "Insert into Jacket(lmbai,seena,kemer,hip,teera,Customerid,CustomerName,CustomerContact,CustomerAddress) values(?,?,?,?,?,?,?,?,?)";
						PreparedStatement pst = conn.prepareStatement(query);

						pst.setString(1, d_1.getText());
						pst.setString(2, d_2.getText());
						pst.setString(3, d_3.getText());
						pst.setString(4, d_4.getText());
						pst.setString(5, d_5.getText());
						pst.setString(6, en.getText());
						pst.setString(7, ec.getText());
						pst.setString(8, ed.getText());
						pst.setString(9, ef.getText());
						pst.execute();
						pst.close();

					} catch (Exception e) {
						e.printStackTrace();
					}
				}

				if (e_1.getText().isEmpty() && e_2.getText().isEmpty() && e_3.getText().isEmpty()
						&& e_4.getText().isEmpty() && e_5.getText().isEmpty() && e_6.getText().isEmpty()
						&& e_7.getText().isEmpty() && e_8.getText().isEmpty() && e_9.getText().isEmpty()) {
				} else {
					try {
						String query = "Insert into Kurta(lmbai,seena,kemer,pait,hip,teera,glaa,baju,bs,Customerid,CustomerName,CustomerContact,CustomerAddress) values(?,?,?,?,?,?,?,?,?,?,?,?,?)";
						PreparedStatement pst = conn.prepareStatement(query);

						pst.setString(1, e_1.getText());
						pst.setString(2, e_2.getText());
						pst.setString(3, e_3.getText());
						pst.setString(4, e_4.getText());
						pst.setString(5, e_5.getText());
						pst.setString(6, e_6.getText());
						pst.setString(7, e_7.getText());
						pst.setString(8, e_8.getText());
						pst.setString(9, e_9.getText());
						pst.setString(10, en.getText());
						pst.setString(11, ec.getText());
						pst.setString(12, ed.getText());
						pst.setString(13, ef.getText());

						pst.execute();
						pst.close();

					} catch (Exception e) {
						e.printStackTrace();
					}
				}

				if (f_1.getText().isEmpty() && f_2.getText().isEmpty() && f_3.getText().isEmpty()
						&& f_4.getText().isEmpty() && f_5.getText().isEmpty() && f_6.getText().isEmpty()
						&& f_7.getText().isEmpty()) {
				} else {
					try {
						String query = "Insert into Pjama(lmbai,kemer,hip,gidri,pinjni,mori,putt,Customerid,CustomerName,CustomerContact,CustomerAddress) values(?,?,?,?,?,?,?,?,?,?,?)";
						PreparedStatement pst = conn.prepareStatement(query);

						pst.setString(1, f_1.getText());
						pst.setString(2, f_2.getText());
						pst.setString(3, f_3.getText());
						pst.setString(4, f_4.getText());
						pst.setString(5, f_5.getText());
						pst.setString(6, f_6.getText());
						pst.setString(7, f_7.getText());
						pst.setString(8, en.getText());
						pst.setString(9, ec.getText());
						pst.setString(10, ed.getText());
						pst.setString(11, ef.getText());

						pst.execute();
						pst.close();

					} catch (Exception e) {
						e.printStackTrace();
					}
				}

				try {

					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
					String query = "select * from Shirt ";
					PreparedStatement statment = conn.prepareStatement(query);
					ResultSet rs = statment.executeQuery();
					table_34.setModel(DbUtils.resultSetToTableModel(rs));

					rs.close();
					statment.close();
				} catch (SQLException e) {

					JOptionPane.showMessageDialog(null, "My Error 2" + e);
				}

				try {

					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
					String query = "select * from pent ";
					PreparedStatement statment = conn.prepareStatement(query);
					ResultSet rs = statment.executeQuery();
					table_39.setModel(DbUtils.resultSetToTableModel(rs));

					rs.close();
					statment.close();
				} catch (SQLException e) {

					JOptionPane.showMessageDialog(null, "My Error 2" + e);
				}

				try {

					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
					String query = "select * from Coat ";
					PreparedStatement statment = conn.prepareStatement(query);
					ResultSet rs = statment.executeQuery();
					table_38.setModel(DbUtils.resultSetToTableModel(rs));

					rs.close();
					statment.close();
				} catch (SQLException e) {

					JOptionPane.showMessageDialog(null, "My Error 2" + e);
				}

				try {

					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
					String query = "select * from Jacket ";
					PreparedStatement statment = conn.prepareStatement(query);
					ResultSet rs = statment.executeQuery();
					table_36.setModel(DbUtils.resultSetToTableModel(rs));

					rs.close();
					statment.close();
				} catch (SQLException e) {

					JOptionPane.showMessageDialog(null, "My Error 2" + e);
				}

				try {

					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
					String query = "select * from Kurta ";
					PreparedStatement statment = conn.prepareStatement(query);
					ResultSet rs = statment.executeQuery();
					table_35.setModel(DbUtils.resultSetToTableModel(rs));

					rs.close();
					statment.close();
				} catch (SQLException e) {

					JOptionPane.showMessageDialog(null, "My Error 2" + e);
				}

				try {

					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
					String query = "select * from Pjama ";
					PreparedStatement statment = conn.prepareStatement(query);
					ResultSet rs = statment.executeQuery();
					table_37.setModel(DbUtils.resultSetToTableModel(rs));
					rs.close();
					statment.close();
				} catch (SQLException e) {

					JOptionPane.showMessageDialog(null, "My Error 2" + e);
				}

				try {

					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
					String query = "select * from Customer ";
					PreparedStatement statment = conn.prepareStatement(query);
					ResultSet rs = statment.executeQuery();
					table_4.setModel(DbUtils.resultSetToTableModel(rs));
					rs.close();
					statment.close();
				} catch (SQLException e) {

					e.printStackTrace();
				}

				JOptionPane.showMessageDialog(null, "Data Save");

				a_2.setText(null);
				a_1.setText(null);
				a_3.setText(null);
				a_4.setText(null);
				a_5.setText(null);
				a_6.setText(null);
				a_7.setText(null);
				a_8.setText(null);
				a_9.setText(null);

				b1.setText(null);
				b2.setText(null);
				b3.setText(null);
				b4.setText(null);
				b5.setText(null);
				b6.setText(null);
				b7.setText(null);

				c1.setText(null);
				c2.setText(null);
				c3.setText(null);
				c4.setText(null);
				c5.setText(null);
				c6.setText(null);
				c7.setText(null);
				c8.setText(null);
				c9.setText(null);
				c10.setText(null);
				c11.setText(null);
				c12.setText(null);

				d_1.setText(null);
				d_2.setText(null);
				d_3.setText(null);
				d_4.setText(null);
				d_5.setText(null);

				e_1.setText(null);
				e_2.setText(null);
				e_3.setText(null);
				e_4.setText(null);
				e_5.setText(null);
				e_6.setText(null);
				e_7.setText(null);
				e_8.setText(null);
				e_9.setText(null);

				f_1.setText(null);
				f_2.setText(null);
				f_3.setText(null);
				f_4.setText(null);
				f_5.setText(null);
				f_6.setText(null);
				f_7.setText(null);

				en.setText(null);
				ec.setText(null);
				ed.setText(null);
				ef.setText(null);

			}
		});

		btnSave01.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 59));
		btnSave01.setBounds(1579, 820, 187, 59);
		panel10.add(btnSave01);
		JButton btnCancel = new JButton(gifImage3gg);

		btnCancel.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent arg0) {
				a_2.setText(null);
				a_1.setText(null);
				a_3.setText(null);
				a_4.setText(null);
				a_5.setText(null);
				a_6.setText(null);
				a_7.setText(null);
				a_8.setText(null);
				a_9.setText(null);

				b1.setText(null);
				b2.setText(null);
				b3.setText(null);
				b4.setText(null);
				b5.setText(null);
				b6.setText(null);
				b7.setText(null);

				c1.setText(null);
				c2.setText(null);
				c3.setText(null);
				c4.setText(null);
				c5.setText(null);
				c6.setText(null);
				c7.setText(null);
				c8.setText(null);
				c9.setText(null);
				c10.setText(null);
				c11.setText(null);
				c12.setText(null);

				d_1.setText(null);
				d_2.setText(null);
				d_3.setText(null);
				d_4.setText(null);
				d_5.setText(null);

				e_1.setText(null);
				e_2.setText(null);
				e_3.setText(null);
				e_4.setText(null);
				e_5.setText(null);
				e_6.setText(null);
				e_7.setText(null);
				e_8.setText(null);
				e_9.setText(null);

				f_1.setText(null);
				f_2.setText(null);
				f_3.setText(null);
				f_4.setText(null);
				f_5.setText(null);
				f_6.setText(null);
				f_7.setText(null);

				en.setText(null);
				ec.setText(null);
				ed.setText(null);
				ef.setText(null);

			}
		});
		btnCancel.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 59));
		btnCancel.setBounds(1578, 911, 187, 59);
		panel10.add(btnCancel);

		JScrollPane scrollPane = new JScrollPane();
		scrollPane.setBounds(12, 233, 545, 785);
		panel10.add(scrollPane);

		table_1 = new JTable();
		table_1.addMouseListener(new MouseAdapter() {
			@Override
			public void mouseClicked(MouseEvent e) {

				table_1.setComponentPopupMenu(popupMenu_1);
			}
		});
		scrollPane.setViewportView(table_1);
	//	table_1.setModel(DbUtils.resultSetToTableModel(rs));

		t_01 = new JTextField();
		t_01.addKeyListener(new KeyAdapter() {
			@Override
			public void keyPressed(KeyEvent e) {

				if (e.getKeyCode() == KeyEvent.VK_ENTER) {
					if (t_01.getText().toString().isEmpty()) {
						JOptionPane.showMessageDialog(null, "h");
					}
				}

			}
		});
		t_01.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 30));
		t_01.setBounds(12, 163, 156, 42);
		panel10.add(t_01);
		t_01.setColumns(10);

		comboBox_01 = new JComboBox();
		comboBox_01.setModel(new DefaultComboBoxModel(
				new String[] { "Customer_id", "Customer_Name", "Customer_Contact", "Customer_Address" }));
		comboBox_01.setToolTipText("");
		comboBox_01.setBounds(12, 108, 156, 42);
		panel10.add(comboBox_01);
		btnSearch = new JButton(btnSearch1);

		btnSearch.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent arg0) {

				d1 = comboBox_01.getSelectedItem().toString();
				d2 = t_01.getText();

				if (d1.equals("Customer_id")) {
					try {
						String query = "Select * from Customer Where Customerid =  '" + d2 + "'  ";
						PreparedStatement pst = conn.prepareStatement(query);
						ResultSet rs = pst.executeQuery();
						table_1.setModel(DbUtils.resultSetToTableModel(rs));

					} catch (Exception e) {
						e.printStackTrace();
					}
				} else if (d1.equals("Customer_Name")) {
					try {
						String query = "Select * from Customer Where CustomerName =  '" + d2 + "'  ";
						PreparedStatement pst = conn.prepareStatement(query);
						ResultSet rs = pst.executeQuery();
						table_1.setModel(DbUtils.resultSetToTableModel(rs));

					} catch (Exception e) {
						e.printStackTrace();
					}
				} else if (d1.equals("Customer_Contact")) {
					try {
						String query = "Select * from Customer Where CustomerContact =  '" + d2 + "'  ";
						PreparedStatement pst = conn.prepareStatement(query);
						ResultSet rs = pst.executeQuery();
						table_1.setModel(DbUtils.resultSetToTableModel(rs));

					} catch (Exception e) {
						e.printStackTrace();
					}
				} else if (d1.equals("Customer_Address")) {
					try {
						String query = "Select * from Customer Where CustomerAddress =  '" + d2 + "'  ";
						PreparedStatement pst = conn.prepareStatement(query);
						ResultSet rs = pst.executeQuery();
						table_1.setModel(DbUtils.resultSetToTableModel(rs));

					} catch (Exception e) {
						e.printStackTrace();
					}
				}

			}
		});
		btnSearch.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 30));
		btnSearch.setBounds(192, 146, 187, 64);
		panel10.add(btnSearch);
		JButton btnBack = new JButton(gifImage13);
		btnBack.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 30));
		btnBack.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent arg0) {

				if (hk1 > 0) {
					panel9.setVisible(true);
					panel10.setVisible(false);
				} else {
					panel6.setVisible(true);
					panel10.setVisible(false);
				}

			}
		});
		btnBack.setBounds(12, 13, 120, 57);
		panel10.add(btnBack);

		JLabel lblJacket_1 = new JLabel("Jacket");
		lblJacket_1.setOpaque(true);
		lblJacket_1.setForeground(Color.RED);
		lblJacket_1.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 30));
		lblJacket_1.setBounds(601, 600, 102, 97);
		panel10.add(lblJacket_1);

		JLabel labael_17 = new JLabel("lmbai");
		labael_17.setOpaque(true);
		labael_17.setForeground(Color.BLACK);
		labael_17.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		labael_17.setBounds(738, 596, 90, 42);
		panel10.add(labael_17);

		JLabel lblSeena_1 = new JLabel("seena");
		lblSeena_1.setOpaque(true);
		lblSeena_1.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		lblSeena_1.setBounds(840, 596, 90, 42);
		panel10.add(lblSeena_1);

		JLabel lblKemer_1 = new JLabel("kemer");
		lblKemer_1.setOpaque(true);
		lblKemer_1.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		lblKemer_1.setAutoscrolls(true);
		lblKemer_1.setBounds(945, 600, 90, 42);
		panel10.add(lblKemer_1);

		JLabel lblHip_1 = new JLabel("hip");
		lblHip_1.setOpaque(true);
		lblHip_1.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		lblHip_1.setBounds(1047, 600, 90, 42);
		panel10.add(lblHip_1);

		JLabel lblBaju_1 = new JLabel("teera");
		lblBaju_1.setOpaque(true);
		lblBaju_1.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		lblBaju_1.setBounds(1149, 600, 90, 42);
		panel10.add(lblBaju_1);

		JLabel lblKurta_1 = new JLabel("Kurta");
		lblKurta_1.setOpaque(true);
		lblKurta_1.setForeground(Color.RED);
		lblKurta_1.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 30));
		lblKurta_1.setBounds(601, 732, 102, 97);
		panel10.add(lblKurta_1);

		JLabel label_28 = new JLabel("lmbai");
		label_28.setOpaque(true);
		label_28.setForeground(Color.BLACK);
		label_28.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		label_28.setBounds(758, 732, 70, 42);
		panel10.add(label_28);

		JLabel lblSeena_2 = new JLabel("seena");
		lblSeena_2.setOpaque(true);
		lblSeena_2.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		lblSeena_2.setBounds(850, 732, 70, 42);
		panel10.add(lblSeena_2);

		JLabel lblKemer_2 = new JLabel("kemer");
		lblKemer_2.setOpaque(true);
		lblKemer_2.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		lblKemer_2.setAutoscrolls(true);
		lblKemer_2.setBounds(939, 732, 70, 42);
		panel10.add(lblKemer_2);

		JLabel lblTeera = new JLabel("pait");
		lblTeera.setOpaque(true);
		lblTeera.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		lblTeera.setBounds(1021, 732, 70, 42);
		panel10.add(lblTeera);

		JLabel lblBaju_2 = new JLabel("hip");
		lblBaju_2.setOpaque(true);
		lblBaju_2.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		lblBaju_2.setBounds(1103, 732, 70, 42);
		panel10.add(lblBaju_2);

		JLabel lblGlaa = new JLabel("teera");
		lblGlaa.setOpaque(true);
		lblGlaa.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		lblGlaa.setBounds(1185, 732, 70, 42);
		panel10.add(lblGlaa);

		JLabel lblSaamanaa = new JLabel("glaa");
		lblSaamanaa.setOpaque(true);
		lblSaamanaa.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		lblSaamanaa.setBounds(1267, 732, 70, 42);
		panel10.add(lblSaamanaa);

		JLabel lblPjama_1 = new JLabel("Pjama");
		lblPjama_1.setOpaque(true);
		lblPjama_1.setForeground(Color.RED);
		lblPjama_1.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 30));
		lblPjama_1.setBounds(601, 875, 102, 97);
		panel10.add(lblPjama_1);

		JLabel label_36 = new JLabel("lmbai");
		label_36.setOpaque(true);
		label_36.setForeground(Color.BLACK);
		label_36.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		label_36.setBounds(738, 875, 90, 42);
		panel10.add(label_36);

		JLabel label_37 = new JLabel("kemer");
		label_37.setOpaque(true);
		label_37.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		label_37.setBounds(840, 875, 90, 42);
		panel10.add(label_37);

		JLabel label_38 = new JLabel("hip");
		label_38.setOpaque(true);
		label_38.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		label_38.setAutoscrolls(true);
		label_38.setBounds(945, 875, 90, 42);
		panel10.add(label_38);

		JLabel lblGidri = new JLabel("gidri");
		lblGidri.setOpaque(true);
		lblGidri.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		lblGidri.setBounds(1047, 875, 90, 42);
		panel10.add(lblGidri);

		JLabel lblPinjni = new JLabel("pinjni");
		lblPinjni.setOpaque(true);
		lblPinjni.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		lblPinjni.setBounds(1149, 875, 90, 42);
		panel10.add(lblPinjni);

		JLabel lblMori = new JLabel("mori");
		lblMori.setOpaque(true);
		lblMori.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		lblMori.setBounds(1247, 875, 90, 42);
		panel10.add(lblMori);

		JLabel lblPutt = new JLabel("putt");
		lblPutt.setOpaque(true);
		lblPutt.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		lblPutt.setBounds(1349, 875, 70, 42);
		panel10.add(lblPutt);

		JLabel lblCoat_1 = new JLabel("Coat");
		lblCoat_1.setOpaque(true);
		lblCoat_1.setForeground(Color.RED);
		lblCoat_1.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 30));
		lblCoat_1.setBounds(601, 438, 102, 97);
		panel10.add(lblCoat_1);

		JLabel label_44 = new JLabel("lmbai");
		label_44.setOpaque(true);
		label_44.setForeground(Color.BLACK);
		label_44.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		label_44.setBounds(743, 438, 90, 42);
		panel10.add(label_44);

		JLabel lblSeena = new JLabel("seena");
		lblSeena.setOpaque(true);
		lblSeena.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		lblSeena.setBounds(845, 438, 90, 42);
		panel10.add(lblSeena);

		JLabel lblKemer = new JLabel("kemer");
		lblKemer.setOpaque(true);
		lblKemer.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		lblKemer.setAutoscrolls(true);
		lblKemer.setBounds(950, 442, 90, 42);
		panel10.add(lblKemer);

		JLabel lblHip = new JLabel("pait");
		lblHip.setOpaque(true);
		lblHip.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		lblHip.setBounds(1052, 442, 90, 42);
		panel10.add(lblHip);

		JLabel lblBaju = new JLabel("hip");
		lblBaju.setOpaque(true);
		lblBaju.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		lblBaju.setBounds(1154, 442, 90, 42);
		panel10.add(lblBaju);

		JLabel lblAasteen = new JLabel("teera");
		lblAasteen.setOpaque(true);
		lblAasteen.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		lblAasteen.setBounds(1252, 442, 90, 42);
		panel10.add(lblAasteen);

		JLabel lblDor = new JLabel("baju");
		lblDor.setOpaque(true);
		lblDor.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		lblDor.setBounds(1354, 442, 70, 42);
		panel10.add(lblDor);

		JLabel lblBack = new JLabel("dor");
		lblBack.setOpaque(true);
		lblBack.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		lblBack.setBounds(1436, 442, 70, 42);
		panel10.add(lblBack);

		JLabel lblBs = new JLabel("back");
		lblBs.setOpaque(true);
		lblBs.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		lblBs.setBounds(1518, 442, 70, 42);
		panel10.add(lblBs);

		JLabel lblBs_1 = new JLabel("b.s");
		lblBs_1.setOpaque(true);
		lblBs_1.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		lblBs_1.setBounds(1600, 442, 70, 42);
		panel10.add(lblBs_1);

		JLabel lblBaju_3 = new JLabel("baju");
		lblBaju_3.setOpaque(true);
		lblBaju_3.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		lblBaju_3.setBounds(1349, 159, 70, 42);
		panel10.add(lblBaju_3);

		JLabel lblBs_2 = new JLabel("b.s");
		lblBs_2.setOpaque(true);
		lblBs_2.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		lblBs_2.setBounds(1436, 159, 70, 42);
		panel10.add(lblBs_2);

		JLabel lblBm = new JLabel("b.m");
		lblBm.setOpaque(true);
		lblBm.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		lblBm.setBounds(1682, 442, 70, 42);
		panel10.add(lblBm);

		JLabel lblSholder = new JLabel("shoulder");
		lblSholder.setOpaque(true);
		lblSholder.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		lblSholder.setBounds(1764, 442, 90, 42);
		panel10.add(lblSholder);

		JLabel lblBaju_4 = new JLabel("baju");
		lblBaju_4.setOpaque(true);
		lblBaju_4.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		lblBaju_4.setBounds(1349, 732, 70, 42);
		panel10.add(lblBaju_4);

		JLabel lblBs_3 = new JLabel("b.s");
		lblBs_3.setOpaque(true);
		lblBs_3.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 20));
		lblBs_3.setBounds(1436, 732, 70, 42);
		panel10.add(lblBs_3);

		JButton btnRefresh_1 = new JButton((Icon) null);
		btnRefresh_1.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent arg0) {

				try {

					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
					String query = "select * from Customer ";
					PreparedStatement statment = conn.prepareStatement(query);
					ResultSet rs = statment.executeQuery();
					table_1.setModel(DbUtils.resultSetToTableModel(rs));
					rs.close();
					statment.close();
				} catch (SQLException e) {

					e.printStackTrace();
				}

			}
		});
		btnRefresh_1.setText("Refresh");
		btnRefresh_1.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 30));
		btnRefresh_1.setBounds(392, 146, 161, 64);
		panel10.add(btnRefresh_1);

		JButton btnUpdate_1 = new JButton((Icon) null);
		btnUpdate_1.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {

				DefaultTableModel model = (DefaultTableModel) table_1.getModel();
				int nn = table_1.getSelectedRow();
				String hk = model.getValueAt(nn, 0).toString();

				try {
					String query = "UPDATE Customer SET Customerid = ?,CustomerName = ?,CustomerContact = ?,CustomerAddress = ? Where Customerid =  '"
							+ hk + "' ";
					PreparedStatement pst = conn.prepareStatement(query);

					pst.setString(1, en.getText());
					pst.setString(2, ec.getText());
					pst.setString(3, ed.getText());
					pst.setString(4, ef.getText());
					pst.executeUpdate();
					JOptionPane.showMessageDialog(null, "Data Updated !");
					pst.close();

				} catch (Exception e1) {
					JOptionPane.showMessageDialog(null, e1);
				}
				try {

					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
					String query = "select * from Customer ";
					PreparedStatement statment = conn.prepareStatement(query);
					ResultSet rs = statment.executeQuery();
					table_1.setModel(DbUtils.resultSetToTableModel(rs));
					rs.close();
					statment.close();
				} catch (SQLException e1) {

					e1.printStackTrace();
				}

			}
		});
		btnUpdate_1.setText("Update");
		btnUpdate_1.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 42));
		btnUpdate_1.setBounds(1682, 239, 187, 59);
		panel10.add(btnUpdate_1);
		JLabel lblNewLabel_newCust = new JLabel(gifImage2);
		lblNewLabel_newCust.setBounds(0, 0, screenSize.width, screenSize.height);
		panel10.add(lblNewLabel_newCust);

		panel9 = new JPanel();
		panel9.setBackground(new Color(102, 0, 0));
		panel9.setBounds(0, 0, screenSize.width, screenSize.height);
		f1.getContentPane().add(panel9);
		panel9.setLayout(null);
		panel9.setVisible(false);

		ImageIcon gifImage3hh = new ImageIcon(this.getClass().getResource("/new c bt.jpg"));
		JButton new_Customer = new JButton(gifImage3hh);
		new_Customer.setContentAreaFilled(false);
		new_Customer.setHideActionText(true);
		new_Customer.setOpaque(false);
		new_Customer.setBorderPainted(false);

		new_Customer.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {

				if (l1 == 1) {
					hk1 = 1;
					panel10.setVisible(true);
					panel9.setVisible(false);
				} else {
					hk1 = 0;
					panel10.setVisible(true);
					panel9.setVisible(false);
				}

			}
		});
		new_Customer.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 16));
		new_Customer.setBounds(258, 205, 217, 135);
		panel9.add(new_Customer);

		ImageIcon gifImage3hhh = new ImageIcon(this.getClass().getResource("/old c bt.jpg"));
		JButton OldCustomer = new JButton(gifImage3hhh);
		OldCustomer.setBorderPainted(false);

		OldCustomer.setOpaque(false);
		OldCustomer.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {

				if (l2 == 1) {
					hk2 = 1;
					panel9.setVisible(false);
					panel11.setVisible(true);

				} else {
					hk2 = 0;
					panel9.setVisible(false);
					panel11.setVisible(true);

				}

			}
		});
		OldCustomer.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 16));
		OldCustomer.setBounds(541, 205, 223, 135);
		panel9.add(OldCustomer);

		ImageIcon gifImage3iii = new ImageIcon(this.getClass().getResource("/deliver bt.jpg"));
		JButton Deliverd = new JButton(gifImage3iii);
		Deliverd.setBorderPainted(false);
		Deliverd.setOpaque(false);
		Deliverd.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {

				if (l3 == 1) {
					hk3 = 1;
					panel9.setVisible(false);
					panel12.setVisible(true);

				} else {
					hk3 = 0;
					panel9.setVisible(false);
					panel12.setVisible(true);

				}

			}
		});
		Deliverd.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 16));
		Deliverd.setBounds(816, 205, 217, 135);
		panel9.add(Deliverd);

		shirtSwitch();
		pentSwitch();
		coatSwitch();
		jacketSwitch();
		kurtaSwitch();
		pjamaSwitch();

		ImageIcon gifImage3jjj = new ImageIcon(this.getClass().getResource("/in work.jpg"));
		JButton InWorking = new JButton(gifImage3jjj);
		InWorking.setContentAreaFilled(false);
		InWorking.setBorderPainted(false);
		InWorking.setOpaque(false);
		InWorking.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {

				if (l4 == 1) {
					hk4 = 1;
					panel9.setVisible(false);
					panel4.setVisible(true);

				} else {
					hk4 = 0;
					panel9.setVisible(false);
					panel4.setVisible(true);

				}

				try {

					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
					String query = "select * from Shirt ";
					PreparedStatement statment = conn.prepareStatement(query);
					ResultSet rs = statment.executeQuery();
					table_34.setModel(DbUtils.resultSetToTableModel(rs));

					rs.close();
					statment.close();
				} catch (SQLException e1) {

					JOptionPane.showMessageDialog(null, "My Error 2" + e1);
				}

				try {

					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
					String query = "select * from pent ";
					PreparedStatement statment = conn.prepareStatement(query);
					ResultSet rs = statment.executeQuery();
					table_39.setModel(DbUtils.resultSetToTableModel(rs));

					rs.close();
					statment.close();
				} catch (SQLException e1) {

					JOptionPane.showMessageDialog(null, "My Error 2" + e1);
				}

				try {

					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
					String query = "select * from Coat ";
					PreparedStatement statment = conn.prepareStatement(query);
					ResultSet rs = statment.executeQuery();
					table_38.setModel(DbUtils.resultSetToTableModel(rs));

					rs.close();
					statment.close();
				} catch (SQLException e1) {

					JOptionPane.showMessageDialog(null, "My Error 2" + e1);
				}

				try {

					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
					String query = "select * from Jacket ";
					PreparedStatement statment = conn.prepareStatement(query);
					ResultSet rs = statment.executeQuery();
					table_36.setModel(DbUtils.resultSetToTableModel(rs));

					rs.close();
					statment.close();
				} catch (SQLException e1) {

					JOptionPane.showMessageDialog(null, "My Error 2" + e1);
				}

				try {

					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
					String query = "select * from Kurta ";
					PreparedStatement statment = conn.prepareStatement(query);
					ResultSet rs = statment.executeQuery();
					table_35.setModel(DbUtils.resultSetToTableModel(rs));

					rs.close();
					statment.close();
				} catch (SQLException e1) {

					JOptionPane.showMessageDialog(null, "My Error 2" + e1);
				}

				try {

					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
					String query = "select * from Pjama ";
					PreparedStatement statment = conn.prepareStatement(query);
					ResultSet rs = statment.executeQuery();
					table_37.setModel(DbUtils.resultSetToTableModel(rs));
					rs.close();
					statment.close();
				} catch (SQLException e1) {

					JOptionPane.showMessageDialog(null, "My Error 2" + e1);
				}

			}
		});
		InWorking.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 16));
		InWorking.setBounds(244, 431, 231, 135);
		panel9.add(InWorking);

		ImageIcon gifImage3qaz = new ImageIcon(this.getClass().getResource("/employe.jpg"));
		JButton Employee = new JButton(gifImage3qaz);
		Employee.setBorderPainted(false);

		Employee.setOpaque(false);
		Employee.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {

				panel9.setVisible(false);
				panel14.setVisible(true);
			}
		});

		ImageIcon gifImage3kkkk = new ImageIcon(this.getClass().getResource("/pending pay..jpg"));
		JButton pending_payments = new JButton(gifImage3kkkk);
		pending_payments.setBorderPainted(false);

		pending_payments.setOpaque(false);
		pending_payments.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {

				panel9.setVisible(false);
				panel24.setVisible(true);
			}
		});
		pending_payments.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 16));
		pending_payments.setBounds(541, 431, 223, 135);
		panel9.add(pending_payments);
		Employee.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 16));
		Employee.setBounds(547, 664, 217, 135);
		panel9.add(Employee);

		ImageIcon gifImage3qq = new ImageIcon(this.getClass().getResource("/new order.jpg"));
		JButton New_order = new JButton(gifImage3qq);
		New_order.setBorderPainted(false);

		New_order.setOpaque(false);
		New_order.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {

				if (l5 == 1) {
					hk5 = 1;
					panel9.setVisible(false);
					panel17.setVisible(true);

				} else {
					hk5 = 0;
					panel9.setVisible(false);
					panel17.setVisible(true);

				}
			}
		});
		New_order.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 16));
		New_order.setBounds(816, 431, 229, 135);
		panel9.add(New_order);

		ImageIcon gifImage3zxs = new ImageIcon(this.getClass().getResource("/del expen.jpg"));
		JButton Daily_expensive = new JButton(gifImage3zxs);
		Daily_expensive.setBorderPainted(false);

		Daily_expensive.setOpaque(false);
		Daily_expensive.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {

				panel9.setVisible(false);
				panel25.setVisible(true);
			}
		});
		Daily_expensive.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 16));
		Daily_expensive.setBounds(829, 664, 217, 135);
		panel9.add(Daily_expensive);

		ImageIcon gifImage31zzqa = new ImageIcon(this.getClass().getResource("/admin.jpg"));
		JButton button_8 = new JButton(gifImage31zzqa);
		button_8.setBorderPainted(false);

		button_8.setOpaque(false);
		button_8.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {

				panel9.setVisible(false);
				panel15.setVisible(true);

				try {

					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
					String query = "select * from Trailor ";
					PreparedStatement statment = conn.prepareStatement(query);
					ResultSet rs = statment.executeQuery();
					table_10.setModel(DbUtils.resultSetToTableModel(rs));

					rs.close();
					statment.close();
				} catch (SQLException e1) {

					JOptionPane.showMessageDialog(null, "My Error 2" + e1);
				}
			}
		});
		button_8.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 16));
		button_8.setBounds(559, 894, 217, 135);
		panel9.add(button_8);

		ImageIcon gifImage3we = new ImageIcon(this.getClass().getResource("/pending work.jpg"));
		JButton PendingWork = new JButton(gifImage3we);
		PendingWork.setBorderPainted(false);

		PendingWork.setOpaque(false);
		PendingWork.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {

				if (l6 == 1) {
					hk6 = 1;
					panel27.setVisible(true);
					panel9.setVisible(false);
				} else {
					hk6 = 0;
					panel27.setVisible(true);
					panel9.setVisible(false);
				}

			}
		});
		PendingWork.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 16));
		PendingWork.setBounds(244, 664, 226, 135);
		panel9.add(PendingWork);

		JSeparator separatoor = new JSeparator();
		separatoor.setOrientation(SwingConstants.VERTICAL);
		separatoor.setBounds(1270, 0, 43, 1037);
		panel9.add(separatoor);

		passwordField = new JPasswordField();
		passwordField.setBounds(1566, 339, 223, 54);
		panel9.add(passwordField);

		JLabel lblNewLabell_1 = new JLabel("Add Employee");
		lblNewLabell_1.setForeground(Color.WHITE);
		lblNewLabell_1.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 60));
		lblNewLabell_1.setBounds(1331, 13, 379, 63);
		panel9.add(lblNewLabell_1);

		JLabel lblUsername_3 = new JLabel("UserName");
		lblUsername_3.setForeground(Color.WHITE);
		lblUsername_3.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 39));
		lblUsername_3.setBounds(1302, 229, 182, 52);
		panel9.add(lblUsername_3);

		JLabel lbllPassword = new JLabel("Password");
		lbllPassword.setForeground(Color.WHITE);
		lbllPassword.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 39));
		lbllPassword.setBounds(1302, 339, 182, 52);
		panel9.add(lbllPassword);

		textField_23 = new JTextField();
		textField_23.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 24));
		textField_23.setBounds(1566, 227, 223, 54);
		panel9.add(textField_23);
		textField_23.setColumns(10);

		ImageIcon log2 = new ImageIcon(this.getClass().getResource("/log in but..jpg"));
		JButton btnNewButtonn_1 = new JButton(log2);
		btnNewButtonn_1.setBorderPainted(false);
		btnNewButtonn_1.setForeground(Color.RED);
		btnNewButtonn_1.setContentAreaFilled(false);
		btnNewButtonn_1.setOpaque(false);
		btnNewButtonn_1.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent arg0) {

				try {
					String query = "Insert into Trailor(UserName,Password,User) values(?,?,?)";
					PreparedStatement pst = conn.prepareStatement(query);
					pst.setString(1, textField_23.getText());
					pst.setString(2, passwordField.getText());
					pst.setString(3, "User");

					pst.execute();
					JOptionPane.showMessageDialog(null, "Data Saved ! ");
					pst.close();

				} catch (Exception e1) {
					JOptionPane.showMessageDialog(null, "The error in saving data : " + e1);
				}

				panel1.setVisible(true);
				panel9.setVisible(false);
			}
		});
		btnNewButtonn_1.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 54));
		btnNewButtonn_1.setBounds(1419, 488, 130, 42);
		panel9.add(btnNewButtonn_1);

		ImageIcon gifImage14 = new ImageIcon(this.getClass().getResource("/back.jpg"));
		JButton btnBackkk = new JButton(gifImage14);
		btnBackkk.setContentAreaFilled(false);
		btnBackkk.setOpaque(false);
		btnBackkk.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent arg0) {

				l0 = 0;
				l1 = 0;
				l2 = 0;
				l3 = 0;
				l4 = 0;
				l5 = 0;
				l6 = 0;

				hk1 = 0;
				hk2 = 0;
				hk3 = 0;
				hk4 = 0;
				hk5 = 0;
				hk6 = 0;

				panel9.setVisible(false);
				panel1.setVisible(true);

			}
		});
		btnBackkk.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 16));
		btnBackkk.setBounds(12, 13, 120, 57);
		panel9.add(btnBackkk);

		ImageIcon gifImage1 = new ImageIcon(this.getClass().getResource("/2nd page.jpg"));
		JLabel lblNewLabel_0101 = new JLabel(gifImage1);
		lblNewLabel_0101.setBackground(Color.RED);
		lblNewLabel_0101.setForeground(Color.RED);
		lblNewLabel_0101.setBounds(0, 0, 1932, 1080);
		panel9.add(lblNewLabel_0101);

		JComboBox comboBox1111 = new JComboBox();
		comboBox1111.setModel(new DefaultComboBoxModel(new String[] { "1=What is your Nickname ?",
				"2=What is your first school ?", "3=What is your Mother's name ?" }));
		comboBox1111.setBounds(401, 244, 276, 46);
		panel2.add(comboBox1111);

		ImageIcon workimage = new ImageIcon(this.getClass().getResource("/5th page.jpg"));
		JLabel lblNewLabel_inworking = new JLabel(workimage);
		lblNewLabel_inworking.setBounds(0, 0, screenSize.width, screenSize.height);
		panel14.add(lblNewLabel_inworking);

		panel5 = new JPanel();
		panel5.setBackground(new Color(102, 0, 0));
		panel5.setBounds(0, 0, screenSize.width, screenSize.height);
		f1.getContentPane().add(panel5);
		panel5.setVisible(false);
		panel5.setLayout(null);

		ImageIcon g3 = new ImageIcon(this.getClass().getResource("/back.jpg"));
		JButton btnBackToButton55505 = new JButton(g3);
		btnBackToButton55505.setBounds(12, 13, 120, 57);
		btnBackToButton55505.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {

				panel5.setVisible(false);
				panel1.setVisible(true);
			}

		});
		panel5.add(btnBackToButton55505);

		JLabel lblNewLabel_41 = new JLabel("Name");
		lblNewLabel_41.setForeground(Color.WHITE);
		lblNewLabel_41.setFont(new Font("Tahoma", Font.BOLD | Font.ITALIC, 24));
		lblNewLabel_41.setBounds(198, 45, 105, 51);
		panel5.add(lblNewLabel_41);

		JLabel lblNewLabel_51 = new JLabel("UserName");
		lblNewLabel_51.setForeground(Color.WHITE);
		lblNewLabel_51.setFont(new Font("Tahoma", Font.BOLD | Font.ITALIC, 24));
		lblNewLabel_51.setBounds(184, 131, 142, 40);
		panel5.add(lblNewLabel_51);

		JComboBox comboBox11 = new JComboBox();
		comboBox11.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent arg0) {

				s7 = comboBox.getSelectedItem().toString();
				JOptionPane.showMessageDialog(null, s7);
			}
		});

		comboBox11.setModel(new DefaultComboBoxModel(new String[] { "1=What is your Nickname ?",
				"2=What is your first school ?", "3=What is your Mother's name ?" }));
		comboBox11.setBounds(360, 241, 252, 51);
		panel5.add(comboBox11);

		JLabel lblNewLabel_61 = new JLabel("Question");
		lblNewLabel_61.setForeground(Color.WHITE);
		lblNewLabel_61.setFont(new Font("Tahoma", Font.BOLD | Font.ITALIC, 24));
		lblNewLabel_61.setBounds(184, 241, 136, 40);
		panel5.add(lblNewLabel_61);

		textField_2 = new JTextField();
		textField_2.setFont(new Font("Tahoma", Font.BOLD | Font.ITALIC, 24));
		textField_2.setBounds(360, 45, 252, 51);
		panel5.add(textField_2);
		textField_2.setColumns(10);

		textField_3 = new JTextField();
		textField_3.setFont(new Font("Tahoma", Font.BOLD | Font.ITALIC, 24));
		textField_3.setBounds(360, 126, 252, 51);
		panel5.add(textField_3);
		textField_3.setColumns(10);

		JLabel lblNewLabel_81 = new JLabel("Answer");
		lblNewLabel_81.setForeground(Color.WHITE);
		lblNewLabel_81.setFont(new Font("Tahoma", Font.BOLD | Font.ITALIC, 26));
		lblNewLabel_81.setBounds(184, 338, 120, 51);
		panel5.add(lblNewLabel_81);

		textField_4 = new JTextField();
		textField_4.setFont(new Font("Tahoma", Font.BOLD | Font.ITALIC, 24));
		textField_4.setBounds(360, 338, 252, 51);
		panel5.add(textField_4);
		textField_4.setColumns(10);

		JButton btnNewButton_3 = new JButton("Proceed");
		btnNewButton_3.setForeground(Color.WHITE);
		btnNewButton_3.setBackground(new Color(153, 0, 0));
		btnNewButton_3.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent arg0) {

				if (textField_2.getText().isEmpty() || textField_3.getText().isEmpty()
						|| textField_4.getText().isEmpty()) {
					JOptionPane.showMessageDialog(null, "Please fill all field");
				}

				else {

					s5 = textField_2.getText();
					s6 = textField_3.getText();
					s7 = comboBox.getSelectedItem().toString();
					s8 = textField_4.getText();

					un = s5;
					n = s6;
					q = s7;
					a = s8;

					panel8.setVisible(true);
					panel5.setVisible(false);

				}

			}

		});
		btnNewButton_3.setFont(new Font("Tahoma", Font.BOLD | Font.ITALIC, 60));
		btnNewButton_3.setBounds(93, 469, 419, 102);
		panel5.add(btnNewButton_3);
		panel9.setVisible(false);

		ImageIcon gifImageza3e = new ImageIcon(this.getClass().getResource("/background without img.jpg"));
		JLabel lblNewLabel_forgot = new JLabel(gifImageza3e);
		lblNewLabel_forgot.setBounds(0, 0, screenSize.width, screenSize.height);
		panel5.add(lblNewLabel_forgot);

		panel7 = new JPanel();
		panel7.setBackground(new Color(102, 0, 0));
		panel7.setBounds(0, 0, screenSize.width, screenSize.height);
		f1.getContentPane().add(panel7);
		panel7.setVisible(false);
		panel7.setLayout(null);

		ImageIcon g1 = new ImageIcon(this.getClass().getResource("/back.jpg"));
		JButton btnBackToButton003 = new JButton(g1);
		btnBackToButton003.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 30));
		btnBackToButton003.setBounds(12, 13, 120, 57);
		btnBackToButton003.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {

				panel7.setVisible(false);
				panel4.setVisible(true);

			}

		});
		panel7.add(btnBackToButton003);

		JLabel lblUsername_2 = new JLabel("UserName");
		lblUsername_2.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 42));
		lblUsername_2.setBounds(203, 572, 195, 61);
		panel7.add(lblUsername_2);

		JLabel labeel_9 = new JLabel("->");
		labeel_9.setFont(new Font("Tahoma", Font.BOLD | Font.ITALIC, 30));
		labeel_9.setBounds(422, 575, 56, 61);
		panel7.add(labeel_9);

		textField_21 = new JTextField();
		textField_21.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 24));
		textField_21.setBounds(510, 572, 269, 68);
		panel7.add(textField_21);
		textField_21.setColumns(10);

		JLabel lbblPassword = new JLabel("Password");
		lbblPassword.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 42));
		lbblPassword.setBounds(203, 702, 195, 61);
		panel7.add(lbblPassword);

		JLabel labbel_18 = new JLabel("->");
		labbel_18.setFont(new Font("Tahoma", Font.BOLD | Font.ITALIC, 30));
		labbel_18.setBounds(422, 705, 56, 61);
		panel7.add(labbel_18);

		textField_22 = new JTextField();
		textField_22.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 24));
		textField_22.setColumns(10);
		textField_22.setBounds(510, 702, 269, 68);
		panel7.add(textField_22);

		JButton btnSignIn = new JButton("Sign in");
		btnSignIn.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 60));
		btnSignIn.setBounds(971, 614, 228, 126);
		panel7.add(btnSignIn);

		panel8 = new JPanel();
		panel8.setBackground(new Color(102, 0, 0));
		panel8.setBounds(0, 0, screenSize.width, screenSize.height);
		f1.getContentPane().add(panel8);
		panel8.setVisible(false);
		panel8.setLayout(null);

		JLabel lblNewLabel_0007 = new JLabel("New Password");
		lblNewLabel_0007.setFont(new Font("Tahoma", Font.BOLD | Font.ITALIC, 24));
		lblNewLabel_0007.setBounds(61, 57, 196, 49);
		panel8.add(lblNewLabel_0007);

		JLabel lblConfirmPass = new JLabel("Confirm Password");
		lblConfirmPass.setFont(new Font("Tahoma", Font.BOLD | Font.ITALIC, 24));
		lblConfirmPass.setBounds(61, 168, 224, 73);
		panel8.add(lblConfirmPass);

		pass = new JTextField();
		pass.setFont(new Font("Tahoma", Font.BOLD | Font.ITALIC, 24));
		pass.setBounds(339, 64, 273, 42);
		panel8.add(pass);
		pass.setColumns(10);

		pass1 = new JTextField();
		pass1.setFont(new Font("Tahoma", Font.BOLD | Font.ITALIC, 24));
		pass1.setBounds(339, 168, 273, 49);
		panel8.add(pass1);
		pass1.setColumns(10);

		JButton btnBackToButton0_4 = new JButton("Set Password");
		btnBackToButton0_4.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 24));
		btnBackToButton0_4.setBounds(93, 469, 419, 102);
		btnBackToButton0_4.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {

				s13 = pass.getText();
				s14 = pass1.getText();

				if (s13.isEmpty() || s14.isEmpty()) {
					JOptionPane.showMessageDialog(null, "Please fill all fields");
				}

				else {
					try {
						String query = "UPDATE Trailor SET Password = ? Where UserName =  '" + n + "' ";
						PreparedStatement pst = conn.prepareStatement(query);

						if (s13.equals(s14)) {
							pst.setString(1, pass.getText());
							pst.executeUpdate();
							JOptionPane.showMessageDialog(null, "Data Updated !");
							pst.close();

							panel1.setVisible(true);
							panel8.setVisible(false);
						}

						else {
							JOptionPane.showMessageDialog(null, "Password Missmatch");
						}
					} catch (Exception e1) {
						JOptionPane.showMessageDialog(null, e1);
					}

				}
			}
		});
		panel8.add(btnBackToButton0_4);

		ImageIcon gifImageza3eaz = new ImageIcon(this.getClass().getResource("/background without img.jpg"));
		JLabel lblNewLabel_forgotaz = new JLabel(gifImageza3eaz);
		lblNewLabel_forgotaz.setBounds(0, 0, screenSize.width, screenSize.height);
		panel8.add(lblNewLabel_forgotaz);

		panel22 = new JPanel();
		panel22.setBackground(new Color(102, 0, 0));
		panel22.setBounds(0, 0, screenSize.width, screenSize.height);
		f1.getContentPane().add(panel22);
		panel22.setVisible(false);
		panel22.setLayout(null);

		JLabel lblNewPassword = new JLabel("New Password");
		lblNewPassword.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 30));
		lblNewPassword.setBounds(250, 76, 195, 74);
		panel22.add(lblNewPassword);

		JLabel lblConfirmPassword = new JLabel("Confirm Password");
		lblConfirmPassword.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 30));
		lblConfirmPassword.setBounds(250, 193, 240, 74);
		panel22.add(lblConfirmPassword);

		JLabel label__4 = new JLabel("->");
		label__4.setFont(new Font("Tahoma", Font.BOLD | Font.ITALIC, 30));
		label__4.setBounds(576, 90, 56, 42);
		panel22.add(label__4);

		JLabel label_7 = new JLabel("->");
		label_7.setFont(new Font("Tahoma", Font.BOLD | Font.ITALIC, 30));
		label_7.setBounds(576, 209, 56, 42);
		panel22.add(label_7);

		textField_8 = new JTextField();
		textField_8.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 24));
		textField_8.setBounds(721, 90, 195, 53);
		panel22.add(textField_8);
		textField_8.setColumns(10);

		textField_9 = new JTextField();
		textField_9.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 24));
		textField_9.setColumns(10);
		textField_9.setBounds(721, 193, 195, 53);
		panel22.add(textField_9);

		JButton btnProceed0 = new JButton("Proceed");
		btnProceed0.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 45));
		btnProceed0.setBounds(514, 352, 195, 53);
		btnBackToButton0_4.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {

				w9 = textField_8.getText();
				w10 = textField_9.getText();
				try {
					String query = "UPDATE Trailor SET Password = ? Where UserName =  '" + qw2 + "' ";
					PreparedStatement pst = conn.prepareStatement(query);

					if (w9.equals(w10)) {
						pst.setString(1, textField_8.getText());
						pst.executeUpdate();
						pst.close();

						panel1.setVisible(true);
						panel22.setVisible(false);
					}

					else {
						JOptionPane.showMessageDialog(null, "Password Missmatch");

					}
				} catch (Exception e1) {
					JOptionPane.showMessageDialog(null, e1);
				}

			}

		});
		panel22.add(btnProceed0);

		panel23 = new JPanel();
		panel23.setBackground(new Color(102, 0, 0));
		panel23.setBounds(0, 0, screenSize.width, screenSize.height);
		f1.getContentPane().add(panel23);
		panel23.setVisible(false);
		panel23.setLayout(null);

		ImageIcon g2 = new ImageIcon(this.getClass().getResource("/back.jpg"));
		JButton btnBaack = new JButton(g2);
		btnBaack.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 21));
		btnBaack.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent arg0) {

				panel23.setVisible(false);
				panel9.setVisible(true);

			}
		});
		btnBaack.setBounds(12, 13, 120, 57);
		panel23.add(btnBaack);

		JButton btnRecovery = new JButton("Restore");
		btnRecovery.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent arg0) {

				JFileChooser chooser = new JFileChooser();
				chooser.setCurrentDirectory(new java.io.File("C:\\"));
				chooser.setDialogTitle(" Select Backup_Trailor_Data folder");

				chooser.setFileSelectionMode(JFileChooser.DIRECTORIES_ONLY);
				// disable the "All files" option.
				chooser.setAcceptAllFileFilterUsed(false);
				if (chooser.showOpenDialog(null) == JFileChooser.APPROVE_OPTION) {
					Path target1 = Paths.get(System.getProperty("user.dir") + "\\Trailor.sqlite");
					Path target = Paths.get(chooser.getSelectedFile() + "\\Trailor.sqlite");
					if (!chooser.getSelectedFile().getName().equals("Backup_Trailor_Data")) {
						JOptionPane.showMessageDialog(null, "it is not Backup folder ,choose Backup_Trailor folder");
					} else if (Files.notExists(target)) {
						JOptionPane.showMessageDialog(null, "your Backup folder will be missing some file");
					} else if (Files.exists(target1, LinkOption.NOFOLLOW_LINKS)) {
						try {
							if (Files.size(target) < 500968) {
								JOptionPane.showMessageDialog(null, "Backup file missing or cruppeted");

							} else {
								int i = JOptionPane.showConfirmDialog(null,
										"Are you sure to restore at Backup this will cause your current data lost ",
										"Select an option", JOptionPane.YES_NO_OPTION, JOptionPane.WARNING_MESSAGE);
								if (i == 0) {
									try {
										conn.close();
									} catch (SQLException e1) {
										// TODO Auto-generated catch block

									}
									try {
										Files.copy(target, target1, StandardCopyOption.REPLACE_EXISTING);
									} catch (IOException e1) {
										// TODO Auto-generated catch block
										JOptionPane.showMessageDialog(null, e1);

									}
									try {
										JOptionPane.showMessageDialog(null,
												"Restore at " + Files.getLastModifiedTime(target) + " sucessfully");
										Window frame = null;
										frame.dispose();
										Trailor.main(null);
									} catch (Exception e11) {

									}

								}
							}
						} catch (HeadlessException e1) {
							// TODO Auto-generated catch block
							e1.printStackTrace();
						} catch (IOException e1) {
							// TODO Auto-generated catch block
							e1.printStackTrace();
						}
					}
				}

			}
		});
		btnRecovery.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 30));
		btnRecovery.setBounds(522, 514, 167, 68);
		panel23.add(btnRecovery);

		JButton btnBackup = new JButton("Backup");
		btnBackup.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent arg0) {

				JFileChooser chooser = new JFileChooser();
				chooser.setCurrentDirectory(new java.io.File("C:\\"));
				chooser.setDialogTitle(" Select Backup Directory");
				chooser.setFileSelectionMode(JFileChooser.DIRECTORIES_ONLY);
				chooser.setAcceptAllFileFilterUsed(false);
				if (chooser.showSaveDialog(null) == JFileChooser.APPROVE_OPTION) {
					Path file = Paths.get(System.getProperty("user.dir") + "\\Trailor.sqlite");
					Path target1 = Paths.get(chooser.getSelectedFile() + "\\Backup_Trailor_Data");
					Path target = Paths.get(target1 + "\\Trailor.sqlite");
					if (Files.exists(target, LinkOption.NOFOLLOW_LINKS)) {
						int i = JOptionPane.showConfirmDialog(null,
								"There is alerady have Backup at this location if you want overwrite the Backup,click yes,othervise change the directory...",
								"Select an option", JOptionPane.YES_NO_OPTION, JOptionPane.WARNING_MESSAGE);
						if (i == 0) {
							try {
								Formatter n = new Formatter(target1 + "\\Backup_Discription.txt");
								n.format("Last Overwrite date is " + LocalDate.now() + ".", "");
								n.flush();
								n.close();
							} catch (FileNotFoundException x) {
								x.printStackTrace();
							}

							try {
								Files.copy(file, target, StandardCopyOption.REPLACE_EXISTING);
							} catch (IOException e1) {
							}
							JOptionPane.showMessageDialog(null, "Backup sucessfully");
						} else {
							Backupalert();
						}
					} else {
						try {
							Files.createDirectory(target1);
						} catch (IOException e2) {
							e2.printStackTrace();
						}
						try {
							Formatter n = new Formatter(target1 + "\\Backup_Discription.txt");
							n.format(" backup Created date is " + LocalDate.now() + ".", "");
							n.flush();
							n.close();
						} catch (FileNotFoundException c) {
							// TODO Auto-generated catch block
							c.printStackTrace();
						}
						try {
							Files.copy(file, target, StandardCopyOption.COPY_ATTRIBUTES);

						} catch (IOException e1) {

						}
						JOptionPane.showMessageDialog(null, "Backup sucessfully");

					}
				}

			}

		});
		btnBackup.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 30));
		btnBackup.setBounds(768, 514, 167, 68);
		panel23.add(btnBackup);

		JScrollPane scrollPanee_2 = new JScrollPane();
		scrollPanee_2.setBounds(217, 53, 744, 412);
		panel23.add(scrollPanee_2);

		table_10 = new JTable();
		try {

			conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
			String query = "select * from Trailor ";
			PreparedStatement statment = conn.prepareStatement(query);
			ResultSet rs = statment.executeQuery();
			table_10.setModel(DbUtils.resultSetToTableModel(rs));

			rs.close();
			statment.close();
		} catch (SQLException e) {

			JOptionPane.showMessageDialog(null, "My Error 2" + e);
		}

		scrollPanee_2.setViewportView(table_10);

		ImageIcon gifImage3btnz11 = new ImageIcon(this.getClass().getResource("/background without img.jpg"));
		JLabel lblNewLabeina = new JLabel(gifImage3btnz11);

		lblNewLabeina.setBounds(0, 0, screenSize.width, screenSize.height);
		panel23.add(lblNewLabeina);

		panel24 = new JPanel();
		panel24.setBackground(new Color(102, 0, 0));
		panel24.setBounds(0, 0, screenSize.width, screenSize.height);
		f1.getContentPane().add(panel24);
		panel24.setVisible(false);
		panel24.setLayout(null);

		JLabel lblUsername_1 = new JLabel("UserName");
		lblUsername_1.setForeground(Color.WHITE);
		lblUsername_1.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 30));
		lblUsername_1.setBounds(142, 167, 149, 50);
		panel24.add(lblUsername_1);

		JLabel lblPasswordd = new JLabel("Password");
		lblPasswordd.setForeground(Color.WHITE);
		lblPasswordd.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 30));
		lblPasswordd.setBounds(142, 266, 149, 50);
		panel24.add(lblPasswordd);

		textField_10 = new JTextField();
		textField_10.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 20));
		textField_10.setBounds(427, 167, 209, 50);
		panel24.add(textField_10);
		textField_10.setColumns(10);

		ImageIcon gifImage3btn1 = new ImageIcon(this.getClass().getResource("/log in but..jpg"));
		JButton btnSignin_01 = new JButton(gifImage3btn1);
		btnSignin_01.setForeground(new Color(102, 51, 51));

		btnSignin_01.addKeyListener(new KeyAdapter() {
			@Override
			public void keyPressed(KeyEvent arg0) {

			}
		});
		btnSignin_01.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent arg0) {

				wt1 = textField_10.getText();
				wt2 = passwordField_1.getText();
				wtx3 = "admin";
				try {

					String query = "Select * from Trailor Where UserName =  '" + wt1 + "'  ";
					PreparedStatement pst = conn.prepareStatement(query);
					ResultSet rs = pst.executeQuery();

					while (rs.next()) {
						wt3 = rs.getString("Username");
						wt4 = rs.getString("Password");
						wt9 = rs.getString("User");
					}

					if (wt1.equals(wt3) && wt2.equals(wt4))

					{

						if (wtx3.equalsIgnoreCase(wt9))

						{

							panel19.setVisible(true);
							panel24.setVisible(false);
						} else {
							JOptionPane.showMessageDialog(null, "Username & Password doesn't exist");
						}

					}

					else {
						JOptionPane.showMessageDialog(null, "Username & Password doesn't exist");
					}

					pst.execute();
					rs.close();
				} catch (Exception e) {
					JOptionPane.showMessageDialog(null, "Error = " + e);
				}

			}
		});
		btnSignin_01.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 42));
		btnSignin_01.setBounds(287, 412, 127, 39);
		panel24.add(btnSignin_01);

		ImageIcon g3za = new ImageIcon(this.getClass().getResource("/back.jpg"));
		JButton btnBackToButton555 = new JButton(g3za);
		btnBackToButton555.setBounds(12, 13, 120, 57);
		btnBackToButton555.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {

				panel24.setVisible(false);
				panel9.setVisible(true);
			}

		});
		panel24.add(btnBackToButton555);

		ImageIcon gifImage3vxwea = new ImageIcon(this.getClass().getResource("/7th page.jpg"));

		passwordField_1 = new JPasswordField();
		passwordField_1.setBounds(427, 250, 209, 50);
		panel24.add(passwordField_1);
		JLabel lblNewLabelpra = new JLabel(gifImage3vxwea);

		lblNewLabelpra.setBounds(0, 0, screenSize.width, screenSize.height);
		panel24.add(lblNewLabelpra);

		ImageIcon g4 = new ImageIcon(this.getClass().getResource("/back.jpg"));

		panel25 = new JPanel();
		panel25.setBackground(new Color(102, 0, 0));
		panel25.setBounds(0, 0, screenSize.width, screenSize.height);
		f1.getContentPane().add(panel25);
		panel25.setVisible(false);
		panel25.setLayout(null);

		JLabel lblUsername_031 = new JLabel("UserName");
		lblUsername_031.setForeground(Color.WHITE);
		lblUsername_031.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 45));
		lblUsername_031.setBounds(167, 149, 200, 68);
		panel25.add(lblUsername_031);

		JLabel lblPassword03 = new JLabel("Password");
		lblPassword03.setForeground(Color.WHITE);
		lblPassword03.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 45));
		lblPassword03.setBounds(167, 249, 200, 67);
		panel25.add(lblPassword03);

		textField__10 = new JTextField();
		textField__10.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 20));
		textField__10.setBounds(427, 167, 209, 50);
		panel25.add(textField__10);
		textField__10.setColumns(10);

		ImageIcon btnSignin_0301_1 = new ImageIcon(this.getClass().getResource("/log in but..jpg"));
		JButton btnSignin_0301 = new JButton(btnSignin_0301_1);
		btnSignin_0301.setForeground(new Color(153, 0, 0));

		btnSignin_0301.addKeyListener(new KeyAdapter() {
			@Override
			public void keyPressed(KeyEvent e) {

			}
		});
		btnSignin_0301.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent arg0) {

				wt5 = textField__10.getText();
				wt6 = passwordField_2.getText();
				wtx4 = "admin";
				try {

					String query = "Select * from Trailor Where UserName =  '" + wt5 + "'  ";
					PreparedStatement pst = conn.prepareStatement(query);
					ResultSet rs = pst.executeQuery();

					while (rs.next()) {
						wt7 = rs.getString("Username");
						wt8 = rs.getString("Password");
						wt10 = rs.getString("User");
					}

					if (wt5.equals(wt7) && wt6.equals(wt8))

					{

						if (wtx4.equalsIgnoreCase(wt10)) {
							panel18.setVisible(true);
							panel25.setVisible(false);
						}

						else {
							JOptionPane.showMessageDialog(null, "Username & Password doesn't exist");
						}

					} else {
						JOptionPane.showMessageDialog(null, "Username & Password doesn't exist");
					}

					pst.execute();
					rs.close();
				} catch (Exception e1) {
					JOptionPane.showMessageDialog(null, "Error = " + e1);
				}

				try {

					conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
					String query = "select * from Employee ";
					PreparedStatement statment = conn.prepareStatement(query);
					ResultSet rs = statment.executeQuery();
					table_2.setModel(DbUtils.resultSetToTableModel(rs));
					rs.close();
					statment.close();
				} catch (SQLException e) {

					e.printStackTrace();
				}

			}
		});
		btnSignin_0301.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 42));
		btnSignin_0301.setBounds(256, 401, 132, 41);
		panel25.add(btnSignin_0301);

		ImageIcon gifImage3back001 = new ImageIcon(this.getClass().getResource("/back.jpg"));
		JButton btnBackToButton55 = new JButton(gifImage3back001);

		btnBackToButton55.setBounds(25, 13, 120, 57);
		btnBackToButton55.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {

				panel25.setVisible(false);
				panel9.setVisible(true);
			}

		});
		panel25.add(btnBackToButton55);

		passwordField_2 = new JPasswordField();
		passwordField_2.setBounds(427, 249, 209, 50);
		panel25.add(passwordField_2);

		ImageIcon g5q1q1 = new ImageIcon(this.getClass().getResource("/6th page.jpg"));
		JLabel lblNewLabeldz = new JLabel(g5q1q1);
		lblNewLabeldz.setForeground(new Color(255, 0, 51));

		lblNewLabeldz.setBounds(0, 0, screenSize.width, screenSize.height);
		panel25.add(lblNewLabeldz);

		panel6 = new JPanel();
		panel6.setBackground(new Color(102, 0, 0));
		panel6.setBounds(0, 0, screenSize.width, screenSize.height);
		f1.getContentPane().add(panel6);
		panel6.setVisible(false);
		panel6.setLayout(null);

		ImageIcon g5 = new ImageIcon(this.getClass().getResource("/back.jpg"));
		JButton btnBackToButton002 = new JButton(g5);
		btnBackToButton002.setFont(new Font("Tahoma", Font.BOLD | Font.ITALIC, 16));
		btnBackToButton002.setBounds(12, 13, 120, 57);
		btnBackToButton002.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {

				l0 = 0;
				l1 = 0;
				l2 = 0;
				l3 = 0;
				l4 = 0;
				l5 = 0;
				l6 = 0;

				hk1 = 0;
				hk2 = 0;
				hk3 = 0;
				hk4 = 0;
				hk5 = 0;
				hk6 = 0;

				panel6.setVisible(false);
				panel1.setVisible(true);
			}

		});
		panel6.add(btnBackToButton002);

		ImageIcon gifImagqazxe3 = new ImageIcon(this.getClass().getResource("/new cust..jpg"));
		JButton newc = new JButton(gifImagqazxe3);
		newc.setOpaque(false);
		newc.setBorderPainted(false);

		newc.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {

				panel10.setVisible(true);
				panel6.setVisible(false);
				panel9.setVisible(false);
				panel1.setVisible(false);
				panel2.setVisible(false);
				panel11.setVisible(false);
				panel12.setVisible(false);
				panel14.setVisible(false);
				panel15.setVisible(false);
				panel20.setVisible(false);
				panel21.setVisible(false);
				panel16.setVisible(false);
				panel17.setVisible(false);
				panel18.setVisible(false);
				panel19.setVisible(false);
				panel4.setVisible(false);
				panel5.setVisible(false);
				panel7.setVisible(false);
				panel8.setVisible(false);
				panel22.setVisible(false);
				panel23.setVisible(false);
				panel24.setVisible(false);
				panel25.setVisible(false);

			}
		});
		newc.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 16));
		newc.setBounds(100, 629, 202, 119);
		panel6.add(newc);

		ImageIcon gifImage3asdfgghh = new ImageIcon(this.getClass().getResource("/old order.jpg"));
		JButton old_c = new JButton(gifImage3asdfgghh);
		old_c.setOpaque(false);
		old_c.setBorderPainted(false);

		old_c.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {

				panel11.setVisible(true);
				panel9.setVisible(false);
				panel6.setVisible(false);
				panel1.setVisible(false);
				panel2.setVisible(false);
				panel10.setVisible(false);
				panel12.setVisible(false);

				panel14.setVisible(false);
				panel15.setVisible(false);
				panel20.setVisible(false);
				panel21.setVisible(false);
				panel16.setVisible(false);
				panel17.setVisible(false);
				panel18.setVisible(false);
				panel19.setVisible(false);
				panel4.setVisible(false);
				panel5.setVisible(false);
				panel7.setVisible(false);
				panel8.setVisible(false);
				panel22.setVisible(false);
				panel23.setVisible(false);
				panel24.setVisible(false);
				panel25.setVisible(false);

			}
		});
		old_c.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 16));
		old_c.setBounds(397, 629, 202, 119);
		panel6.add(old_c);

		ImageIcon gifImage3____1 = new ImageIcon(this.getClass().getResource("/deliv.jpg"));
		JButton deliverd = new JButton(gifImage3____1);
		deliverd.setOpaque(false);
		deliverd.setBorderPainted(false);

		deliverd.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {

				panel12.setVisible(true);
				panel6.setVisible(false);
				panel9.setVisible(false);
				panel1.setVisible(false);
				panel2.setVisible(false);
				panel11.setVisible(false);
				panel10.setVisible(false);

				panel14.setVisible(false);
				panel15.setVisible(false);
				panel20.setVisible(false);
				panel21.setVisible(false);
				panel16.setVisible(false);
				panel17.setVisible(false);
				panel18.setVisible(false);
				panel19.setVisible(false);
				panel4.setVisible(false);
				panel5.setVisible(false);
				panel7.setVisible(false);
				panel8.setVisible(false);
				panel22.setVisible(false);
				panel23.setVisible(false);
				panel24.setVisible(false);
				panel25.setVisible(false);

			}
		});
		deliverd.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 16));
		deliverd.setBounds(1317, 629, 202, 119);
		panel6.add(deliverd);

		ImageIcon gifImage3_worki = new ImageIcon(this.getClass().getResource("/in worki.jpg"));
		JButton in_work = new JButton(gifImage3_worki);
		in_work.setOpaque(false);
		in_work.setBorderPainted(false);

		in_work.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {

				panel4.setVisible(true);
				panel6.setVisible(false);

			}
		});
		in_work.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 16));
		in_work.setBounds(1015, 629, 202, 119);
		panel6.add(in_work);

		ImageIcon gifImage3_a_a = new ImageIcon(this.getClass().getResource("/new ord..jpg"));
		JButton new_c = new JButton(gifImage3_a_a);
		new_c.setOpaque(false);
		new_c.setBorderPainted(false);

		new_c.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {

				panel17.setVisible(true);
				panel6.setVisible(false);
				panel9.setVisible(false);
				panel1.setVisible(false);
				panel2.setVisible(false);
				panel11.setVisible(false);
				panel12.setVisible(false);

				panel14.setVisible(false);
				panel15.setVisible(false);
				panel20.setVisible(false);
				panel21.setVisible(false);
				panel16.setVisible(false);
				panel10.setVisible(false);
				panel18.setVisible(false);
				panel19.setVisible(false);
				panel4.setVisible(false);
				panel5.setVisible(false);
				panel7.setVisible(false);
				panel8.setVisible(false);
				panel22.setVisible(false);
				panel23.setVisible(false);
				panel24.setVisible(false);
				panel25.setVisible(false);
			}
		});

		ImageIcon gifImage3a1a1a1 = new ImageIcon(this.getClass().getResource("/pending wrk.jpg"));
		JButton pen_work = new JButton(gifImage3a1a1a1);
		pen_work.setOpaque(false);
		pen_work.setBorderPainted(false);

		pen_work.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent arg0) {

				panel27.setVisible(true);
				panel6.setVisible(false);
				panel9.setVisible(false);
				panel1.setVisible(false);
				panel2.setVisible(false);
				panel11.setVisible(false);
				panel12.setVisible(false);

				panel14.setVisible(false);
				panel15.setVisible(false);
				panel20.setVisible(false);
				panel21.setVisible(false);
				panel16.setVisible(false);
				panel10.setVisible(false);
				panel18.setVisible(false);
				panel19.setVisible(false);
				panel4.setVisible(false);
				panel5.setVisible(false);
				panel7.setVisible(false);
				panel8.setVisible(false);
				panel22.setVisible(false);
				panel23.setVisible(false);
				panel24.setVisible(false);
				panel25.setVisible(false);

			}
		});
		pen_work.setFont(new Font("Dialog", Font.BOLD | Font.ITALIC, 16));
		pen_work.setBounds(1609, 629, 202, 119);
		panel6.add(pen_work);
		new_c.setFont(new Font("Snap ITC", Font.BOLD | Font.ITALIC, 16));
		new_c.setBounds(700, 629, 202, 119);
		panel6.add(new_c);

		ImageIcon gsadifImage3a = new ImageIcon(this.getClass().getResource("/8th page.jpg"));
		JLabel lbnlNewLabel_1 = new JLabel(gsadifImage3a);

		lbnlNewLabel_1.setBounds(0, 0, screenSize.width, screenSize.height);
		panel6.add(lbnlNewLabel_1);

		panel26 = new JPanel();
		panel26.setBackground(new Color(102, 0, 0));
		panel26.setBounds(0, 0, screenSize.width, screenSize.height);
		f1.getContentPane().add(panel26);
		panel26.setVisible(false);
		panel26.setLayout(null);

		ImageIcon g6 = new ImageIcon(this.getClass().getResource("/back.jpg"));
		JButton btnBackToButtonn7 = new JButton(g6);
		btnBackToButtonn7.setFont(new Font("Sitka Text", Font.BOLD | Font.ITALIC, 48));
		btnBackToButtonn7.setBounds(12, 13, 120, 57);
		btnBackToButtonn7.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {

				if (hk5 > 0) {
					panel17.setVisible(true);
					panel26.setVisible(false);
				} else {
					panel17.setVisible(true);
					panel26.setVisible(false);
				}
			}

		});
		panel26.add(btnBackToButtonn7);

		JLabel lblCoat = new JLabel("Coat");
		lblCoat.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 45));
		lblCoat.setBounds(147, 107, 100, 53);
		panel26.add(lblCoat);

		JLabel lblJacket = new JLabel("Jacket");
		lblJacket.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 45));
		lblJacket.setBounds(624, 107, 131, 53);
		panel26.add(lblJacket);

		JLabel lblKurta = new JLabel("Kurta");
		lblKurta.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 45));
		lblKurta.setBounds(1613, 107, 109, 53);
		panel26.add(lblKurta);

		JLabel lblPjama = new JLabel("Pjama");
		lblPjama.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 45));
		lblPjama.setBounds(1101, 107, 121, 53);
		panel26.add(lblPjama);

		JSeparator separator01 = new JSeparator();
		separator01.setBounds(0, 88, 1921, 29);
		panel26.add(separator01);

		JLabel lblMeasurement_1 = new JLabel("Measurement");
		lblMeasurement_1.setFont(new Font("Times New Roman", Font.BOLD | Font.ITALIC, 81));
		lblMeasurement_1.setBounds(429, 0, 477, 75);
		panel26.add(lblMeasurement_1);

		JSeparator separator_1 = new JSeparator();
		separator_1.setOrientation(SwingConstants.VERTICAL);
		separator_1.setBounds(484, 88, 17, 918);
		panel26.add(separator_1);

		JSeparator separator_2 = new JSeparator();
		separator_2.setOrientation(SwingConstants.VERTICAL);
		separator_2.setBounds(952, 88, 17, 918);
		panel26.add(separator_2);

		JSeparator separator_3 = new JSeparator();
		separator_3.setOrientation(SwingConstants.VERTICAL);
		separator_3.setBounds(1448, 88, 17, 918);
		panel26.add(separator_3);

		panel27 = new JPanel();
		panel27.setBackground(new Color(102, 0, 0));
		panel27.setBounds(0, 0, screenSize.width, screenSize.height);
		f1.getContentPane().add(panel27);
		panel27.setLayout(null);
		panel27.setVisible(false);

		ImageIcon g7 = new ImageIcon(this.getClass().getResource("/back.jpg"));
		JButton bbtnBackToButtonn7 = new JButton(g7);
		bbtnBackToButtonn7.setFont(new Font("Sitka Text", Font.BOLD | Font.ITALIC, 48));
		bbtnBackToButtonn7.setBounds(12, 13, 120, 57);
		bbtnBackToButtonn7.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {

				if (hk6 > 0) {
					panel9.setVisible(true);
					panel27.setVisible(false);
				} else {
					panel6.setVisible(true);
					panel27.setVisible(false);
				}

			}

		});
		panel27.add(bbtnBackToButtonn7);

		JScrollPane scrollPane_010 = new JScrollPane();
		scrollPane_010.setBounds(199, 77, 700, 280);
		panel27.add(scrollPane_010);

		table_6 = new JTable();
		table_6.setAutoResizeMode(JTable.AUTO_RESIZE_OFF);
		try {

			conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
			String query = "select * from pending_shirt ";
			PreparedStatement statment = conn.prepareStatement(query);
			ResultSet rs = statment.executeQuery();
			table_6.setModel(DbUtils.resultSetToTableModel(rs));

			rs.close();
			statment.close();
		} catch (SQLException e) {
			JOptionPane.showMessageDialog(null, "My Error 1" + e);
		}
		table_6.addMouseListener(new MouseAdapter() {
			@Override
			public void mouseClicked(MouseEvent e) {
				DefaultTableModel model = (DefaultTableModel) table_6.getModel();
				int row = table_6.getSelectedRow();
				String id1 = model.getValueAt(row, 9).toString();

				try {
					String query = "Select * from pending_shirt where Customerid='" + id1 + "' ";
					PreparedStatement pst = conn.prepareStatement(query);
					ResultSet rs = pst.executeQuery();

					while (rs.next()) {

						z1 = rs.getString("lmbai");
						z2 = rs.getString("seena");
						z3 = rs.getString("kemer");
						z4 = rs.getString("pait");
						z5 = rs.getString("hip");
						z6 = rs.getString("teera");
						z7 = rs.getString("glaa");
						z8 = rs.getString("baju");
						z9 = rs.getString("bs");
						z10 = rs.getString("Customerid");
						z11 = rs.getString("CustomerName");
						z12 = rs.getString("CustomerContact");
						z13 = rs.getString("CustomerAddress");
						z14 = rs.getString("price");
						z15 = rs.getString("advance_payments");
						z16 = rs.getString("pending_payments");
						z17 = rs.getString("Starting_date");
						z18 = rs.getString("Ending_date");
						z19 = rs.getString("price1");
						z20 = rs.getString("quantity");
						z21 = rs.getString("extra");

					}

					rs.close();
					pst.close();

				} catch (Exception e1) {
					e1.printStackTrace();
				}

				int dialogButton = JOptionPane.YES_NO_OPTION;
				JOptionPane.showConfirmDialog(null, "Would You Like to Save your Previous Note First?", "Warning",
						dialogButton);

				if (dialogButton == JOptionPane.YES_OPTION) {

					String h[] = { z1, z2, z3, z4, z5, z6, z7, z8, z9, z10, z11, z12, z13, z14, z15, z16, z17, z18, z19,
							z20, z21 };
					hello.main(h);
					try {

						conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
						String query = "Insert into deliverd_shirt (lmbai ,seena ,kemer ,pait ,hip ,teera ,glaa ,baju ,bs,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";

						PreparedStatement statment = conn.prepareStatement(query);

						statment.setString(1, z1);
						statment.setString(2, z2);
						statment.setString(3, z3);
						statment.setString(4, z4);
						statment.setString(5, z5);
						statment.setString(6, z6);
						statment.setString(7, z7);
						statment.setString(8, z8);
						statment.setString(9, z9);
						statment.setString(10, z10);
						statment.setString(11, z11);
						statment.setString(12, z12);
						statment.setString(13, z13);
						statment.setString(14, z14);
						statment.setString(15, z15);
						statment.setString(16, z16);
						statment.setString(17, z17);
						statment.setString(18, z18);
						statment.setString(19, z19);
						statment.setString(20, z20);
						statment.setString(21, z21);

						statment.execute();

						statment.close();
					} catch (SQLException e1) {

						e1.printStackTrace();
					}

					try {
						String query1 = " DELETE FROM pending_shirt where Customerid= '" + id1 + "' ";
						PreparedStatement pst2 = conn.prepareStatement(query1);
						pst2.execute();
						pst2.close();
					} catch (Exception e1) {
						e1.printStackTrace();
					}
				} else {

				}
				String h[] = { z1, z2, z3, z4, z5, z6, z7, z8, z9, z10, z11, z12, z13, z14, z15, z16, z17, z18, z19,
						z20, z21 };
				hello.main(h);
			}
		});

		scrollPane_010.setViewportView(table_6);

		JScrollPane scrollPane030 = new JScrollPane();
		scrollPane030.setBounds(199, 386, 700, 280);
		panel27.add(scrollPane030);

		table_16 = new JTable();
		table_16.setAutoResizeMode(JTable.AUTO_RESIZE_OFF);

		try {

			conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
			String query = "select * from pending_coat ";
			PreparedStatement statment = conn.prepareStatement(query);
			ResultSet rs = statment.executeQuery();
			table_16.setModel(DbUtils.resultSetToTableModel(rs));

			rs.close();
			statment.close();
		} catch (SQLException e) {
			JOptionPane.showMessageDialog(null, "My Error 1" + e);
		}
		table_16.addMouseListener(new MouseAdapter() {
			@Override
			public void mouseClicked(MouseEvent e) {
				DefaultTableModel model = (DefaultTableModel) table_16.getModel();
				int row = table_16.getSelectedRow();
				String id1 = model.getValueAt(row, 12).toString();

				try {
					String query = "Select * from pending_coat where Customerid='" + id1 + "' ";
					PreparedStatement pst = conn.prepareStatement(query);
					ResultSet rs = pst.executeQuery();

					while (rs.next()) {

						z1 = rs.getString("lmbai");
						z2 = rs.getString("seena");
						z3 = rs.getString("kemer");
						z4 = rs.getString("pait");
						z5 = rs.getString("hip");
						z6 = rs.getString("teera");
						z7 = rs.getString("baju");
						z8 = rs.getString("dor");
						z9 = rs.getString("back");
						z10 = rs.getString("bs");
						z11 = rs.getString("bm");
						z12 = rs.getString("shoulder");
						z13 = rs.getString("Customerid");
						z14 = rs.getString("CustomerName");
						z15 = rs.getString("CustomerContact");
						z16 = rs.getString("CustomerAddress");
						z17 = rs.getString("price");
						z18 = rs.getString("advance_payments");
						z19 = rs.getString("pending_payments");
						z20 = rs.getString("Starting_date");
						z21 = rs.getString("Ending_date");
						z22 = rs.getString("price1");
						z23 = rs.getString("quantity");
						z24 = rs.getString("extra");

					}

					rs.close();
					pst.close();

				} catch (Exception e1) {
					e1.printStackTrace();
				}

				int dialogButton = JOptionPane.YES_NO_OPTION;
				JOptionPane.showConfirmDialog(null, "Would You Like to Save your Previous Note First?", "Warning",
						dialogButton);

				if (dialogButton == JOptionPane.YES_OPTION) {

					String h[] = { z1, z2, z3, z4, z5, z6, z7, z8, z9, z10, z11, z12, z13, z14, z15, z16, z17, z18, z19,
							z20, z21, z22, z23, z24 };
					hello2.main(h);
					try {

						conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
						String query = "Insert into deliverd_coat (lmbai2 ,seena1 ,kemer2 ,pait1 ,hip2 ,teera1 ,baju ,dor ,back ,bs ,bm ,shoulder,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";

						PreparedStatement statment = conn.prepareStatement(query);

						statment.setString(1, z1);
						statment.setString(2, z2);
						statment.setString(3, z3);
						statment.setString(4, z4);
						statment.setString(5, z5);
						statment.setString(6, z6);
						statment.setString(7, z7);
						statment.setString(8, z8);
						statment.setString(9, z9);
						statment.setString(10, z10);
						statment.setString(11, z11);
						statment.setString(12, z12);
						statment.setString(13, z13);
						statment.setString(14, z14);
						statment.setString(15, z15);
						statment.setString(16, z16);
						statment.setString(17, z17);
						statment.setString(18, z18);
						statment.setString(19, z19);
						statment.setString(20, z20);
						statment.setString(21, z21);
						statment.setString(22, z22);
						statment.setString(23, z23);
						statment.setString(24, z24);

						statment.execute();

						statment.close();
					} catch (SQLException e1) {

						e1.printStackTrace();
					}

					try {
						String query1 = " DELETE FROM pending_coat where Customerid= '" + id1 + "' ";
						PreparedStatement pst2 = conn.prepareStatement(query1);
						pst2.execute();
						pst2.close();
					} catch (Exception e1) {
						e1.printStackTrace();
					}
				} else {

				}
				String h[] = { z1, z2, z3, z4, z5, z6, z7, z8, z9, z10, z11, z12, z13, z14, z15, z16, z17, z18, z19,
						z20, z21, z22, z23, z24 };
				hello2.main(h);
			}
		});

		scrollPane030.setViewportView(table_16);

		JScrollPane scrollPane_050 = new JScrollPane();
		scrollPane_050.setBounds(199, 697, 700, 280);
		panel27.add(scrollPane_050);

		table_17 = new JTable();
		table_17.setAutoResizeMode(JTable.AUTO_RESIZE_OFF);

		try {

			conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
			String query = "select * from pending_kurta ";
			PreparedStatement statment = conn.prepareStatement(query);
			ResultSet rs = statment.executeQuery();
			table_17.setModel(DbUtils.resultSetToTableModel(rs));

			rs.close();
			statment.close();
		} catch (SQLException e) {
			JOptionPane.showMessageDialog(null, "My Error 1" + e);
		}
		table_17.addMouseListener(new MouseAdapter() {
			@Override
			public void mouseClicked(MouseEvent e) {
				DefaultTableModel model = (DefaultTableModel) table_17.getModel();
				int row = table_17.getSelectedRow();
				String id1 = model.getValueAt(row, 9).toString();

				try {
					String query = "Select * from pending_kurta where Customerid='" + id1 + "' ";
					PreparedStatement pst = conn.prepareStatement(query);
					ResultSet rs = pst.executeQuery();

					while (rs.next()) {

						z1 = rs.getString("lmbai");
						z2 = rs.getString("seena");
						z3 = rs.getString("kemer");
						z4 = rs.getString("pait");
						z5 = rs.getString("hip");
						z6 = rs.getString("teera");
						z7 = rs.getString("glaa");
						z8 = rs.getString("baju");
						z9 = rs.getString("bs");
						z10 = rs.getString("Customerid");
						z11 = rs.getString("CustomerName");
						z12 = rs.getString("CustomerContact");
						z13 = rs.getString("CustomerAddress");
						z14 = rs.getString("price");
						z15 = rs.getString("advance_payments");
						z16 = rs.getString("pending_payments");
						z17 = rs.getString("Starting_date");
						z18 = rs.getString("Ending_date");
						z19 = rs.getString("price1");
						z20 = rs.getString("quantity");
						z21 = rs.getString("extra");

					}

					rs.close();
					pst.close();

				} catch (Exception e1) {
					e1.printStackTrace();
				}

				int dialogButton = JOptionPane.YES_NO_OPTION;
				JOptionPane.showConfirmDialog(null, "Would You Like to Save your Previous Note First?", "Warning",
						dialogButton);

				if (dialogButton == JOptionPane.YES_OPTION) {

					String h[] = { z1, z2, z3, z4, z5, z6, z7, z8, z9, z10, z11, z12, z13, z14, z15, z16, z17, z18, z19,
							z20, z21 };
					hello4.main(h);
					try {

						conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
						String query = "Insert into deliverd_kurta (lmbai ,seena ,kemer ,pait ,hip ,teera ,glaa ,baju ,bs,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";

						PreparedStatement statment = conn.prepareStatement(query);

						statment.setString(1, z1);
						statment.setString(2, z2);
						statment.setString(3, z3);
						statment.setString(4, z4);
						statment.setString(5, z5);
						statment.setString(6, z6);
						statment.setString(7, z7);
						statment.setString(8, z8);
						statment.setString(9, z9);
						statment.setString(10, z10);
						statment.setString(11, z11);
						statment.setString(12, z12);
						statment.setString(13, z13);
						statment.setString(14, z14);
						statment.setString(15, z15);
						statment.setString(16, z16);
						statment.setString(17, z17);
						statment.setString(18, z18);
						statment.setString(19, z19);
						statment.setString(20, z20);
						statment.setString(21, z21);

						statment.execute();

						statment.close();
					} catch (SQLException e1) {

						e1.printStackTrace();
					}

					try {
						String query1 = " DELETE FROM pending_kurta where Customerid= '" + id1 + "' ";
						PreparedStatement pst2 = conn.prepareStatement(query1);
						pst2.execute();
						pst2.close();
					} catch (Exception e1) {
						e1.printStackTrace();
					}
				} else {

				}
				String h[] = { z1, z2, z3, z4, z5, z6, z7, z8, z9, z10, z11, z12, z13, z14, z15, z16, z17, z18, z19,
						z20, z21 };
				hello4.main(h);
			}
		});

		scrollPane_050.setViewportView(table_17);

		JScrollPane scrollPane_020 = new JScrollPane();
		scrollPane_020.setBounds(996, 77, 700, 280);
		panel27.add(scrollPane_020);

		table_18 = new JTable();
		table_18.setAutoResizeMode(JTable.AUTO_RESIZE_OFF);

		try {

			conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
			String query = "select * from pending_pent";
			PreparedStatement statment = conn.prepareStatement(query);
			ResultSet rs = statment.executeQuery();
			table_18.setModel(DbUtils.resultSetToTableModel(rs));

			rs.close();
			statment.close();
		} catch (SQLException e) {
			JOptionPane.showMessageDialog(null, "My Error 1" + e);
		}
		table_18.addMouseListener(new MouseAdapter() {
			@Override
			public void mouseClicked(MouseEvent e) {
				DefaultTableModel model = (DefaultTableModel) table_18.getModel();
				int row = table_18.getSelectedRow();
				String id1 = model.getValueAt(row, 7).toString();

				try {
					String query = "Select * from pending_pent where Customerid='" + id1 + "' ";
					PreparedStatement pst = conn.prepareStatement(query);
					ResultSet rs = pst.executeQuery();

					while (rs.next()) {

						z1 = rs.getString("lmbai");
						z2 = rs.getString("kemer");
						z3 = rs.getString("hip");
						z4 = rs.getString("gidri");
						z5 = rs.getString("pinjni");
						z6 = rs.getString("mori");
						z7 = rs.getString("putt");
						z8 = rs.getString("Customerid");
						z9 = rs.getString("CustomerName");
						z10 = rs.getString("CustomerContact");
						z11 = rs.getString("CustomerAddress");
						z12 = rs.getString("price");
						z13 = rs.getString("advance_payments");
						z14 = rs.getString("pending_payments");
						z15 = rs.getString("Starting_date");
						z16 = rs.getString("Ending_date");
						z17 = rs.getString("price1");
						z18 = rs.getString("quantity");
						z19 = rs.getString("extra");

					}

					rs.close();
					pst.close();

				} catch (Exception e1) {
					JOptionPane.showMessageDialog(null, "In all shirt selecting " + e1);
				}

				int dialogButton = JOptionPane.YES_NO_OPTION;
				JOptionPane.showConfirmDialog(null, "Would You Like to Save your Previous Note First?", "Warning",
						dialogButton);

				if (dialogButton == JOptionPane.YES_OPTION) {

					String h[] = { z1, z2, z3, z4, z5, z6, z7, z8, z9, z10, z11, z12, z13, z14, z15, z16, z17, z18,
							z19 };
					hello1.main(h);
					try {

						conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
						String query = "Insert into deliverd_pent (lmbai,kemer,hip,gidri,pinjni,mori,putt,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";

						PreparedStatement statment = conn.prepareStatement(query);

						statment.setString(1, z1);
						statment.setString(2, z2);
						statment.setString(3, z3);
						statment.setString(4, z4);
						statment.setString(5, z5);
						statment.setString(6, z6);
						statment.setString(7, z7);
						statment.setString(8, z8);
						statment.setString(9, z9);
						statment.setString(10, z10);
						statment.setString(11, z11);
						statment.setString(12, z12);
						statment.setString(13, z13);
						statment.setString(14, z14);
						statment.setString(15, z15);
						statment.setString(16, z16);
						statment.setString(17, z17);
						statment.setString(18, z18);
						statment.setString(19, z19);

						statment.execute();

						statment.close();
					} catch (SQLException e1) {

						e1.printStackTrace();
					}

					try {
						String query1 = " DELETE FROM pending_pent where Customerid= '" + id1 + "' ";
						PreparedStatement pst2 = conn.prepareStatement(query1);
						pst2.execute();
						pst2.close();
					} catch (Exception e1) {
						e1.printStackTrace();
					}
				} else {

				}
				String h[] = { z1, z2, z3, z4, z5, z6, z7, z8, z9, z10, z11, z12, z13, z14, z15, z16, z17, z18, z19 };
				hello1.main(h);
			}
		});

		scrollPane_020.setViewportView(table_18);

		JScrollPane scrollPane_040 = new JScrollPane();
		scrollPane_040.setBounds(996, 386, 700, 280);
		panel27.add(scrollPane_040);

		table_19 = new JTable();
		table_19.setAutoResizeMode(JTable.AUTO_RESIZE_OFF);

		try {

			conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
			String query = "select * from pending_jacket ";
			PreparedStatement statment = conn.prepareStatement(query);
			ResultSet rs = statment.executeQuery();
			table_19.setModel(DbUtils.resultSetToTableModel(rs));

			rs.close();
			statment.close();
		} catch (SQLException e) {
			JOptionPane.showMessageDialog(null, "My Error 1" + e);
		}
		table_19.addMouseListener(new MouseAdapter() {
			@Override
			public void mouseClicked(MouseEvent e) {
				DefaultTableModel model = (DefaultTableModel) table_19.getModel();
				int row = table_19.getSelectedRow();
				String id1 = model.getValueAt(row, 5).toString();

				try {
					String query = "Select * from pending_jacket where Customerid='" + id1 + "' ";
					PreparedStatement pst = conn.prepareStatement(query);
					ResultSet rs = pst.executeQuery();

					while (rs.next()) {

						z1 = rs.getString("lmbai");
						z2 = rs.getString("seena");
						z3 = rs.getString("kemer");
						z4 = rs.getString("hip");
						z5 = rs.getString("teera");
						z6 = rs.getString("Customerid");
						z7 = rs.getString("CustomerName");
						z8 = rs.getString("CustomerContact");
						z9 = rs.getString("CustomerAddress");
						z10 = rs.getString("price");
						z11 = rs.getString("advance_payments");
						z12 = rs.getString("pending_payments");
						z13 = rs.getString("Starting_date");
						z14 = rs.getString("Ending_date");
						z15 = rs.getString("price1");
						z16 = rs.getString("quantity");
						z17 = rs.getString("extra");

					}

					rs.close();
					pst.close();

				} catch (Exception e1) {
					JOptionPane.showMessageDialog(null, "In all shirt selecting " + e1);
				}

				int dialogButton = JOptionPane.YES_NO_OPTION;
				JOptionPane.showConfirmDialog(null, "Would You Like to Save your Previous Note First?", "Warning",
						dialogButton);

				if (dialogButton == JOptionPane.YES_OPTION) {

					String h[] = { z1, z2, z3, z4, z5, z6, z7, z8, z9, z10, z11, z12, z13, z14, z15, z16, z17 };
					hello3.main(h);
					try {

						conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
						String query = "Insert into deliverd_jacket (lmbai,seena,kemer,hip,teera,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";

						PreparedStatement statment = conn.prepareStatement(query);

						statment.setString(1, z1);
						statment.setString(2, z2);
						statment.setString(3, z3);
						statment.setString(4, z4);
						statment.setString(5, z5);
						statment.setString(6, z6);
						statment.setString(7, z7);
						statment.setString(8, z8);
						statment.setString(9, z9);
						statment.setString(10, z10);
						statment.setString(11, z11);
						statment.setString(12, z12);
						statment.setString(13, z13);
						statment.setString(14, z14);
						statment.setString(15, z15);
						statment.setString(16, z16);
						statment.setString(17, z17);

						statment.execute();

						statment.close();
					} catch (SQLException e1) {

						JOptionPane.showMessageDialog(null, "In all shirt selecting " + e1);
					}

					try {
						String query1 = " DELETE FROM pending_jacket where Customerid= '" + id1 + "' ";
						PreparedStatement pst2 = conn.prepareStatement(query1);
						pst2.execute();
						pst2.close();
					} catch (Exception e1) {
						e1.printStackTrace();
					}
				} else {

				}
				String h[] = { z1, z2, z3, z4, z5, z6, z7, z8, z9, z10, z11, z12, z13, z14 };
				hello3.main(h);
			}
		});

		scrollPane_040.setViewportView(table_19);

		JScrollPane scrollPane_060 = new JScrollPane();
		scrollPane_060.setBounds(996, 697, 700, 280);
		panel27.add(scrollPane_060);

		table_20 = new JTable();
		table_20.setAutoResizeMode(JTable.AUTO_RESIZE_OFF);

		try {

			conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
			String query = "select * from pending_pjama";
			PreparedStatement statment = conn.prepareStatement(query);
			ResultSet rs = statment.executeQuery();
			table_20.setModel(DbUtils.resultSetToTableModel(rs));

			rs.close();
			statment.close();
		} catch (SQLException e) {
			JOptionPane.showMessageDialog(null, "My Error 1" + e);
		}
		table_20.addMouseListener(new MouseAdapter() {
			@Override
			public void mouseClicked(MouseEvent e) {
				DefaultTableModel model = (DefaultTableModel) table_20.getModel();
				int row = table_20.getSelectedRow();
				String id1 = model.getValueAt(row, 7).toString();

				try {
					String query = "Select * from pending_pjama where Customerid='" + id1 + "' ";
					PreparedStatement pst = conn.prepareStatement(query);
					ResultSet rs = pst.executeQuery();

					while (rs.next()) {

						z1 = rs.getString("lmbai");
						z2 = rs.getString("kemer");
						z3 = rs.getString("hip");
						z4 = rs.getString("gidri");
						z5 = rs.getString("pinjni");
						z6 = rs.getString("mori");
						z7 = rs.getString("putt");
						z8 = rs.getString("Customerid");
						z9 = rs.getString("CustomerName");
						z10 = rs.getString("CustomerContact");
						z11 = rs.getString("CustomerAddress");
						z12 = rs.getString("price");
						z13 = rs.getString("advance_payments");
						z14 = rs.getString("pending_payments");
						z15 = rs.getString("Starting_date");
						z16 = rs.getString("Ending_date");
						z17 = rs.getString("price1");
						z18 = rs.getString("quantity");
						z19 = rs.getString("extra");

					}

					rs.close();
					pst.close();

				} catch (Exception e1) {
					JOptionPane.showMessageDialog(null, "In all shirt selecting " + e1);
				}

				int dialogButton = JOptionPane.YES_NO_OPTION;
				JOptionPane.showConfirmDialog(null, "Would You Like to Save your Previous Note First?", "Warning",
						dialogButton);

				if (dialogButton == JOptionPane.YES_OPTION) {

					String h[] = { z1, z2, z3, z4, z5, z6, z7, z8, z9, z10, z11, z12, z13, z14, z15, z16, z17, z18,
							z19 };
					hello5.main(h);
					try {

						conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
						String query = "Insert into deliverd_pjama (lmbai,kemer,hip,gidri,pinjni,mori,putt,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";

						PreparedStatement statment = conn.prepareStatement(query);

						statment.setString(1, z1);
						statment.setString(2, z2);
						statment.setString(3, z3);
						statment.setString(4, z4);
						statment.setString(5, z5);
						statment.setString(6, z6);
						statment.setString(7, z7);
						statment.setString(8, z8);
						statment.setString(9, z9);
						statment.setString(10, z10);
						statment.setString(11, z11);
						statment.setString(12, z12);
						statment.setString(13, z13);
						statment.setString(14, z14);
						statment.setString(15, z15);
						statment.setString(16, z16);
						statment.setString(17, z17);
						statment.setString(18, z18);
						statment.setString(19, z19);

						statment.execute();

						statment.close();
					} catch (SQLException e1) {

						JOptionPane.showMessageDialog(null, "In all shirt selecting " + e1);
					}

					try {
						String query1 = " DELETE FROM pending_pjama where Customerid= '" + id1 + "' ";
						PreparedStatement pst2 = conn.prepareStatement(query1);
						pst2.execute();
						pst2.close();
					} catch (Exception e1) {
						e1.printStackTrace();
					}
				} else {

				}
				String h[] = { z1, z2, z3, z4, z5, z6, z7, z8, z9, z10, z11, z12, z13, z14, z15, z16, z17, z18, z19 };
				hello5.main(h);
			}
		});

		scrollPane_060.setViewportView(table_20);

		ImageIcon pendingimage = new ImageIcon(this.getClass().getResource("/5th page.jpg"));
		JLabel lblNewLabel_pending = new JLabel(pendingimage);
		lblNewLabel_pending.setBounds(0, 0, screenSize.width, screenSize.height);
		panel27.add(lblNewLabel_pending);

	}

	public void shirtSwitch() {
		try {

			String s = "Select * from Shirt ";
			PreparedStatement pst = conn.prepareStatement(s);
			ResultSet rs = pst.executeQuery();
			while (rs.next()) {

				q1 = rs.getString("lmbai");

				q2 = rs.getString("seena");

				q3 = rs.getString("kemer");

				q4 = rs.getString("pait");

				q5 = rs.getString("hip");

				q6 = rs.getString("teera");

				q7 = rs.getString("glaa");

				q8 = rs.getString("baju");

				q9 = rs.getString("bs");

				q10 = rs.getString("Customerid");

				q11 = rs.getString("CustomerName");

				q12 = rs.getString("CustomerContact");

				q13 = rs.getString("CustomerAddress");

				q14 = rs.getString("price");

				q15 = rs.getString("advance_payments");

				q16 = rs.getString("pending_payments");

				q17 = rs.getString("Starting_date");

				q18 = rs.getString("Ending_date");
				q19 = rs.getString("price1");
				q20 = rs.getString("quantity");
				q21 = rs.getString("extra");

				if (q18 == null) {

					rs.close();
					pst.close();
				} else {
					Date ldl = new SimpleDateFormat("yyyy-MM-dd").parse(q18);

					LocalDate billDate = ldl.toInstant().atZone(ZoneId.systemDefault()).toLocalDate();
					d = LocalDate.now();

					i = d.compareTo(billDate);

					if (i > 0) {

						String query = "Insert into pending_shirt (lmbai,seena,kemer,pait,hip,teera,glaa,baju,bs,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
						PreparedStatement pst1 = conn.prepareStatement(query);
						pst1.setString(1, q1);
						pst1.setString(2, q2);
						pst1.setString(3, q3);
						pst1.setString(4, q4);
						pst1.setString(5, q5);
						pst1.setString(6, q6);
						pst1.setString(7, q7);
						pst1.setString(8, q8);
						pst1.setString(9, q9);
						pst1.setString(10, q10);
						pst1.setString(11, q11);
						pst1.setString(12, q12);
						pst1.setString(13, q13);
						pst1.setString(14, q14);
						pst1.setString(15, q15);
						pst1.setString(16, q16);
						pst1.setString(17, q17);
						pst1.setString(18, q18);
						pst1.setString(19, q19);
						pst1.setString(20, q20);
						pst1.setString(21, q21);

						pst1.execute();
						pst1.close();

						try {
							String query1 = " DELETE FROM Shirt where Ending_Date= '" + q18 + "' ";
							PreparedStatement pst2 = conn.prepareStatement(query1);
							pst2.execute();
							pst2.close();
						} catch (Exception e1) {
							JOptionPane.showMessageDialog(null, "deleting shirt " + e1);
						}
					}

					else {
					}
				}
				rs.close();
				pst.close();
			}

		} catch (Exception e1) {
			e1.printStackTrace();
		}

		try {

			conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
			String query = "select * from Shirt ";
			PreparedStatement statment = conn.prepareStatement(query);
			ResultSet rs = statment.executeQuery();
			table_34.setModel(DbUtils.resultSetToTableModel(rs));

			rs.close();
			statment.close();
		} catch (SQLException e) {

			JOptionPane.showMessageDialog(null, "My Error 2" + e);
		}
	}

	public void pentSwitch() {
		try {
			String s = "Select * from pent";
			PreparedStatement pst = conn.prepareStatement(s);
			ResultSet rs = pst.executeQuery();
			while (rs.next()) {

				q1 = rs.getString("lmbai");
				q2 = rs.getString("kemer");
				q3 = rs.getString("hip");
				q4 = rs.getString("gidri");
				q5 = rs.getString("pinjni");
				q6 = rs.getString("mori");
				q7 = rs.getString("putt");
				q8 = rs.getString("Customerid");
				q9 = rs.getString("CustomerName");
				q10 = rs.getString("CustomerContact");
				q11 = rs.getString("CustomerAddress");
				q12 = rs.getString("price");
				q13 = rs.getString("advance_payments");
				q14 = rs.getString("pending_payments");
				q15 = rs.getString("Starting_date");
				q16 = rs.getString("Ending_date");
				q17 = rs.getString("price1");
				q18 = rs.getString("quantity");
				q19 = rs.getString("extra");

				if (q16 == null) {
					rs.close();
					pst.close();
				} else {

					Date ldl = new SimpleDateFormat("yyyy-MM-dd").parse(q16);

					LocalDate billDate = ldl.toInstant().atZone(ZoneId.systemDefault()).toLocalDate();
					dx1 = LocalDate.now();

					ix1 = dx1.compareTo(billDate);

					if (ix1 > 0) {
						String query = "Insert into pending_pent (lmbai,kemer,hip,gidri,pinjni,mori,putt,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
						PreparedStatement pst1 = conn.prepareStatement(query);
						pst1.setString(1, q1);
						pst1.setString(2, q2);
						pst1.setString(3, q3);
						pst1.setString(4, q4);
						pst1.setString(5, q5);
						pst1.setString(6, q6);
						pst1.setString(7, q7);
						pst1.setString(8, q8);
						pst1.setString(9, q9);
						pst1.setString(10, q10);
						pst1.setString(11, q11);
						pst1.setString(12, q12);
						pst1.setString(13, q13);
						pst1.setString(14, q14);
						pst1.setString(15, q15);
						pst1.setString(16, q16);
						pst1.setString(17, q17);
						pst1.setString(18, q18);
						pst1.setString(19, q19);

						pst1.execute();
						pst1.close();

						String query1 = " DELETE FROM pent where Ending_Date= '" + q16 + "' ";
						try {
							PreparedStatement pst2 = conn.prepareStatement(query1);
							pst2.execute();
							pst2.close();
						} catch (Exception e1) {
							e1.printStackTrace();
						}
					} else {

					}
				}
			}
			rs.close();
			pst.close();

		} catch (Exception e1) {
			JOptionPane.showMessageDialog(null, "In pent" + e1);
		}

		try {

			conn = DriverManager.getConnection("jdbc:sqlite:Trailor.sqlite");
			String query = "select * from pent ";
			PreparedStatement statment = conn.prepareStatement(query);
			ResultSet rs = statment.executeQuery();
			table_39.setModel(DbUtils.resultSetToTableModel(rs));

			rs.close();
			statment.close();
		} catch (Exception e) {
		}
	}

	public void coatSwitch() {
		try {
			String s = "Select * from Coat ";
			PreparedStatement pst = conn.prepareStatement(s);
			ResultSet rs = pst.executeQuery();
			while (rs.next()) {

				q1 = rs.getString("lmbai");
				q2 = rs.getString("seena");
				q3 = rs.getString("kemer");
				q4 = rs.getString("pait");
				q5 = rs.getString("hip");
				q6 = rs.getString("teera");
				q7 = rs.getString("baju");
				q8 = rs.getString("dor");
				q9 = rs.getString("back");
				q10 = rs.getString("bs");
				q11 = rs.getString("bm");
				q12 = rs.getString("shoulder");
				q13 = rs.getString("Customerid");
				q14 = rs.getString("CustomerName");
				q15 = rs.getString("CustomerContact");
				q16 = rs.getString("CustomerAddress");
				q17 = rs.getString("price");
				q18 = rs.getString("advance_payments");
				q19 = rs.getString("pending_payments");
				q20 = rs.getString("Starting_date");
				q21 = rs.getString("Ending_date");
				q22 = rs.getString("price1");
				q23 = rs.getString("quantity");
				q24 = rs.getString("extra");

				if (q21 == null) {
					rs.close();
					pst.close();
				} else {

					Date ldl = new SimpleDateFormat("yyyy-MM-dd").parse(q21);
					LocalDate billDate = ldl.toInstant().atZone(ZoneId.systemDefault()).toLocalDate();
					dx2 = LocalDate.now();

					ix2 = dx2.compareTo(billDate);

					if (ix2 > 0) {
						String query = "Insert into pending_coat (lmbai ,seena ,kemer ,pait ,hip ,teera ,baju ,dor ,back ,bs ,bm ,shoulder,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
						PreparedStatement pst1 = conn.prepareStatement(query);
						pst1.setString(1, q1);
						pst1.setString(2, q2);
						pst1.setString(3, q3);
						pst1.setString(4, q4);
						pst1.setString(5, q5);
						pst1.setString(6, q6);
						pst1.setString(7, q7);
						pst1.setString(8, q8);
						pst1.setString(9, q9);
						pst1.setString(10, q10);
						pst1.setString(11, q11);
						pst1.setString(12, q12);
						pst1.setString(13, q13);
						pst1.setString(14, q14);
						pst1.setString(15, q15);
						pst1.setString(16, q16);
						pst1.setString(17, q17);
						pst1.setString(18, q18);
						pst1.setString(19, q19);
						pst1.setString(20, q20);
						pst1.setString(21, q21);
						pst1.setString(22, q22);
						pst1.setString(23, q23);
						pst1.setString(24, q24);

						pst1.execute();

						pst1.close();

						String query1 = " DELETE FROM Coat where Ending_Date= '" + q21 + "' ";
						try {
							PreparedStatement pst2 = conn.prepareStatement(query1);
							pst2.execute();
							pst2.close();
						} catch (Exception e1) {
							e1.printStackTrace();
						}

					} else {

					}

				}
			}

			rs.close();
			pst.close();
		} catch (Exception e1) {
			JOptionPane.showMessageDialog(null, "In coat " + e1);
		}
		try {

			String s = "Select * from Coat ";
			PreparedStatement pst = conn.prepareStatement(s);
			ResultSet rs = pst.executeQuery();
			table_38.setModel(DbUtils.resultSetToTableModel(rs));

		} catch (Exception e) {
			JOptionPane.showMessageDialog(null, "in coat " + e1);
		}

	}

	public void jacketSwitch() {
		try {
			String s = "Select * from Jacket ";
			PreparedStatement pst = conn.prepareStatement(s);
			ResultSet rs = pst.executeQuery();
			while (rs.next()) {

				q1 = rs.getString("lmbai");
				q2 = rs.getString("seena");
				q3 = rs.getString("kemer");
				q4 = rs.getString("hip");
				q5 = rs.getString("teera");
				q6 = rs.getString("Customerid");
				q7 = rs.getString("CustomerName");
				q8 = rs.getString("CustomerContact");
				q9 = rs.getString("CustomerAddress");
				q10 = rs.getString("price");
				q11 = rs.getString("advance_payments");
				q12 = rs.getString("pending_payments");
				q13 = rs.getString("Starting_date");
				q14 = rs.getString("Ending_date");
				q15 = rs.getString("price1");
				q16 = rs.getString("quantity");
				q17 = rs.getString("extra");

				if (q14 == null) {
					rs.close();
					pst.close();
				} else {

					Date ldl = new SimpleDateFormat("yyyy-MM-dd").parse(q14);
					LocalDate billDate = ldl.toInstant().atZone(ZoneId.systemDefault()).toLocalDate();
					dx3 = LocalDate.now();

					ix3 = dx3.compareTo(billDate);

					if (ix3 > 0) {
						String query = "Insert into pending_jacket (lmbai,seena,kemer,hip,teera,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
						PreparedStatement pst1 = conn.prepareStatement(query);
						pst1.setString(1, q1);
						pst1.setString(2, q2);
						pst1.setString(3, q3);
						pst1.setString(4, q4);
						pst1.setString(5, q5);
						pst1.setString(6, q6);
						pst1.setString(7, q7);
						pst1.setString(8, q8);
						pst1.setString(9, q9);
						pst1.setString(10, q10);
						pst1.setString(11, q11);
						pst1.setString(12, q12);
						pst1.setString(13, q13);
						pst1.setString(14, q14);
						pst1.setString(15, q15);
						pst1.setString(16, q16);
						pst1.setString(17, q17);

						pst1.execute();

						pst1.close();
						String query1 = " DELETE FROM Jacket where Ending_Date= '" + q14 + "' ";
						try {
							PreparedStatement pst2 = conn.prepareStatement(query1);
							pst2.execute();
							pst2.close();
						} catch (Exception e1) {
							e1.printStackTrace();
						}

					} else {
					}

				}
			}

			rs.close();
			pst.close();
		} catch (Exception e1) {
			JOptionPane.showMessageDialog(null, "in jacket" + e1);
		}
		try {

			String s = "Select * from Jacket ";
			PreparedStatement pst = conn.prepareStatement(s);
			ResultSet rs = pst.executeQuery();
			table_36.setModel(DbUtils.resultSetToTableModel(rs));

		} catch (Exception e) {
			JOptionPane.showMessageDialog(null, "In all jacket selecting " + e);
		}
	}

	public void kurtaSwitch() {
		try {
			String s = "Select * from Kurta ";
			PreparedStatement pst = conn.prepareStatement(s);
			ResultSet rs = pst.executeQuery();
			while (rs.next()) {

				q1 = rs.getString("lmbai");
				q2 = rs.getString("seena");
				q3 = rs.getString("kemer");
				q4 = rs.getString("pait");
				q5 = rs.getString("hip");
				q6 = rs.getString("teera");
				q7 = rs.getString("glaa");
				q8 = rs.getString("baju");
				q9 = rs.getString("bs");
				q10 = rs.getString("Customerid");
				q11 = rs.getString("CustomerName");
				q12 = rs.getString("CustomerContact");
				q13 = rs.getString("CustomerAddress");
				q14 = rs.getString("price");
				q15 = rs.getString("advance_payments");
				q16 = rs.getString("pending_payments");
				q17 = rs.getString("Starting_date");
				q18 = rs.getString("Ending_date");
				q19 = rs.getString("price1");
				q20 = rs.getString("quantity");
				q21 = rs.getString("extra");

				if (q18 == null) {
					rs.close();
					pst.close();
				} else {

					Date ldl = new SimpleDateFormat("yyyy-MM-dd").parse(q18);
					LocalDate billDate = ldl.toInstant().atZone(ZoneId.systemDefault()).toLocalDate();
					dx4 = LocalDate.now();

					ix4 = dx4.compareTo(billDate);

					if (ix4 > 0) {
						String query = "Insert into pending_kurta (lmbai ,seena ,kemer ,pait ,hip ,teera ,glaa ,baju ,bs,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
						PreparedStatement pst1 = conn.prepareStatement(query);
						pst1.setString(1, q1);
						pst1.setString(2, q2);
						pst1.setString(3, q3);
						pst1.setString(4, q4);
						pst1.setString(5, q5);
						pst1.setString(6, q6);
						pst1.setString(7, q7);
						pst1.setString(8, q8);
						pst1.setString(9, q9);
						pst1.setString(10, q10);
						pst1.setString(11, q11);
						pst1.setString(12, q12);
						pst1.setString(13, q13);
						pst1.setString(14, q14);
						pst1.setString(15, q15);
						pst1.setString(16, q16);
						pst1.setString(17, q17);
						pst1.setString(18, q18);
						pst1.setString(19, q19);
						pst1.setString(20, q20);
						pst1.setString(21, q21);
						pst1.execute();

						pst1.close();
						String query1 = " DELETE FROM Kurta where Ending_Date= '" + q18 + "' ";
						try {
							PreparedStatement pst2 = conn.prepareStatement(query1);
							pst2.execute();
							pst2.close();
						} catch (Exception e1) {
							e1.printStackTrace();
						}

					} else {
					}
				}
			}

			rs.close();
			pst.close();
		} catch (Exception e1) {
			JOptionPane.showMessageDialog(null, "In kurta " + e1);
		}
		try {

			String s = "Select * from Kurta ";
			PreparedStatement pst = conn.prepareStatement(s);
			ResultSet rs = pst.executeQuery();
			table_35.setModel(DbUtils.resultSetToTableModel(rs));

		} catch (Exception e) {
			JOptionPane.showMessageDialog(null, "in kurta " + e);
		}
	}

	public void pjamaSwitch() {
		try {
			String s = "Select * from Pjama ";
			PreparedStatement pst = conn.prepareStatement(s);
			ResultSet rs = pst.executeQuery();
			while (rs.next()) {

				q1 = rs.getString("lmbai");
				q2 = rs.getString("kemer");
				q3 = rs.getString("hip");
				q4 = rs.getString("gidri");
				q5 = rs.getString("pinjni");
				q6 = rs.getString("mori");
				q7 = rs.getString("putt");
				q8 = rs.getString("Customerid");
				q9 = rs.getString("CustomerName");
				q10 = rs.getString("CustomerContact");
				q11 = rs.getString("CustomerAddress");
				q12 = rs.getString("price");
				q13 = rs.getString("advance_payments");
				q14 = rs.getString("pending_payments");
				q15 = rs.getString("Starting_date");
				q16 = rs.getString("Ending_date");
				q17 = rs.getString("price1");
				q18 = rs.getString("quantity");
				q19 = rs.getString("extra");

				if (q16 == null) {
					rs.close();
					pst.close();
				} else {

					Date ldl = new SimpleDateFormat("yyyy-MM-dd").parse(q16);
					LocalDate billDate = ldl.toInstant().atZone(ZoneId.systemDefault()).toLocalDate();
					dx5 = LocalDate.now();

					ix5 = dx5.compareTo(billDate);

					if (ix5 > 0) {
						String query = "Insert into pending_pjama (lmbai,kemer,hip,gidri,pinjni,mori,putt,Customerid,CustomerName,CustomerContact,CustomerAddress,price,advance_payments,pending_payments,Starting_Date,Ending_Date,price1,quantity,extra) values(?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)";
						PreparedStatement pst1 = conn.prepareStatement(query);
						pst1.setString(1, q1);
						pst1.setString(2, q2);
						pst1.setString(3, q3);
						pst1.setString(4, q4);
						pst1.setString(5, q5);
						pst1.setString(6, q6);
						pst1.setString(7, q7);
						pst1.setString(8, q8);
						pst1.setString(9, q9);
						pst1.setString(10, q10);
						pst1.setString(11, q11);
						pst1.setString(12, q12);
						pst1.setString(13, q13);
						pst1.setString(14, q14);
						pst1.setString(15, q15);
						pst1.setString(16, q16);
						pst1.setString(17, q17);
						pst1.setString(18, q18);
						pst1.setString(19, q19);
						pst1.execute();

						pst1.close();

						String query1 = " DELETE FROM Pjama where Ending_Date= '" + q16 + "' ";
						try {
							PreparedStatement pst2 = conn.prepareStatement(query1);
							pst2.execute();
							pst2.close();
						} catch (Exception e1) {
							JOptionPane.showMessageDialog(null, "In all shirt selecting " + e1);
						}
					} else {
					}
				}
			}
			rs.close();
			pst.close();

		} catch (Exception e1) {
			JOptionPane.showMessageDialog(null, "in pjama " + e1);
		}
		try {

			String s = "Select * from Pjama ";
			PreparedStatement pst = conn.prepareStatement(s);
			ResultSet rs = pst.executeQuery();
			table_37.setModel(DbUtils.resultSetToTableModel(rs));

		} catch (Exception e) {
			JOptionPane.showMessageDialog(null, "in pjama " + e);
		}
	}

	public static String[] printShirtData(String id, String name, String contact, String address) {
		String[] detail = new String[17];
		try {
			String query = "Select * from Shirt where Customerid = '" + id + "' AND CustomerName = '" + name
					+ "' AND CustomerContact = '" + contact + "' AND CustomerAddress = '" + address + "'";
			PreparedStatement preparedStatement = conn.prepareStatement(query);
			ResultSet rs = preparedStatement.executeQuery();
			while (rs.next()) {
				detail[0] = rs.getString("lmbai");
				detail[1] = rs.getString("seena");
				detail[2] = rs.getString("kemer");
				detail[3] = rs.getString("pait");
				detail[4] = rs.getString("hip");
				detail[5] = rs.getString("teera");
				detail[6] = rs.getString("glaa");
				detail[7] = rs.getString("baju");
				detail[8] = rs.getString("bs");
				detail[9] = rs.getString("price");
				detail[10] = rs.getString("advance_payments");
				detail[11] = rs.getString("pending_payments");
				detail[12] = rs.getString("Starting_date");
				detail[13] = rs.getString("Ending_date");
				detail[14] = rs.getString("price1");
				detail[15] = rs.getString("quantity");
				detail[16] = rs.getString("extra");
			}
			preparedStatement.close();
			rs.close();
		} catch (Exception e) {
			JOptionPane.showMessageDialog(null, e);
		}
		return detail;
	}

	public static String[] printPentData(String id, String name, String contact, String address) {
		String[] detail = new String[15];
		try {
			String query = "Select * from pent where Customerid = '" + id + "' AND CustomerName = '" + name
					+ "' AND CustomerContact = '" + contact + "' AND CustomerAddress = '" + address + "'";
			PreparedStatement preparedStatement = conn.prepareStatement(query);
			ResultSet rs = preparedStatement.executeQuery();
			while (rs.next()) {
				detail[0] = rs.getString("lmbai");
				detail[1] = rs.getString("kemer");
				detail[2] = rs.getString("hip");
				detail[3] = rs.getString("gidri");
				detail[4] = rs.getString("pinjni");
				detail[5] = rs.getString("mori");
				detail[6] = rs.getString("putt");
				detail[7] = rs.getString("price");
				detail[8] = rs.getString("advance_payments");
				detail[9] = rs.getString("pending_payments");
				detail[10] = rs.getString("Starting_date");
				detail[11] = rs.getString("Ending_date");
				detail[12] = rs.getString("price1");
				detail[13] = rs.getString("quantity");
				detail[14] = rs.getString("extra");

			}
			preparedStatement.close();
			rs.close();
		} catch (Exception e) {
			JOptionPane.showMessageDialog(null, e);
		}
		return detail;
	}

	public static String[] printCoatData(String id, String name, String contact, String address) {
		String[] detail = new String[20];
		try {
			String query = "Select * from Coat where Customerid = '" + id + "' AND CustomerName = '" + name
					+ "' AND CustomerContact = '" + contact + "' AND CustomerAddress = '" + address + "'";
			PreparedStatement preparedStatement = conn.prepareStatement(query);
			ResultSet rs = preparedStatement.executeQuery();
			while (rs.next()) {
				detail[0] = rs.getString("lmbai");
				detail[1] = rs.getString("seena");
				detail[2] = rs.getString("kemer");
				detail[3] = rs.getString("pait");
				detail[4] = rs.getString("hip");
				detail[5] = rs.getString("teera");
				detail[6] = rs.getString("baju");
				detail[7] = rs.getString("dor");
				detail[8] = rs.getString("back");
				detail[9] = rs.getString("bs");
				detail[10] = rs.getString("bm");
				detail[11] = rs.getString("shoulder");
				detail[12] = rs.getString("price");
				detail[13] = rs.getString("advance_payments");
				detail[14] = rs.getString("pending_payments");
				detail[15] = rs.getString("Starting_date");
				detail[16] = rs.getString("Ending_date");
				detail[17] = rs.getString("price1");
				detail[18] = rs.getString("quantity");
				detail[19] = rs.getString("extra");

			}
			preparedStatement.close();
			rs.close();
		} catch (Exception e) {
			JOptionPane.showMessageDialog(null, e);
		}
		return detail;
	}

	public static String[] printJacketData(String id, String name, String contact, String address) {
		String[] detail = new String[13];
		try {
			String query = "Select * from Jacket where Customerid = '" + id + "' AND CustomerName = '" + name
					+ "' AND CustomerContact = '" + contact + "' AND CustomerAddress = '" + address + "'";
			PreparedStatement preparedStatement = conn.prepareStatement(query);
			ResultSet rs = preparedStatement.executeQuery();
			while (rs.next()) {
				detail[0] = rs.getString("lmbai");
				detail[1] = rs.getString("seena");
				detail[2] = rs.getString("kemer");
				detail[3] = rs.getString("hip");
				detail[4] = rs.getString("teera");
				detail[5] = rs.getString("price");
				detail[6] = rs.getString("advance_payments");
				detail[7] = rs.getString("pending_payments");
				detail[8] = rs.getString("Starting_date");
				detail[9] = rs.getString("Ending_date");
				detail[10] = rs.getString("price1");
				detail[11] = rs.getString("quantity");
				detail[12] = rs.getString("extra");

			}
			preparedStatement.close();
			rs.close();
		} catch (Exception e) {
			JOptionPane.showMessageDialog(null, e);
		}
		return detail;
	}

	public static String[] printKurtaData(String id, String name, String contact, String address) {
		String[] detail = new String[17];
		try {
			String query = "Select * from Kurta where Customerid = '" + id + "' AND CustomerName = '" + name
					+ "' AND CustomerContact = '" + contact + "' AND CustomerAddress = '" + address + "'";
			PreparedStatement preparedStatement = conn.prepareStatement(query);
			ResultSet rs = preparedStatement.executeQuery();
			while (rs.next()) {
				detail[0] = rs.getString("lmbai");
				detail[1] = rs.getString("seena");
				detail[2] = rs.getString("kemer");
				detail[3] = rs.getString("pait");
				detail[4] = rs.getString("hip");
				detail[5] = rs.getString("teera");
				detail[6] = rs.getString("glaa");
				detail[7] = rs.getString("baju");
				detail[8] = rs.getString("bs");
				detail[9] = rs.getString("price");
				detail[10] = rs.getString("advance_payments");
				detail[11] = rs.getString("pending_payments");
				detail[12] = rs.getString("Starting_date");
				detail[13] = rs.getString("Ending_date");
				detail[14] = rs.getString("price1");
				detail[15] = rs.getString("quantity");
				detail[16] = rs.getString("extra");

			}
			preparedStatement.close();
			rs.close();
		} catch (Exception e) {
			JOptionPane.showMessageDialog(null, e);
		}
		return detail;
	}

	public static String[] printPjamaData(String id, String name, String contact, String address) {
		String[] detail = new String[15];
		try {
			String query = "Select * from Pjama where Customerid = '" + id + "' AND CustomerName = '" + name
					+ "' AND CustomerContact = '" + contact + "' AND CustomerAddress = '" + address + "'";
			PreparedStatement preparedStatement = conn.prepareStatement(query);
			ResultSet rs = preparedStatement.executeQuery();
			while (rs.next()) {

				detail[0] = rs.getString("lmbai");
				detail[1] = rs.getString("kemer");
				detail[2] = rs.getString("hip");
				detail[3] = rs.getString("gidri");
				detail[4] = rs.getString("pinjni");
				detail[5] = rs.getString("mori");
				detail[6] = rs.getString("putt");
				detail[7] = rs.getString("price");
				detail[8] = rs.getString("advance_payments");
				detail[9] = rs.getString("pending_payments");
				detail[10] = rs.getString("Starting_date");
				detail[11] = rs.getString("Ending_date");
				detail[12] = rs.getString("price1");
				detail[13] = rs.getString("quantity");
				detail[14] = rs.getString("extra");

			}
			preparedStatement.close();
			rs.close();
		} catch (Exception e) {
			JOptionPane.showMessageDialog(null, e);
		}
		return detail;
	}
}
